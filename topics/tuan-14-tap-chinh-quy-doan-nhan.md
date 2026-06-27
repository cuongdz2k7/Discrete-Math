# Tuần 14. Tập chính quy và đoán nhận ngôn ngữ

## Vai trò trong đề thi

Liên quan trực tiếp tới tự luận ôtômát hữu hạn và trắc nghiệm ngôn ngữ hình thức.

## Nguồn đã nạp

- `materials/raw/lectures/Tuan14.pdf`
- `materials/extracted/lectures/Tuan14.txt`
- `materials/raw/homework/hw14.pdf`

## Kiến thức cốt lõi

- Phép ghép hai tập xâu $AB$ lấy mọi xâu $xy$ với $x\in A$, $y\in B$.
- Kleene star $A^*$ là ghép hữu hạn tùy ý các xâu trong $A$, gồm cả $\lambda$.
- Biểu thức chính quy được xây từ $\emptyset$, $\lambda$, ký hiệu đơn, hợp, ghép và star.
- Định lý Kleene: tập chính quy đúng bằng tập được máy hữu hạn nhận.
- Văn phạm chính quy tương đương với tập chính quy/máy hữu hạn.

## Định nghĩa/công thức/thuật toán cần nhớ

- $A^0=\{\lambda\}$, $A^{n+1}=A^nA$.
- $A^*=\bigcup_{n\ge0}A^n$.
- Regular expression cho “độ dài chẵn” trên $\{0,1\}$: $(00\cup01\cup10\cup11)^*$.
- Chuyển văn phạm chính quy sang máy: mỗi nonterminal thành trạng thái, luật $A\to aB$ thành cạnh $a$, luật $A\to a$ tới trạng thái kết thúc.
- Chuyển máy sang văn phạm: mỗi trạng thái thành nonterminal, mỗi chuyển $s\xrightarrow{a}t$ thành $A_s\to aA_t$; nếu $t$ kết thúc thêm $A_s\to a$.

## Dạng bài hay ra

- Mô tả ngôn ngữ của biểu thức chính quy.
- Viết biểu thức chính quy cho điều kiện xâu.
- Dựng NFA/DFA từ biểu thức chính quy.
- Dựng NFA từ văn phạm chính quy.
- Dựng văn phạm chính quy từ máy hữu hạn.

## Lỗi sai thường gặp

- Quên $\lambda$ thuộc $A^*$.
- Nhầm hợp với ghép.
- Viết regular expression đúng ý tưởng nhưng sinh thừa xâu.
- Khi dựng văn phạm từ máy, quên luật kết thúc.

## Bài đại diện nên xem lại

- `hw14`: Bài 1-2 cho mô tả và viết biểu thức chính quy.
- `hw14`: Bài 3-4 cho NFA và văn phạm chính quy.
- `hw14`: Bài 5 cho dựng văn phạm từ NFA.

