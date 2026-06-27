# Tuần 12. Văn phạm và ngôn ngữ hình thức

## Vai trò trong đề thi

Thuộc phần trắc nghiệm về ngôn ngữ hình thức / Máy Turing và hỗ trợ tự luận ôtômát qua văn phạm chính quy.

## Nguồn đã nạp

- `materials/raw/lectures/Tuan12.pdf`
- `materials/extracted/lectures/Tuan12.txt`
- `materials/raw/homework/hw12.pdf`

## Kiến thức cốt lõi

- Ngôn ngữ hình thức có quy tắc cú pháp xác định rõ.
- Văn phạm $G=(V,T,S,P)$ sinh ngôn ngữ bằng các bước dẫn xuất từ $S$ tới xâu terminal.
- Cần phân biệt terminal, nonterminal, ký hiệu bắt đầu và luật sinh.
- Cây dẫn xuất biểu diễn dẫn xuất của văn phạm phi ngữ cảnh.
- Phân loại Chomsky dựa trên dạng luật sinh: loại 0, 1, 2, 3.
- Backus-Naur Form là cách viết gọn luật sinh, hay dùng mô tả cú pháp.

## Định nghĩa/công thức cần nhớ

- $V^*$ là tập mọi xâu hữu hạn trên từ vựng $V$, gồm cả $\lambda$.
- $L(G)=\{w\in T^* \mid S\Rightarrow^* w\}$.
- Văn phạm chính quy có luật dạng $S\to\lambda$, $A\to a$, $A\to aB$.
- Văn phạm phi ngữ cảnh có vế trái là một nonterminal.
- $\{0^m1^n\}$ là chính quy; $\{0^n1^n\}$ là phi ngữ cảnh; $\{0^n1^n2^n\}$ là cảm ngữ cảnh.

## Dạng bài hay ra

- Chứng minh một xâu thuộc/không thuộc ngôn ngữ sinh bởi văn phạm.
- Tìm ngôn ngữ của một văn phạm.
- Viết văn phạm sinh một ngôn ngữ đơn giản.
- Phân loại văn phạm theo Chomsky.
- Dựng cây dẫn xuất.
- Viết BNF cho cú pháp.

## Lỗi sai thường gặp

- Dẫn xuất còn nonterminal nhưng đã kết luận xâu thuộc ngôn ngữ.
- Nhầm $\lambda$ với ký tự rỗng trong bảng chữ cái.
- Phân loại văn phạm chỉ nhìn một luật mà quên kiểm tra toàn bộ $P$.

## Bài đại diện nên xem lại

- `hw12`: Bài 1-6 cho dẫn xuất và dựng văn phạm.
- `hw12`: Bài 7 cho phân loại Chomsky.
- `hw12`: Bài 8-10 cho kết hợp văn phạm, cây dẫn xuất và parsing.

