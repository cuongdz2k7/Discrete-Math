# Tuần 07. Hoán vị, tổ hợp và hệ số nhị thức

## Vai trò trong đề thi

Thuộc phần trắc nghiệm. Đây là phần dễ ra câu ngắn nhưng có bẫy thứ tự, lặp và điều kiện.

## Nguồn đã nạp

- `materials/raw/lectures/Tuan07.pdf`
- `materials/extracted/lectures/Tuan07.txt`
- `materials/raw/homework/hw07.pdf`

## Kiến thức cốt lõi

- Hoán vị là sắp xếp toàn bộ có thứ tự.
- Chỉnh hợp chọn $r$ phần tử có thứ tự.
- Tổ hợp chọn $r$ phần tử không xét thứ tự.
- Chỉnh hợp/tổ hợp lặp xử lý trường hợp được chọn lại.
- Hoán vị lặp xử lý các phần tử giống nhau.
- Hệ số nhị thức xuất hiện trong khai triển $(x+y)^n$.

## Công thức cần nhớ

- $P(n,r)=\frac{n!}{(n-r)!}$.
- $C(n,r)=\frac{n!}{r!(n-r)!}=C(n,n-r)$.
- Tổ hợp lặp: $C(n+r-1,r)$.
- Hoán vị lặp: $\frac{n!}{n_1!\cdots n_k!}$.
- $(x+y)^n=\sum_{k=0}^n C(n,k)x^{n-k}y^k$.
- Pascal: $C(n+1,r)=C(n,r-1)+C(n,r)$.

## Dạng bài hay ra

- Đếm xâu bit có đúng/ít nhất/nhiều nhất một số bit.
- Đếm thứ tự về đích, trao giải, xếp hàng.
- Đếm hệ số trong khai triển nhị thức.
- Đếm đường đi lưới.
- Đếm nghiệm nguyên không âm bằng tổ hợp lặp.

## Lỗi sai thường gặp

- Nhầm có thứ tự với không thứ tự.
- Quên chia cho giai thừa khi có phần tử lặp.
- Trong khai triển, ghép sai số mũ với chỉ số tổ hợp.

## Bài đại diện nên xem lại

- `hw07`: Bài 1-5 cho hoán vị, tổ hợp, xâu bit.
- `hw07`: Bài 6-10 cho hệ số nhị thức.

