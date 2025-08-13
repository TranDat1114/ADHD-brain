# Mô phỏng Dòng Suy Nghĩ Phi Tuyến (ADHD)

Trang web một trang (single HTML) mô phỏng cách luồng suy nghĩ của một bộ não ADHD có thể:

- Phân nhánh nhanh từ một ý trung tâm sang ý tưởng, ký ức, phân tâm, hoặc nhiệm vụ khác.
- Nhảy cóc (jump) bất ngờ tới một thought xa không liên quan rõ ràng.
- Mất dần (fade) các ý cũ theo thời gian trong khi ý mới sinh ra liên tục.
- Bị ảnh hưởng bởi mức hỗn loạn (chaos), xác suất phân nhánh và thời gian lưu giữ mà người dùng điều chỉnh.

Mục tiêu: Trực quan hoá cảm giác “dòng suy nghĩ bật tắt và rẽ nhánh” – giúp người xem thấu hiểu trải nghiệm nhận thức ADHD (không phải công cụ chẩn đoán y khoa).

## Cách tương tác nhanh

- Kéo (Alt + kéo chuột) hoặc chạm để pan; Ctrl + cuộn để zoom.
- Nhấn “Nhảy cóc” để ép một cú chuyển ngẫu nhiên.
- Thêm ý nghĩ của bạn ở ô nhập để xem nó lan nhánh.
- Tạm dừng / Tiếp tục để quan sát trạng thái tĩnh.

## Kỹ thuật chính

Vanilla HTML/CSS/JS, không thư viện ngoài. Các “thought” là thẻ DIV được đặt trong không gian 2D với chuyển động jitter nhẹ; quan hệ cha-con được nối bằng đường SVG. Xác suất xuất hiện loại thought mới dựa trên ma trận chuyển tiếp + heuristics từ từ khoá.

## Lưu ý

Mô phỏng chỉ nhằm mục đích giáo dục và minh họa. Không dùng để tự chẩn đoán hay thay thế tư vấn chuyên gia.

---
Bạn có thể tùy biến danh sách mảnh văn bản (FRAGMENTS), ma trận TRANSITION hoặc giao diện theo nhu cầu.

## Tác giả

TranDat1114  
Github: [TranDat1114](https://github.com/TranDat1114)
