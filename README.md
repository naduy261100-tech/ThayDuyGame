# THẦY DUY GAME

Không gian trò chơi học tập tương tác dành cho học sinh tiểu học.

## Danh sách trò chơi
- [Chém đáp án – Camera AI](chem-dap-an.html)
- [Nghiêng đầu – Chọn đáp án](nghieng-dau.html)

## Chém đáp án
- Hai học sinh chơi cùng lúc, mỗi em được phân vùng trái/phải riêng.
- Nhận diện tối đa hai bàn tay bằng MediaPipe Hand Landmarker.
- Theo dõi đầu ngón trỏ, lọc tư thế chỉ ngón và kiểm tra đường vung tay cắt qua vùng đáp án.
- Giáo viên biên soạn, sửa, xóa câu hỏi; nhập hàng loạt từ văn bản hoặc sao lưu/khôi phục ngân hàng JSON.
- Dữ liệu câu hỏi được lưu trong localStorage của trình duyệt; không gửi camera/video lên máy chủ.
- Có chế độ chơi thử bằng chuột.
- Yêu cầu HTTPS, quyền camera và kết nối Internet để tải thư viện/mô hình AI.

## Triển khai
GitHub Pages tự động triển khai từ nhánh `main`.
