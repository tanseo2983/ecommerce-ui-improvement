# E-commerce UI Improvement

## 1. Giới thiệu

Đây là bài tập cá nhân Chương 1 của môn Phát triển ứng dụng WEB/TMĐT. Bài tập tập trung vào thiết kế lại thẻ sản phẩm trong danh mục Laptop của Thế Giới Di Động. Trang minh họa có bốn mẫu laptop để thể hiện cách bố trí hình ảnh, giá, thông số và ưu đãi khi người mua xem nhiều sản phẩm cùng lúc.

## 2. Website tham khảo

- **Tên website** — Thế Giới Di Động.
- **URL** — [thegioididong.com](https://www.thegioididong.com/).
- **Khu vực đã khảo sát** — Trang chủ, danh mục Laptop, chi tiết sản phẩm, tìm kiếm, so sánh và giỏ hàng.
- **Khu vực chọn cải tiến** — Thẻ sản phẩm trong danh mục Laptop.

## 3. Chức năng

- Hiển thị danh sách bốn mẫu laptop gồm MacBook Air, ASUS Vivobook, HP Pavilion và Dell Inspiron.
- Hiển thị hình ảnh, tên máy, giá bán, giá gốc, mức giảm, ưu đãi và thông số kỹ thuật.
- Minh họa các nút **Thêm vào giỏ** và **So sánh** trên từng thẻ.
- Điều chỉnh số cột của danh sách theo chiều rộng màn hình.

Giá, ưu đãi và thông tin bán hàng trên trang phục vụ mục đích minh họa cho bài tập.

## 4. Công nghệ

- **HTML5** dùng để tạo cấu trúc trang và nội dung các thẻ.
- **CSS3** dùng để định dạng thẻ, nhãn ưu đãi và lưới sản phẩm trên các kích thước màn hình.

## 5. Cách chạy

1. Tải mã nguồn về máy và giải nén nếu tải dưới dạng ZIP.
2. Mở tệp `index.html` bằng trình duyệt. Tệp CSS nằm ở `css/style.css` và hình ảnh nằm trong thư mục `images/`.

## 6. Cải tiến đã thực hiện

Khi khảo sát danh mục Laptop, tôi thấy phần trăm giảm đã xuất hiện cạnh giá gốc nhưng có kích thước nhỏ. Tôi dùng nhãn giảm giá có nền vàng để mức giảm dễ nhận ra khi xem lướt. Tôi tách màu của nhãn trả chậm, ưu đãi thành viên và ưu đãi sinh viên để người xem phân biệt các nhóm thông tin.

Tôi trình bày thông số kỹ thuật bằng biểu tượng đi kèm giá trị và đặt ảnh quà tặng trong một khối riêng. Ở cuối thẻ, hai nút **Thêm vào giỏ** và **So sánh** nằm cùng hàng. Nút **Thêm vào giỏ** rộng hơn để làm rõ thao tác chính.

## 7. Hỗ trợ từ AI

Tôi dùng AI để hỗ trợ phân tích website tham khảo, đề xuất bố cục thẻ Laptop, tạo mã HTML/CSS và giải thích các phần mã cần chỉnh. Tôi đối chiếu đề xuất với kết quả khảo sát và chọn phương án phù hợp với mục tiêu của bài. Nhật ký prompt, kết quả và các điểm đã kiểm tra hoặc điều chỉnh được ghi trong [AI_USAGE.md](AI_USAGE.md).
