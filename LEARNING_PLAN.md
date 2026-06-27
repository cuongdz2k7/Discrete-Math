# Kế hoạch ôn Toán rời rạc

Mục tiêu: ôn theo hướng A+, bám cấu trúc đề năm nay và luyện bài khó vừa sức thi.

## Nguyên tắc ưu tiên

1. Luôn đọc `EXAM_CONTEXT.md` trước khi ra đề, chọn bài sát đề hoặc đánh giá mức độ quan trọng.
2. Đề cũ trong `EXAM_ANALYSIS.md` chỉ dùng để cân độ khó và style kỹ năng, không dùng để suy ra format.
3. Với mỗi chương, học theo bộ ba: `topics/` để nắm lý thuyết, `exercises/` để chọn bài HW, `FORMULAS.md` để kiểm công thức.
4. Bài A+ phải khó ở nhận dạng và lập luận, không khó vì số xấu hoặc tính toán dài.

## Ưu tiên theo cấu trúc năm nay

| Mảng | Vai trò | Cách ôn |
| --- | --- | --- |
| Đồ thị | Trắc nghiệm và tự luận | Ưu tiên tuần 9-10: bậc, Euler/Hamilton, đẳng cấu, đường đi ngắn nhất, phẳng, tô màu. |
| Cây | Trắc nghiệm và tự luận | Ưu tiên tuần 11: DFS, BFS, Prim, Kruskal, rừng khung nhỏ nhất. |
| Ôtômát hữu hạn | Tự luận | Ưu tiên tuần 13-14: DFA/NFA, regex, chuyển NFA sang DFA, grammar qua automata. |
| Logic | Trắc nghiệm | Tuần 1-2: kéo theo, tương đương, lượng từ, luật suy luận, phương pháp chứng minh. |
| Thuật toán/RSA | Trắc nghiệm | Tuần 3-4: Big-O, giả mã, Euclid mở rộng, modulo, RSA. |
| Quy nạp/đệ quy | Trắc nghiệm | Tuần 5: quy nạp thường/mạnh, truy hồi, định nghĩa đệ quy. |
| Boolean | Trắc nghiệm | Tuần 3: luật Boolean, SOP, mạch, K-map cơ bản. |
| Ngôn ngữ hình thức/Máy Turing | Trắc nghiệm | Tuần 12, 15: văn phạm, dẫn xuất, phân loại, mô phỏng/thiết kế máy Turing đơn giản. |
| Đếm tổ hợp | Trắc nghiệm | Tuần 6-8: cộng/nhân, bao hàm - loại trừ, Dirichlet, hoán vị/tổ hợp có ràng buộc. |

## Lộ trình đề xuất

### Giai đoạn 1: Khóa phần tự luận

1. Học `topics/tuan-09-do-thi.md`, làm theo `exercises/tuan-09-do-thi-priority.md`.
2. Học `topics/tuan-10-duong-di-ngan-nhat.md`, làm theo `exercises/tuan-10-duong-di-ngan-nhat-priority.md`.
3. Học `topics/tuan-11-cay.md`, làm theo `exercises/tuan-11-cay-priority.md`.
4. Học `topics/tuan-13-automata-huu-han.md` và `topics/tuan-14-tap-chinh-quy-doan-nhan.md`.

### Giai đoạn 2: Phủ trắc nghiệm rộng

1. Logic và chứng minh: tuần 1-2.
2. Boolean, thuật toán và RSA: tuần 3-4.
3. Quy nạp, đệ quy: tuần 5.
4. Đếm tổ hợp: tuần 6-8.
5. Văn phạm và máy Turing: tuần 12, 15.

### Giai đoạn 3: Luyện A+

1. Làm các nhóm được đánh dấu `Bắt buộc A+` trong từng file `exercises/*-priority.md`.
2. Tạo đề mô phỏng theo `rules/exam-practice.md`.
3. Sau mỗi đề, cập nhật lỗi vào `MISTAKES.md` và câu chưa chắc vào `QUESTIONS.md`.
4. Làm lại bài sai sau 24-48 giờ, không chỉ đọc lời giải.

## Checklist trước khi ra đề mô phỏng

- Đã đọc `AGENTS.md` và `EXAM_CONTEXT.md`.
- Phần trắc nghiệm có đủ: Logic, Thuật toán, Quy nạp, Đệ quy, Boolean, Ngôn ngữ hình thức/Máy Turing, Đếm tổ hợp, RSA, Đồ thị, Cây.
- Phần tự luận có đúng trọng tâm: Đồ thị, Cây, Ôtômát hữu hạn.
- Độ khó tham khảo từ `EXAM_ANALYSIS.md`, nhưng format theo năm nay.
- Câu khó có lời giải trong thời gian thi, không yêu cầu tính toán rườm rà.

## Cách học một chương

1. Đọc topic tương ứng trong `topics/`.
2. Mở file priority trong `exercises/` để chọn nhóm bài.
3. Làm bài không nhìn lời giải, ghi lại bước kẹt.
4. So lại `FORMULAS.md` và cập nhật `MISTAKES.md` nếu sai do công thức/bẫy.
5. Yêu cầu agent tạo 3-5 bài biến thể cùng mức hoặc khó hơn một nấc.
