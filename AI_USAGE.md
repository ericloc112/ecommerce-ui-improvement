# AI Usage Log

## 1. Công cụ AI

Tên công cụ: Google Gemini (Personal AI Collaborator)

## 2. Mục đích sử dụng

- Phân tích nghiệp vụ và thiết kế trải nghiệm người dùng (UX/UI) cho 5 khu vực của website thương mại điện tử.
- Giải thích và xây dựng cấu trúc mã nguồn HTML5 và CSS3 tách file riêng biệt.
- Đề xuất bố cục, màu sắc và tối ưu hóa trải nghiệm đáp ứng (Responsive Design) cho máy tính và điện thoại.
- Hỗ trợ gỡ lỗi hiển thị khi gặp sự cố mã nguồn.

## 3. Prompt đã sử dụng

- "Hãy giúp tôi lập bảng phân tích các khu vực: Trang chủ, Danh mục sản phẩm, Chi tiết sản phẩm, Tìm kiếm, Giỏ hàng..."
- "Tôi đang thực hiện bài tập phát triển giao diện website thương mại điện tử bằng HTML5 và CSS3. Tôi muốn cải tiến khu vực: trang chủ..."
- "như phần này bạn đag nhầm loại dịch vụ rồi 'Đi Chung Xe - Leo núi mỗi tuần' vaf website https://dichungxe.net/"
- "Tôi chọn thiết kế hiện đại, chuyên nghiệp hơn; phạm vi: trang chủ đầy đủ Responsive Desktop và Mobile. Hãy triển khai mã nguồn theo phương án đã thống nhất."

## 4. Kết quả AI đề xuất

- Đưa ra bảng phân tích chi tiết 5 khu vực với đầy đủ mục đích, thành phần giao diện, ưu điểm, vấn đề và đề xuất cải tiến.
- Cung cấp mã nguồn hoàn chỉnh gồm tệp `index.html` (chuẩn semantic tags) và `style.css` (sử dụng CSS Variables, Flexbox, Grid và Media Queries) không dùng backend hay thư viện ngoài.

## 5. Kiểm tra và điều chỉnh

- **Điểm đã kiểm tra:** Kiểm tra tính chính xác của tên miền và mô hình hoạt động thực tế của `dichungxe.net` (chuyên về trekking, leo núi thay vì xe ghép hành khách thông thường).
- **Điểm sửa đổi / khắc phục:** Khắc phục lỗi người dùng mở tệp HTML bị hiển thị dạng văn bản thô bằng cách hướng dẫn lại thao tác dán mã chính xác vào tệp `index.html`.
- **Phần không sử dụng:** Không sử dụng các JavaScript framework nặng hay thư viện CSS ngoài (như Bootstrap/Tailwind) để đảm bảo tuân thủ đúng yêu cầu chỉ dùng HTML5 và CSS3 thuần.

## 6. Phần tôi hiểu và có thể giải thích

- **Cấu trúc HTML5 Semantic:** Hiểu cách phân chia các vùng ngữ nghĩa như `<header>`, `<main>`, `<section>`, `<article>`, `<footer>` giúp tối ưu SEO và khả năng truy cập (Accessibility).
- **Hệ thống CSS Grid & Flexbox:** Hiểu cách dùng `grid-template-columns: repeat(4, 1fr)` để dàn đều 4 sản phẩm trên máy tính và tự động co giãn thành 1 hoặc 2 cột trên thiết bị di động thông qua Media Queries (`@media (max-width: 768px)`).
- **Kỹ thuật Responsive:** Hiểu cách ẩn/hiện các thành phần linh hoạt (như ẩn menu ngang trên PC và bật thanh điều hướng đáy `mobile-bottom-nav` trên điện thoại) nhằm tối ưu hóa trải nghiệm người dùng thực tế.
