# Tuần 13. Ôtômát hữu hạn - bài tập ưu tiên

## Vai trò trong đề thi

Ôtômát hữu hạn là nội dung tự luận năm nay, nên đây là cụm ưu tiên rất cao. Cần luyện mô phỏng FSM, thiết kế DFA/NFA, regex và chuyển NFA sang DFA.

## Nguồn bài tập

- `materials/raw/homework/hw13.pdf`
- `materials/extracted/homework/hw13.txt`
- Lý thuyết liên quan: `topics/tuan-13-automata-huu-han.md`

## Bảng lọc bài tập

| Bài | Dạng bài | Mức độ | Khả năng ra thi | Ưu tiên | Ghi chú A+ |
| --- | --- | --- | --- | --- | --- |
| 1 | Mô phỏng FSM với chuỗi vào | Vừa | Cao | Bắt buộc | Ghi dãy trạng thái hoặc bảng chuyển. |
| 2 | Máy bán hàng/trạng thái có output | Vừa | Trung bình cao | Nên làm | Rèn mô hình hóa trạng thái theo ngữ cảnh. |
| 3 | Thiết kế FSM theo điều kiện bit | Khó vừa | Cao | Bắt buộc A+ | Rất sát tự luận ôtômát. |
| 4-5 | Tập chuỗi, nối, lũy thừa, membership | Vừa | Cao | Bắt buộc | Củng cố ngôn ngữ trước khi dựng automata. |
| 6-8 | Biểu thức chính quy và ngôn ngữ | Vừa | Cao | Bắt buộc | Cần chuyển đổi giữa mô tả lời và regex. |
| 9 | Dựng NFA cho regex/ngôn ngữ | Vừa - khó | Cao | Bắt buộc A+ | Tập dùng nhánh \(\epsilon\) hoặc nhánh lựa chọn. |
| 10 | Chuyển NFA sang DFA | Khó vừa | Cao | Bắt buộc A+ | Dạng tự luận đẹp, phân loại rõ. |

## Công cụ bắt buộc

| Nội dung | Dùng khi nào | Bẫy |
| --- | --- | --- |
| DFA | Mỗi trạng thái và ký tự có đúng một chuyển | Thiếu chuyển trạng thái chết. |
| NFA | Có thể có nhiều chuyển hoặc \(\epsilon\)-move | Quên lấy \(\epsilon\)-closure nếu có. |
| Regex | Mô tả ngôn ngữ chính quy | Dấu `*` áp dụng cho khối ngay trước nó. |
| Subset construction | Chuyển NFA sang DFA | Bỏ sót tập trạng thái rỗng hoặc tập chưa xét. |

## Khung tư duy

### Thiết kế DFA/FSM

- Trạng thái phải lưu đúng lượng thông tin cần nhớ.
- Xác định trạng thái bắt đầu và trạng thái chấp nhận.
- Kiểm tra mọi ký tự trong alphabet đều có đường đi.
- Test chuỗi ngắn: rỗng, độ dài 1, chuỗi biên thỏa/không thỏa.

### Chuyển NFA sang DFA

- Trạng thái DFA là tập trạng thái NFA.
- Bắt đầu từ \(\epsilon\)-closure của trạng thái đầu nếu có \(\epsilon\).
- Với mỗi tập và mỗi ký tự, lấy hợp các đích rồi closure.
- Trạng thái DFA chấp nhận nếu tập chứa trạng thái chấp nhận của NFA.

## Thứ tự làm đề xuất

1. Làm 1, 4, 5 để chắc mô phỏng và ngôn ngữ.
2. Làm 6-8 để chắc regex.
3. Làm 3, 9, 10 vì sát tự luận A+.
4. Làm 2 nếu muốn luyện mô hình hóa thực tế.

## Lỗi dễ mất điểm

- Thiết kế DFA thiếu trạng thái chết.
- Không ghi alphabet nên máy bị mơ hồ.
- Nhận nhầm chuỗi do không test trường hợp biên.
- Chuyển NFA sang DFA nhưng quên trạng thái là tập, không phải một đỉnh đơn.
