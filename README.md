# E-commerce UI Improvement

## 1. Giới thiệu

Dự án này tập trung nghiên cứu, phân tích và cải tiến giao diện trang chủ của nền tảng cộng đồng du lịch trải nghiệm, leo núi và trekking. Giao diện được thiết kế theo phong cách hiện đại, tối ưu hóa trải nghiệm người dùng (UX/UI) và tương thích hoàn toàn trên đa thiết bị từ máy tính đến điện thoại di động.

## 2. Website tham khảo

- Tên website: Đi Chung Xe (DCX)
- URL: [https://dichungxe.net](https://dichungxe.net)
- Khu vực đã khảo sát: 
  1. Trang chủ
  2. Danh mục sản phẩm (Lịch trình chuyến đi)
  3. Chi tiết sản phẩm (Chi tiết lịch trình)
  4. Tìm kiếm
  5. Giỏ hàng (Xác nhận đặt chỗ)

## 3. Chức năng

- Hiển thị danh sách sản phẩm (các tour trekking/leo núi nổi bật).
- Hiển thị hình ảnh minh họa, tên chuyến đi, thời lượng, cấp độ thể lực và giá tiền trọn gói.
- Bố cục hỗ trợ nhiều kích thước màn hình (Responsive Design cho Desktop, Tablet và Mobile).
- Khung tìm kiếm và bộ lọc nhanh theo địa điểm, thời gian và cấp độ thể lực.
- Thanh điều hướng tối ưu cho ngón cái trên thiết bị di động (Mobile Bottom Navigation).

## 4. Công nghệ

- HTML5 (sử dụng các thẻ ngữ nghĩa chuẩn SEO như `<header>`, `<main>`, `<section>`, `<article>`, `<footer>`)
- CSS3 (sử dụng CSS Variables, Flexbox, CSS Grid và Media Queries)

## 5. Cách chạy

1. Tải và giải nén thư mục dự án (ví dụ: `dichungxe-modern`).
2. Đảm bảo hai tệp `index.html` và `style.css` nằm cùng một cấp trong thư mục.
3. Mở tệp `index.html` bằng bất kỳ trình duyệt web hiện đại nào (Chrome, Edge, Safari...).

## 6. Cải tiến đã thực hiện

- **Vấn đề ban đầu:** Giao diện cũ hoặc các thiết kế chung chung thường nhầm lẫn mô hình đi chung xe giao thương mại với dịch vụ du lịch trekking, thiếu tính trực quan về cấp độ thể lực và chưa tối ưu trải nghiệm thao tác trên điện thoại.
- **Thay đổi đã thực hiện:** 
  - Định hình lại đúng đặc thù dịch vụ outdoor (tour leo núi, cắm trại, trekking).
  - Bổ sung khung tìm kiếm thông minh tích hợp chọn cấp độ thể lực và ngày khởi hành.
  - Thiết kế thẻ sản phẩm (Trip Card) hiển thị rõ các tiện ích bao gồm (xe đưa đón, bảo hiểm, y tế, porter) giúp tăng tỷ lệ chuyển đổi.
  - Thêm thanh menu đáy cố định (`Mobile Bottom Navigation`) giúp người dùng mobile thao tác thuận tiện bằng một tay.

## 7. Hỗ trợ từ AI

- **Phần AI hỗ trợ:** Đề xuất cấu trúc bảng phân tích UX/UI cho 5 khu vực, tư vấn bố cục trang chủ hiện đại (Modern Outdoor E-commerce) và viết mẫu mã nguồn HTML5/CSS3 tách file riêng.
- **Phần tôi đã kiểm tra, điều chỉnh hoặc bổ sung:** 
  - Đính chính lại định hướng dịch vụ của website từ xe ghép thương mại thành cộng đồng leo núi/trekking (`dichungxe.net`).
  - Kiểm tra và sửa lỗi hiển thị cấu trúc thư mục dạng văn bản nhầm lẫn trong tệp `index.html`.
  - Tự tay kiểm tra khả năng tương phản màu sắc, cấu trúc lưới Responsive trên các kích thước màn hình thực tế qua công cụ Developer Tools của trình duyệt.
