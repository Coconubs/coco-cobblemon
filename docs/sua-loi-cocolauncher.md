# Sửa lỗi CocoLauncher: Windows, macOS, Android

Các lỗi đã biết và cách xử lý theo từng hệ điều hành.

## Windows

- **SmartScreen chặn file cài:** [cài từ Microsoft Store](https://apps.microsoft.com/detail/9NPG31VS7T2H?cid=github), hoặc [đối chiếu mã SHA-256](tai-cocolauncher.md#kiểm-tra-file-tải) trước khi chạy file .exe.
- **Launcher báo game thoát mã 1 ngay sau khi bấm Chơi:** game dừng trước khi nạp mod. Ca đã gặp là ổ đĩa hết dung lượng, hãy dọn ổ rồi thử lại. Chi tiết lỗi nằm ở `instance/logs/launcher-game-output.log`.
- **Game chậm hoặc văng:** chỉnh RAM ở mục Cấu hình nhanh trong launcher, tắt bớt ứng dụng khác.
- **Mod lỗi sau khi tự chép file:** bỏ mod đó khỏi thư mục SideMods rồi bấm Chơi. Launcher kiểm tra lại gói mod mỗi lần chạy.

## macOS

- **Máy báo không xác minh được nhà phát triển:** macOS 15 trở lên vào System Settings > Privacy & Security, bấm Open Anyway. macOS 14 trở xuống Control + click, chọn Open.
- **Máy báo "is damaged":** tải lại file từ [trang tải](tai-cocolauncher.md), đối chiếu mã SHA-256. Vẫn lỗi thì hỏi trên Discord, không tự gỡ cơ chế kiểm tra bảo mật của macOS.

## Android

- **Giả lập bị văng:** dùng file dành cho giả lập, không dùng file điện thoại.
- **Đen màn hình hoặc văng:** trong Cài đặt, mục Bộ dựng hình đang Tự động thì thử LTW hoặc Zink.
- **Máy nóng, giật:** giảm độ phân giải xuống 50 đến 70%.
- **Văng giữa chừng:** để Bộ nhớ cho game ở mức khuyên dùng, tắt bớt ứng dụng khác.

## Vẫn lỗi?

Gửi ảnh lỗi trên [Discord](https://discord.gg/hyspace). Trên Android dùng nút Gửi log lỗi cho admin trong Cài đặt.

---

[Trang chính](../README.md) · [Cách vào server](cach-vao-server.md) · [Tải CocoLauncher](tai-cocolauncher.md) · [Tính năng](tinh-nang.md) · [Discord](https://discord.gg/hyspace)

*CocoLauncher và Coco Cobblemon không phải sản phẩm chính thức và không được xác nhận bởi Mojang, Microsoft, Nintendo, The Pokémon Company hay nhóm phát triển Cobblemon. Cập nhật: 02/11/2026.*
