# Tuần 07. Phép đếm tổ hợp - bài tập ưu tiên

## Vai trò trong đề thi

Tuần 7 là lõi của phần đếm tổ hợp: hoán vị, chỉnh hợp, tổ hợp, lặp và hệ số nhị thức. Đây là nhóm rất dễ xuất hiện ở trắc nghiệm tính nhanh.

## Nguồn bài tập

- `materials/raw/homework/hw07.pdf`
- `materials/extracted/homework/hw07.txt`
- Lý thuyết liên quan: `topics/tuan-07-phep-dem-to-hop.md`

## Bảng lọc bài tập

| Bài | Dạng bài | Mức độ | Khả năng ra thi | Ưu tiên | Ghi chú A+ |
| --- | --- | --- | --- | --- | --- |
| 1-2 | Hoán vị, chỉnh hợp, tổ hợp cơ bản | Cơ bản | Cao | Bắt buộc | Phải nhận ra có xét thứ tự hay không. |
| 3-5 | Chuỗi bit, chọn vị trí, điều kiện số lượng | Vừa | Cao | Bắt buộc | Dạng rất sát trắc nghiệm. |
| 6-8 | Hệ số nhị thức, khai triển Newton | Vừa | Cao | Bắt buộc | Chú ý hệ số cụ thể sau khai triển. |
| 9-10 | Đồng nhất thức tổ hợp | Vừa - khó | Trung bình cao | A+ | Nên biết cả chứng minh đại số và chứng minh đếm. |

## Công cụ bắt buộc

| Nội dung | Dùng khi nào | Bẫy |
| --- | --- | --- |
| \(P(n)=n!\) | Sắp toàn bộ phần tử khác nhau | Dùng sai khi có phần tử lặp. |
| \(A(n,k)=n!/(n-k)!\) | Chọn có thứ tự | Nhầm với tổ hợp. |
| \(C(n,k)=n!/(k!(n-k)!)\) | Chọn không thứ tự | Quên điều kiện \(0\le k\le n\). |
| Nhị thức Newton | Tìm hệ số trong \((x+y)^n\) | Bỏ sót lũy thừa biến. |

## Khung tư duy

### Chọn công thức

- Hỏi trước: thứ tự có quan trọng không?
- Có được lặp không?
- Có điều kiện "ít nhất", "nhiều nhất", "chính xác" không?
- Nếu điều kiện phức, đếm bù có thể nhanh hơn.

### Hệ số nhị thức

- Viết hạng tổng quát.
- Áp điều kiện số mũ cần tìm.
- Lấy đúng hệ số, bao gồm cả hệ số từ biến/hằng trong ngoặc.

## Thứ tự làm đề xuất

1. Làm 1-5 cho nhuần nhuyễn nhận dạng.
2. Làm 6-8 để khóa nhị thức.
3. Làm 9-10 để luyện A+ và chứng minh đồng nhất thức.

## Lỗi dễ mất điểm

- Không phân biệt chỉnh hợp với tổ hợp.
- Đếm chuỗi bit bằng hoán vị khi chỉ cần chọn vị trí.
- Với "ít nhất", cộng thiếu trường hợp hoặc quên đếm bù.
- Quên hệ số âm/dấu khi khai triển biểu thức có dấu trừ.
