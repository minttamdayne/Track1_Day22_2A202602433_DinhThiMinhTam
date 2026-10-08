# Day22 — AI Product GTM & Monetization

**Đinh Thị Minh Tâm · 2A202602433 · Track 1 · 09/10/2026**

Bài lab xây dựng mô hình **Triplan — AI Travel Planner** theo hướng B2C, PLG và usage-based pricing: xác định chi phí cho một lịch trình được xuất thành công, chọn kênh phân phối trong 90 ngày đầu và lập evidence pack để kiểm chứng giả thuyết.

## Hồ sơ nộp bài

- [Excel model](Day22-AI-Product-GTM-Monetization-Model.xlsx): mô hình Cost/Job, Pricing, Value Metric, Channel Fit, 90-Day Plan, Benchmarks và Assumptions/Sources.
- [Word One-Pager](Day22-AI-Product-GTM-One-Pager-Template.docx): one-pager gồm Pricing, Go-to-Market và Evidence Pack của Triplan.

## Kết luận mô hình

Triplan chọn **Usage-based Pricing**: **$2.49 cho mỗi lịch trình 2–5 ngày được kiểm tra hợp lệ và xuất thành công**; không tính API call hoặc kết quả lỗi. Cost/Job dự phóng là **$0.531**, giá sàn theo hệ số 3× là **$1.593**, Gross Margin dự phóng **78.68%**, và containment tối thiểu để đạt GM 60% là **59.28%**. Containment hiện tại **80%** mới là giả định, chưa có telemetry.

Kênh 90 ngày đầu là **PLG qua Organic Google Search**: đưa người dùng từ các truy vấn như “lịch trình Đà Lạt 3 ngày 2 đêm” đến trang lịch trình mẫu, sau đó cho phép tùy chỉnh bằng AI và xuất lịch trình. Mô hình cho ARPU **$2.988/tháng**, ngân sách CAC **$7.053/khách**, trong khi CAC sales-assisted scenario là **$133.33**, cao hơn ngân sách khoảng **18.90 lần**. Đây là đối chứng cho việc chưa chọn Sales-Led, không phải CAC PLG thực tế.

Đầu vào chính vẫn là giả định hoặc chưa được kiểm chứng: 500 job thử/tháng, 80% containment, token usage, infra **$0.22/job**, retry **8%**, HITL và willingness-to-pay. Chưa có conversion, retention, thanh toán hoặc pilot thực tế của Triplan. Vì vậy, các mục tiêu trong kế hoạch 90 ngày là kế hoạch dự kiến, không phải kết quả đã đạt được.

## Evidence Pack và giới hạn xác minh

- **Eval Results:** chưa có; cần đánh giá 40 lịch trình về ngày, địa điểm, ngân sách và trùng lặp trước **31/10/2026**.
- **Risk Checklist:** chưa có; cần kiểm tra dữ liệu địa điểm/giá, PII/consent và phương án xuất/xóa dữ liệu trước **31/10/2026**.
- **Pilot Report:** chưa có; cần pilot 2 tuần với mục tiêu ít nhất 20 người, đo thành công, willingness-to-pay, thanh toán, chi phí AI và hỗ trợ trước **20/11/2026**.
- **Bài test người lạ:** người đọc xác định được sản phẩm, khách hàng và đơn vị tính tiền; xác định được mô hình có lãi và số liệu chứng minh; nhưng chưa xác định được kênh tiếp cận khách hàng một cách đầy đủ.

##
