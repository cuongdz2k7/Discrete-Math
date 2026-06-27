# Tuần 05. Quy nạp và đệ quy - bài tập ưu tiên

## Vai trò trong đề thi

Quy nạp và đệ quy thuộc trắc nghiệm năm nay. Cần nhận ra khi nào dùng quy nạp thường, quy nạp mạnh, định nghĩa đệ quy và kiểm tra công thức truy hồi.

## Nguồn bài tập

- `materials/raw/homework/hw05.pdf`
- `materials/extracted/homework/hw05.txt`
- Lý thuyết liên quan: `topics/tuan-05-quy-nap-de-quy.md`

## Bảng lọc bài tập

| Bài | Dạng bài | Mức độ | Khả năng ra thi | Ưu tiên | Ghi chú A+ |
| --- | --- | --- | --- | --- | --- |
| 1-8 | Quy nạp thường | Vừa | Cao | Bắt buộc | Chú ý bước cơ sở và biến đổi từ \(P(k)\) sang \(P(k+1)\). |
| 9-12 | Quy nạp mạnh | Khó vừa | Cao | Bắt buộc A+ | Hợp với bài chia trường hợp, truy hồi, biểu diễn số. |
| 13 | Trò chơi/chiến lược kiểu Chomp | Khó | Thấp - trung bình | Tùy thời gian | Là bài tư duy, không ưu tiên nếu sát ngày thi. |
| 14-17 | Định nghĩa đệ quy, dãy truy hồi | Vừa | Cao | Bắt buộc | Đọc được base case và recursive step. |
| 18-20 | Đệ quy trên chuỗi/cấu trúc, Fibonacci | Khó vừa | Trung bình cao | A+ | Luyện nhận dạng cấu trúc và chứng minh theo định nghĩa. |

## Công cụ bắt buộc

| Nội dung | Dùng khi nào | Bẫy |
| --- | --- | --- |
| Quy nạp thường | Mệnh đề phụ thuộc \(n\) và bước \(k \to k+1\) rõ | Thiếu bước cơ sở. |
| Quy nạp mạnh | Bước sau cần nhiều trường hợp trước | Chỉ giả sử \(P(k)\) khiến chứng minh kẹt. |
| Đệ quy | Dãy, chuỗi, cấu trúc tự gọi lại | Không kiểm tra điều kiện dừng. |
| Structural induction | Cấu trúc như chuỗi/cây/biểu thức | Bỏ sót cách sinh phần tử. |

## Khung tư duy

### Quy nạp

- Ghi mệnh đề \(P(n)\) rõ ràng.
- Làm bước cơ sở tại giá trị nhỏ nhất.
- Giả sử quy nạp đúng phạm vi cần thiết.
- Chứng minh bước tiếp theo, chỉ dùng giả thiết hợp lệ.

### Đệ quy

- Tách base case và recursive case.
- Tính vài giá trị đầu để đoán mẫu.
- Nếu chứng minh công thức đóng, dùng quy nạp trên chỉ số.

## Thứ tự làm đề xuất

1. Làm 1-8 để chắc format trình bày.
2. Làm 14-17 để nối sang đệ quy.
3. Làm 9-12 và 18-20 để đạt mức phân loại A+.

## Lỗi dễ mất điểm

- Không nêu rõ miền \(n \ge n_0\).
- Bước quy nạp biến đổi đại số thiếu mục tiêu.
- Dùng giả thiết quy nạp cho giá trị chưa được phép.
- Viết đệ quy nhưng thiếu điều kiện dừng.
