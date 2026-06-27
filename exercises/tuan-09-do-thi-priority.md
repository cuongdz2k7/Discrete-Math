# Tuần 09. Đồ thị - bài tập ưu tiên

## Vai trò trong đề thi

Đồ thị thuộc cả trắc nghiệm và tự luận năm nay. Đây là mảng trọng tâm, cần luyện định nghĩa, mô hình hóa, bậc, liên thông, Euler, Hamilton, đẳng cấu và các đồ thị chuẩn.

## Nguồn bài tập

- `materials/raw/homework/hw09.pdf`
- `materials/extracted/homework/hw09.txt`
- Lý thuyết liên quan: `topics/tuan-09-do-thi.md`

## Bảng lọc bài tập

| Bài | Dạng bài | Mức độ | Khả năng ra thi | Ưu tiên | Ghi chú A+ |
| --- | --- | --- | --- | --- | --- |
| 1-3 | Mô hình hóa mạng bằng đồ thị | Cơ bản - vừa | Trung bình | Nên làm | Giúp đọc đề tự luận nhanh. |
| 4, 8 | Bậc đỉnh, định lý bắt tay, tính khả thi | Vừa | Cao | Bắt buộc | Rất sát trắc nghiệm. |
| 5-7 | Đồ thị chuẩn \(K_n, C_n, W_n, Q_n, K_{m,n}\) | Vừa | Cao | Bắt buộc | Cần nhớ số đỉnh/cạnh và tính lưỡng phân. |
| 9-11 | Ma trận kề, ma trận liên thuộc, đỉnh cô lập | Vừa | Cao | Bắt buộc | Dễ ra dạng đọc bảng/ma trận. |
| 12-14 | Không đẳng cấu, số đường đi, đẳng cấu | Khó vừa | Trung bình cao | A+ | Dùng bất biến: bậc, chu trình, liên thông, tam giác. |
| 15 | Độ liên thông đỉnh/cạnh của \(K_{m,n}\) | Khó vừa | Trung bình | A+ | Gọn nhưng cần nhớ kết quả đúng. |
| 16 | Đồ thị lưỡng phân iff không có chu trình lẻ | Khó vừa | Cao | Bắt buộc A+ | Dạng chứng minh đẹp, có thể hỗ trợ tự luận. |
| 17-19 | Euler, Hamilton cho đồ thị chuẩn | Vừa - khó | Cao | Bắt buộc | Đây là lõi tự luận/trắc nghiệm đồ thị. |

## Công cụ bắt buộc

| Nội dung | Dùng khi nào | Bẫy |
| --- | --- | --- |
| Định lý bắt tay | Tổng bậc, số cạnh, số đỉnh bậc lẻ | Quên tổng bậc bằng \(2|E|\). |
| Bất biến đẳng cấu | So sánh hai đồ thị | Chỉ nhìn hình vẽ mà không kiểm bậc/chu trình. |
| Euler | Chu trình/đường đi qua mọi cạnh | Nhầm với Hamilton qua mọi đỉnh. |
| Lưỡng phân | Chia hai tập đỉnh, không có cạnh trong cùng tập | Chu trình lẻ phá lưỡng phân. |

## Khung tư duy

### Đồ thị có thể tồn tại không

- Kiểm tra tổng bậc chẵn.
- Kiểm tra bậc không vượt quá \(n-1\) với đồ thị đơn.
- Nếu cần, thử dựng hoặc dùng Havel-Hakimi.

### Euler/Hamilton

- Euler: nhìn bậc đỉnh và liên thông.
- Hamilton: tìm chu trình qua mọi đỉnh, dùng phản ví dụ/cản trở nếu không có.
- Không dùng điều kiện Euler để kết luận Hamilton.

### Đẳng cấu

- So sánh số đỉnh, số cạnh, dãy bậc.
- So sánh số thành phần liên thông, chu trình, tam giác.
- Nếu các bất biến khớp, mới thử lập ánh xạ.

## Thứ tự làm đề xuất

1. Làm 4, 5, 6, 7, 8, 9-11 để chắc công cụ nền.
2. Làm 17-19 vì sát trọng tâm đồ thị.
3. Làm 12-16 để lên mức A+.
4. Làm 1-3 để luyện mô hình hóa nếu còn thời gian.

## Lỗi dễ mất điểm

- Nhầm cạnh với đỉnh trong Euler/Hamilton.
- Quên điều kiện liên thông khi xét Euler.
- Kết luận hai đồ thị đẳng cấu chỉ vì cùng số đỉnh/cạnh.
- Nhầm \(W_n\) theo quy ước số đỉnh của chu trình và đỉnh tâm.
