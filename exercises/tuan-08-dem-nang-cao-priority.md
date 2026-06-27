# Tuần 08. Đếm nâng cao - bài tập ưu tiên

## Vai trò trong đề thi

Tuần 8 gom các bài đếm phối hợp: chuỗi, sắp xếp có ràng buộc, Dirichlet nâng cao, đếm bù và các bài kiểu phân loại. Đây là nguồn tốt để luyện trắc nghiệm A+.

## Nguồn bài tập

- `materials/raw/homework/hw08.pdf`
- `materials/extracted/homework/hw08.txt`
- Lý thuyết liên quan: `topics/tuan-08-dem-nang-cao.md`

## Bảng lọc bài tập

| Nhóm bài | Dạng bài | Mức độ | Khả năng ra thi | Ưu tiên | Ghi chú A+ |
| --- | --- | --- | --- | --- | --- |
| Phần 1: 1-4 | Chuỗi bit, chia hết, chuỗi chữ cái cơ bản | Cơ bản - vừa | Cao | Làm nhanh | Dùng để tăng tốc tính trắc nghiệm. |
| Phần 1: 5-8 | Sắp xếp người/vật có ràng buộc | Vừa - khó | Cao | Bắt buộc A+ | Đặc biệt chú ý đứng cạnh/không đứng cạnh/xen kẽ. |
| Phần 1: 9-10 | RNA, hàm số/bảng chân trị | Vừa | Trung bình cao | Nên làm | Phủ dạng ngữ cảnh lạ nhưng công cụ quen. |
| Phần 1: 11-16 | Đếm bù, Euler phi kiểu \(pq\), truth table | Khó vừa | Cao | Bắt buộc A+ | Dạng tốt để phân loại năng lực. |
| Phần 2: 1-2 | Dirichlet nâng cao với lịch/bội số | Khó vừa | Cao | Bắt buộc A+ | Cần chọn hộp tinh tế. |
| Phần 2: 3-7 | Bi, tổng số, phân phối | Vừa | Trung bình cao | Nên làm | Tập chuyển lời văn sang hộp/ngăn. |
| Phần 2: 8, 11-12 | Ramsey, điểm trong không gian, dây cáp | Khó | Trung bình | A+ | Chỉ chọn bài có lời giải ngắn, không sa tính toán. |
| Phần 3 | Hoán vị/tổ hợp với chuỗi con, không kề nhau | Vừa - khó | Cao | Bắt buộc A+ | Rất sát dạng trắc nghiệm nhiều bẫy. |

## Công cụ bắt buộc

| Nội dung | Dùng khi nào | Bẫy |
| --- | --- | --- |
| Đếm bù | Điều kiện "không", "ít nhất", "không chứa" | Quên tổng không gian mẫu. |
| Gom khối | Các phần tử phải đứng cạnh nhau | Quên hoán vị trong khối. |
| Khe trống | Không cho hai phần tử kề nhau | Chọn khe sai sau khi xếp nhóm còn lại. |
| Dirichlet tinh | Câu đảm bảo với số ngày, bội số, cặp | Chọn hộp không phản ánh điều cần ép. |

## Khung tư duy

### Sắp xếp có ràng buộc

- Nếu phải cạnh nhau, gom thành một khối.
- Nếu không cạnh nhau, xếp nhóm nền rồi chọn khe.
- Nếu xen kẽ, xác định mẫu vị trí trước rồi hoán vị từng nhóm.

### Đếm bù

- Tính tổng số cấu hình trước.
- Xác định điều kiện xấu đơn giản hơn.
- Trừ đúng số cấu hình xấu, dùng bao hàm - loại trừ nếu xấu giao nhau.

### Dirichlet nâng cao

- Tìm đại lượng bị ép: tổng, khoảng, cặp, bội số, màu.
- Thiết kế hộp sao cho hai vật cùng hộp tạo ra kết luận.
- Kiểm tra ngưỡng tối thiểu.

## Thứ tự làm đề xuất

1. Làm Phần 1 bài 1-8 để chắc mô hình đếm.
2. Làm Phần 3 các bài chuỗi con/không kề nhau.
3. Làm Phần 2 bài 1-2, 8, 11-12 để luyện Dirichlet A+.
4. Quay lại các bài còn lại để phủ rộng.

## Lỗi dễ mất điểm

- Gom khối nhưng quên hoán vị nội bộ.
- Dùng khe trống khi đối tượng nền chưa được xếp.
- Đếm bù nhưng điều kiện xấu có giao mà không dùng bao hàm - loại trừ.
- Với câu "đảm bảo", đưa ví dụ thay vì chứng minh bằng Dirichlet.
