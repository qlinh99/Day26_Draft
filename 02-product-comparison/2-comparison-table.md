---
artifact: 2 - Bảng so sánh 2 sản phẩm theo 5 mục
bai-tap: 2 - Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Chuyển giao Phase 2 -> Phase 3 (5 phút)
time: 5 phút
input: 1-research-notes.md + screenshots/
nop-cuoi: Không - file trung gian (đầu vào cho `3-FINAL-analysis-outline.md`)
---

# 2 - Bảng so sánh 2 sản phẩm theo 5 mục slide deck

Mục tiêu: gộp toàn bộ quan sát ở Bước 1 thành **một bảng so sánh nén** - cùng cấu trúc 5 mục mà slide deck cuối sẽ dùng.

Dữ liệu được lấy từ `1-research-notes.md`, `Gemini-result.md`, `Chatgpt-result.md` và folder `screenshots/`.

---

## Phần A - Bảng so sánh 5 mục

| Mục | Sản phẩm A - Google Gemini | Sản phẩm B - ChatGPT |
|---|---|---|
| **S1 - Product Moment**<br><sup>Entry point + ý định người dùng + surface chính</sup> | Entry point là khung chat Gemini với gợi ý tool; có thể dùng ngay bằng free account. Surface chính là chat tổng quát, phù hợp người dùng muốn hỏi nhanh để ra shortlist laptop AI/ML. | Entry point là giao diện ChatGPT quen thuộc, có chọn model GPT-5.5 trong lúc test. Surface chính là chat có search/citation và preview sản phẩm ở panel bên, tạo cảm giác gần với hành vi tìm mua thực tế hơn. |
| **S2 - Workflow Evidence**<br><sup>Trước / trong / sau khi dùng AI. Friction chính</sup> | Workflow ngắn: mở Gemini -> nhập prompt -> đọc output -> có thể copy/export sang trang tính. Friction chính là output không có citation nên nếu mua thật vẫn phải tự kiểm tra giá và link shop. | Workflow cũng ngắn: mở ChatGPT -> nhập prompt -> đọc output có ảnh/link -> mở preview sản phẩm. Friction thấp hơn ở bước xác minh vì có citation/hình ảnh, nhưng output không có bảng so sánh tổng hợp như Gemini. |
| **S3 - Output & Trust**<br><sup>Chất lượng output + citation + disclaimer + control</sup> | Output dài 58 dòng, 746 từ, có bảng so sánh và lời khuyên theo góc nhìn AI Engineer; có disclaimer "Gemini là AI và có thể mắc sai sót". Điểm yếu là không có citation trong kết quả test. | Output ngắn hơn 50 dòng, 412 từ, nhưng có citation, hình ảnh và giá tham khảo cho từng laptop; có disclaimer "ChatGPT có thể mắc lỗi...". Điểm mạnh là trust signal rõ hơn khi người dùng cần quyết định mua. |
| **S4 - Business Signal**<br><sup>Pricing + paywall + định vị Cost-Capability-Speed</sup> | Free tier dùng được ngay; Google AI Pro/Ultra tăng giới hạn và ưu tiên tính năng trong Gemini Apps. Định vị nghiêng về **cân bằng**: miễn phí để thu hút user, trả phí để mở khóa model/tính năng mạnh hơn trong hệ sinh thái Google. | Free tier dùng được ngay; ChatGPT Plus $20/tháng, Pro $200/tháng, Business tính theo user/tháng trên trang pricing. Định vị nghiêng về **mạnh-đắt** ở tier cao, nhưng vẫn có free tier để mở rộng adoption. |
| **S5 - Product Judgment**<br><sup>Verdict 1 dòng</sup> | **Promising** - output có cấu trúc tốt và gắn với hệ sinh thái Google, nhưng bài test mua laptop bị thiếu citation nên trust khi ra quyết định mua chưa mạnh. | **Strong** - output có citation, ảnh sản phẩm, preview và phân tích chi tiết; với use case tìm mua laptop, ChatGPT giảm công xác minh tốt hơn. |

---

## Phần B - Đối chiếu 3 friction areas

- **Physical load**: Cả hai sản phẩm đều cần ít thao tác (mở web, nhập prompt, đọc output), nhưng ChatGPT giảm thêm việc mở tab tìm kiếm vì có citation và preview sản phẩm ngay trong kết quả.
- **Cognitive burden**: Gemini dễ đọc hơn khi cần bảng so sánh nhanh; ChatGPT dễ tin hơn khi cần xác minh từng mẫu laptop, giá và nguồn.
- **User workarounds**: Với Gemini, nhóm phải tự bù đắp bằng việc kiểm tra nguồn/giá bên ngoài; với ChatGPT, workaround chính là tự lập bảng so sánh tổng hợp vì output nghiêng về giải thích từng sản phẩm.

---

## Phần C - Đối chiếu 6 trust signals

| Tín hiệu đáng tin | Sản phẩm A - Google Gemini | Sản phẩm B - ChatGPT |
|---|---|---|
| 1. Dẫn nguồn (citation) - link mở được, đúng nội dung | **Không** trong kết quả test; output không kèm link nguồn. | **Có**; kết quả có citation, hình ảnh sản phẩm và preview ở panel bên. |
| 2. Disclaimer khi không chắc | **Có**; giao diện hiện "Gemini là AI và có thể mắc sai sót." | **Có**; giao diện hiện "ChatGPT có thể mắc lỗi..." và nhắc kiểm tra thông tin quan trọng. |
| 3. Fallback / dừng lại khi out-of-scope | **Chưa có bằng chứng**; prompt nằm trong phạm vi nên không test out-of-scope. | **Chưa có bằng chứng**; prompt nằm trong phạm vi nên không test out-of-scope. |
| 4. Consistency - chạy 2 lần cùng prompt | **Chưa test lần 2**; cần test thêm nếu đưa vào slide sau. | **Chưa test lần 2**; cần test thêm nếu đưa vào slide sau. |
| 5. User control - sửa lại, dừng, regenerate, undo | **Có**; có regenerate, copy/export, gợi ý câu hỏi tiếp theo, feedback thumb up/down. | **Có**; có regenerate, copy, lịch sử, feedback thumb up/down; không thấy gợi ý câu hỏi tiếp theo trong log. |
| 6. Explanation - giải thích tại sao AI nói thế | **Có**; giải thích theo cấu hình GPU/RAM, use case AI Engineer và bảng so sánh. | **Có**; giải thích từng laptop theo GPU, RAM, mức giá và độ phù hợp AI/ML. |

---

## Phần D - Định vị 2 sản phẩm trên Cost-Capability-Speed

- **Sản phẩm A nghiêng về**: **cân bằng** - lý do: free tier phản hồi nhanh 11 giây, output có cấu trúc tốt; trả phí Google AI Pro/Ultra tăng giới hạn, model và tính năng trong Gemini Apps/Google One.
- **Sản phẩm B nghiêng về**: **mạnh-đắt** - lý do: free tier vẫn dùng được, nhưng các năng lực mạnh và giới hạn cao nằm ở Plus/Pro/Business; trong bài test, ChatGPT trả lời nhanh hơn (9 giây) và có citation.

---

## Phần E - Verdict sơ bộ

- **Sản phẩm A - verdict sơ bộ**: **Promising**
  - Lý do 1 câu: Gemini cho câu trả lời có cấu trúc, bảng so sánh và lời khuyên tốt, nhưng thiếu citation làm giảm độ tin trong use case mua laptop.
- **Sản phẩm B - verdict sơ bộ**: **Strong**
  - Lý do 1 câu: ChatGPT phù hợp hơn với tác vụ tìm mua sản phẩm vì kết hợp giải thích, citation, hình ảnh và preview link, giúp người dùng xác minh nhanh hơn.

---

## Bảng kiểm trước khi sang Bước 3

- [x] Mỗi ô của bảng so sánh 5 mục có ít nhất 1-2 câu, không trống.
- [x] Mỗi nhận định đều có thể chỉ về ảnh / log trong `1-research-notes.md` làm bằng chứng.
- [x] Đã định vị cả 2 sản phẩm trên Cost-Capability-Speed.
- [x] Đã có verdict sơ bộ cho cả 2 sản phẩm.
- [x] Các mục thiếu bằng chứng (fallback, consistency) đã được đánh dấu rõ để không bị suy diễn.

Sang `3-FINAL-analysis-outline.md` để dựng outline 5 mục đầy đủ trước khi build slide.
