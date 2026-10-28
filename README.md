# Nguyễn Quốc Khải - Interactive 3D Portfolio (Software Development)

Trang Portfolio cá nhân tương tác 3D chuẩn Awwwards dành cho **Nguyễn Quốc Khải** (Chuyên ngành: **Software Development**).

## 🌟 Tính Năng Nổi Bật

1. **Giao Diện Semi-Light / Bright Futuristic (Alabaster & Frosted Glass):**
   - Nền màu ngọc trai & ánh sáng ban ngày (`#F4F7FB` đến `#E8EEF7`).
   - Hiệu ứng kính mờ Frosted Glassmorphism cao cấp (`backdrop-filter: blur(16px)`).
   - Điểm nhấn dải màu Electric Indigo (`#4F46E5`), Sky Cyan (`#0EA5E9`) và Soft Violet (`#8B5CF6`).

2. **Quy Tắc Chữ Nghiêm Ngặt ("Chữ Không Bao Giờ Nhảy Dòng"):**
   - Họ tên `Nguyễn Quốc Khải` và `Software Development` luôn hiển thị trên một dòng duy nhất bằng `white-space: nowrap;` kết hợp `clamp(...)` responsive mượt mà.
   - Toàn bộ thanh điều hướng, nút bấm, huy hiệu và tiêu đề kỹ thuật đều tuân thủ `flex-shrink: 0`.

3. **Mô Hình 3D Three.js & Tương Tác Chuột:**
   - Khối hình học trung tâm gồm Icosahedron khúc xạ ánh sáng (Physical Transmission Glass Material) kết hợp Torus Knot mượt mà và các vòng quỹ đạo Geodesic.
   - Các huy hiệu ngôn ngữ 3D (`Java`, `Python`, `React`, `FastAPI`, `MySQL`, `Docker`,...) bay lơ lửng trên quỹ đạo 3 chiều.
   - Hiệu ứng Parallax mượt mà theo tọa độ chuột (`lerp damping 0.05`).
   - Hệ thống 3 nguồn sáng đa sắc (Indigo, Cyan, Violet) đổ bóng và phản chiếu lung linh.

4. **Hiệu Ứng Cuộn 2 Chiều Mượt Mà (Lenis Smooth Scroll + GSAP ScrollTrigger):**
   - Camera 3D tự động di chuyển góc nhìn nghệ thuật khi cuộn xuống và đảo chiều hoàn hảo khi cuộn ngược lên từ dưới lên trên.
   - Thẻ dự án và kỹ năng tích hợp hiệu ứng nghiêng 3D (3D Card Tilt) kết hợp vệt phản chiếu ánh sáng (Specular Glare) theo vị trí con trỏ chuột.
   - Thanh tiến trình dọc (Timeline progress) bám sát độ cuộn trang.

5. **Hệ Sinh Thái Kỹ Năng & Logo Chuẩn Devicon CDN:**
   - 24 thẻ kỹ năng và cơ sở dữ liệu với logo vector chính thức (Java, Python, TypeScript, React, Next.js, FastAPI, Spring Boot, MySQL, PostgreSQL, Redis, Docker, Ubuntu,...).
   - Bộ lọc phân loại trực quan theo danh mục.

6. **Dự Án Thực Chiến & Trình Xem Kiến Trúc:**
   - 4 dự án phần mềm tiêu biểu kèm số liệu hiệu năng.
   - Modal hiển thị chi tiết sơ đồ kiến trúc, điểm nổi bật và công nghệ sử dụng.

7. **Bộ Tương Tác & Tiện Ích Cao Cấp:**
   - Âm thanh tương tác công nghệ cao (Web Audio API Synthesizer - không cần tải file âm thanh ngoài).
   - Nút bật/tắt âm thanh ở góc màn hình.
   - Modal xem và tải CV chuẩn ATS (1-click download).
   - Sao chép Email / Số điện thoại 1-click với thông báo Toast thời gian thực.
   - Form liên hệ mô phỏng với hiệu ứng phản hồi tức thì.

---

## 🚀 Cách Mở & Sử Dụng

Bạn có thể mở trực tiếp tệp `index.html` trong bất kỳ trình duyệt nào:
- **Nhấp đúp vào `index.html`**, hoặc
- Mở bằng Live Server trong VS Code / IDE của bạn.
- Đầy đủ 100% tài nguyên qua CDN (Tailwind, Three.js, GSAP, Lenis, Devicon, Google Fonts) không lo thiếu file.
