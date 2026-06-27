# Tuần 14. Tập chính quy và đoán nhận - bài tập ưu tiên

## Vai trò trong đề thi

Tuần 14 nối regex, NFA và văn phạm chính quy. Nội dung này hỗ trợ trực tiếp tự luận ôtômát hữu hạn và trắc nghiệm ngôn ngữ hình thức.

## Nguồn bài tập

- `materials/raw/homework/hw14.pdf`
- `materials/extracted/homework/hw14.txt`
- Lý thuyết liên quan: `topics/tuan-14-tap-chinh-quy-doan-nhan.md`

## Bảng lọc bài tập

| Bài | Dạng bài | Mức độ | Khả năng ra thi | Ưu tiên | Ghi chú A+ |
| --- | --- | --- | --- | --- | --- |
| 1 | Mô tả ngôn ngữ của regex | Vừa | Cao | Bắt buộc | Đọc đúng phạm vi của `*`, hợp và nối. |
| 2 | Viết regex cho tập chuỗi | Vừa - khó | Cao | Bắt buộc A+ | Dạng rất sát trắc nghiệm/tự luận ngắn. |
| 3 | Dựng NFA | Vừa - khó | Cao | Bắt buộc A+ | Ưu tiên cách dựng rõ, dễ kiểm tra. |
| 4 | Dựng NFA từ văn phạm chính quy | Khó vừa | Trung bình cao | A+ | Cần quy tắc chuyển production sang cạnh. |
| 5 | Dựng văn phạm chính quy từ NFA | Khó vừa | Trung bình cao | A+ | Dạng đảo chiều, hay phân loại sinh viên chắc bản chất. |

## Công cụ bắt buộc

| Nội dung | Dùng khi nào | Bẫy |
| --- | --- | --- |
| Regular expression | Mô tả tập chính quy | Nhầm ưu tiên phép toán. |
| NFA nhận regex | Dựng máy cho hợp/nối/lặp | Quên trạng thái nhận sau cùng. |
| Regular grammar phải tuyến tính | Chuyển grammar và automata | Trộn tuyến tính trái/phải không kiểm soát. |
| Grammar \(\leftrightarrow\) NFA | Bài chuyển đổi | Quên production sinh \(\lambda\). |

## Khung tư duy

### Regex sang NFA

- Tách regex theo hợp, nối, sao Kleene.
- Dựng từng khối nhỏ rồi ghép.
- Đánh dấu trạng thái bắt đầu và chấp nhận rõ ràng.

### NFA sang grammar

- Mỗi trạng thái ứng với một biến.
- Cạnh \(q_i \xrightarrow{a} q_j\) thành production \(A_i \to aA_j\).
- Trạng thái chấp nhận cho production sinh \(\lambda\) nếu cần.

### Grammar sang NFA

- Mỗi biến thành một trạng thái.
- Production \(A \to aB\) thành cạnh nhãn \(a\) từ \(A\) đến \(B\).
- Production \(A \to a\) đi đến trạng thái nhận cuối.

## Thứ tự làm đề xuất

1. Làm 1-2 để chắc regex.
2. Làm 3 để luyện dựng NFA.
3. Làm 4-5 để lên mức A+ và nối với văn phạm.

## Lỗi dễ mất điểm

- Đặt dấu sao Kleene sai phạm vi.
- Dựng NFA nhận thiếu chuỗi rỗng hoặc nhận thừa chuỗi rỗng.
- Chuyển grammar sang NFA nhưng quên trạng thái cuối.
- Không test máy bằng vài chuỗi thuộc/không thuộc ngôn ngữ.
