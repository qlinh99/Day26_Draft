---
artifact: 3 — Outline 5 mục cho slide deck Analysis Report
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Phase 3 — Dựng slide deck
time: 10 phút outline + 5 phút build slide
input: 1-research-notes.md + 2-comparison-table.md + screenshots/ + prompts/08-analysis-report.md
nop-cuoi: Có gián tiếp — dùng làm cốt cho `analysis-report.pdf`
---

# 3 — Outline 5 mục cho slide deck

Outline này tổng hợp kết quả test **Gemini Ultra / Gemini 3.1 Pro** và **ChatGPT Plus / GPT-5.5** với cùng prompt.

---

## Thông tin chung của báo cáo

- **Mã 2 thành viên + tên**: 2A202600466 (Hứa Quang Linh) + 2A202600366 (Dương Khoa Điềm)
- **Ngành chọn**: A — Tìm kiếm
- **Nhiệm vụ chung đã test**: Tìm 3 mẫu laptop phù hợp để học AI/ML với ngân sách 50 triệu VNĐ.
- **Sản phẩm A**: Google Gemini Ultra / Gemini 3.1 Pro — https://gemini.google.com/
- **Sản phẩm B**: ChatGPT Plus / GPT-5.5 — https://chatgpt.com/
- **Câu prompt chính xác đã dùng**:

```text
Tôi có 50 triệu VNĐ, muốn mua laptop để học AI/ML. Hãy gợi ý 3 mẫu laptop phù hợp tại thị trường Việt Nam, kèm giá tham khảo, cấu hình chính, lý do phù hợp cho AI/ML, điểm yếu cần lưu ý, nguồn tham khảo nếu có, và kết luận nên chọn mẫu nào theo từng nhu cầu.
```

- **Giới hạn nghiên cứu**: Nhóm không test guest mode, không test free tier, không test consistency bằng lần chạy thứ hai. Kết luận chỉ áp dụng cho nhiệm vụ cụ thể đã test.

---

## S1 — Product Moment

### S1.1 — Bảng so sánh nhanh

| Yếu tố | Gemini Ultra / Gemini 3.1 Pro | ChatGPT Plus / GPT-5.5 |
|---|---|---|
| Tên + URL | Google Gemini Ultra — https://gemini.google.com/ | ChatGPT Plus — https://chatgpt.com/ |
| Entry point | Giao diện Gemini nền tối, badge **ULTRA**, menu model có **Gemini 3 → Pro — Giải toán và lập trình nâng cao với 3.1 Pro**. | Giao diện ChatGPT, tài khoản **Plus**, model selector hiển thị **Mới nhất · 5.5** và chế độ **Thinking**. |
| Ý định người dùng | Hỏi nhanh để nhận shortlist laptop và tư vấn kỹ thuật. | Hỏi để nhận shortlist laptop kèm nguồn/citation có thể kiểm chứng. |
| Surface chính | Chat tổng quát trong Gemini. | Chat tổng quát có Thinking + citation/search. |
| Đăng nhập / paywall | Đã đăng nhập Ultra; không gặp paywall trong prompt chính. | Đã đăng nhập Plus; không gặp paywall trong prompt chính. |

### S1.2 — Bằng chứng ảnh

- [product-A-ultra-1-entry.png](./screenshots/product-A-ultra-1-entry.png) — Gemini hiển thị badge ULTRA và menu model Pro.
- [product-A-ultra-2-input.png](./screenshots/product-A-ultra-2-input.png) — Gemini đã nhập prompt chung.
- [product-B-plus-1-entry.png](./screenshots/product-B-plus-1-entry.png) — ChatGPT hiển thị tài khoản Plus / model selector.
- [product-B-plus-2-input.png](./screenshots/product-B-plus-2-input.png) — ChatGPT đã nhập prompt chung.

### S1.3 — Nhận định

Cả hai sản phẩm đều có entry point đơn giản vì đều dùng surface chat. Gemini làm rõ trạng thái Ultra/model Pro ngay trên giao diện, trong khi ChatGPT làm rõ trạng thái Plus và chế độ Thinking. Với người dùng tìm mua laptop, ChatGPT tạo kỳ vọng “có thể kiểm chứng” tốt hơn vì gắn với citation/search trong output.

---

## S2 — Workflow Evidence

### S2.1 — Luồng người dùng

```text
TRƯỚC khi gặp AI:
- Người dùng có ngân sách 50 triệu VNĐ, muốn học AI/ML và cần chọn laptop tại thị trường Việt Nam.
- Tiêu chí quan trọng: GPU NVIDIA, VRAM, RAM, SSD, tản nhiệt, giá và nguồn tham khảo.

TRONG khi dùng Gemini Ultra:
1. Mở Gemini.
2. Kiểm tra trạng thái Ultra / model Pro.
3. Nhập prompt chung.
4. Đọc output gồm 3 mẫu laptop và giải thích kỹ thuật.
5. Tự kiểm tra thêm nguồn vì output chỉ nêu tên website tham khảo.

TRONG khi dùng ChatGPT Plus:
1. Mở ChatGPT.
2. Kiểm tra trạng thái Plus / GPT-5.5 Thinking.
3. Nhập prompt chung.
4. Đợi khoảng 1 phút theo giao diện.
5. Đọc output có bảng, citation/link nguồn và kết luận.

SAU khi dùng AI:
- Người dùng so sánh 3 mẫu, kiểm tra lại link/giá/tồn kho, rồi chọn laptop theo nhu cầu.
```

### S2.2 — 3 Friction Areas

| Friction | Gemini Ultra | ChatGPT Plus |
|---|---|---|
| **Physical load** | Ít thao tác, nhưng cần tự mở web ngoài để xác minh nguồn/giá. | Ít thao tác và có citation, giảm bước tìm nguồn ngoài. |
| **Cognitive burden** | Giải thích dễ hiểu, có cấu trúc; nhưng phải tự đánh giá độ tin của nguồn. | Citation/link giúp giảm gánh nặng xác minh; bảng thông tin rõ. |
| **User workarounds** | Tự tìm link sản phẩm từ các nguồn được nêu tên. | Kiểm tra lại giá/tồn kho thực tế; có thể cần mở citation để xác minh chi tiết. |

### S2.3 — Bằng chứng

- [product-A-ultra-3-output.png](./screenshots/product-A-ultra-3-output.png)
- [product-B-plus-3-output.png](./screenshots/product-B-plus-3-output.png)
- [Gemini-result.md](./Gemini-result.md)
- [Chatgpt-result.md](./Chatgpt-result.md)

### S2.4 — Nhận định

ChatGPT Plus giảm friction tốt hơn trong tác vụ tìm mua sản phẩm vì citation/link nguồn là phần quan trọng của workflow sau output. Gemini Ultra tạo output dễ đọc và giàu giải thích, nhưng đẩy phần kiểm chứng sang người dùng. Với use case mua laptop, friction lớn nhất không phải thao tác nhập prompt mà là xác minh giá/cấu hình, nên ChatGPT có lợi thế hơn.

---

## S3 — Output & Trust

### S3.1 — Chất lượng output

- **Gemini Ultra**:
  - Trả lời đúng câu hỏi: có, gợi ý 3 mẫu laptop.
  - Có giá tham khảo: có.
  - Có cấu hình chính: có.
  - Có lý do phù hợp AI/ML: có, nhấn mạnh GPU, CUDA, RAM, SSD, tản nhiệt.
  - Có điểm yếu: có.
  - Có nguồn: một phần, nêu tên website nhưng không thấy link clickable.
  - Hallucination: chưa phát hiện rõ trong log, nhưng cần kiểm tra lại vì thiếu citation trực tiếp.

- **ChatGPT Plus**:
  - Trả lời đúng câu hỏi: có, gợi ý 3 mẫu laptop.
  - Có giá tham khảo: có.
  - Có cấu hình chính: có.
  - Có lý do phù hợp AI/ML: có, nhấn mạnh RTX 4070/4060, VRAM, RAM, SSD, cloud GPU.
  - Có điểm yếu: có.
  - Có nguồn: có citation/link cụ thể.
  - Hallucination: chưa phát hiện rõ trong log; vẫn cần mở link kiểm tra trước khi mua.

### S3.2 — 6 trust signals

| Tín hiệu | Gemini Ultra | ChatGPT Plus |
|---|---|---|
| 1. Dẫn nguồn | Một phần — có tên nguồn, chưa có link trực tiếp. | Có — có citation/link cụ thể. |
| 2. Disclaimer | Có. | Có. |
| 3. Fallback/out-of-scope | Chưa test. | Chưa test. |
| 4. Consistency | Chưa test lần 2. | Chưa test lần 2. |
| 5. User control | Có hội thoại và công cụ; chưa ghi rõ regenerate/copy trong ảnh. | Có hội thoại, model selector, input control; chưa ghi rõ regenerate/copy trong ảnh. |
| 6. Explanation | Có giải thích kỹ thuật rõ. | Có giải thích kỹ thuật rõ và gắn nguồn hơn. |

### S3.3 — Nhận định

ChatGPT Plus tạo trust mạnh hơn vì có citation/link nguồn mở được từ raw output. Gemini Ultra có cấu trúc và reasoning tốt, nhưng với tác vụ có rủi ro mua sai sản phẩm, thiếu link trực tiếp làm độ tin thấp hơn. Vì vậy S3 nghiêng về ChatGPT Plus.

---

## S4 — Business Signal

### S4.1 — Định vị tam giác

- **Gemini Ultra**: **rất mạnh-rất đắt / ecosystem-driven** — model hiển thị Pro trong gói Ultra; ảnh pricing ghi **Google AI Ultra 6.000.000đ/tháng**. Phù hợp người dùng đã ở hệ sinh thái Google AI và cần quyền truy cập cấp cao nhất.
- **ChatGPT Plus**: **mạnh-vừa đắt / productivity-driven** — tài khoản Plus dùng GPT-5.5 Thinking; ảnh pricing ghi **Plus 522.500 VND/tháng**. Phù hợp người dùng muốn năng lực reasoning/search/citation mạnh trong nhiều workflow.

**Bằng chứng ảnh pricing**:

- [product-A-ultra-5-pricing.png](./screenshots/product-A-ultra-5-pricing.png)
- [product-B-plus-5-plan.png](./screenshots/product-B-plus-5-plan.png)

### S4.2 — Pricing pattern

| Yếu tố | Gemini Ultra | ChatGPT Plus |
|---|---|---|
| Mô hình giá | Subscription Google AI plans / Google One. | Subscription cá nhân Plus + các gói Pro/Business/Enterprise. |
| Giá entry | Không phân tích free tier trong bài này. | Không phân tích free tier trong bài này. |
| Giá trả phí | Ảnh pricing ghi Google AI Plus **33.000đ/tháng trong 3 tháng đầu**, Google AI Pro **122.000đ/tháng trong 3 tháng đầu**, Google AI Ultra **6.000.000đ/tháng**. Bằng chứng: [product-A-ultra-5-pricing.png](./screenshots/product-A-ultra-5-pricing.png). | Ảnh pricing ghi ChatGPT Go **132.000 VND/tháng**, ChatGPT Plus **522.500 VND/tháng**, ChatGPT Pro **2.849.000 VND/tháng**. Bằng chứng: [product-B-plus-5-plan.png](./screenshots/product-B-plus-5-plan.png). |
| Paywall | Không gặp trong prompt chính. | Không gặp trong prompt chính. |

### S4.3 — Nhận định

Gemini có lợi thế ecosystem: Google có thể đưa Gemini vào Search, Workspace, Android và Google One. ChatGPT có lợi thế product habit và trust/search trong trải nghiệm chat độc lập. Trong bài test laptop, ChatGPT thể hiện business value rõ hơn vì giúp người dùng đi gần hơn tới quyết định mua.

---

## S5 — Product Judgment

### S5.1 — Verdict

- **Gemini Ultra**: **Promising** — output có cấu trúc tốt và reasoning kỹ thuật rõ, nhưng thiếu citation clickable nên trust chưa đủ mạnh trong use case mua laptop.
- **ChatGPT Plus**: **Strong** — output có citation/link, bảng dữ liệu, giá/cấu hình/điểm yếu rõ, giúp người dùng xác minh nhanh hơn.

### S5.2 — User base + tăng trưởng

- **Gemini**: Google công bố trong Q4 2025 rằng Gemini App có hơn **750 triệu monthly active users**. Nguồn: https://blog.google/company-news/inside-google/message-ceo/alphabet-earnings-q4-2025/
- **ChatGPT**: TechCrunch đưa tin Sam Altman nói ChatGPT đạt **800 triệu weekly active users** vào tháng 10/2025. Nguồn: https://techcrunch.com/2025/10/06/sam-altman-says-chatgpt-has-hit-800m-weekly-active-users/

Ghi chú: Các số liệu này là số liệu cấp sản phẩm/nền tảng, không phải số liệu riêng cho gói Ultra hoặc Plus.

### S5.3 — Doanh thu / pricing power

- **Gemini Ultra**: Google không công bố doanh thu riêng của Gemini Ultra trong file nhóm hiện tại. Pricing power đến từ bundling trong Google AI plans, Google One và hệ sinh thái Google. Ảnh pricing nhóm chụp ghi Google AI Ultra **6.000.000đ/tháng**; Plus/Pro có giá ưu đãi 3 tháng đầu.
- **ChatGPT Plus**: OpenAI không công bố doanh thu riêng của ChatGPT Plus trong file nhóm hiện tại. Pricing power đến từ các paid tiers như Go/Plus/Pro/Business/Enterprise. Ảnh pricing nhóm chụp ghi ChatGPT Plus **522.500 VND/tháng**, Go **132.000 VND/tháng**, Pro **2.849.000 VND/tháng**.

### S5.4 — Moat phân tích

| Moat | Gemini Ultra | ChatGPT Plus |
|---|---|---|
| Data | **Mạnh** — Google có hệ sinh thái Search/Workspace/Android, nhưng việc dùng dữ liệu bị ràng buộc chính sách riêng tư. | **Mạnh** — lượng tương tác ChatGPT lớn, có feedback từ consumer/enterprise/workflow. |
| Network effects | **Trung bình** — chatbot cá nhân không có network effect trực tiếp mạnh, nhưng ecosystem Google tạo phân phối rộng. | **Trung bình-mạnh** — custom GPTs, sharing, workspace và cộng đồng tạo lan tỏa. |
| Switching cost | **Trung bình** — tăng nếu user đã dùng Gmail/Docs/Drive/Google One. | **Trung bình** — history, memory, projects, custom GPTs và workspace tạo chi phí đổi. |
| Brand | **Mạnh** — Google brand và Gemini brand đang tăng. | **Rất mạnh** — ChatGPT là brand gắn với chatbot AI đại chúng. |
| Distribution | **Rất mạnh** — Search, Android, Chrome, Workspace, Google One. | **Mạnh** — web/mobile/desktop, API, enterprise, product-led growth. |

### S5.5 — Data flywheel + feedback loop

- **Gemini Ultra**: User prompt, feedback, lịch sử hội thoại và tích hợp Google ecosystem có thể tạo feedback loop. Loop có compounding nếu Gemini trở thành lớp AI mặc định trong Search/Workspace/Android.
- **ChatGPT Plus**: User prompt, feedback, memory, projects, custom GPTs, business workflows và citation/search tạo feedback loop. Loop thể hiện rõ hơn trong bài test vì ChatGPT biến truy vấn thành output có nguồn, giúp user quay lại trong các tác vụ tìm kiếm/ra quyết định.

### S5.6 — Niche Down + AI Feature Map

- **Gemini Ultra**:
  - Niche cụ thể: người dùng Google ecosystem cần trợ lý AI tổng quát mạnh để tìm kiếm, học tập, viết, research và làm việc với Google tools.
  - User Value: **Cao** — trả lời đầy đủ, có cấu trúc, có giải thích kỹ thuật.
  - User Alignment: **Trung bình-cao** — đúng nhu cầu, nhưng thiếu link nguồn trực tiếp trong tác vụ mua laptop.
  - Business Value: **Cao** — giúp Google giữ user trong Google AI/Google One ecosystem.

- **ChatGPT Plus**:
  - Niche cụ thể: người dùng cần trợ lý AI tổng quát có reasoning/search/citation để ra quyết định nhanh.
  - User Value: **Cao** — trả lời đúng yêu cầu, có bảng, giá, nguồn và kết luận.
  - User Alignment: **Cao** — rất bám sát tác vụ mua laptop AI/ML trong ngân sách 50 triệu.
  - Business Value: **Cao** — paid tier tạo habit và monetization trực tiếp từ power users.

### S5.7 — Spark → Loop → System

- **Gemini Ultra**: **System** — đã nằm trong hệ sinh thái Google AI, có distribution lớn và gắn với Google One/Workspace/Search. Dự báo 12 tháng tới: Gemini mạnh hơn trong workflow Google-native; cần cải thiện trust/citation cho các tác vụ research/mua sắm.
- **ChatGPT Plus**: **System** — đã là sản phẩm AI đại chúng có paid tiers, memory/projects/citation/search và enterprise workflows. Dự báo 12 tháng tới: ChatGPT tiếp tục chuyển từ chatbot sang agent/workspace; rủi ro là trust, pricing và giới hạn quota.

### S5.8 — Liên hệ Lab 1

- **Gemini Ultra có rủi ro disruption tương tự case Lab 1 ở điểm nào?** Nếu Gemini chỉ đưa câu trả lời tổng quát mà thiếu citation/trust trong từng workflow cụ thể, các công cụ tìm kiếm/mua sắm chuyên sâu có thể lấy use case đó.
- **ChatGPT Plus có rủi ro disruption tương tự case Lab 1 ở điểm nào?** Nếu nhiều sản phẩm bắt kịp model quality, ChatGPT phải giữ lợi thế workflow, memory, citation, agent và brand thay vì chỉ dựa vào câu trả lời hay.
- **Bài học rút ra**: Từ case Stack Overflow ở Lab 1, sản phẩm AI không chỉ thắng nhờ output tốt; nó phải nằm đúng workflow và giảm công việc sau output. Với use case mua laptop, ChatGPT thắng hơn vì giảm công xác minh nguồn, còn Gemini cần cải thiện citation để tăng trust.

---

## Bảng kiểm trước khi build slide

- [x] S1 → S4 đã điền đầy đủ.
- [x] S5.1 + S5.6 + S5.7 + S5.8 đã hoàn thành.
- [x] S5.2 → S5.5 đã hoàn thành, có ghi rõ giới hạn số liệu.
- [x] Mỗi nhận định nối được về ảnh / log / số liệu cụ thể.
- [x] Verdict S5.1 nhất quán với phân tích trust/moat.
- [x] Đã bổ sung ảnh pricing riêng cho Gemini Ultra và ChatGPT Plus.
- [ ] Cần export slide thành [analysis-report.pdf](./analysis-report.pdf).

---

## Sau khi xong outline

1. Tạo 12–15 slide bám theo cấu trúc S1 → S5.
2. Mỗi slide nên có ít nhất 1 ảnh tham chiếu từ [screenshots/](./screenshots/).
3. Ưu tiên đưa bảng S1/S2/S3 và verdict S5 vào slide, không copy quá nhiều chữ.
4. Export PDF thành  [analysis-report.pdf](./analysis-report.pdf)trong cùng folder.
