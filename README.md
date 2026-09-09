# Auto-clash-updet

🚀 **Hệ thống phân phối bản cập nhật & bộ cài AutoClash qua GitHub Releases**

---

## 📦 Bản phát hành mới nhất: [v2.5.0](https://github.com/hoanbaby/Auto-clash-updet/releases/tag/v2.5.0)

| Tệp tải về | Dung lượng | Mô tả | Link tải trực tiếp |
| :--- | :--- | :--- | :--- |
| **`AutoClash_Setup.exe`** | ~120 MB | Bộ cài đặt đồ họa tự động All-In-One | [Tải về Setup](https://github.com/hoanbaby/Auto-clash-updet/releases/download/v2.5.0/AutoClash_Setup.exe) |
| **`AutoClash_v2.5.0.zip`** | ~110 MB | Bản đầy đủ giải nén dùng ngay (Portable) | [Tải về ZIP Full](https://github.com/hoanbaby/Auto-clash-updet/releases/download/v2.5.0/AutoClash_v2.5.0.zip) |
| **`update_v2.5.0.zip`** | ~28.6 MB | Gói nâng cấp tự động cho `Updater.exe` | [Tải về Update](https://github.com/hoanbaby/Auto-clash-updet/releases/download/v2.5.0/update_v2.5.0.zip) |
| **`version.json`** | ~600 B | Định tuyến phiên bản cho Auto-Updater | [Xem version.json](https://raw.githubusercontent.com/hoanbaby/Auto-clash-updet/main/version.json) |

---

## 🔄 Cơ chế tự động tải cập nhật của phần mềm

1. Khi người dùng mở `AutoClash.exe` hoặc `Updater.exe`:
2. Hệ thống kiểm tra phiên bản mới nhất từ:  
   `https://raw.githubusercontent.com/hoanbaby/Auto-clash-updet/main/version.json`
3. Nếu phát hiện có bản cập nhật mới:
   - Hiển thị bảng thông báo và nút **[ ⚡ CẬP NHẬT NGAY ]**.
   - Tự động kết nối và tải gói `update_v2.5.0.zip` trực tiếp từ GitHub Releases.
   - Tự giải nén, ghi đè các file cập nhật và khởi chạy lại bot game an toàn.

---

## 🛠 Hướng dẫn phát hành bản cập nhật mới (Admin)

1. Đóng gói bản update thành `update_vX.X.X.zip` (hoặc `AutoClash_Setup.exe` mới).
2. Tạo Release mới trên GitHub:
   ```bash
   gh release create vX.X.X file1 file2 --title "AutoClash vX.X.X" --notes "Nội dung cập nhật"
   ```
3. Cập nhật `download_url` và `version` trong `version.json`, sau đó `git commit && git push`.
