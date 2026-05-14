---
artifact: 1 — Ghi chú nghiên cứu khi test 2 sản phẩm AI
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Phase 2 — Thử nghiệm + chụp ảnh + research (20 phút)
time: 20 phút (xem deck Day 26 slide 18-19 để biết khung giờ chính xác)
input: group-members.md (nhóm đã chốt ngành + 2 sản phẩm + nhiệm vụ chung)
nop-cuoi: Không — file trung gian (đầu vào cho `2-comparison-table.md`)
---

# 1 — Ghi chú nghiên cứu khi test 2 sản phẩm AI

Mục tiêu: trong 20 phút thử nghiệm, 2 thành viên cùng test 2 sản phẩm AI với 1 nhiệm vụ chung. File này ghi lại **quan sát thật** (không phải đánh giá tổng kết) — sẽ làm nền cho bảng so sánh ở bước 2.

Lý do làm bước này: slide deck Lab 2 chỉ có sức nặng khi mỗi nhận định dựa trên quan sát cụ thể có ảnh chụp + tên model + thời gian + câu prompt cụ thể. Nếu chỉ "thấy A tốt hơn B" mà không có log → không phòng thủ được khi giảng viên cold-call.

Quy tắc: **không có ảnh chụp / log = không có quan sát**. Mỗi quan sát phải có ảnh tham chiếu hoặc log cụ thể (timestamp, prompt, response excerpt).

## Quy trình 20 phút

```text
2 phút   — Ghi setup chung (nhiệm vụ + câu prompt + tài khoản dùng)
8 phút   — Test Sản phẩm A: chụp 3-5 ảnh + ghi log
8 phút   — Test Sản phẩm B: chụp 3-5 ảnh + ghi log
2 phút   — First impressions: ghi 3 quan sát nổi nhất cho mỗi sản phẩm
```

---

## Phần A — Setup chung (2 phút)

Trước khi test, 2 thành viên thống nhất các thông số chung. Câu prompt phải **giống y nhau** cho cả 2 sản phẩm — nếu khác sẽ không so sánh được.

- **Nhiệm vụ chung** (1 câu mô tả): Mua laptop học AI
- **Câu prompt chính xác**: Tôi có 50 triệu, muốn mua laptop cho học AI/ML. Gợi ý 3 mẫu phù hợp + tại sao.
- **Loại tài khoản dùng**:
  - Sản phẩm A: free
  - Sản phẩm B: free
- **Trình duyệt + thời gian test** (để dễ tham chiếu ảnh sau này): chrome, 2026-05-14

---

## Phần B — Log Sản phẩm A (8 phút)

**Tên sản phẩm A**: Gemini
**URL**: https://gemini.google.com/
**Model dưới mui xe** (nếu hiển thị): gemini 3 pro

### B.1 — Entry point + lần chạm đầu

Trước khi bắt đầu nhiệm vụ, người dùng thấy gì?

- Trang đầu / màn hình đầu hiển thị gì? Khung chat + gợi ý chức năng tool
- Có hint / sample prompt sẵn không? Không
- Cần đăng nhập / paywall trước khi dùng không? Không cần đăng nhập vẫn sử dụng được
- Ảnh đã chụp: `screenshots/product-A-1-entry.png`

### B.2 — Khi gõ prompt + nhận output

- Thời gian phản hồi: 11 giây
- Có hiển thị "AI đang nghĩ..." / streaming hay đứng yên? Chỉ có icon Gemino loading không hiển thị AI đang nghĩ gì cụ thể
- Output dài bao nhiêu (số câu / dòng / từ)? 58 dòng , 746 từ
- Output có dẫn nguồn không? không 
- Có hiển thị disclaimer / cảnh báo không (vd: "có thể sai", "kiểm tra lại")? có, "Gemini là AI và có thể mắc sai sót."
- Ảnh đã chụp: `screenshots/product-A-2-input.png` + `screenshots/product-A-3-output.png`

### B.3 — Phản hồi sau khi nhận output

- Có nút "regenerate" / "thử lại" không? Có 
- Có nút copy / export ra format khác không? Có
- Có gợi ý câu hỏi tiếp theo không? Có
- Có lưu lịch sử để truy lại không? Có 
- Có thumb up / thumb down để feedback không? Có 

### B.4 — Quan sát nổi (3 quan sát)

Ghi 3 quan sát ấn tượng nhất khi dùng. Mỗi quan sát kèm tham chiếu (ảnh hoặc log):

1. [Có bảng so sánh nhanh các sản phẩm và khuyên dùng cho từng mục đích cụ thể + ref `02-product-comparison\Gemini-result.md`]
2. [Có lời khuyên từ góc độ AI Engineer +ref `02-product-comparison\Gemini-result.md`]
3. [Xuất nhanh sang trang tính thuận tiện báo cáo + ref `02-product-comparison\Gemini-result.md`]

---

## Phần C — Log Sản phẩm B (8 phút)

**Tên sản phẩm B**: Chatgpt 
**URL**: https://chatgpt.com/
**Model dưới mui xe** (nếu hiển thị): gpt-5.5

### C.1 — Entry point + lần chạm đầu

- Trang đầu / màn hình đầu hiển thị gì? giao diện chatgpt thông thường với 2 model, chọn 5.5
- Có hint / sample prompt sẵn không? [...] Không
- Cần đăng nhập / paywall trước khi dùng không? Không cần đăng nhập vẫn sử dụng được
- Ảnh đã chụp: `screenshots/product-B-1-entry.png`

### C.2 — Khi gõ prompt + nhận output

- Thời gian phản hồi: 9 giây
- Có hiển thị "AI đang nghĩ..." / streaming hay đứng yên? có hiển thị AI đang nghĩ gì cụ thể
- Output dài bao nhiêu (số câu / dòng / từ)? 50 dòng , 412 từ
- Output có dẫn nguồn không? có 
- Có hiển thị disclaimer / cảnh báo không? có, "ChatGPT có thể mắc lỗi. Hãy kiểm tra các thông tin quan trọng. Vui lòng tham khảo"
- Ảnh đã chụp: `screenshots/product-B-2-input.png` + `screenshots/product-B-3-output.png`

### C.3 — Phản hồi sau khi nhận output

- Có nút "regenerate" / "thử lại" không? Có  
- Có nút copy / export ra format khác không? Có 
- Có gợi ý câu hỏi tiếp theo không? Không
- Có lưu lịch sử để truy lại không? Có 
- Có thumb up / thumb down để feedback không? Có 

### C.4 — Quan sát nổi (3 quan sát)

1. [Có dẫn nguồn kèm hình ảnh sản phẩm rất trực quan + ref `02-product-comparison\screenshots\product-B-3-output.png`]
2. [Có phân tích từng sản phẩm rất chi tiết, không có bảng so sánh 3 sản phẩm như Gemini + ref `02-product-comparison\screenshots\product-B-3-output.png`]
3. [Khi click vào sản phẩm mở preview ở thanh bên trước khi truy cập trang web + ref `02-product-comparison\screenshots\product-B-3-output.png`]

---

## Phần D — First impressions (2 phút)

Sau khi test cả 2, mỗi thành viên trả lời nhanh 3 câu:

1. **Sản phẩm nào "cảm giác" dễ dùng hơn lần đầu? Tại sao?**
   - ChatGPT dễ dùng hơn vì có giao diện quen thuộc và có nguồn thực tế kèm theo

2. **Sản phẩm nào "cảm giác" cho output đáng tin hơn? Tại sao?**
   - ChatGPT cho output đáng tin hơn vì có dẫn nguồn kèm hình ảnh sản phẩm rất trực quan

3. **Câu hỏi mà nhóm CHƯA trả lời được sau 20 phút test** (sẽ cần đào thêm khi dựng slide):
   - [...]

> Đây là first impressions — chưa phải nhận định. Khi sang `2-comparison-table.md` sẽ đối chiếu chéo với số liệu cụ thể.

---

## Bảng kiểm trước khi sang Bước 2

- [ ] Câu prompt giống y nhau cho cả 2 sản phẩm.
- [ ] Đã chụp tối thiểu 3 ảnh cho mỗi sản phẩm (entry + input + output).
- [ ] Mỗi quan sát có ảnh / log tham chiếu.
- [ ] First impressions ghi rõ — không dùng từ chung chung như "hay hơn", "tốt hơn" mà không kèm lý do.
- [ ] Đã trả lời 5 câu trong `group-members.md` về phân chia trách nhiệm.

Sang `2-comparison-table.md` để dựng bảng so sánh 2 sản phẩm theo 5 mục của slide deck.
