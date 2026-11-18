# PREMIER LEAGUE VIETNAM HUB - BÀI TẬP LỚN MÔN THIẾT KẾ WEB (A3)

## 📌 Giới thiệu dự án
Dự án **Premier League Vietnam Hub** là sản phẩm Bài tập lớn A3 môn Thiết kế Web, xây dựng một trang web tĩnh đa trang (multi-page website) chuyên nghiệp dành cho cộng đồng người hâm mộ bóng đá Ngoại Hạng Anh. Website cung cấp thông tin tổng quan về các câu lạc bộ hàng đầu, bảng xếp hạng thời gian thực, lịch thi đấu tâm điểm và bảng thống kê chi tiết cuộc đua Vua phá lưới (Chiếc Giày Vàng).

## 👨‍💻 Thông tin sinh viên thực hiện
- **Họ và tên:** Vũ Nam Hải
- **Mã sinh viên:** 2071020062
- **Chuyên ngành:** Công nghệ Thông tin (CNTT20-04)
- **Trường:** Đại học Đại Nam 
- **Link truy cập trực tiếp (URL):** [Dán link GitHub Pages / Vercel của bạn vào đây]
- **Chạy trực tiếp trên máy (Local):** Tải mã nguồn về máy, mở thư mục `Premier-League-Hub` và nhấp đúp vào file `index.html` để mở trên trình duyệt (hoặc chạy qua tiện ích Live Server trên VS Code).

## 🚀 Các tính năng nổi bật
- **Hệ thống đa trang (Multi-page):** Liên kết mạch lạc giữa trang chủ (`index.html`) và trang phụ thống kê Vua phá lưới (`ghi-ban.html`) qua thanh điều hướng trực quan.
- **Giao diện Responsive & Hiện đại:** 
  - Sử dụng CSS Grid và Flexbox giúp giao diện hiển thị hoàn hảo trên mọi thiết bị từ máy tính để bàn đến điện thoại di động.
  - Phối màu theo chuẩn nhận diện thương hiệu Ngoại Hạng Anh (`#37003c`, `#00ff85`, `#ff2882`).
- **Tương tác JavaScript thông minh:**
  - Bộ lọc tìm kiếm câu lạc bộ tức thì theo tên hoặc biệt danh.
  - Chức năng tra cứu nhanh chân sút và câu lạc bộ trong danh sách ghi bàn.
  - Bục vinh danh Top 3 cầu thủ dẫn đầu danh sách Vua phá lưới.
- **Quản lý tài nguyên hình ảnh:** Tích hợp hệ thống logo câu lạc bộ và ảnh chân dung cầu thủ kèm cơ chế dự phòng (`onerror`) chống lỗi giao diện khi thiếu tệp.

## 📁 Cấu trúc thư mục dự án
```text
📁 Premier-League-Hub/
 ├── index.html       # Trang chủ (Giới thiệu, hệ thống CLB, BXH, Lịch thi đấu)
 ├── ghi-ban.html     # Trang con (Bảng xếp hạng Vua phá lưới & Top 3 cầu thủ)
 ├── style.css        # Tệp định dạng CSS dùng chung cho toàn bộ dự án
 └── 📁 images/       # Thư mục chứa tài nguyên hình ảnh
      ├── arsenal.png
      ├── liverpool.png
      ├── mancity.png
      ├── chelsea.png
      ├── manutd.png
      ├── tottenham.png
      ├── haaland.jpg
      ├── salah.jpg
      └── palmer.jpg