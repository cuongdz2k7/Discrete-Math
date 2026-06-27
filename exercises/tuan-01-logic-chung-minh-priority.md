# Tuần 01. Logic và chứng minh - bài tập ưu tiên

## Vai trò trong đề thi

Logic thuộc phần trắc nghiệm năm nay. Mục tiêu là nhận dạng nhanh mệnh đề, kéo theo, tương đương logic, vị từ và lượng từ, đặc biệt trong câu nhiều đáp án đúng.

## Nguồn bài tập

- `materials/raw/homework/hw01.pdf`
- `materials/extracted/homework/hw01.txt`
- Lý thuyết liên quan: `topics/tuan-01-logic-chung-minh.md`

## Bảng lọc bài tập

| Bài | Dạng bài | Mức độ | Khả năng ra thi | Ưu tiên | Ghi chú A+ |
| --- | --- | --- | --- | --- | --- |
| 1, 4 | Dịch câu tự nhiên sang mệnh đề logic | Cơ bản - vừa | Cao | Bắt buộc | Chú ý phân biệt "if", "only if", "unless", "iff". |
| 2, 3, 6 | Bảng chân trị, giá trị của kéo theo | Cơ bản | Cao | Bắt buộc | Phải làm nhanh, không nhầm trường hợp \(p \to q\) chỉ sai khi \(p\) đúng, \(q\) sai. |
| 5 | Mệnh đề đảo, phản đảo, phản đảo ngược | Cơ bản | Trung bình | Nên làm | Dạng dễ mất điểm vì dịch sai tiếng Việt. |
| 7-10 | Chứng minh tương đương logic | Vừa - khó | Cao | Bắt buộc A+ | Ưu tiên dùng luật logic thay vì bảng chân trị dài. |
| 11-17 | Vị từ, miền xác định, lượng từ | Vừa | Cao | Bắt buộc | Ghi rõ miền, thứ tự lượng từ và biến tự do. |
| 18-20 | Phủ định/lượng từ lồng nhau, dịch câu định lượng | Khó vừa | Cao | Bắt buộc A+ | Đây là nhóm sát trắc nghiệm phân loại. |

## Công cụ bắt buộc

| Nội dung | Dùng khi nào | Bẫy |
| --- | --- | --- |
| Luật kéo theo \(p \to q \equiv \neg p \lor q\) | Rút gọn, phủ định, tương đương | Nhầm với \(q \to p\). |
| De Morgan | Phủ định biểu thức logic và lượng từ | Quên đổi \(\forall\) thành \(\exists\). |
| Tương đương \(p \leftrightarrow q\) | Câu "khi và chỉ khi" | Cần cả hai chiều. |
| Thứ tự lượng từ | Câu có nhiều biến | \(\forall x\exists y\) khác \(\exists y\forall x\). |

## Khung tư duy

### Dịch mệnh đề

- Xác định mệnh đề nguyên tử trước.
- Đổi từ khóa ngôn ngữ tự nhiên sang phép logic.
- Kiểm tra chiều kéo theo bằng câu "điều kiện đủ" và "điều kiện cần".

### Chứng minh tương đương

- Bắt đầu từ vế phức tạp hơn.
- Dùng từng luật logic và ghi tên luật nếu cần.
- Nếu biểu thức ngắn, bảng chân trị là phương án kiểm tra nhanh.

### Vị từ và lượng từ

- Ghi miền xác định trước khi kết luận.
- Khi phủ định, đổi lượng từ và phủ định mệnh đề bên trong.
- Với lượng từ lồng nhau, thử một ví dụ nhỏ để kiểm tra ý nghĩa.

## Thứ tự làm đề xuất

1. Làm nhanh 1, 2, 3, 4, 5, 6 để khóa nền.
2. Làm 7-10 đến khi biến đổi luật logic không cần nhìn công thức.
3. Làm 11-20, ưu tiên 18-20 nếu đang luyện A+.

## Lỗi dễ mất điểm

- Dịch "only if" thành sai chiều kéo theo.
- Phủ định \(\forall x P(x)\) thành \(\forall x \neg P(x)\).
- Không ghi miền xác định nên câu vị từ bị mơ hồ.
- Chọn đáp án nhiều lựa chọn theo cảm giác thay vì kiểm từng trường hợp.
