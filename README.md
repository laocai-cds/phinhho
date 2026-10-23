# Đảng ủy xã Phình Hồ

Hệ thống theo dõi thu nộp đảng phí · Đảng ủy xã Phình Hồ

Giao diện và ảnh chia sẻ sử dụng tông xanh da trời trong suốt theo ảnh tham khảo. Ảnh xem trước Open Graph: `og-image-ph.png` (sau khi tải lên hosting, đặt `og:image` và `twitter:image` thành URL công khai đầy đủ của ảnh).

Firebase Realtime Database: `https://phinhho-5c8a1-default-rtdb.firebaseio.com` (US Central). Rules giới hạn đã được publish: read/write bị chặn ở gốc; chỉ `/presence` và `/stats/visits` mở đúng quyền cần thiết cho hai bộ đếm.

Lưu ý triển khai: thay dữ liệu dự phòng của Trạm Tấu bằng dữ liệu Phình Hồ trước khi đưa vào sử dụng.





