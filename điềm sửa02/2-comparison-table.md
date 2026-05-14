---
artifact: 2 — Bảng so sánh 2 sản phẩm theo 5 mục
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Chuyển giao Phase 2 → Phase 3
time: 5 phút
input: 1-research-notes.md + screenshots/
nop-cuoi: Không — file trung gian
---

# 2 — Bảng so sánh 2 sản phẩm theo 5 mục slide deck

Dữ liệu lấy từ [1-research-notes.md](./1-research-notes.md), [Gemini-result.md](./Gemini-result.md), [Chatgpt-result.md](./Chatgpt-result.md) và folder [screenshots/](./screenshots/).

---

## Phần A — Bảng so sánh 5 mục

| Mục | Sản phẩm A — Gemini Ultra / Gemini 3.1 Pro | Sản phẩm B — ChatGPT Plus / GPT-5.5 |
|---|---|---|
| **S1 — Product Moment**<br><sup>Entry point + ý định người dùng + surface chính</sup> | Entry point là Gemini nền tối, badge **ULTRA**, menu model hiển thị **Gemini 3 → Pro — Giải toán và lập trình nâng cao với 3.1 Pro**. Surface chính là chat tổng quát, phù hợp người dùng muốn nhận shortlist laptop nhanh và có giải thích kỹ thuật. | Entry point là ChatGPT nền sáng, tài khoản **Plus**, model selector hiển thị **Mới nhất · 5.5** và chế độ **Thinking**. Surface chính là chat có khả năng tra cứu/citation, phù hợp người dùng cần vừa gợi ý vừa kiểm chứng nguồn. |
| **S2 — Workflow Evidence**<br><sup>Trước / trong / sau khi dùng AI. Friction chính</sup> | Workflow: mở Gemini → chọn Pro → nhập prompt → đọc output. Friction chính là output chỉ ghi tên nguồn tham khảo, không có link trực tiếp nên người dùng vẫn phải tự kiểm tra giá/cấu hình. | Workflow: mở ChatGPT → chọn GPT-5.5 Thinking → nhập prompt → đọc output có citation. Friction thấp hơn ở bước xác minh vì output có nguồn/link, nhưng thời gian suy nghĩ hiển thị khoảng 1 phút. |
| **S3 — Output & Trust**<br><sup>Chất lượng output + citation + disclaimer + control</sup> | Output khoảng 80 dòng / 877 từ, có 3 laptop, giá tham khảo, cấu hình, lý do, điểm yếu và kết luận; có disclaimer “Gemini là AI và có thể mắc sai sót.” Điểm yếu: không thấy citation clickable trong raw output. | Output khoảng 70 dòng / 693 từ, có bảng so sánh, giá, cấu hình, lý do, điểm yếu và nguồn link; có disclaimer của ChatGPT. Trust signal mạnh hơn vì citation cụ thể đến NVIDIA, An Phát, CellphoneS, Thế Giới Di Động. |
| **S4 — Business Signal**<br><sup>Pricing + giới hạn / paywall + Cost-Capability-Speed</sup> | Gemini Ultra là paid tier, dùng trong hệ sinh thái Google AI/Gemini; ảnh pricing cho thấy Google AI Ultra **6.000.000đ/tháng**. Định vị nghiêng về **rất mạnh-rất đắt / ecosystem-driven** với lợi thế tích hợp hệ sinh thái và badge Ultra rõ ràng. Bằng chứng: [product-A-ultra-5-pricing.png](./screenshots/product-A-ultra-5-pricing.png). | ChatGPT Plus là paid tier; ảnh pricing cho thấy Plus **522.500 VND/tháng**. Ảnh tài khoản/model hiển thị Plus và GPT-5.5/Thinking. Định vị nghiêng về **mạnh-vừa đắt / productivity-driven**, có lợi thế search/citation trong tác vụ quyết định mua hàng. Bằng chứng: [product-B-plus-5-plan.png](./screenshots/product-B-plus-5-plan.png). |
| **S5 — Product Judgment**<br><sup>Verdict 1 dòng</sup> | **Promising** — cấu trúc output tốt, lý giải kỹ thuật rõ, nhưng thiếu citation clickable nên chưa mạnh bằng ChatGPT trong use case mua hàng cần kiểm chứng. | **Strong** — trả lời đúng nhu cầu, có citation/link nguồn, có bảng dữ liệu, giúp giảm công xác minh trước khi mua laptop. |

---

## Phần B — Đối chiếu 3 friction areas

- **Physical load**: Cả hai đều ít thao tác; ChatGPT giảm thêm thao tác mở tab nhờ citation/link nguồn trong output, còn Gemini yêu cầu tự kiểm tra nguồn bên ngoài.
- **Cognitive burden**: Gemini dễ đọc phần tư vấn tổng quan; ChatGPT giảm gánh nặng xác minh vì có bảng và nguồn cụ thể.
- **User workarounds**: Với Gemini, workaround chính là tự tìm link/giá ở các website được nêu tên. Với ChatGPT, workaround chính là kiểm tra lại tồn kho/giá thực tế vì giá thị trường có thể thay đổi.

---

## Phần C — Đối chiếu 6 trust signals

| Tín hiệu đáng tin | Gemini Ultra / Gemini 3.1 Pro | ChatGPT Plus / GPT-5.5 |
|---|---|---|
| 1. Dẫn nguồn clickable | **Một phần** — có nêu tên nguồn như Laptop88, GearVN, ThinkPro, FPT Shop, CellphoneS, Phong Vũ, An Phát, Hanoicomputer; chưa thấy link clickable. | **Có** — raw output có link/citation đến NVIDIA, An Phát, CellphoneS, Thế Giới Di Động. |
| 2. Disclaimer khi không chắc | **Có** — “Gemini là AI và có thể mắc sai sót.” | **Có** — ChatGPT có disclaimer về khả năng mắc lỗi/cần kiểm tra thông tin quan trọng. |
| 3. Fallback / dừng lại khi out-of-scope | **Chưa test** — prompt nằm trong phạm vi. | **Chưa test** — prompt nằm trong phạm vi. |
| 4. Consistency — chạy 2 lần cùng prompt | **Chưa test lần 2**. | **Chưa test lần 2**. |
| 5. User control | **Có một phần** — có hội thoại, menu công cụ; chưa ghi rõ regenerate/copy trong ảnh. | **Có một phần** — có hội thoại, model selector, input control; chưa ghi rõ regenerate/copy trong ảnh. |
| 6. Explanation | **Có** — giải thích theo GPU, CUDA, RAM, SSD, tản nhiệt và nhu cầu AI/ML. | **Có** — giải thích theo VRAM, CUDA/Tensor Cores, RAM, SSD, giá và nhu cầu học AI/ML. |

---

## Phần D — Định vị Cost-Capability-Speed

- **Gemini Ultra nghiêng về**: **rất mạnh-rất đắt / hệ sinh thái** — lý do: có Ultra badge, Pro model, output dài và có cấu trúc; ảnh pricing ghi **6.000.000đ/tháng**. Lợi thế nằm ở tích hợp Google AI nhưng thiếu citation clickable trong bài test.
- **ChatGPT Plus nghiêng về**: **mạnh-vừa đắt / trust-search** — lý do: có GPT-5.5 Thinking, output có citation và nguồn cụ thể; ảnh pricing ghi **522.500 VND/tháng** cho Plus. Phù hợp tác vụ cần kiểm chứng, dù thời gian suy nghĩ dài hơn.
- **Bằng chứng pricing**: [product-A-ultra-5-pricing.png](./screenshots/product-A-ultra-5-pricing.png), [product-B-plus-5-plan.png](./screenshots/product-B-plus-5-plan.png).

---

## Phần E — Verdict sơ bộ

- **Gemini Ultra — verdict sơ bộ**: **Promising**
  - Lý do: output mạnh về cấu trúc và giải thích kỹ thuật, nhưng trust signal yếu hơn do chưa có link nguồn trực tiếp.
- **ChatGPT Plus — verdict sơ bộ**: **Strong**
  - Lý do: output có citation/link, bảng thông tin và kết luận rõ theo nhu cầu; phù hợp hơn với tác vụ tìm mua laptop ở thị trường Việt Nam.

---

## Bảng kiểm trước khi sang Bước 3

- [x] Mỗi ô của bảng so sánh 5 mục có ít nhất 1-2 câu, không trống.
- [x] Mỗi nhận định có thể chỉ về ảnh / log trong [1-research-notes.md](./1-research-notes.md).
- [x] Đã định vị cả 2 sản phẩm trên Cost-Capability-Speed.
- [x] Đã có verdict sơ bộ cho cả 2 sản phẩm.
- [x] Các mục thiếu bằng chứng như consistency/fallback/pricing cụ thể đã đánh dấu rõ.
