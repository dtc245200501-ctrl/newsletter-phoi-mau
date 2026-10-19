# Bài thực hành phối màu Newsletter Trello

## Mở bài
Giải nén toàn bộ thư mục rồi nhấp đúp `index.html`. Dùng liên kết Phiên bản 1 / Phiên bản 2 ở đầu trang để chuyển bản.
- newsletter_version1.html: bảng màu tương đồng (Analogous).
- newsletter_version2.html: bảng màu bổ túc (Complementary).
- style.css: bố cục chung, có CSS dự phòng để xem khi mất mạng.
- style1.css, style2.css: biến CSS của mỗi bảng màu.
- Bootstrap 5.3.3 được liên kết qua CDN. Cần mạng để tải Bootstrap; giao diện vẫn có bố cục dự phòng khi offline.

## Lựa chọn màu
Bảng màu được lấy trực tiếp từ công cụ Color Wheel của Adobe Color ngày 19/10/2026 bằng cách chọn Analogous và Complementary với màu gốc #10288C.
https://color.adobe.com/create/color-wheel

| Bản | Màu 1 | Màu 2 | Màu 3 | Màu 4 | Màu 5 |
|---|---|---|---|---|---|
| 1 | #10288C | #0F508C | #1E0F8C | #0F778C | #470F8C |
| 2 | #10288C | #8C6C0F | #1C254D | #372F18 | #9CAFFF |

Bản 1: xanh và tím tạo cảm giác đồng bộ, năng động; dùng trắng trên nền đậm.
Bản 2: xanh đậm và vàng nâu tạo cảm giác trầm, chuyên nghiệp; xanh nhạt làm điểm nhấn cho nút và bảng minh họa.
Hai bản giữ nguyên cấu trúc, nội dung; chỉ thay cách phân bổ màu qua biến CSS. Trắng, xám là màu trung tính hỗ trợ. Minh họa bảng công việc được dựng bằng HTML/CSS, không phụ thuộc ảnh ngoài.
Đề chưa cung cấp file newsletter Trello gốc nên sử dụng cấu trúc Bootstrap gợi ý trong ảnh đề bài.

## Nộp GitHub
1. Tạo repository mới trên GitHub.
2. Chọn Add file → Upload files.
3. Tải các file đã giải nén lên (không chỉ tải file ZIP).
4. Chọn Commit changes.
5. Sao chép link repository và dán vào ô nộp bài.

## Ảnh cần chụp gửi giảng viên
1. Giao diện phiên bản 1 (thấy bảng màu ở cuối).
2. Giao diện phiên bản 2 (thấy bảng màu ở cuối).
3. Adobe Color với từng quy tắc và năm mã HEX tương ứng nếu giảng viên yêu cầu minh chứng thao tác.
4. Repository GitHub có đủ file HTML/CSS.

Chưa đăng GitHub và chưa nộp lên hệ thống học tập.
