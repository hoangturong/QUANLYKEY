# QUANLYKEY

## INSTALL
Tải file cài đặt tại đây: [install.exe](https://github.com/hoangturong/QUANLYKEY/raw/refs/heads/main/install.exe)  
- Chạy file `install.exe` để cài đặt.  
- Lưu ý: Ứng dụng không tạo shortcut tự động.

## Hướng Dẫn Sử Dụng App Quản Lý
### 1. Trình Duyệt
Mở trang web mặc định của ứng dụng.

### 2. Check Key
- Nhập **Key** và (tùy chọn) **IP**.  
- Nhấn nút **"Check Key"** để kiểm tra:  
  - Nếu nhập IP: Kiểm tra key cho IP đã nhập.  
  - Nếu không nhập IP: Kiểm tra key dựa trên IP của máy hiện tại.  
- Kết quả sẽ hiển thị trạng thái của key và IP.

### 3. Check IP
Hiển thị trang web kiểm tra IP hiện tại.

### 4. Cài Đặt
- Tùy chỉnh **màu nền** và **kích thước cửa sổ** của ứng dụng.

### 5. Trợ Giúp
Xem hướng dẫn sử dụng này trong ứng dụng.

## API
- **Check key theo IP:**  
  `https://vantrong.x10.mx/keyip/checkkey.php?ip={ip}&key={key}`  
- **Check IP:**  
  `https://vantrong.x10.mx/keyip/?ip`  
- **Check key không cần IP (tự động lấy IP):**  
  `https://vantrong.x10.mx/keyip/?key={key}`
