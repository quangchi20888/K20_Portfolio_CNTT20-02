# Portfolio học tập

## Sản phẩm này là gì?
Website tổng hợp phần giới thiệu, kiến thức đang học và bài tập thực hành của một sinh viên CNTT. Trang dùng HTML và CSS, có thể xem trực tiếp bằng trình duyệt.

## Demo
https://quangchi20888.github.io/K20_Portfolio_CNTT20-02/

## Tính năng
- Chuyển nhanh giữa năm phần bằng menu đầu trang.
- Xem ba bài thực hành và bảng học tập trong học kỳ.
- Nhập lời nhắn vào form có kiểm tra dữ liệu bắt buộc.
- Quay về phần Liên hệ từ trang thông báo kết quả.

## Cách mở
1. Bấm đường dẫn ở mục Demo.
2. Chọn **Giới thiệu** để đọc thông tin chung.
3. Chọn **Dự án** để xem các bài tập được giới thiệu.
4. Chọn **Liên hệ**, để trống form và bấm **Gửi lời nhắn** để thử thông báo yêu cầu nhập dữ liệu.
5. Nhập họ tên ít nhất 2 ký tự, email hợp lệ và lời nhắn từ 10 đến 500 ký tự, rồi bấm **Gửi lời nhắn**.
6. Bấm **Quay lại liên hệ** tại trang kết quả.

Chỉ sử dụng dữ liệu giả khi thử form. Nếu muốn xem trên máy tính, chọn **Code → Download ZIP** trên GitHub, giải nén và mở tệp `index.html`; không cần cài đặt thêm.

## Cấu trúc thư mục
- `index.html`: nội dung chính.
- `ket-qua.html`: thông báo sau bước kiểm tra form.
- `css/style.css`: bố cục và định dạng.
- `assets/`: ảnh đại diện và ảnh dự án.
- `CHANGELOG.md`: ghi những việc thực hiện ở V8.
- `docs/evidence-index.md`: bảng kiểm tra có kết quả quan sát.
- `docs/AI_LOG.md`: phần khai báo hỗ trợ AI trong Lab 8.
- `docs/evidence/`: các ảnh kiểm tra.
- `AI_log.md`: nhật ký của buổi trước.

## Đã kiểm tra
Ngày 07/11/2026, AI hỗ trợ kiểm tra bản Pages trên máy tính: bốn ảnh tải được, menu dẫn đến đúng phần, form trống bị chặn và form hợp lệ chuyển tới trang kết quả. Xem [bảng minh chứng](docs/evidence-index.md).

## Hạn chế và chưa kiểm tra
- Ba địa chỉ dự án hiện chưa phải liên kết có thể bấm.
- Form chỉ phục vụ thực hành, không gửi email; dữ liệu được đặt trên URL theo phương thức GET.
- Chưa thử ở cửa sổ ẩn danh, độ rộng 375px và điện thoại thật.
- Chưa nhận kết quả kiểm tra chéo của hai bạn.

## Khai báo AI
Xem [nhật ký Lab 8](docs/AI_LOG.md). Sinh viên cần đọc lại, tự thực hành và điền thông tin trong báo cáo.
