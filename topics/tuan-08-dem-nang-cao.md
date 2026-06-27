# Tuần 08. Đếm nâng cao, truy hồi và hàm sinh

## Vai trò trong đề thi

Thuộc phần trắc nghiệm. Nội dung này giúp xử lý bài đếm nhiều điều kiện, truy hồi và mô hình hóa thuật toán.

## Nguồn đã nạp

- `materials/raw/lectures/Tuan08.pdf`
- `materials/extracted/lectures/Tuan08.txt`
- `materials/raw/homework/hw08.pdf`

## Kiến thức cốt lõi

- Truy hồi mô tả số lượng ở bước $n$ qua các bước trước đó.
- Fibonacci xuất hiện trong bài thỏ và xâu nhị phân không có hai bit 1 kề nhau.
- Tháp Hà Nội có truy hồi $T_n=2T_{n-1}+1$.
- Chia để trị tạo bài toán con không chồng lặp; quy hoạch động lưu kết quả bài toán con chồng lặp.
- Hàm sinh biến bài đếm thành tìm hệ số của chuỗi lũy thừa.

## Công thức/ý tưởng cần nhớ

- Xâu nhị phân độ dài $n$ không có hai bit 1 kề nhau thường cho truy hồi Fibonacci.
- Tháp Hà Nội: $T_n=2^n-1$.
- Hàm sinh thường: $G(x)=\sum a_kx^k$.
- $\frac{1}{1-x}=1+x+x^2+\cdots$.
- Tổ hợp lặp có thể đọc bằng hệ số trong tích các hàm sinh.

## Dạng bài hay ra

- Đếm xâu nhị phân có ràng buộc.
- Đếm số bằng chia hết/không chia hết, chữ số phân biệt.
- Tổ bồ câu nâng cao: chuỗi ngày liên tiếp, chia hết, Ramsey $R(3,3)$.
- Hoán vị chứa xâu con, xếp xen kẽ, không kề nhau.
- Truy hồi và hàm sinh cho bài phân phối có giới hạn.

## Lỗi sai thường gặp

- Đếm xâu “không chứa” bằng trực tiếp trong khi dùng phần bù dễ hơn.
- Với truy hồi, thiếu điều kiện đầu.
- Với hàm sinh, lấy sai hệ số cần tìm.

## Bài đại diện nên xem lại

- `hw08`: Phần 1 cho đếm cơ bản nhưng nhiều điều kiện.
- `hw08`: Phần 2 cho tổ bồ câu nâng cao.
- `hw08`: Phần 3 cho hoán vị/tổ hợp tổng hợp.

