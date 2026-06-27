# Tuần 05. Quy nạp và đệ quy

## Vai trò trong đề thi

Thuộc phần trắc nghiệm, đồng thời hỗ trợ chứng minh trong các chương sau. Cần biết chọn quy nạp thường, quy nạp mạnh hoặc quy nạp cấu trúc.

## Nguồn đã nạp

- `materials/raw/lectures/Tuan05.pdf`
- `materials/extracted/lectures/Tuan05.txt`
- `materials/raw/homework/hw05.pdf`

## Kiến thức cốt lõi

- Quy nạp thường chứng minh $P(1)$ rồi $P(n)\to P(n+1)$.
- Quy nạp mạnh dùng nhiều mệnh đề trước đó để chứng minh bước tiếp theo.
- Đệ quy định nghĩa đối tượng bằng chính nó: cần cơ sở và bước sinh.
- Quy nạp cấu trúc dùng cho đối tượng sinh đệ quy như xâu, cây, tập điểm.
- Thuật toán đệ quy giải bài toán bằng bài toán cùng dạng nhỏ hơn.

## Định nghĩa/công thức/thuật toán cần nhớ

- Cơ sở phải đúng tại điểm bắt đầu của miền.
- Bước quy nạp phải chứng minh đúng phát biểu kế tiếp, không chỉ kiểm tra ví dụ.
- $0!=1$, $n!=n(n-1)!$.
- $l(\lambda)=0$, $l(wx)=l(w)+1$.
- GCD đệ quy: $\gcd(a,b)=\gcd(b,a\bmod b)$.

## Dạng bài hay ra

- Chứng minh tổng, bất đẳng thức, chia hết bằng quy nạp.
- Chứng minh biểu diễn số bằng quy nạp mạnh.
- Tính giá trị hàm đệ quy.
- Định nghĩa đệ quy cho tập/xâu.
- Chứng minh tính chất Fibonacci hoặc xâu bằng quy nạp.

## Lỗi sai thường gặp

- Bước cơ sở không khớp miền đề bài.
- Dùng giả thiết $P(n)$ nhưng cần quy nạp mạnh.
- Bỏ sót điều kiện dừng của đệ quy.
- Trong quy nạp cấu trúc, không kiểm tra mọi luật sinh.

## Bài đại diện nên xem lại

- `hw05`: Bài 1-8 cho quy nạp thường.
- `hw05`: Bài 9-13 cho quy nạp mạnh.
- `hw05`: Bài 14-20 cho đệ quy và quy nạp cấu trúc.

