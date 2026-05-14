# 1 — Ghi chú nghiên cứu khi test 2 sản phẩm AI

File này ghi lại quan sát thật khi test **Gemini Ultra / Gemini 3.1 Pro** và **ChatGPT Plus / GPT-5.5** với cùng một prompt.

---

## Phần A — Setup chung

- **Nhiệm vụ chung**: Tìm 3 mẫu laptop phù hợp để học AI/ML với ngân sách 50 triệu VNĐ.
- **Câu prompt chính xác**:

```text
Tôi có 50 triệu VNĐ, muốn mua laptop để học AI/ML. Hãy gợi ý 3 mẫu laptop phù hợp tại thị trường Việt Nam, kèm giá tham khảo, cấu hình chính, lý do phù hợp cho AI/ML, điểm yếu cần lưu ý, nguồn tham khảo nếu có, và kết luận nên chọn mẫu nào theo từng nhu cầu.
```

- **Loại tài khoản dùng**:
  - Sản phẩm A: Gemini Ultra / paid / logged-in. Giao diện có badge **ULTRA** và menu model hiển thị **Gemini 3 → Pro — Giải toán và lập trình nâng cao với 3.1 Pro**.
  - Sản phẩm B: ChatGPT Plus / paid / logged-in. Giao diện tài khoản hiển thị **Plus**, model selector hiển thị **Mới nhất · 5.5** và chế độ **Thinking**.
- **Trình duyệt + thời gian test**: Chrome, 2026-05-14.
- **Giới hạn test**: Không test guest mode, không test free tier, không test consistency bằng lần chạy thứ hai.

---

## Phần B — Log Sản phẩm A

**Tên sản phẩm A**: Google Gemini Ultra  
**URL**: https://gemini.google.com/  
**Model / plan hiển thị**: Gemini Ultra; menu model hiển thị **Gemini 3 → Pro — Giải toán và lập trình nâng cao với 3.1 Pro**.

### B.1 — Entry point + lần chạm đầu

- Trang đầu / màn hình đầu hiển thị gì? Giao diện Gemini nền tối, có badge **ULTRA** ở góc phải, khung nhập prompt ở giữa, các gợi ý như tạo hình ảnh, tạo nhạc, tạo video, giúp tôi học.
- Có hint / sample prompt sẵn không? Có các nút gợi ý tác vụ, không có prompt mẫu cụ thể cho mua laptop.
- Cần đăng nhập / paywall trước khi dùng không? Có đăng nhập tài khoản Gemini Ultra; không gặp paywall khi chạy prompt chính. Ảnh pricing cho thấy Google AI Ultra có giá **6.000.000đ/tháng**, bên cạnh Google AI Plus và Google AI Pro.
- Ảnh đã chụp:
  - [product-A-ultra-1-entry.png](./screenshots/product-A-ultra-1-entry.png)
  - [product-A-ultra-2-input.png](./screenshots/product-A-ultra-2-input.png)
  - [product-A-ultra-5-pricing.png](./screenshots/product-A-ultra-5-pricing.png)

### B.2 — Khi gõ prompt + nhận output

- Thời gian phản hồi: Chưa ghi chính xác bằng đồng hồ; ảnh output không hiển thị thời gian phản hồi. Cần bổ sung nếu nhóm muốn đo thời gian chính xác.
- Có hiển thị "AI đang nghĩ..." / streaming hay đứng yên? Output được tạo trong giao diện chat, có biểu tượng Gemini; ảnh không ghi rõ trạng thái streaming.
- Output dài bao nhiêu? Khoảng **80 dòng / 877 từ** theo file [Gemini-result.md](./Gemini-result.md).
- Output có dẫn nguồn không? Có nêu tên nguồn tham khảo như Laptop88, GearVN, ThinkPro, FPT Shop, CellphoneS, Phong Vũ, An Phát Computer, Hanoicomputer; **không thấy citation/link clickable trong kết quả đã lưu**.
- Có hiển thị disclaimer / cảnh báo không? Có dòng dưới giao diện: "Gemini là AI và có thể mắc sai sót."
- Ảnh đã chụp:
  - [product-A-ultra-3-output.png](./screenshots/product-A-ultra-3-output.png)
- Raw output: [Gemini-result.md](./Gemini-result.md)

### B.3 — Phản hồi sau khi nhận output

- Có nút regenerate / thử lại không? Chưa ghi nhận trong ảnh hiện tại.
- Có nút copy / export ra format khác không? Chưa ghi nhận trong ảnh hiện tại.
- Có gợi ý câu hỏi tiếp theo không? Chưa ghi nhận rõ trong ảnh hiện tại.
- Có lưu lịch sử để truy lại không? Có hội thoại trong Gemini.
- Có thumb up / thumb down để feedback không? Chưa ghi nhận rõ trong ảnh hiện tại.

### B.4 — Quan sát nổi

1. Gemini Ultra trả lời có cấu trúc rõ: 3 mẫu laptop, giá tham khảo, cấu hình, lý do phù hợp AI/ML, điểm yếu và kết luận theo nhu cầu. Tham chiếu: [Gemini-result.md](./Gemini-result.md), [product-A-ultra-3-output.png](./screenshots/product-A-ultra-3-output.png).
2. Gemini nhấn mạnh đúng tiêu chí kỹ thuật cho AI/ML: GPU NVIDIA RTX 4070, CUDA, RAM 32GB, SSD 1TB và tản nhiệt. Tham chiếu: [Gemini-result.md](./Gemini-result.md).
3. Điểm yếu lớn nhất là phần nguồn: có nêu tên nguồn tham khảo nhưng không có link/citation mở trực tiếp trong output đã lưu, nên người dùng vẫn phải tự kiểm tra giá/cấu hình trước khi mua.

---

## Phần C — Log Sản phẩm B

**Tên sản phẩm B**: ChatGPT Plus  
**URL**: https://chatgpt.com/  
**Model / plan hiển thị**: Tài khoản **Plus**; model selector hiển thị **Mới nhất · 5.5**, chế độ **Thinking**.

### C.1 — Entry point + lần chạm đầu

- Trang đầu / màn hình đầu hiển thị gì? Giao diện ChatGPT nền sáng, thanh input ở giữa, model selector có **Mới nhất · 5.5**, chế độ **Thinking**, menu tài khoản hiển thị **Plus**.
- Có hint / sample prompt sẵn không? Có các nút tác vụ như tạo ảnh, viết/chỉnh sửa, tra cứu thông tin.
- Cần đăng nhập / paywall trước khi dùng không? Có đăng nhập tài khoản Plus; không gặp paywall khi chạy prompt chính. Ảnh pricing cho thấy gói ChatGPT Plus có giá **522.500 VND/tháng**, gói Go **132.000 VND/tháng**, gói Pro **2.849.000 VND/tháng**.
- Ảnh đã chụp:
  - [product-B-plus-1-entry.png](./screenshots/product-B-plus-1-entry.png)
  - [product-B-plus-2-input.png](./screenshots/product-B-plus-2-input.png)
  - [product-B-plus-5-plan.png](./screenshots/product-B-plus-5-plan.png)

### C.2 — Khi gõ prompt + nhận output

- Thời gian phản hồi: Ảnh output hiển thị **"Đã suy nghĩ trong 1m 0s"**.
- Có hiển thị "AI đang nghĩ..." / streaming hay đứng yên? Có hiển thị trạng thái Thinking.
- Output dài bao nhiêu? Khoảng **70 dòng / 693 từ** theo file [Chatgpt-result.md](./Chatgpt-result.md).
- Output có dẫn nguồn không? Có citation/link nguồn trong raw output: NVIDIA, An Phát Computer, CellphoneS, Thế Giới Di Động.
- Có hiển thị disclaimer / cảnh báo không? Có dòng dưới giao diện ChatGPT về khả năng mắc lỗi / cần kiểm tra thông tin quan trọng.
- Ảnh đã chụp:
  - [product-B-plus-3-output.png](./screenshots/product-B-plus-3-output.png)
- Raw output: [Chatgpt-result.md](./Chatgpt-result.md)

### C.3 — Phản hồi sau khi nhận output

- Có nút regenerate / thử lại không? Chưa ghi nhận rõ trong ảnh hiện tại.
- Có nút copy / export ra format khác không? Chưa ghi nhận rõ trong ảnh hiện tại.
- Có gợi ý câu hỏi tiếp theo không? Chưa ghi nhận rõ trong ảnh hiện tại.
- Có lưu lịch sử để truy lại không? Có hội thoại trong ChatGPT.
- Có thumb up / thumb down để feedback không? Chưa ghi nhận rõ trong ảnh hiện tại.

### C.4 — Quan sát nổi

1. ChatGPT Plus tạo bảng so sánh có citation/link nguồn cụ thể cho từng mẫu laptop, giúp kiểm tra giá và cấu hình nhanh hơn. Tham chiếu: [Chatgpt-result.md](./Chatgpt-result.md), [product-B-plus-3-output.png](./screenshots/product-B-plus-3-output.png).
2. ChatGPT nêu rõ tiêu chí kỹ thuật AI/ML trước khi đưa danh sách: RTX 4070/4060, VRAM 8GB, RAM 32GB hoặc nâng cấp được, SSD 1TB, tản nhiệt tốt. Tham chiếu: [Chatgpt-result.md](./Chatgpt-result.md).
3. Output có tính mua hàng cao hơn vì có giá tham khảo, cấu hình cụ thể, điểm yếu và link nguồn; tuy nhiên thời gian suy nghĩ dài hơn và vẫn cần kiểm tra lại tồn kho/giá thực tế.

---

## Phần D — First impressions

1. **Sản phẩm nào dễ dùng hơn lần đầu?**
   - Cả hai đều dễ dùng vì cùng surface chat. ChatGPT dễ kiểm chứng hơn nhờ citation/link nguồn; Gemini dễ đọc phần giải thích tổng quan hơn nhưng cần tự tìm nguồn.

2. **Sản phẩm nào cho output đáng tin hơn?**
   - ChatGPT Plus đáng tin hơn cho use case mua laptop vì có citation/link nguồn cụ thể. Gemini Ultra có cấu trúc tốt nhưng nguồn chỉ là tên website, thiếu link trực tiếp.

3. **Câu hỏi nhóm chưa trả lời được sau test**
   - Gemini Ultra có thể bật citation/link nguồn bằng chế độ/setting nào không?
   - Thời gian phản hồi chính xác của Gemini Ultra là bao nhiêu giây?
   - Nếu chạy lại cùng prompt lần 2, hai sản phẩm có ổn định lựa chọn laptop không?

---

## Bảng kiểm trước khi sang Bước 2

- [x] Câu prompt giống y nhau cho cả 2 sản phẩm.
- [x] Đã chụp tối thiểu 3 ảnh cho mỗi sản phẩm: entry, input, output.
- [x] Mỗi quan sát có ảnh / log tham chiếu.
- [x] First impressions ghi rõ lý do.
- [x] Đã trả lời phân công trong [group-members.md](./group-members.md).

Ghi chú: Nhóm đã bổ sung ảnh pricing: [product-A-ultra-5-pricing.png](./screenshots/product-A-ultra-5-pricing.png) và [product-B-plus-5-plan.png](./screenshots/product-B-plus-5-plan.png). Nhóm vẫn chưa có ảnh riêng [product-B-plus-4-source.png](./screenshots/product-B-plus-4-source.png); bằng chứng nguồn hiện lấy từ output và [Chatgpt-result.md](./Chatgpt-result.md).
