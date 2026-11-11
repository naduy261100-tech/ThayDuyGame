# Game Thầy Duy

Các trò chơi tương tác dành cho học sinh tiểu học, chạy trực tiếp trên trình duyệt.

## Trò chơi

- [Thẻ QR – Chọn đáp án](index.html)
- [Nghiêng đầu – Chọn đáp án](nghieng-dau.html)
- [Chém đáp án – Camera AI](chem-dap-an.html)

## Chém đáp án – Camera AI

Hai học sinh đứng ở hai nửa trái/phải màn hình, sử dụng bàn tay trước webcam để chém các đáp án đang bay. Mỗi đáp án đúng được cộng 10 điểm; đáp án sai bị trừ 2 điểm.

- Nhận diện tối đa 4 bàn tay bằng MediaPipe Tasks Vision ngay trên trình duyệt.
- Có ngân hàng câu hỏi mẫu: Toán 5, Tiếng Việt, Khoa học, Lịch sử và Địa lí.
- Giáo viên có thể tự nhập câu hỏi theo cấu trúc: Câu hỏi | Đáp án đúng | Đáp án sai 1 | Đáp án sai 2 | Đáp án sai 3.
- Có chế độ chơi thử bằng chuột khi chưa kết nối camera.
- Cần mở bằng HTTPS và cấp quyền camera; cần kết nối Internet để tải thư viện AI và mô hình nhận diện tay.

Hình ảnh camera được xử lý trực tiếp trong trình duyệt, trò chơi không gửi video lên máy chủ.
