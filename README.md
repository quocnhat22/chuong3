# Dự Án Backup Database

## Mô Tả
Ứng dụng Python tự động sao lưu cơ sở dữ liệu có đuôi `.sql` và `.sqlite3` từ thư mục `databases` vào thư mục `backups`. Gửi email thông báo khi sao lưu thành công hoặc thất bại.

## Yêu Cầu
- Python 3.x
- Thư viện: `schedule`, `smtplib`, `dotenv`, v.v.

## Cài Đặt
1. Cài đặt các thư viện:
   ```bash
   pip install -r requirements.txt
