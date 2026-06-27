# Dạng bài ôn thi

Các pattern dưới đây bám `EXAM_CONTEXT.md`. Đề cũ chỉ dùng để cân độ khó và phong cách hỏi.

## Trắc nghiệm năm nay

| Chủ đề | Pattern cần luyện | Mức A+ cần đạt | Bẫy hay gặp |
| --- | --- | --- | --- |
| Logic | Bảng chân trị, tương đương, kéo theo, phủ định lượng từ, suy diễn | Nhận ra mệnh đề tương đương mà không cần lập full bảng nếu có thể | Nhầm kéo theo với hai chiều; phủ định lượng từ sai. |
| Thuật toán | Đọc giả mã, Big-O/Omega/Theta, tìm kiếm, greedy, chia để trị | Ước lượng bậc tăng nhanh và hiểu điều kiện dừng | Giữ hệ số/hạng thấp không cần thiết; nhầm $O$ với $\Theta$. |
| Quy nạp | Quy nạp thường, mạnh, phản ví dụ quy nạp sai | Biết chọn bước cơ sở đúng miền và giả thiết đủ mạnh | Bỏ qua $n$ bắt đầu từ đâu; bước quy nạp không dùng được cho trường hợp đầu. |
| Đệ quy | Tính giá trị, định nghĩa đệ quy, Fibonacci, xâu, cây | Viết được cơ sở + bước đệ quy rõ | Thiếu điều kiện dừng hoặc định nghĩa sinh thừa/thiếu. |
| Đại số Boolean | Rút gọn, tổng-các-tích, NAND/NOR, mạch logic | Dựng biểu thức/mạch từ mô tả | Nhầm $+$ Boolean với cộng số học; thiếu minterm. |
| Ngôn ngữ hình thức / Máy Turing | Văn phạm, phân loại Chomsky, dẫn xuất, Turing theo bộ năm | Mô phỏng máy và nhận dạng tác dụng của máy | Nhầm terminal/nonterminal; quên trường hợp máy không dừng. |
| Đếm tổ hợp | Cộng/nhân, bao hàm - loại trừ, tổ bồ câu, hoán vị/tổ hợp, nhị thức, truy hồi/hàm sinh | Chọn mô hình đếm đúng trước khi tính | Đếm trùng, nhầm có thứ tự/không thứ tự, quên điều kiện chẵn/lẻ. |
| RSA | Đồng dư, nghịch đảo modulo, mã hóa/giải mã, lũy thừa nhanh | Làm được với số nhỏ bằng Euclid/lũy thừa modulo | Quên điều kiện $\gcd(e,\varphi(n))=1$; dùng modulo sai. |
| Đồ thị và Cây | Bậc, liên thông, Euler/Hamilton, phẳng, tô màu, cây, DFS/BFS/MST | Nhận định lý cần dùng và trình bày chứng minh ngắn | Dùng tiêu chuẩn Euler cho Hamilton; nhầm DFS/BFS/Prim/Kruskal. |

## Tự luận năm nay

| Chủ đề | Dạng nên luyện | Tiêu chuẩn lời giải |
| --- | --- | --- |
| Đồ thị | Bậc, Euler, Hamilton, phân đôi, phẳng, tô màu, đường đi ngắn nhất | Nêu định nghĩa/định lý, kiểm tra điều kiện, kết luận rõ. |
| Cây | Cây khung, DFS/BFS, MST, tính chất $n-1$ cạnh, cây có gốc | Trình bày từng bước thuật toán, thứ tự xét đỉnh/cạnh không mơ hồ. |
| Ôtômát hữu hạn | Dựng DFA/NFA, giao/hợp ngôn ngữ, văn phạm chính quy | Ghi đủ tập trạng thái, bảng chữ cái, trạng thái đầu, trạng thái kết thúc, hàm chuyển/bảng chuyển. |

## Bài A+ nên tạo

- Logic: tình huống tự nhiên có nhiều phát biểu sai/đúng, yêu cầu suy ra trường hợp bắt buộc.
- Đếm: bài có điều kiện chẵn/lẻ hoặc chia hết nhưng số liệu nhỏ, dùng được bao hàm - loại trừ.
- Đồ thị: chứng minh một đồ thị có/không có Euler, phân đôi, phẳng; tránh hình quá rối.
- Cây: chạy BFS/DFS/MST có bảng bước rõ.
- Ôtômát: dựng máy cho điều kiện kết hợp như “số chẵn ký tự a” và “độ dài chia hết cho 3”, rồi lấy giao/hợp.

