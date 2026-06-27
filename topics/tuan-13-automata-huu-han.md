# Tuần 13. Ôtômát hữu hạn

## Vai trò trong đề thi

Thuộc trọng tâm tự luận năm nay. Cần làm chắc cách đọc, mô phỏng và xây dựng máy.

## Nguồn đã nạp

- `materials/raw/lectures/Tuan13.pdf`
- `materials/extracted/lectures/Tuan13.txt`
- `materials/raw/homework/hw13.pdf`

## Kiến thức cốt lõi

- Máy hữu hạn có trạng thái, bảng chữ cái đầu vào, hàm chuyển và trạng thái bắt đầu.
- Máy có đầu ra còn có bảng chữ cái đầu ra và hàm đầu ra.
- Máy không đầu ra nhận xâu nếu sau khi đọc hết xâu, trạng thái hiện tại thuộc tập kết thúc.
- DFA có đúng một trạng thái tiếp theo cho mỗi cặp trạng thái/ký hiệu.
- NFA có thể có nhiều trạng thái tiếp theo; NFA và DFA tương đương về sức nhận dạng.
- Thiết kế máy thường dựa trên “ý nghĩa trạng thái”: trạng thái lưu thông tin tối thiểu cần nhớ.

## Định nghĩa/công thức/thuật toán cần nhớ

- DFA: $M=(S,I,f,s_0,F)$.
- FSM có đầu ra: $M=(S,I,O,f,g,s_0)$.
- Hàm chuyển mở rộng: $f(s,\lambda)=s$, $f(s,xa)=f(f(s,x),a)$.
- Xâu $x$ được nhận nếu $f(s_0,x)\in F$.
- Subset construction biến NFA thành DFA bằng cách lấy tập trạng thái NFA làm trạng thái DFA.

## Dạng bài hay ra

- Mô phỏng máy với xâu đầu vào và ghi chuỗi trạng thái/đầu ra.
- Thiết kế máy kiểm tra hậu tố, số lượng ký tự chẵn/lẻ, độ dài chia hết cho $k$.
- Tìm ngôn ngữ máy nhận.
- Dựng NFA ít trạng thái cho biểu thức đơn giản.
- Chuyển NFA sang DFA.

## Lỗi sai thường gặp

- Quên chỉ rõ trạng thái bắt đầu và trạng thái kết thúc.
- Trạng thái không có ý nghĩa rõ nên thiếu chuyển.
- Với điều kiện “kết thúc bằng”, chỉ nhìn ký tự hiện tại mà quên lịch sử cần nhớ.
- Với giao hai điều kiện, không dùng tích Descartes trạng thái.

## Bài đại diện nên xem lại

- `hw13`: Bài 1-3 cho máy có đầu ra.
- `hw13`: Bài 4-5 cho ngôn ngữ/xâu.
- `hw13`: Bài 6-10 cho regular expression, NFA và subset construction.

