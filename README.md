
# :rocket: PROJECT:SMART-FARM :rocket:
- **SMART-FARM** sẽ giúp bạn theo dõi môi trường-tưới tự động-cảnh báo kịp thời-tiết kiệm chi phí
## Hướng dẫn cài đặt & Sử dụng
### 1. Tải và đăng nhập
- Mở ứng dựng
- Nhập tài khoản và mật khẩu
### 2. Xem thông số môi trường
- Xem các thông số theo thời gian thực
- Màu sắc giúp nhận biết nhanh tình trạng
### 3. Nhận cảnh báo
- Khi thông số vượt ngưỡng hệ thống sẽ gửi cảnh báo
- Kiểm tra và xử lí kịp thời
### 4. Điều khiển thiết bị
- Bật/tắt thủ công
- Hoặc chọn chế độ tự động
### 5. Xem báo cáo
- Xem lịch sử dữ liệu theo ngày, tuần, tháng
- Xuất báo cáo khi cần
## Tính năng
**Smart-Farm** đang có một số chức năng và đang phát triển thêm một số chức năng khác
- [x] tự động bật/tắt hệ thống bơm
- [x] theo dõi nhiệt đọ
- [ ] AI hỗ trợ


**BẢNG THÔNG SỐ**
| STT | Thông số | Giá trị |
|---:|---|---:|
| 1 | Nhiệt độ | 28.6 °C |
| 2 | Độ ẩm không khí | 78% |
| 3 | Độ ẩm đất | 65% |
| 4 | Ánh sáng | 1200 lux |
| 5 | Độ dẫn điện EC | 1.6 mS/cm |
| 6 | Độ pH | 6.2 |

```
1. Fetch: CPU lấy lệnh tưới Lan từ bộ nhớ RAM

 2. Decode: CPU giải mã lệnh để xác định cần bật máy bơm tưới

 3. Execute: CPU gửi tín hiệu điều khiển đến thiết bị, bật máy bơm để tưới Lan
 ```
 ## Lưu ý an toàn
- Kiểm tra dung lượng RAM thường xuyên
- Sao lưu nhật ký quan trọng trước khi xóa
- Xóa các file log không còn cần thiết
- Nên lưu nhật ký dài hạn vào ổ cứng
- Nếu RAM bị đầy, kiểm tra tiến trình đang sử dụng nhiều bộ nhớ và xử lý an toàn trước khi khởi động lại
