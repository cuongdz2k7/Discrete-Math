# Tuần 15. Nhận dạng ngôn ngữ và Máy Turing

## Vai trò trong đề thi

Thuộc phần trắc nghiệm về ngôn ngữ hình thức / Máy Turing. Có thể hỏi mô phỏng máy hoặc nhận dạng tác dụng của máy.

## Nguồn đã nạp

- `materials/raw/lectures/Tuan15.pdf`
- `materials/extracted/lectures/Tuan15.txt`
- `materials/raw/homework/hw15.pdf`

## Kiến thức cốt lõi

- Máy hữu hạn chỉ nhận được các tập chính quy; có ngôn ngữ không chính quy như $\{0^n1^n\}$.
- Pushdown automata mạnh hơn máy hữu hạn nhờ ngăn xếp, nhận được ngôn ngữ phi ngữ cảnh.
- Máy Turing là mô hình tổng quát với băng vô hạn, đầu đọc/ghi và hàm chuyển.
- Máy Turing có thể dùng để nhận ngôn ngữ hoặc tính hàm.
- Bài toán dừng là ví dụ điển hình của bài toán không quyết định được.
- Lớp $P$ và $NP$ được mô tả bằng máy Turing tất định/không tất định thời gian đa thức.

## Định nghĩa/công thức/thuật toán cần nhớ

- Máy Turing $T=(S,I,f,s_0)$.
- Bộ năm $(s,x,s',x',d)$ nghĩa là đang ở $s$ đọc $x$, ghi $x'$, sang $s'$, rồi dịch $d\in\{L,R\}$.
- Nếu không có chuyển cho cặp $(s,x)$ thì máy dừng.
- Máy nhận xâu nếu dừng ở trạng thái kết thúc.
- Số nguyên không âm $n$ có thể biểu diễn nhất phân bằng $n+1$ ký tự $1$.

## Dạng bài hay ra

- Mô phỏng máy Turing trên đầu vào ngắn.
- Xác định máy làm gì với xâu bit bất kỳ.
- Dựng máy thay ký tự đầu tiên hoặc tất cả ký tự theo điều kiện.
- Dựng máy nhận xâu kết thúc bằng 0 hoặc có số lượng 1 chẵn.
- Dựng máy tính hàm đơn giản trên biểu diễn nhất phân.

## Lỗi sai thường gặp

- Quên xét ký hiệu trắng $B$.
- Dừng ở trạng thái không kết thúc nhưng vẫn kết luận nhận.
- Khi mô phỏng, ghi rồi mới dịch; không được dịch trước.
- Nhầm “không nhận” với “dừng và từ chối”; máy cũng có thể chạy mãi.

## Bài đại diện nên xem lại

- `hw15`: Bài 1-2 cho mô phỏng máy.
- `hw15`: Bài 3-6 cho dựng máy nhận/chỉnh xâu bit.
- `hw15`: Bài 7 cho máy tính hàm.

