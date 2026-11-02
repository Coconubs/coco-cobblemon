# Tải CocoLauncher (Coco Launcher) cho Windows, macOS, Android

CocoLauncher là launcher của server Coco Cobblemon, tự cài Java, Minecraft, Fabric và gói mod để người chơi vào server chỉ bằng một nút. Nhà phát hành là Coconubs.

| Nền tảng | Link tải |
|---|---|
| Windows (khuyên dùng) | [Microsoft Store](https://apps.microsoft.com/detail/9NPG31VS7T2H) |
| Windows, file cài | [Tải file .exe](https://github.com/Coconubs/cocolauncher-pack/releases/download/launcher/CocoLauncher-Setup.exe) |
| macOS M1-M4 và mới hơn (chip Apple) | [Tải file .dmg](https://github.com/Coconubs/cocolauncher-pack/releases/download/launcher/CocoLauncher-Mac-AppleSilicon.dmg) |
| macOS Intel | [Tải file .dmg](https://github.com/Coconubs/cocolauncher-pack/releases/download/launcher/CocoLauncher-Mac-Intel.dmg) |
| Android (thử nghiệm, RAM từ 6 GB) | [Tải file .apk](https://github.com/Coconubs/cocolauncher-pack/releases/download/android-app/CocoLauncher-Android.apk) |
| Android trên giả lập PC (MuMu, LDPlayer) | [Tải file .apk](https://github.com/Coconubs/cocolauncher-pack/releases/download/android-app/CocoLauncher-Android-GiaLap.apk) |
| iOS | Chưa có |

Chỉ tải từ các link trên. Bản đăng lại ở trang khác có thể đã bị sửa.

## CocoLauncher làm gì

- Một nút **Chơi**: tự tải và kiểm tra Java, Minecraft, Fabric Loader, gói mod và resource pack.
- Mod tự cập nhật theo server, người chơi không phải chép file tay.
- Lưu nhiều tên chơi, chỉnh RAM, độ phân giải, thư mục game.
- Xem số người online. Giao diện tiếng Việt và tiếng Anh.

## Cài trên Windows

1. Cài từ Microsoft Store, hoặc tải file .exe rồi mở.
2. Ưu tiên bản Microsoft Store. File .exe chưa có chữ ký số nên SmartScreen có thể cảnh báo. Chỉ tiếp tục khi bạn tải đúng từ Releases của Coconubs và mã SHA-256 khớp.
3. Nhập tên trong game 3 đến 16 ký tự, bấm **Chơi**.

## Cài trên macOS

1. Mở file .dmg, kéo CocoLauncher vào Applications. Không biết máy loại nào thì xem dòng Chip trong About This Mac.
2. macOS 15 trở lên: mở app 1 lần, chọn Done, vào System Settings > Privacy & Security, bấm **Open Anyway**. macOS 14 trở xuống: Control + click vào app, chọn Open.
3. Bản Mac không tự cập nhật launcher. Khi có thông báo bản mới, tải lại .dmg và kéo đè, dữ liệu game giữ nguyên.

## Cài trên Android (thử nghiệm)

1. Cần RAM từ 6 GB, khuyên dùng 8 GB trở lên, chip tầm trung trở lên, trống khoảng 2 GB.
2. Mở file .apk, cho phép cài ứng dụng không rõ nguồn gốc nếu máy hỏi.
3. Nhập tên, bấm **Chơi**. Lần đầu tải khoảng 400 MB, nên dùng Wi-Fi. Android dùng gói Coco Lite khoảng 125 mod.

## Kiểm tra file tải

Trên Windows, mở PowerShell tại thư mục tải và chạy:

```powershell
Get-FileHash CocoLauncher-Setup.exe
```

Kết quả phải trùng mã `sha256` hiện cạnh file trên [GitHub Releases](https://github.com/Coconubs/cocolauncher-pack/releases/tag/launcher). Không khớp thì đừng mở file, hãy tải lại từ link trên và báo trên Discord.

---

[Trang chính](../README.md) · [Cách vào server](cach-vao-server.md) · [Tính năng](tinh-nang.md) · [Sửa lỗi](sua-loi-cocolauncher.md) · [Discord](https://discord.gg/hyspace)

*CocoLauncher và Coco Cobblemon không phải sản phẩm chính thức và không được xác nhận bởi Mojang, Microsoft, Nintendo, The Pokémon Company hay nhóm phát triển Cobblemon. Cập nhật: 02/11/2026.*
