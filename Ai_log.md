# NHẬT KÝ SỬ DỤNG AI (AI_LOG)
* **Môn học / Bài tập:** Thiết kế & Phát triển Web
* **Công cụ AI đã sử dụng:** Gemini / ChatGPT
* **Mục đích chung:** Hỗ trợ gợi ý cấu trúc giao diện, kiểm tra lỗi CSS responsive và rà soát câu chữ báo cáo.

| STT | Thời gian / Giai đoạn | Nội dung yêu cầu (Prompt) | Kết quả AI gợi ý | Cách sinh viên kiểm tra & chỉnh sửa |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Lên cấu trúc HTML | Gợi ý bố cục trang web giới thiệu sản phẩm gồm header, bảng thông số và footer. | Đưa ra khung thẻ semantic (`<header>`, `<main>`, `<table>`, `<footer>`). | Tự viết lại các class theo quy chuẩn đặt tên của bài và điền nội dung thực tế. |
| 2 | Sửa lỗi Responsive (TC4b) | Cách khắc phục bảng bị tràn khung và mất chữ khi thu nhỏ màn hình điện thoại. | Đề xuất bọc thẻ `<table>` vào một thẻ `<div>` có thuộc tính `overflow-x: auto;`. | Tạo class `.table-wrap` trong file CSS, áp dụng vào HTML và test lại trên Chrome DevTools (F12). |
| 3 | Hoàn thiện báo cáo | Rà soát lỗi chính tả và thuật ngữ cho phần mô tả sửa lỗi và tài liệu bàn giao. | Chỉnh sửa lỗi gõ từ ("wed" -> "web", "aut" -> "auto") và chuẩn hóa văn phong. | Đối chiếu lại với yêu cầu của giảng viên trước khi điền vào phiếu nộp bài. |
