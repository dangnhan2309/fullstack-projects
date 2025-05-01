# 🚆 Metro Info Platform - Full Stack + Data Engineering Project

> Một dự án học tập giúp bạn trở thành **Full Stack Developer** chuyên về **Data Engineering**, thông qua việc xây dựng một website cung cấp thông tin và phân tích mạng lưới **tàu điện đô thị** như HCM Metro, Tokyo Metro,...

---

## 🎯 Mục Tiêu Dự Án

| Mục tiêu | Trạng thái |
|----------|------------|
| ✔️ Xây dựng API cung cấp dữ liệu tuyến tàu điện | ☐ |
| ✔️ Thiết kế giao diện bản đồ tương tác | ☐ |
| ✔️ ETL dữ liệu từ Tokyo/HCM Metro để phân tích | ☐ |
| ✔️ Tạo hệ thống dashboard và biểu đồ trực quan | ☐ |
| ✔️ Phân tích dữ liệu mạng lưới tàu điện theo thời gian | ☐ |
| ✔️ So sánh hệ thống CBTC / không-CBTC | ☐ |

---

## 🗓️ Kế Hoạch Theo Tuần

| Tuần | Nội dung | Trạng thái |
|------|----------|------------|
| 1 | Phân tích yêu cầu, thiết kế CSDL, thu thập dữ liệu ban đầu | ☐ |
| 2 | Xây dựng backend API (Express/FastAPI) kết nối database | ☐ |
| 3 | Phát triển giao diện frontend (React/Next.js) + gọi API | ☐ |
| 4 | Xây dựng pipeline ETL để thu thập & phân tích dữ liệu | ☐ |
| 5 | Hiển thị bản đồ tương tác, mô phỏng tuyến chạy | ☐ |
| 6 | Hoàn thiện dashboard thống kê và triển khai sản phẩm | ☐ |

👉 Dùng emoji ☐ ✅ để đánh dấu trạng thái từng mục.

---

## 📦 Công Nghệ Sử Dụng

| Thành phần | Công nghệ |
|------------|-----------|
| Frontend | React.js, Tailwind CSS, Leaflet.js / Mapbox |
| Backend | Node.js (Express) hoặc Python (FastAPI) |
| Database | PostgreSQL, MongoDB |
| ETL & Phân tích | Python (pandas, requests), Jupyter |
| Visualization | Chart.js, Mapbox, Dash |
| DevOps | Docker, Docker Compose, Railway / Render |
| CI/CD | GitHub Actions (optional) |

---

## ⚙️ Khởi Chạy Dự Án Với Docker

```bash
# clone project
git clone https://github.com/yourusername/metro-info-platform.git
cd metro-info-platform

# khởi động toàn bộ hệ thống
docker-compose up --build
