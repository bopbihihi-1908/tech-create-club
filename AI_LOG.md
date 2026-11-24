# AI_LOG – Khai báo sử dụng AI có trách nhiệm

## Phạm vi khai báo

Tài liệu này ghi lại các bước mà sinh viên đã sử dụng AI hỗ trợ trong quá trình hoàn thiện Bài tập lớn A3. AI đóng vai trò trợ lý đề xuất, sinh viên là người quyết định, kiểm tra, chỉnh sửa và xác nhận theo mã nguồn thực tế.

| STT | Công việc / giai đoạn | Công cụ sử dụng | Nội dung AI đề xuất hoặc hỗ trợ | Phần sinh viên tự kiểm tra, chỉnh sửa và xác minh |
|---:|---|---|---|---|
| 1 | Lên khung HTML5 ngữ nghĩa | GitHub Copilot trong VS Code | Gợi ý cấu trúc tài liệu HTML5 với `header`, `nav`, `main`, các thẻ `section`, `article`, `footer`, liên kết bỏ qua nội dung, biểu mẫu và một thẻ `h1` trên trang chủ. | Sinh viên đối chiếu từng thẻ với đề tài, giữ đúng nội dung câu lạc bộ, kiểm tra liên kết neo, thuộc tính `for`/`id`, thứ tự tiêu đề và duy nhất `h1` trong `index.html`; sửa nội dung tiếng Việt cho phù hợp và kiểm tra trang kết quả. |
| 2 | Thiết kế bố cục và nội dung Hero | GitHub Copilot trong VS Code | Gợi ý bố cục Hero, khối mã minh họa, các nút điều hướng và phần thống kê bằng HTML/CSS. | Sinh viên chọn nội dung không phóng đại tính năng, kiểm tra liên kết đến `#tham-gia` và `#hoat-dong`, đồng thời kiểm tra hiển thị trên trình duyệt ở kích thước nhỏ và lớn. |
| 3 | Viết CSS Mobile-First responsive | GitHub Copilot trong VS Code | Gợi ý CSS reset, biến màu, bố cục Flexbox/Grid, hai breakpoint `640px` và `960px`, trạng thái `:focus-visible`, `:user-invalid` và kiểu bảng cuộn ngang. | Sinh viên kiểm tra trực tiếp tệp `css/style.css`, xác nhận không có JavaScript, điều chỉnh màu sắc/bố cục phù hợp, kiểm tra lớp responsive, thanh cuộn bảng và khả năng đọc ở các breakpoint. |
| 4 | Thiết kế biểu mẫu mô phỏng | GitHub Copilot trong VS Code | Gợi ý form thuần HTML5 với `action="ket-qua.html"`, `method="get"`, các thuộc tính `required`, `type="email"`, `minlength`, `maxlength` và trang kết quả. | Sinh viên xác nhận không có backend/CSDL/API, thử dữ liệu rỗng, sai email, chuỗi quá ngắn và dữ liệu giả hợp lệ; kiểm tra thông báo giới hạn dữ liệu trong form và trang kết quả. |
| 5 | Kịch bản kiểm thử | GitHub Copilot trong VS Code | Gợi ý phân chia kiểm thử theo ngữ nghĩa HTML, điều hướng, responsive, bàn phím, form, và GitHub Pages. | Sinh viên tự lập kịch bản mong đợi – thao tác – kết quả – minh chứng; thêm các bước có thể đo lường tại `320px`, `390px`, `640px`, `960px`, `1366px` và lưu ảnh hoặc ghi log thực tế khi kiểm thử. |
| 6 | Biên tập tài liệu bàn giao | GitHub Copilot trong VS Code | Gợi ý khung README, nhật ký AI, bảng test case, nội dung mục báo cáo và phụ lục bàn giao. | Sinh viên đối chiếu tên tệp, số commit, URL repository, URL GitHub Pages và cấu trúc mã nguồn thực tế; loại bỏ mô tả JavaScript/backend/CSDL không tồn tại; rà lại chính tả, thuật ngữ và tính nhất quán của tài liệu. |

## Nguyên tắc sử dụng

- AI chỉ hỗ trợ đề xuất khung nội dung, mã khởi đầu, kiểm tra ý tưởng và biên tập văn bản.
- Sinh viên là người quyết định chỉnh sửa; mọi đoạn mã được xem xét, chạy thử hoặc kiểm tra trong trình duyệt trước khi bàn giao.
- Không sử dụng AI để làm giả kết quả kiểm thử, số liệu biểu mẫu, lịch sử commit hoặc trạng thái GitHub Pages.
- Tài nguyên và nội dung do AI đề xuất không được dùng trừ khi đã kiểm tra tính phù hợp với đề tài và phạm vi bài tập.

## Xác nhận của sinh viên

- [x] Đã đối chiếu cây thư mục và tệp mã nguồn thực tế.
- [x] Đã kiểm tra HTML và CSS bằng trình duyệt hoặc công cụ phát triển.
- [x] Đã kiểm tra form bằng dữ liệu giả và các điều kiện hợp lệ của HTML5.
- [x] Đã xác minh repository và các commit bằng Git.
- [x] Các tài liệu bàn giao phản ánh đúng mô hình website tĩnh, không backend, không CSDL và không JavaScript.
