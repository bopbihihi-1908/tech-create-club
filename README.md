# Website Câu lạc bộ Công nghệ &amp; Sáng tạo (Tech &amp; Create)

Bài tập lớn A3 – học phần **Thiết kế Web và Triển khai Hệ thống Phần mềm (FIT4014)**, Trường Đại học Đại Nam.

## Thông tin sinh viên và giảng viên

- Sinh viên thực hiện: **Trần Văn Anh Ngọc**
- MSSV: **2071020143**
- Lớp: **CNTT 20-04**
- Đề tài: Thiết kế Website Câu lạc bộ Công nghệ &amp; Sáng tạo bằng HTML5 và CSS3 thuần
- Giảng viên hướng dẫn: **ThS. Lê Thái Bảo**

## Mô tả

Website là sản phẩm tĩnh giới thiệu mô hình Câu lạc bộ Công nghệ &amp; Sáng tạo. Nội dung bao gồm phần giới thiệu Hero, giới thiệu câu lạc bộ, ba nhóm hoạt động, lịch sinh hoạt mẫu và biểu mẫu đăng ký mô phỏng.

Dự án sử dụng HTML5 và CSS3, không dùng JavaScript, framework hay backend.

## Cấu trúc thư mục

```text
tech-create-club/
├── index.html
├── ket-qua.html
├── css/
│   └── style.css
├── README.md
├── AI_LOG.md
└── TEST_CASES.md
```

- `index.html`: trang chủ, giao diện một trang với phần Hero, giới thiệu, hoạt động, lịch, form và footer.
- `ket-qua.html`: trang kết quả mô phỏng sau khi form vượt qua kiểm tra hợp lệ của HTML5.
- `css/style.css`: toàn bộ style CSS3, gồm bố cục Mobile-First, Flexbox, Grid, hai breakpoint `640px` và `960px`, `:focus-visible` và `:user-invalid`.
- `README.md`: mô tả dự án và hướng dẫn triển khai.
- `AI_LOG.md`: khai báo hỗ trợ AI có trách nhiệm.
- `TEST_CASES.md`: kịch bản kiểm thử và minh chứng.

## Chạy cục bộ

Cách đơn giản nhất:

1. Mở thư mục dự án bằng Visual Studio Code.
2. Mở tệp `index.html` bằng Live Server hoặc một tiện ích phục vụ trang tĩnh tương tự.
3. Truy cập địa chỉ do Live Server cung cấp.

Hoặc chạy bằng Python nếu đã cài đặt:

```powershell
cd "D:\Bài Tập_Học Kỳ 1_2026-2027\Thiết Kế Web\Bài Làm\A3_TranVanAnhNgoc\tech-create-club"
python -m http.server 5500
```

Sau đó truy cập `http://localhost:5500/`.

## Truy cập bản công khai

- Repository: https://github.com/bopbihihi-1908/tech-create-club
- GitHub Pages: https://bopbihihi-1908.github.io/tech-create-club/

## Giới hạn phạm vi

Biểu mẫu trong `index.html` có thuộc tính `action="ket-qua.html"` và `method="get"`. Khi dữ liệu thỏa mãn các ràng buộc HTML5, trình duyệt chuyển sang trang `ket-qua.html` cùng các tham số trên URL. Website không gửi email, không lưu dữ liệu vào cơ sở dữ liệu, không gửi dữ liệu đến máy chủ xử lý và không có backend. Người dùng chỉ nên nhập dữ liệu giả lập để kiểm thử.
