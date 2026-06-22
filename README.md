# Báo Cáo Thực Hành Kiểm Thử Hiệu Năng Với JMeter

## 1. Thông tin sinh viên
- **Họ và tên:** Nguyễn Viết Huy
- **Mã sinh viên:** 22012376
- **Lớp:** Đánh giá và kiểm thử chất lượng phần mềm

## 2. Kết quả kiểm thử trên GitHub Codespace
- **Công cụ sử dụng:** Apache JMeter 5.6.3 chạy ở chế độ Non-GUI.
- **Mục tiêu kiểm thử (Target):** Trang web dịch vụ `httpbin.org`.
- **Số lượng người dùng mô phỏng (Threads):** 100 users cùng lúc (Ramp-up trong 10 giây).
- **Chuỗi kịch bản hành động:** 
  1. Yêu cầu 1: Vào trang chủ (Phương thức GET)
  2. Thời gian chờ (Timer): Đợi 2 giây mô phỏng thao tác người dùng.
  3. Yêu cầu 2: Gửi dữ liệu lên hệ thống (Phương thức POST)
- **Tổng số yêu cầu xử lý (Samples):** 200 requests.
- **Tỉ lệ lỗi (Error %):** Đạt 2.50% (Hệ thống có hiện tượng quá tải nhẹ khi 100 users truy cập cùng lúc).

## 3. Hình ảnh kết quả thực hiện
![Kết quả kiểm thử nâng cao](ketqua.png)

