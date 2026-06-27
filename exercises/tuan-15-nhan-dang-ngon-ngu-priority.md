# Tuần 15. Nhận dạng ngôn ngữ và máy Turing - bài tập ưu tiên

## Vai trò trong đề thi

Máy Turing thuộc phạm vi trắc nghiệm năm nay. Mục tiêu là hiểu cơ chế đọc/ghi/di chuyển, mô phỏng máy và thiết kế máy đơn giản, không sa vào bài quá dài.

## Nguồn bài tập

- `materials/raw/homework/hw15.pdf`
- `materials/extracted/homework/hw15.txt`
- Lý thuyết liên quan: `topics/tuan-15-nhan-dang-ngon-ngu.md`

## Bảng lọc bài tập

| Bài | Dạng bài | Mức độ | Khả năng ra thi | Ưu tiên | Ghi chú A+ |
| --- | --- | --- | --- | --- | --- |
| 1-2 | Mô phỏng và mô tả máy Turing | Vừa | Cao | Bắt buộc | Trắc nghiệm có thể hỏi trạng thái/kết quả sau vài bước. |
| 3 | Thay ký tự đầu tiên thỏa điều kiện | Vừa | Cao | Bắt buộc | Mẫu máy đơn giản, dễ kiểm tra. |
| 4 | Thay tất cả trừ ký tự đặc biệt | Khó vừa | Trung bình cao | A+ | Cần trạng thái nhớ đã gặp ký tự đầu tiên. |
| 5 | Nhận bit string kết thúc bằng 0 | Vừa | Cao | Bắt buộc | Thiết kế máy nhận dạng ngắn, sát đề. |
| 6 | Nhận chuỗi có số lượng 1 chẵn | Vừa - khó | Cao | Bắt buộc A+ | Dùng hai trạng thái parity. |
| 7 | Máy tính hàm \(f(n)=n-3\) nếu \(n\ge3\), ngược lại 0 | Khó | Trung bình | A+ nếu còn thời gian | Dạng thiết kế sâu hơn, không nên ưu tiên sát ngày thi. |

## Công cụ bắt buộc

| Nội dung | Dùng khi nào | Bẫy |
| --- | --- | --- |
| Cấu hình máy Turing | Mô phỏng từng bước | Quên vị trí đầu đọc. |
| Hàm chuyển \(\delta(q,a)=(q',b,D)\) | Đọc bảng máy | Nhầm ghi ký tự với ký tự đọc. |
| Trạng thái chấp nhận/từ chối | Kết luận máy nhận hay không | Dừng không đồng nghĩa luôn chấp nhận. |
| Ý tưởng trạng thái nhớ | Thiết kế máy | Dùng băng để nhớ khi chỉ cần trạng thái. |

## Khung tư duy

### Mô phỏng máy

- Ghi cấu hình: băng, vị trí đầu đọc, trạng thái.
- Mỗi bước áp đúng một dòng chuyển.
- Dừng khi vào trạng thái halt/accept/reject hoặc không có chuyển hợp lệ.

### Thiết kế máy

- Mô tả ý tưởng trước khi viết bảng.
- Chọn trạng thái để nhớ thông tin tối thiểu: đã gặp gì, parity, đang quét trái/phải.
- Test chuỗi rỗng, chuỗi ngắn, chuỗi biên.

## Thứ tự làm đề xuất

1. Làm 1-2 để đọc máy.
2. Làm 3, 5, 6 để luyện thiết kế sát trắc nghiệm.
3. Làm 4 nếu muốn tăng độ chắc.
4. Làm 7 cuối cùng cho A+ tư duy, không dùng làm bài luyện chính sát ngày thi.

## Lỗi dễ mất điểm

- Mô phỏng sai vì quên di chuyển đầu đọc sau khi ghi.
- Không quy định ký hiệu trắng.
- Thiết kế máy nhận thừa chuỗi rỗng.
- Viết bảng chuyển thiếu trường hợp nên máy kẹt ngoài ý muốn.
