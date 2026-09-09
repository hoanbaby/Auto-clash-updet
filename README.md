# Auto-clash-updet

🚀 **Hệ thống lưu trữ & phân phối bản cập nhật từ xa cho AutoClash (Cloud Update Server)**

---

## 📦 Tệp tin cập nhật hiện tại (v2.5.0)

- **Phiên bản mới nhất**: `v2.5.0`
- **Ngày phát hành**: `06/09/2026`
- **File cập nhật**: [`update_v2.5.0.zip`](update_v2.5.0.zip) (~28.6 MB)
- **File định tuyến phiên bản**: [`version.json`](version.json)

---

## 🔗 Liên kết tải trực tiếp (Direct CDN Links)

- **Kiểm tra phiên bản (`version.json`)**:  
  `https://raw.githubusercontent.com/hoanbaby/Auto-clash-updet/main/version.json`

- **Tải gói cập nhật (`update_v2.5.0.zip`)**:  
  `https://raw.githubusercontent.com/hoanbaby/Auto-clash-updet/main/update_v2.5.0.zip`

---

## 📋 Chi tiết bản cập nhật v2.5.0

- ✔ Tích hợp sẵn ADB Platform-Tools và Tesseract OCR nhận diện AI
- ✔ Khắc phục lỗi cài đặt và khởi chạy trên Windows 10 & Windows 11
- ✔ Nâng cấp tính năng auto cày tài nguyên vàng, dầu và tự động đập tường
- ✔ Tối ưu hóa cơ chế Auto-Updater từ xa tốc độ cao qua GitHub Cloud

---

## ⚙ Hướng dẫn cập nhật phiên bản mới (Dành cho Quản trị viên)

Mỗi khi có bản cập nhật mới (ví dụ `v2.5.1`):
1. Đóng gói các file cần cập nhật thành file `update_v2.5.1.zip`.
2. Đặt file vào thư mục này.
3. Sửa thông tin `version`, `release_date`, `download_url`, `changelog` trong file `version.json`.
4. Commit và push lên GitHub:
   ```bash
   git add .
   git commit -m "Release v2.5.1"
   git push origin main
   ```
5. Tất cả người dùng chạy `AutoClash.exe` hoặc `Updater.exe` sẽ tự động nhận được thông báo cập nhật!
