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

Báo cáo giữ tỷ lệ, tối đa hai ảnh một trang để đọc thước và số cân. Với 10 ảnh cân C3-11 đến C3-20, khung ảnh trong Word cắt 200 px phía trên và 220 px phía dưới của ảnh 720 × 1600 px để không hiển thị tên người gửi và thanh ứng dụng. Phần lá, hình giấy và số cân được giữ trong khung. Các tệp ảnh lưu tại đây vẫn là bản nhận được, nguyên dữ liệu; Word chỉ điều chỉnh khung hiển thị. Hai ảnh minh họa từ mẫu Word được ghi nguồn riêng ở Chương 2.

## Ghi chú dùng cho tiểu luận

- Số cân trong CSV được đọc từ màn hình của từng ảnh, đơn vị g. Đây là số hiển thị, chưa phải kết quả tính toán hoặc số liệu đã hiệu chỉnh.
- Tên cây và cặp lá–giấy được đối chiếu theo [file kết quả đo kích thước](du-lieu/Ket_qua_do_kich_thuoc_la.docx) do nhóm cung cấp. Mã mẫu thống nhất trong Word, danh mục ảnh và [bảng số liệu 3.1](bang-3-1-so-lieu-la.csv): M01 Xà cừ; M02 Muồng hoàng yến; M03 Muồng ràng ràng; M04 Giáng hương quả to; M05 Keo lá tràm. Các cột `ma_mau` và `ten_cay` trong danh mục chỉ rõ liên kết này.
- Muồng hoàng yến: lá C3-06, giấy C3-05, cân lá 0,787 g (C3-19), cân giấy 0,539 g (C3-20). Giáng hương quả to: lá C3-04, giấy C3-08, cân lá 0,802 g (C3-17), cân giấy 0,444 g (C3-18). Việc đối chiếu dựa theo cặp lá thật 1–giấy cắt 1 và lá thật 2–giấy cắt 2 trong file kết quả mới.
- [Bảng kích thước nguồn](ket-qua-do-kich-thuoc-la.csv) giữ đủ 10 dòng đo, tên ảnh và ghi chú nguyên văn; bổ sung mã ảnh lưu trữ tương ứng. Các tên `6216.jpg`…`6234.jpg` là tên ghi trong file kết quả, khác với tên các tệp đã nhận trong ZIP.
- Ảnh `C3-21` hiển thị nhiều tờ giấy trên cân và số `2.530 g`; chưa xác nhận số tờ hoặc diện tích giấy chuẩn.
- [File kết quả mới có S₀](du-lieu/Ket_qua_do_kich_thuoc_la_co_S0.docx) định nghĩa S₀ là diện tích **hình chữ nhật bao quanh mẫu**, bằng dài × rộng. Đã kiểm tra và tính đủ 10 giá trị trong [bảng S₀](ket-qua-do-kich-thuoc-la-co-S0.csv), kèm chênh lệch dài/rộng/diện tích bao trong bảng tổng hợp 3.1.
- Diện tích bao trong file không phải diện tích thực của phiến lá và không phải diện tích bộ giấy chuẩn 2,530 g. Hai cột `S_giay_chuan_cm2` và `S_phien_la_can_giay_cm2` còn trống vì chưa có phép đo/đối chiếu tương ứng. Không tự gán diện tích bao hoặc tổng các diện tích bao cho bộ giấy chuẩn.
- Chiều dài và chiều rộng được chép đúng từ file kết quả của nhóm, không tự ước lượng lại từ ảnh. Không dùng dài × rộng của lá hoặc hình giấy làm diện tích thực của phiến lá hay làm S₀.
- Khung cắt trong Word có thể chỉnh lại bằng công cụ định dạng ảnh của Word; nội dung các ảnh nguồn không bị vẽ lại hoặc thay số đo.
