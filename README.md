DỰ ÁN: TỪ DỮ LIỆU ĐẾN PHÂN TÍCH VỚI PYTHON
Họ và tên: [Nguyễn Anh Khang]
MSSV: [ 2311553866 ]
Lớp: [ 24DTH2A ]
Trả lời câu hỏi thu hoạch
Câu 1: Chuỗi tiếng Việt có dấu thường tốn nhiều byte hơn chuỗi tiếng Anh có cùng số ký tự vì UTF-8 sử dụng số byte thay đổi tùy theo ký tự. Các ký tự tiếng Anh thông dụng thường chiếm 1 byte, trong khi nhiều ký tự tiếng Việt có dấu chiếm 2 hoặc 3 byte.
Câu 2: CSV lưu dữ liệu theo hàng và cột, phù hợp với dữ liệu dạng bảng. JSON lưu dữ liệu bằng các cặp khóa–giá trị và hỗ trợ danh sách, đối tượng lồng nhau. Vì vậy, JSON thường phù hợp hơn khi dữ liệu có cấu trúc phân cấp (nested).
Câu 3: Khi mở file ảnh PNG bằng Notepad, ta thường thấy các ký tự khó đọc hoặc ký hiệu lạ. Nguyên nhân là PNG lưu dữ liệu ở dạng nhị phân, không phải văn bản thuần, nên Notepad không thể hiển thị nội dung đó thành hình ảnh.
Câu 4: data/raw/ dùng để lưu dữ liệu gốc, còn data/processed/ lưu dữ liệu đã được làm sạch hoặc biến đổi. Việc tách riêng giúp dễ quản lý và tái lập quá trình phân tích. File .gitignore giúp Git bỏ qua các file không cần theo dõi như cache, môi trường ảo và file chứa thông tin bí mật.
Câu 5: Với bộ dữ liệu mẫu gồm 5 sinh viên có GPA lần lượt là 3.4, 3.8, 3.1, 3.6 và 2.9, GPA trung bình là 3.36, cao nhất là 3.8 và thấp nhất là 2.9. Nhìn chung, kết quả học tập của nhóm tương đối khá. Các số liệu này cần được điều chỉnh nếu biểu đồ phân tích Buổi 2 sử dụng bộ dữ liệu khác.