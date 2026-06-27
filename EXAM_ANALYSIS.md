# Phân tích đề cũ

File này phân tích đề cũ để tham khảo độ khó và kỹ năng kiểm tra. Không dùng đề cũ để quyết định format năm nay; format năm nay nằm ở `EXAM_CONTEXT.md`.

## Ma trận đề đã đọc

| Đề | Cấu trúc cũ | Chủ đề xuất hiện | Độ khó tham khảo | Ghi chú dùng cho năm nay |
| --- | --- | --- | --- | --- |
| `exam-2020-2021-hk2-chuan.pdf` | 5 câu, 70 phút | Đếm nghiệm nguyên, đồ thị, đường đi ngắn nhất, MST, văn phạm chính quy, ôtômát, bảng chân trị, kéo theo | Trung bình đến khó | Hữu ích để luyện tự luận đồ thị + ôtômát, nhưng format khác năm nay. |
| `exam-2020-2021-hk2-clc23.pdf` | 5 câu, 70 phút | Bao hàm - loại trừ, đồ thị, đường đi ngắn nhất, MST, regular expression, ôtômát, logic mệnh đề | Khó hơn do phụ thuộc MSSV và nhiều biến thể | Dùng để tạo bài luyện biến tham số, không dùng làm format. |
| `exam-2023-2024-hk2-de1.pdf` | 5 câu, 90 phút | Đồ thị con đầy đủ, cây khung, đẳng cấu, vị từ/suy diễn, NFA, văn phạm chính quy, MST | Khó vừa, thiên tự luận | Rất tốt để cân độ khó tự luận đồ thị + ôtômát. |
| `exam-2024-2025-hk2-de2.pdf` | 5 câu, 90 phút | Logic cổng nói dối, đếm hoán vị/chọn tập, hypercube 6-bit, Euler/phân đôi/phẳng, cây khung, DFS/BFS, DFA giao/hợp, văn phạm | Khó, tổng hợp nhiều chương | Dùng tham khảo độ khó gần nhất; năm nay vẫn phải theo `EXAM_CONTEXT.md`. |

## Pattern độ khó rút ra từ đề cũ

- Logic không chỉ hỏi bảng chân trị đơn giản; có thể hỏi dịch tình huống tự nhiên thành mệnh đề và suy luận các trường hợp.
- Đếm thường kết hợp bao hàm - loại trừ, hoán vị lặp, chọn tập con và điều kiện chẵn/lẻ.
- Đồ thị trong đề cũ thường không chỉ nhận dạng định nghĩa; hay yêu cầu chứng minh Euler, phân đôi, không phẳng, đếm cây khung hoặc chạy thuật toán.
- Cây thường gắn với cây khung, DFS/BFS, MST bằng Prim/Kruskal.
- Ôtômát thường yêu cầu dựng máy cho ngôn ngữ cụ thể, lấy giao/hợp máy, hoặc chuyển qua văn phạm chính quy.
- Câu khó vừa sức thi thường có nhiều ý nhỏ, mỗi ý dùng một định lý rõ ràng; ít khi cần tính toán số xấu dài.

## Cảnh báo khi dùng đề cũ

- Đề cũ có format 5 câu tự luận, trong khi năm nay có trắc nghiệm 20-30 câu và tự luận 2 câu.
- Các bài cũ về đồ thị/ôtômát vẫn rất đáng luyện vì trùng trọng tâm tự luận năm nay.
- Các bài cũ về đếm/logic nên chuyển thành trắc nghiệm nhiều đáp án đúng hoặc bài ngắn.

