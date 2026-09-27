# PROMPT: THIẾT KẾ LANDING PAGE BẤT ĐỘNG SẢN VINHOMES GRAND PARK

Bạn là một Chuyên gia Lập trình Frontend (Senior Frontend Developer) và Chuyên gia Thiết kế UI/UX hàng đầu. Hãy tạo một trang Landing Page hoàn chỉnh, sang trọng và tối ưu chuyển đổi cho dự án bất động sản **Vinhomes Grand Park tại TP. Thủ Đức**.

---

## 1. YÊU CẦU KỸ THUẬT & RÀNG BUỘC (TECHNICAL CONSTRAINTS)

* **Công nghệ sử dụng:**
  * HTML5 (Semantic HTML)
  * CSS3 (Custom CSSVars)
  * Vanilla JavaScript (JS thuần, không dùng thư viện ngoài ngoại trừ Bootstrap)
  * Bootstrap 5 (nhúng qua CDN)
  * Bootstrap Icons (nhúng qua CDN)
* **Quy cách đóng gói:**
  * Toàn bộ mã nguồn (HTML, CSS, JavaScript) nằm gọn trong **duy nhất 1 tệp `index.html`**.
  * CSS nằm trong thẻ `<style>` ở phần `<head>`.
  * JS nằm trong thẻ `<script>` ngay trước thẻ đóng `</body>`.
  * **Tệp phải chạy được ngay** khi người dùng mở trực tiếp `index.html` trên trình duyệt.
* **Tương thích:** Responsive hoàn hảo trên Desktop, Tablet và Mobile.
* **Tuyệt đối không dùng:** Backend, Node.js, React/Vue/Angular, Sass/Less build tools.

---

## 2. HỆ THỐNG THIẾT KẾ & MÀU SẮC (DESIGN SYSTEM)

* **Phong cách:** Premium, Sang trọng, Tối giản, Hiện đại. Ưu tiên không gian thoáng (Whitespace) và khoảng cách giữa các phần.
* **Bảng màu chủ đạo (Color Palette):**
  * `Main Background`: `#f2f2f2`
  * `Card / Section Background`: `#ffffff`
  * `Primary Text / Accent Color`: `#2d2d86` (Xanh navy đậm sang trọng)
  * `Secondary Text`: `#555555`
  * `CTA Hover / Focus`: Tông màu `#1c1c5e`
* **Typography:** Phông chữ không chân hiện đại (Segoe UI, system-ui, sans-serif), phân cấp chữ rõ ràng (Hierarchy).
* **Hiệu ứng:** Bo góc nhẹ (`border-radius: 8px - 16px`), bóng đổ tinh tế (`box-shadow` mỏng nhẹ), hiệu ứng Hover chuyển động mượt (Transition 0.3s).

---

## 3. CẤU TRÚC VÀ NỘI DUNG CÁC SECTION

### Section 1: Header / Navbar
* Sticky hoặc Fixed top, nền trắng hơi trong suốt (`backdrop-filter` nhẹ).
* **Logo/Brand:** `VINHOMES` (Viết hoa, màu `#2d2d86`, font-weight dày).
* **Menu điều hướng:** Trang chủ, Về dự án, Tiện ích, Vị trí, Liên hệ.
* **Nút CTA:** "Đăng ký tư vấn" (Nổi bật).
* **Mobile:** Tự động co lại thành Hamburger menu của Bootstrap.

### Section 2: Hero Section
* Chiều cao `70vh` đến `90vh` trên Desktop.
* **Bên trái (Cột nội dung):**
  * Badge nhỏ: `VINHOMES GRAND PARK`
  * Tiêu đề lớn (H1): *"Kiến tạo chuẩn sống thượng lưu giữa lòng TP. Thủ Đức"*
  * Mô tả ngắn (2-3 câu): Giới thiệu không gian sống xanh và hiện đại.
  * 2 Nút CTA: Nút chính *"Nhận thông tin dự án"* (Màu navy) và Nút phụ *"Xem tiện ích"* (Border outline).
* **Bên phải (Cột hình ảnh):**
  * Hình ảnh biệt thự / khu đô thị cao cấp chất lượng cao (lấy link ảnh chất lượng từ Unsplash).
  * Bo góc ảnh đẹp mắt, có shadow nâng khối.

### Section 3: Project Introduction (Giới thiệu)
* Bố cục 2 cột: 1 Cột ảnh minh họa + 1 Cột văn bản giới thiệu vị trí chiến lược và giá trị an cư tại TP. Thủ Đức.

### Section 4: Features Section (Giá trị cốt lõi)
* Tiêu đề: *"Những giá trị tạo nên chuẩn sống khác biệt"*
* 3 Card tính năng xếp hàng ngang (Responsive trên mobile):
  1. **Lối sống thượng lưu:** Icon sang trọng (`bi-gem`), mô tả về cộng đồng tinh hoa.
  2. **Tiện ích tối ưu:** Icon tiện ích (`bi-stars`), mô tả hệ sinh thái trọn vẹn.
  3. **Thông tin minh bạch:** Icon bảo mật (`bi-shield-check`), mô tả quy trình hỗ trợ rõ ràng.

### Section 5: Amenities Grid (Hệ thống tiện ích)
* Lưới 6 ô icon tròn hiển thị các tiện ích: Công viên, Hồ bơi, Khu thể thao, Khu vui chơi, Trung tâm thương mại, Y tế & Giáo dục.

### Section 6: Gallery Section (Thư viện hình ảnh)
* Lưới 3 hình ảnh kiến trúc / nội thất cao cấp. Hiệu ứng phóng to nhẹ (Zoom in) khi di chuột qua.

### Section 7: CTA & Contact Form
* Banner CTA khối nổi màu `#2d2d86` chứa Form đăng ký.
* Form bao gồm: Họ tên, Số điện thoại, Email, Nội dung cần tư vấn + Nút *"Gửi yêu cầu tư vấn"*.
* Validation bằng JS thuần phía Client: Khi gửi form, không load lại trang mà hiển thị alert/toast thông báo: *"Cảm ơn bạn! Thông tin của bạn đã được ghi nhận."*

### Section 8: Footer
* Thương hiệu VINHOMES, mô tả ngắn, danh mục liên kết nhanh.
* Thông tin liên hệ mẫu: `0900 000 000`, `contact@example.com`.
* Dòng Copyright cuối trang.

---

## 4. TÍNH NĂNG JAVASCRIPT & HỆ THỐNG HIỆU ỨNG

1. **Scroll Reveal Animation:** Sử dụng `IntersectionObserver` trong Vanilla JS để các Section xuất hiện mượt mà (Fade-in-up) khi cuộn chuột đến.
2. **Form Handling:** Lắng nghe sự kiện `submit` form, `preventDefault()`, kiểm tra dữ liệu và hiện thông báo xác nhận thành công.
3. **Smooth Scroll:** Tự động cuộn mượt khi bấm vào các liên kết trên Navbar.
4. **Auto-close Mobile Menu:** Tự động đóng menu Hamburger khi người dùng bấm vào một mục menu trên điện thoại.

---

## 5. SEO VÀ ACCESSIBILITY (CHUẨN CHẤT LƯỢNG)

* Thẻ `<title>` và `<meta name="description">` đầy đủ chuẩn SEO.
* Sử dụng chuẩn Semantic Tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`).
* Tất cả thẻ `<img>` phải chứa `alt` miêu tả cụ thể.

---

## 6. YÊU CẦU ĐẦU RA (OUTPUT DELIVERABLE)

Hãy xuất ra **DUY NHẤT một khối mã nguồn HTML hoàn chỉnh** nằm trong codeblock ````html ... ```` chứa đầy đủ CSS và JS bên trong. Không để lại chú thích dở dang (`// Add more code here...`), không viết thiếu bất kỳ đoạn code nào.
