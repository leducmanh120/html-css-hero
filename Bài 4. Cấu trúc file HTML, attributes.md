# Bài 4. Cấu trúc file HTML, attributes

- Mỗi file HTML sẽ có phần đuôi mở rộng là `.html`
- Khi ta muốn đưa website lên internet, chúng ta cần thuê hosting/server (máy chủ web) để lưu trữ website thì người khác mới truy cập được. Trên hầu hết các máy chủ web đều được cấu hình mặc định để tự động đọc file index.html đầu tiên và hiển thị ra website. Vì vậy ta thường dùng file để index.html code trang chủ.
- Tìm hiểu kỹ hơn về web hosting <a href="https://tiny.one/4vwd7arx" target="_blank" rel="noopener noreferrer">tại đây</a>.

## Cấu trúc file HTML

- `<!DOCTYPE html>`: là dòng code đầu tiên cần được khai báo trong mọi file HTML. Khai báo DOCTYPE giúp trình duyệt hiểu về phiên bản HTML mà website đang sử dụng (HTML5).
- Thẻ `<html>`: toàn bộ trang web được bao bọc trong cặp thẻ html (gồm thẻ mở `<html>` và thẻ đóng `</html>`). Thẻ `<html>` (hay phần tử `<html>`) còn được gọi là phần tử gốc (**root**), đây là phần tử cấp cao nhất vì tất cả các phần tử khác đều là con của phần tử này.
- Thẻ `<head>`: thẻ `<head>` là nơi chứa các thẻ _meta_, là các thẻ cung cấp thêm thông tin hiển thị của trang web. Ví dụ: tiêu đề trang web, các đường link tới file CSS, khả năng thu/phóng của trang web,…
  Thẻ `<body>`: thẻ `<body>` là nơi chứa toàn bộ nội dung hiển thị của trang web. Mọi nội dung người dùng nhìn thấy trên các trang web đều nằm trong thẻ `<body>`.

## Attributes

- Thuộc tính (attribute) được sử dụng để bổ sung thêm thông tin và dữ liệu cho các thẻ HTML. Các thuộc tính có dạng `key="value"` và luôn được viết trong thẻ mở của các thẻ HTML (không bao giờ được viết trong thẻ đóng). Có thể sử dụng đồng thời nhiều thuộc tính trong một thẻ HTML, mỗi thuộc tính (mỗi cặp `key="value"`) được cách nhau bởi một khoảng trắng.
- Các trang web sẽ sử dụng thuộc tính `lang` trong thẻ mở html nhằm chỉ định ngôn ngữ được sử dụng trong nội dung của trang web. Mã ngôn ngữ của tiếng Anh là `en`, tiếng Việt là `vi`, tìm hiểu thêm [tại đây](https://tiny.one/yzu3mdmm).
- <a href="https://tiny.one/4z9cnjpe" target="_blank" rel="noopener noreferrer">Global Attributes</a>: là những thuộc tính có thể sử dụng cho toàn bộ các thẻ HTML.

---
