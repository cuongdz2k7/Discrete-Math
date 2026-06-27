# Tuần 04. Lý thuyết số, thuật toán, RSA - bài tập ưu tiên

## Vai trò trong đề thi

RSA thuộc phần trắc nghiệm năm nay, còn thuật toán số học hỗ trợ nhiều câu về đồng dư, nghịch đảo modulo và tính lũy thừa nhanh.

## Nguồn bài tập

- `materials/raw/homework/hw04.pdf`
- `materials/extracted/homework/hw04.txt`
- Lý thuyết liên quan: `topics/tuan-04-ly-thuyet-so-thuat-toan-rsa.md`

## Bảng lọc bài tập

| Bài | Dạng bài | Mức độ | Khả năng ra thi | Ưu tiên | Ghi chú A+ |
| --- | --- | --- | --- | --- | --- |
| 1-3 | Đổi cơ số, phân tích thừa số nguyên tố | Cơ bản | Trung bình | Làm nhanh | Là nền cho RSA nhưng không nên tốn nhiều thời gian. |
| 4 | Nghịch đảo modulo bằng Euclid mở rộng | Vừa | Cao | Bắt buộc | Kỹ năng lõi cho RSA và hệ đồng dư. |
| 5 | Hệ đồng dư/kiểu CRT | Khó vừa | Trung bình cao | A+ | Chọn số đẹp, luyện phương pháp hơn là tính dài. |
| 6 | Hàm băm | Cơ bản - vừa | Trung bình | Nên làm | Dễ thành câu trắc nghiệm kiểm tra công thức. |
| 7 | Kiểm tra chẵn lẻ/parity | Cơ bản | Trung bình | Nên làm | Dạng nhận dạng nhanh. |
| 8-9 | Mã Caesar, mã hoán vị | Vừa | Trung bình | Nên làm | Chú ý quy ước modulo chữ cái. |
| 10 | RSA mã hóa/giải mã | Vừa - khó | Cao | Bắt buộc A+ | Tập dùng nghịch đảo modulo và bình phương nhân nhanh. |

## Công cụ bắt buộc

| Nội dung | Dùng khi nào | Bẫy |
| --- | --- | --- |
| Euclid mở rộng | Tìm \(s,t\) sao cho \(as+bt=\gcd(a,b)\) | Chỉ có nghịch đảo khi gcd bằng 1. |
| Đồng dư | Rút gọn phép tính modulo | Rút gọn sai với phép chia. |
| Bình phương nhân nhanh | Tính \(a^k \bmod n\) | Tính trực tiếp số rất lớn. |
| RSA | Mã hóa/giải mã | Nhầm \(e\), \(d\), \(\varphi(n)\). |

## Khung tư duy

### Nghịch đảo modulo

- Kiểm tra \(\gcd(a,m)=1\).
- Chạy Euclid mở rộng để viết \(ax+my=1\).
- Lấy \(x \bmod m\) làm nghịch đảo.

### RSA

- Tính \(n=pq\), \(\varphi(n)=(p-1)(q-1)\).
- Chọn/kiểm tra \(e\) nguyên tố cùng nhau với \(\varphi(n)\).
- Tìm \(d=e^{-1}\pmod{\varphi(n)}\).
- Mã hóa \(c=m^e\bmod n\), giải mã \(m=c^d\bmod n\).

## Thứ tự làm đề xuất

1. Làm 4 trước vì là kỹ năng lõi.
2. Làm 10 ngay sau đó để ghép nghịch đảo vào RSA.
3. Làm 5 để nâng mức A+.
4. Làm 1-3, 6-9 để phủ trắc nghiệm.

## Lỗi dễ mất điểm

- Tìm nghịch đảo modulo khi hai số không nguyên tố cùng nhau.
- Quên lấy số dư dương cuối cùng.
- Tính lũy thừa trực tiếp dẫn đến rối số.
- Dùng đề cũ để suy luận RSA tự luận; năm nay RSA nằm trong phạm vi trắc nghiệm.
