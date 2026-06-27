# Tuần 03. Đại số Boolean - bài tập ưu tiên

## Vai trò trong đề thi

Đại số Boolean thuộc trắc nghiệm năm nay. Cần nắm luật biến đổi, dạng tổng các tích, mạch logic và tối giản hàm để xử lý câu lý thuyết lẫn bài tính ngắn.

## Nguồn bài tập

- `materials/raw/homework/hw03.pdf`
- `materials/extracted/homework/hw03.txt`
- Lý thuyết liên quan: `topics/tuan-03-dai-so-boolean.md`

## Bảng lọc bài tập

| Bài | Dạng bài | Mức độ | Khả năng ra thi | Ưu tiên | Ghi chú A+ |
| --- | --- | --- | --- | --- | --- |
| 1-5 | Luật Boolean, đối ngẫu, chứng minh đẳng thức | Vừa | Cao | Bắt buộc | Rèn biến đổi bằng luật thay vì thử mò bảng. |
| 6-8 | Dạng tổng các tích, minterm/maxterm | Vừa | Cao | Bắt buộc | Cần đọc được từ bảng giá trị và viết đúng biến phủ định. |
| 9-12 | Mạch logic, cổng NAND/NOR, biểu diễn hàm | Vừa | Trung bình cao | Nên làm | Sát câu hỏi nhận dạng mạch/cổng. |
| 13-14 | Karnaugh, Quine-McCluskey | Khó vừa | Trung bình | A+ | Hữu ích để phân loại, nhưng tránh bài tính quá dài. |
| 15-22 | Thuật toán, giả mã, tìm kiếm, độ phức tạp | Vừa | Cao | Bắt buộc | Thuật toán thuộc trắc nghiệm năm nay, cần đọc giả mã nhanh. |

## Công cụ bắt buộc

| Nội dung | Dùng khi nào | Bẫy |
| --- | --- | --- |
| Luật hấp thụ | Tối giản biểu thức Boolean | Bỏ sót nhân tử chung. |
| Đối ngẫu | Câu hỏi biến đổi luật | Đổi \(+\) với \(\cdot\), \(0\) với \(1\), không đổi biến. |
| SOP chuẩn | Viết hàm từ bảng chân trị | Chỉ lấy dòng hàm bằng 1. |
| Big-O cơ bản | Đánh giá thuật toán | Lẫn hằng số với bậc tăng trưởng. |

## Khung tư duy

### Boolean

- Nếu có bảng, xác định dòng bằng 1 trước.
- Nếu có biểu thức, thử luật hấp thụ, De Morgan, phân phối.
- Nếu cần tối giản bằng K-map, nhóm ô \(1\) theo lũy thừa của 2, nhóm càng lớn càng tốt.

### Thuật toán

- Xác định input và output.
- Đếm vòng lặp theo biến kích thước \(n\).
- Với tìm kiếm, phân biệt tuyến tính, nhị phân và điều kiện dữ liệu đã sắp.

## Thứ tự làm đề xuất

1. Làm 1-8 để chắc Boolean nền.
2. Làm 15-22 xen kẽ vì thuật toán nằm trong trắc nghiệm năm nay.
3. Làm 9-14 để lên mức A+ và tăng tốc xử lý mạch/tối giản.

## Lỗi dễ mất điểm

- Viết sai minterm do quên phủ định biến ở dòng giá trị 0.
- Nhóm Karnaugh không theo số ô \(1,2,4,8,\ldots\).
- Đánh giá Big-O bằng số bước cụ thể thay vì bậc tăng trưởng.
- Nhầm NAND/NOR với AND/OR có phủ định đầu vào.
