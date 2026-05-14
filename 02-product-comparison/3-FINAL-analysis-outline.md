---
artifact: 3 - Outline 5 mục cho slide deck Analysis Report
bai-tap: 2 - Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Phase 3 - Dựng slide deck (15 phút)
time: 10 phút outline + 5 phút build slide
input: 1-research-notes.md + 2-comparison-table.md + screenshots/ + prompts/08-analysis-report.md
nop-cuoi: Có gián tiếp - outline này dùng làm cốt cho `analysis-report.pdf`
---

# 3 - Outline 5 mục cho slide deck

Outline này tổng hợp kết quả test Google Gemini và ChatGPT với cùng prompt: "Tôi có 50 triệu, muốn mua laptop cho học AI/ML. Gợi ý 3 mẫu phù hợp + tại sao."

---

## Thông tin chung của báo cáo

- **Mã 2 thành viên + tên**: 2A202600466 (Hứa Quang Linh) + 2A202600366 (Dương Khoa Điềm)
- **Ngành chọn**: A - Tìm kiếm
- **Nhiệm vụ chung đã test**: Tìm 3 mẫu laptop phù hợp để học AI/ML với ngân sách 50 triệu VND.
- **Sản phẩm A**: Google Gemini - https://gemini.google.com/
- **Sản phẩm B**: ChatGPT - https://chatgpt.com/
- **Câu prompt chính xác đã dùng**: "Tôi có 50 triệu, muốn mua laptop cho học AI/ML. Gợi ý 3 mẫu phù hợp + tại sao."

---

## S1 - Product Moment (slide 1-2)

### S1.1 - Bảng so sánh nhanh

| Yếu tố | Sản phẩm A - Google Gemini | Sản phẩm B - ChatGPT |
|---|---|---|
| Tên + URL | Google Gemini - https://gemini.google.com/ | ChatGPT - https://chatgpt.com/ |
| Entry point | Khung chat Gemini với gợi ý tool; không thấy sample prompt sẵn trong log. | Giao diện ChatGPT quen thuộc, có chọn model GPT-5.5 trong lúc test; không thấy sample prompt sẵn trong log. |
| Ý định người dùng | Vào để hỏi nhanh và nhận shortlist laptop AI/ML theo ngân sách. | Vào để tìm laptop, đọc lý do, xem citation/hình ảnh và preview sản phẩm. |
| Surface chính | Chat tổng quát. | Chat tổng quát có search/citation và preview link. |
| Cần đăng nhập / paywall ngay không | Không cần paywall ngay; free account dùng được trong bài test. | Không cần paywall ngay; free account dùng được trong bài test. |

### S1.2 - Bằng chứng ảnh tham chiếu

- `screenshots/product-A-1-entry.png` - màn hình vào Gemini với khung chat và các tool gợi ý.
- `screenshots/product-B-1-entry.png` - màn hình vào ChatGPT với giao diện chat và lựa chọn model.

### S1.3 - Nhận định so sánh entry point

ChatGPT tạo first impression tốt hơn cho use case tìm mua vì người dùng thấy ngay một môi trường chat quen thuộc, sau đó có citation và preview sản phẩm trong output. Gemini vào nhanh và gọn, nhưng entry point không báo trước rằng kết quả sẽ có nguồn hay không. Nếu người dùng chỉ cần ý tưởng nhanh, Gemini đủ tốt; nếu người dùng sắp ra quyết định mua, ChatGPT tạo cảm giác đáng tin hơn.

---

## S2 - Workflow Evidence (slide 3-4)

### S2.1 - Luồng người dùng

```text
TRƯỚC khi gặp AI:
- Người dùng có ngân sách 50 triệu VND và cần chọn laptop học AI/ML, ưu tiên GPU NVIDIA, RAM, khả năng nâng cấp và giá thực tế.

TRONG khi dùng Sản phẩm A - Gemini:
1. Mở gemini.google.com và vào khung chat.
2. Nhập prompt chung.
3. Đợi khoảng 11 giây, đọc output 58 dòng / 746 từ.
4. Copy/export nếu cần đưa sang báo cáo hoặc bảng tính.

TRONG khi dùng Sản phẩm B - ChatGPT:
1. Mở chatgpt.com và chọn model GPT-5.5 trong lúc test.
2. Nhập prompt chung.
3. Đợi khoảng 9 giây, đọc output 50 dòng / 412 từ.
4. Kiểm tra citation, hình ảnh, preview sản phẩm ở panel bên.

SAU khi dùng AI:
- Người dùng so sánh 3 laptop, kiểm tra lại giá/nguồn, chọn mẫu phù hợp nhất hoặc copy nội dung vào slide/report.
```

### S2.2 - 3 Friction Areas

| Friction | Sản phẩm A - Google Gemini | Sản phẩm B - ChatGPT |
|---|---|---|
| **Physical load** | Ít thao tác: mở web, nhập prompt, đọc output; có copy/export. | Ít thao tác tương tự, thêm lợi thế citation và preview giúp giảm việc mở tab tìm kiếm riêng. |
| **Cognitive burden** | Bảng so sánh nhanh giúp đọc dễ, nhưng người dùng phải tự đánh giá độ tin vì không có nguồn. | Citation/hình ảnh làm giảm gánh nặng xác minh, nhưng output thiếu bảng tổng hợp 3 mẫu nên người dùng phải tự gom lại nếu muốn trình bày. |
| **User workarounds** | Cần tự tìm link/giá và kiểm tra thông tin laptop bên ngoài. | Cần tự tạo bảng so sánh tổng hợp nếu đưa vào slide, nhưng ít phải workaround về nguồn. |

### S2.3 - Bằng chứng

- `screenshots/product-A-2-input.png` + `screenshots/product-A-3-output.png`
- `screenshots/product-B-2-input.png` + `screenshots/product-B-3-output.png`

### S2.4 - Nhận định

ChatGPT giảm friction tốt hơn trong workflow tìm mua vì citation, ảnh và preview làm bước xác minh nhanh hơn. Gemini giảm friction ở bước đọc/so sánh nhờ bảng so sánh nhanh, nhưng đẩy phần xác minh sang người dùng. Với tác vụ có rủi ro mua sai sản phẩm, friction quan trọng nhất không phải số click mà là công kiểm tra nguồn, nên ChatGPT có lợi thế rõ.

---

## S3 - Output & Trust (slide 5-6)

### S3.1 - Chất lượng output

- **Sản phẩm A - Gemini**:
  - Output trả lời đúng câu hỏi: có, đề xuất 3 laptop và giải thích tại sao phù hợp AI/ML.
  - Hallucination: chưa phát hiện rõ trong log, nhưng thiếu citation nên không thể xác minh giá/cấu hình ngay trong giao diện.
  - Độ đầy đủ: đầy đủ về lý do kỹ thuật, có bảng so sánh và lời khuyên AI Engineer; yếu ở phần nguồn mua/giá thực tế.
- **Sản phẩm B - ChatGPT**:
  - Output trả lời đúng câu hỏi: có, đề xuất 3 laptop trong tầm 50 triệu và nêu lý do chọn.
  - Hallucination: chưa phát hiện rõ trong log; citation và preview giúp giảm rủi ro nhưng vẫn cần kiểm tra lại trước khi mua.
  - Độ đầy đủ: đủ cho quyết định ban đầu, có giá tham khảo, ảnh/link và giải thích từng mẫu; thiếu bảng so sánh tổng hợp.

### S3.2 - 6 Tín hiệu đáng tin

| Tín hiệu | Sản phẩm A - Google Gemini | Sản phẩm B - ChatGPT |
|---|---|---|
| 1. Dẫn nguồn | Không có citation trong kết quả test. | Có citation, hình ảnh và preview sản phẩm. |
| 2. Disclaimer khi không chắc | Có: "Gemini là AI và có thể mắc sai sót." | Có: "ChatGPT có thể mắc lỗi..." và nhắc kiểm tra thông tin quan trọng. |
| 3. Fallback / dừng lại khi out-of-scope | Chưa có bằng chứng vì prompt không out-of-scope. | Chưa có bằng chứng vì prompt không out-of-scope. |
| 4. Consistency | Chưa test lần 2 cùng prompt. | Chưa test lần 2 cùng prompt. |
| 5. User control | Có regenerate, copy/export, gợi ý follow-up, lịch sử, feedback. | Có regenerate, copy, lịch sử, feedback; không thấy follow-up suggestion trong log. |
| 6. Explanation | Có giải thích theo GPU/RAM, mục đích training/inference, góc nhìn AI Engineer. | Có giải thích theo GPU/RAM/giá và khuyên dùng theo từng tình huống. |

### S3.3 - Nhận định

ChatGPT tạo trust mạnh hơn trong bài test này vì đưa citation, ảnh và preview sản phẩm vào cùng output. Gemini có logic giải thích tốt và cấu trúc dễ đưa lên slide, nhưng không có nguồn làm người dùng phải tự xác minh lại. Với nhóm người dùng đang mua laptop, trust signal quan trọng nhất là "có thể bấm vào nguồn để kiểm tra giá/cấu hình", nên ChatGPT thắng S3.

---

## S4 - Business Signal (slide 7)

### S4.1 - Định vị tam giác

- **Sản phẩm A - Gemini**: **cân bằng** - model dưới mui xe trong log: Gemini 3 Pro - lý do: free tier cho dùng nhanh, các gói Google AI tăng giới hạn/model/tính năng và gắn với hệ sinh thái Google.
- **Sản phẩm B - ChatGPT**: **mạnh-đắt** - model dưới mui xe trong log: GPT-5.5 - lý do: free tier có giá trị cao, nhưng các năng lực mạnh hơn nằm ở Plus/Pro/Business với giá theo tháng/user.

### S4.2 - Pricing pattern

| Yếu tố | Sản phẩm A - Google Gemini | Sản phẩm B - ChatGPT |
|---|---|---|
| Mô hình giá | Freemium + subscription Google AI/Google One. | Freemium + subscription cá nhân + seat-based Business/Enterprise. |
| Giá entry | Free tier dùng được trong bài test; Google Help ghi có thể nâng cấp Google AI plan để có higher limits và priority access. | Free tier $0/tháng trên trang ChatGPT pricing; có giới hạn truy cập model/tính năng. |
| Giá trả phí | Google AI Pro/Ultra tùy thị trường; nguồn chính thức trong Gemini Apps dẫn người dùng nâng cấp qua Google One, không hiện giá cố định trên trang Help. | ChatGPT Plus $20/tháng, Pro $200/tháng; Business tính theo user/tháng trên trang pricing. |
| Paywall xuất hiện ở đâu | Khi cần giới hạn cao hơn, model Pro/Ultra, tính năng premium trong Gemini Apps/Google One. | Khi cần giới hạn cao hơn, model/tính năng nâng cao, workspace doanh nghiệp, agent/deep research/connector. |

### S4.3 - Nhận định chiến lược kinh doanh

Gemini được Google đẩy theo chiến lược hệ sinh thái: free tier để tăng adoption, gói trả phí gắn với Google One, Gmail, Docs và các năng lực AI cao hơn. ChatGPT được OpenAI đẩy theo chiến lược sản phẩm AI độc lập: free để mở rộng tập người dùng, Plus/Pro để monetize power users, Business/Enterprise để monetize tổ chức. Khác biệt lớn nhất là Gemini có lợi thế distribution sẵn có của Google, còn ChatGPT có lợi thế brand và product habit riêng.

---

## S5 - Product Judgment (slide 8-12)

### S5.1 - Verdict

- **Sản phẩm A - Google Gemini**: **Promising** - Lý do: output có cấu trúc và giải thích tốt, nhưng trong use case mua laptop, việc thiếu citation làm verdict chưa lên Strong.
- **Sản phẩm B - ChatGPT**: **Strong** - Lý do: kết hợp output đúng nhu cầu, citation, hình ảnh, preview và tốc độ nhanh hơn trong test, nên phù hợp hơn với tác vụ tìm mua sản phẩm.

### S5.2 - User base + tăng trưởng

- **Sản phẩm A - Google Gemini**: TechCrunch ngày 2026-02-04 dẫn báo cáo earnings Q4/2025 của Alphabet: Gemini app vượt **750 triệu MAU**, tăng từ 650 triệu MAU quý trước. Nguồn: https://techcrunch.com/2026/02/04/googles-gemini-app-has-surpassed-750m-monthly-active-users/
- **Sản phẩm B - ChatGPT**: OpenAI trong báo cáo "The state of enterprise AI" ngày 2025-12-08 ghi ChatGPT phục vụ hơn **800 triệu users mỗi tuần**. Nguồn: https://openai.com/index/the-state-of-enterprise-ai-2025-report/

### S5.3 - Doanh thu / pricing power

- **Sản phẩm A - Google Gemini**: Google không công bố doanh thu riêng của Gemini app; Alphabet 2025 vượt mốc **$400B annual revenue** theo báo cáo Q4/2025 được TechCrunch/Gadgets360 trích dẫn. Pricing power đến từ bundling với Google AI/Google One/Workspace và distribution sẵn có.
- **Sản phẩm B - ChatGPT**: OpenAI không tách doanh thu ChatGPT riêng trong trang product; CNBC/TechCrunch 2025 đưa tin OpenAI đạt khoảng **$10B annual recurring revenue** nhờ tăng trưởng ChatGPT và sản phẩm doanh nghiệp. Pricing power đến từ Plus/Pro/Business/Enterprise và API.

### S5.4 - Moat phân tích

| Moat | Sản phẩm A - Google Gemini | Sản phẩm B - ChatGPT |
|---|---|---|
| Data | **Mạnh** - Google có dữ liệu và hệ sinh thái Search/YouTube/Workspace, nhưng việc dùng dữ liệu bị ràng buộc chính sách riêng tư. | **Mạnh** - lượng tương tác ChatGPT cực lớn tạo feedback product/model, đặc biệt ở consumer và enterprise. |
| Network effects | **Trung bình** - giá trị tăng khi Gemini được tích hợp vào Google products, nhưng chatbot cá nhân không có network effect trực tiếp mạnh. | **Trung bình-mạnh** - custom GPTs, sharing, workspace và habit cộng đồng tạo hiệu ứng lan tỏa. |
| Switching cost | **Trung bình** - nếu user đã dùng Gmail/Docs/Drive, Gemini có switching cost cao hơn. | **Trung bình** - projects, memory, history, custom GPTs và workspace tạo chi phí đổi công cụ. |
| Brand | **Mạnh** - Google có brand và distribution toàn cầu; Gemini brand đang tăng nhanh. | **Mạnh** - ChatGPT là tên gắn liền với chatbot AI đại chúng, có top-of-mind cao. |
| Distribution | **Rất mạnh** - Search, Android, Chrome, Workspace, Google One. | **Mạnh** - web/mobile/desktop, API, enterprise, đối tác và product-led growth. |

### S5.5 - Data flywheel + feedback loop

- **Sản phẩm A - Gemini**: Loop đến từ user prompt, feedback, usage trong Gemini Apps và hệ sinh thái Google; compounding mạnh nếu Google biến Gemini thành lớp AI mặc định trong Search/Workspace/Android. Trong bài test, feedback thumb up/down và lịch sử chat là tín hiệu thu thập feedback rõ.
- **Sản phẩm B - ChatGPT**: Loop đến từ hàng trăm triệu user mỗi tuần, feedback, lịch sử, custom GPTs, Business/Enterprise workflows và API usage; compounding rõ vì product habit và model improvement liên tục làm user quay lại. Trong bài test, citation/search làm loop tin cậy hơn cho use case tìm kiếm.

### S5.6 - Niche Down + AI Feature Map

- **Sản phẩm A - Google Gemini**:
  - Niche cụ thể: người dùng Google ecosystem cần trợ lý AI tổng quát để hỏi nhanh, viết, research và làm việc với Google tools.
  - AI Feature Map:
    - User Value: **Cao** - câu trả lời có cấu trúc, có bảng so sánh và lời khuyên theo use case.
    - User Alignment: **Trung bình-cao** - đúng prompt và nhu cầu, nhưng thiếu citation trong tác vụ mua laptop.
    - Business Value: **Cao** - đẩy adoption vào Google AI/Google One/Workspace và giữ user trong hệ sinh thái Google.
- **Sản phẩm B - ChatGPT**:
  - Niche cụ thể: người dùng cần trợ lý AI tổng quát có khả năng search, phân tích, tạo nội dung và hỗ trợ quyết định nhanh.
  - AI Feature Map:
    - User Value: **Cao** - trả lời đúng nhu cầu, có citation/hình ảnh/preview và giải thích rõ.
    - User Alignment: **Cao** - output bám sát việc mua laptop AI/ML trong ngân sách 50 triệu.
    - Business Value: **Cao** - free tier tạo habit, paid tiers monetize power users và doanh nghiệp.

### S5.7 - Spark -> Loop -> System

- **Sản phẩm A - Google Gemini**: **System** - Lý do: đã nằm trong chiến lược AI hệ sinh thái của Google, có distribution lớn và MAU rất cao. Dự báo 12 tháng tới: Gemini sẽ mạnh hơn ở các workflow gắn Google Search, Workspace, Android và Chrome; trust/citation cần ổn định hơn để thắng use case mua sắm/research.
- **Sản phẩm B - ChatGPT**: **System** - Lý do: đã có user base hàng trăm triệu mỗi tuần, nhiều paid tiers, enterprise workflows và brand mạnh. Dự báo 12 tháng tới: ChatGPT tiếp tục mở rộng từ chatbot sang agent/workspace; rủi ro là pricing, giới hạn quota và trust nếu citation/ads/product incentives không minh bạch.

### S5.8 - Liên hệ Lab 1

- **Sản phẩm A có rủi ro disruption tương tự case nào của nhóm?** Tương tự các case bigtech có distribution mạnh nhưng bị sản phẩm chuyên dụng tấn công: nếu Gemini chỉ là chatbot tổng quát không có trust/citation tốt, các AI shopping/research tool chuyên sâu có thể lấy use case mua sắm.
- **Sản phẩm B có rủi ro disruption tương tự case nào của nhóm?** Tương tự case sản phẩm dẫn đầu bị commoditize khi nhiều đối thủ bắt kịp model quality; ChatGPT cần giữ lợi thế workflow, memory, agent và trust chứ không chỉ dựa vào câu trả lời hay.
- **Bài học rút từ Lab 1 áp dụng**: Bigtech/distribution là lợi thế lớn nhưng không thay thế được product fit trong từng workflow cụ thể. Với use case tìm mua laptop, người dùng cần trust signal và khả năng xác minh hơn là câu trả lời dài; sản phẩm nào giảm công việc sau output tốt hơn sẽ có cơ hội giữ user lâu hơn.

---

## Bảng kiểm trước khi build slide

- [x] S1 -> S4 đã điền đầy đủ.
- [x] S5.1 + S5.6 + S5.7 + S5.8 đã hoàn thành.
- [x] S5.2 -> S5.5 đã hoàn thành, có ghi rõ nơi nào không có số liệu công khai tách riêng.
- [x] Mỗi nhận định nối được về ảnh / log / số liệu cụ thể.
- [x] Verdict S5.1 nhất quán với moat S5.4 và giai đoạn S5.7.
- [x] Các phần cần thuyết trình thêm: consistency/fallback chưa test lần 2, cần nói rõ đây là giới hạn của bài test 20 phút.

---

## Sau khi xong outline

1. Tạo 12-15 slide bám theo cấu trúc S1 -> S5.
2. Mỗi slide nên có ít nhất 1 ảnh tham chiếu từ `screenshots/`.
3. Ưu tiên đưa bảng S1/S2/S3 và verdict S5 vào slide, không copy quá nhiều chữ.
4. Export PDF thành `analysis-report.pdf` trong cùng folder.
