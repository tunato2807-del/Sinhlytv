# Tư liệu ảnh Chương 3

Tư liệu ảnh đo kích thước lá, mẫu giấy theo hình lá và cân khối lượng, phục vụ bài tiểu luận.

**Đã lưu đủ 21 ảnh từ tệp `ảnh.zip` và chèn vào Chương 3 của [báo cáo Word](../bao-cao/Bao_cao_tieu_luan_SLTV.docx).**

## Danh mục

Xem [danh-muc-anh.csv](danh-muc-anh.csv). Mã `C3-01` đến `C3-21` thống nhất với thứ tự ảnh đã gửi trong hội thoại và chú thích trong Word. Cột `duong_dan_anh` chứa đường dẫn thực tế tính từ thư mục này; `tep_nguon_trong_zip` lưu tên tệp nguồn; `sha256` dùng để đối chiếu nội dung. Cột `ten_co_so_du_kien` giữ lại tên cơ sở đã chuẩn bị trước khi nhận ZIP.

| Nhóm | Số ảnh | Thư mục |
| --- | ---: | --- |
| Đo lá với thước | 5 | [do-la](anh-goc/do-la/) |
| Đo mẫu giấy theo hình lá | 5 | [do-mau-giay](anh-goc/do-mau-giay/) |
| Cân lá | 5 | [can-la](anh-goc/can-la/) |
| Cân mẫu giấy theo hình lá | 5 | [can-mau-giay](anh-goc/can-mau-giay/) |
| Cân các tờ giấy | 1 | [can-giay](anh-goc/can-giay/) |

## Lưu trữ và chèn ảnh

Các ảnh được đối chiếu nội dung với danh mục, giữ nguyên định dạng JPG, độ phân giải và toàn bộ dữ liệu tệp nhận được. Chỉ đổi tên để dễ quản lý; mã băm được kiểm tra khớp với từng tệp trong ZIP. Cả 21 tệp mở được và có mã băm khác nhau.

Báo cáo chèn nguyên ảnh, giữ tỷ lệ, tối đa hai ảnh một trang để đọc thước và số cân; không cắt phần số đo hoặc giao diện ảnh chụp màn hình. Hai ảnh minh họa có sẵn trong mẫu Word vẫn được ghi nguồn riêng ở Chương 2.

## Ghi chú dùng cho tiểu luận

- Số cân trong CSV được đọc từ màn hình của từng ảnh, đơn vị g. Đây là số hiển thị, chưa phải kết quả tính toán hoặc số liệu đã hiệu chỉnh.
- Tên cây được bổ sung theo danh sách nhóm cung cấp, đối chiếu chữ ghi trên mẫu giấy và hình dạng mẫu. Mã mẫu thống nhất trong Word, danh mục ảnh và [bảng số liệu 3.1](bang-3-1-so-lieu-la.csv): M01 Xà cừ; M02 Muồng hoàng yến; M03 Muồng ràng ràng; M04 Giáng hương quả to; M05 Keo lá tràm. Các cột `ma_mau` và `ten_cay` trong danh mục chỉ rõ liên kết này.
- Ảnh `C3-21` hiển thị nhiều tờ giấy trên cân và số `2.530 g`; chưa xác nhận số tờ hoặc diện tích giấy chuẩn.
- Nhóm chưa biết tổng diện tích bộ giấy chuẩn; do đó `S0_tong_bo_giay_cm2` và `S_la_cm2` để trống. Không suy đoán kích thước giấy từ ảnh. Biểu thức diện tích trong Word chỉ áp dụng khi dùng đúng tổng diện tích của bộ giấy 2,530 g và giấy hình lá cùng định lượng.
- Chưa trích số đo chiều dài/chiều rộng từ ảnh thước để tránh ghi số liệu chưa xác minh.
- Một số ảnh cân là ảnh chụp màn hình có giao diện ứng dụng. Nếu cần cắt khung để đưa vào bài, tạo bản riêng trong `anh-chen-bai/`, giữ nguyên ảnh gốc và toàn bộ phần số cân/thước cần làm bằng chứng.
