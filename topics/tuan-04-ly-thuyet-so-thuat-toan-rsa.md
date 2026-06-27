# Tuần 04. Lý thuyết số, đồng dư và RSA

## Vai trò trong đề thi

Thuộc phần trắc nghiệm: thuật toán, số học modulo, RSA. Số trong đề nên đủ nhỏ để làm tay.

## Nguồn đã nạp

- `materials/raw/lectures/Tuan04.pdf`
- `materials/extracted/lectures/Tuan04.txt`
- `materials/raw/homework/hw04.pdf`

## Kiến thức cốt lõi

- Đồng dư xét phần dư khi chia cho modulo.
- Bézout và Euclid mở rộng là công cụ tìm nghịch đảo modulo.
- Hàm băm, kiểm tra chẵn lẻ, mã Caesar và RSA là ứng dụng của số học đồng dư.
- RSA cần chọn $n=pq$, số mũ $e$ nguyên tố cùng nhau với $(p-1)(q-1)$, rồi tìm $d$ là nghịch đảo modulo.
- Lũy thừa modulo nhanh giúp tính $M^e\bmod n$ hoặc $C^d\bmod n$.

## Định nghĩa/công thức/thuật toán cần nhớ

- $a\equiv b\pmod m$ khi $m\mid(a-b)$.
- Nếu $a\equiv b$ và $c\equiv d\pmod m$ thì $a+c\equiv b+d$, $ac\equiv bd\pmod m$.
- $\gcd(a,b)=sa+tb$.
- $a^{-1}\pmod m$ tồn tại khi $\gcd(a,m)=1$.
- RSA: $C=M^e\bmod n$, $M=C^d\bmod n$, $de\equiv1\pmod{(p-1)(q-1)}$.

## Dạng bài hay ra

- Đổi cơ số, phân tích thừa số nguyên tố.
- Tìm nghịch đảo modulo.
- Giải hệ đồng dư nhỏ.
- Tính hàm băm $h(k)=k\bmod m$.
- Kiểm tra parity bit.
- Mã hóa/giải mã Caesar, hoán vị, RSA.

## Lỗi sai thường gặp

- Tìm nghịch đảo khi $\gcd(a,m)\ne1$.
- Dùng modulo $n$ thay vì modulo $(p-1)(q-1)$ khi tìm $d$ trong RSA.
- Tính lũy thừa trực tiếp quá dài thay vì bình phương liên tiếp.
- Quên chuẩn hóa block khi mã hóa/giải mã RSA.

## Bài đại diện nên xem lại

- `hw04`: Bài 4-5 cho nghịch đảo và hệ đồng dư.
- `hw04`: Bài 8-10 cho mã hóa và RSA.

