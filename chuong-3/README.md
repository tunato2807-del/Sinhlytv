# Tư liệu ảnh Chương 3

Danh mục chuẩn bị cho các ảnh đo kích thước lá, mẫu giấy theo hình lá và cân khối lượng, phục vụ chèn hình vào bài tiểu luận.

**Trạng thái: đã lập danh mục từ 21 ảnh hiển thị trong hội thoại; chưa lưu tệp ảnh vào kho.** Cần bổ sung tệp ảnh đính kèm ở dạng tải xuống được để hoàn thành việc lưu trữ.

## Danh mục

Xem `danh-muc-anh.csv`. Mã `C3-01` đến `C3-21` theo đúng thứ tự ảnh trong tin nhắn, không phải số hình chính thức trong tiểu luận. Các tên trong cột `ten_co_so_du_kien` là tên dự kiến, chưa phải đường dẫn tới ảnh có sẵn.

| Nhóm | Số ảnh | Thư mục dự kiến |
| --- | ---: | --- |
| Đo lá với thước | 5 | `anh-goc/do-la/` |
| Đo mẫu giấy theo hình lá | 5 | `anh-goc/do-mau-giay/` |
| Cân lá | 5 | `anh-goc/can-la/` |
| Cân mẫu giấy theo hình lá | 5 | `anh-goc/can-mau-giay/` |
| Cân các tờ giấy | 1 | `anh-goc/can-giay/` |

## Khi bổ sung ảnh

1. Nhận các tệp JPG/PNG hoặc ZIP chứa ảnh. Đối chiếu nội dung với thứ tự và mô tả trong danh mục, không chỉ dựa vào thứ tự tệp trong ZIP.
2. Giữ nguyên nội dung, độ phân giải và định dạng ảnh nhận được. Dùng tên cơ sở dự kiến cùng phần mở rộng đúng với định dạng thực tế; không chuyển đổi ảnh để đổi đuôi tệp.
3. Kiểm tra mỗi ảnh mở được, đủ 21 ảnh và không trùng tệp. Cập nhật danh mục bằng đường dẫn thực tế, tên tệp nguồn và trạng thái đã lưu.
4. Lưu ảnh gốc cùng danh mục lên GitHub, rồi kiểm tra commit từ kho từ xa trước khi báo hoàn tất.

## Ghi chú dùng cho tiểu luận

- Số cân trong CSV được đọc từ màn hình của từng ảnh, đơn vị g. Đây là số hiển thị, chưa phải kết quả tính toán hoặc số liệu đã hiệu chỉnh.
- Chưa xác nhận tên loài, mã mẫu, số lá trên đĩa cân hoặc cặp lá–mẫu giấy tương ứng. Không ghép cặp các ảnh để tính diện tích trước khi xác nhận.
- Ảnh `C3-21` hiển thị nhiều tờ giấy trên cân và số `2.530 g`; chưa xác nhận số tờ hoặc diện tích giấy chuẩn.
- Chưa trích số đo chiều dài/chiều rộng từ ảnh thước để tránh ghi số liệu chưa xác minh.
- Một số ảnh cân là ảnh chụp màn hình có giao diện ứng dụng. Nếu cần cắt khung để đưa vào bài, tạo bản riêng trong `anh-chen-bai/`, giữ nguyên ảnh gốc và toàn bộ phần số cân/thước cần làm bằng chứng.
