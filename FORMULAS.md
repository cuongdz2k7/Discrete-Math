# Công thức, định nghĩa và thuật toán quan trọng

File này gom các công cụ dùng lại nhiều lần khi ôn Toán rời rạc. Khi làm bài, luôn kiểm tra điều kiện áp dụng trước khi thay công thức.

## Logic và chứng minh

- Mệnh đề: phát biểu chỉ có một trong hai giá trị đúng/sai.
- Phủ định: $\neg p$ đổi đúng thành sai và ngược lại.
- Hội: $p \land q$ đúng khi cả hai đúng.
- Tuyển: $p \lor q$ sai khi cả hai sai.
- XOR: $p \oplus q$ đúng khi đúng đúng một vế.
- Kéo theo: $p \to q$ chỉ sai khi $p$ đúng và $q$ sai.
- Hai chiều: $p \leftrightarrow q$ đúng khi $p,q$ cùng giá trị.
- Phản đảo của $p \to q$ là $\neg q \to \neg p$ và tương đương với mệnh đề gốc.
- Luật De Morgan: $\neg(p \land q) \equiv \neg p \lor \neg q$, $\neg(p \lor q) \equiv \neg p \land \neg q$.
- Phủ định lượng từ: $\neg \forall x P(x) \equiv \exists x \neg P(x)$, $\neg \exists x P(x) \equiv \forall x \neg P(x)$.
- Suy diễn hay dùng: Modus Ponens, Modus Tollens, tam đoạn luận giả thuyết, tam đoạn luận tuyển, cộng, đơn giản hóa.
- Kiểu chứng minh: trực tiếp, gián tiếp/phản đảo, phản chứng, chia trường hợp, chứng minh tương đương, chứng minh tồn tại có/không kiến thiết.

## Đại số Boolean và mạch logic

- Biến Boolean nhận giá trị trong $\{0,1\}$.
- Phép cơ bản: bù $\bar{x}$, tổng Boolean $x+y$, tích Boolean $xy$.
- Thứ tự ưu tiên: bù, tích, tổng.
- Luật cần nhớ: phủ định kép, lũy đẳng, trội, giao hoán, kết hợp, phân phối, De Morgan, hấp thụ, đơn vị, không.
- Tiểu hạng (minterm): tích có đủ mọi biến, mỗi biến xuất hiện đúng một lần ở dạng thường hoặc phủ định.
- Dạng tổng-các-tích: lấy tổng các minterm ứng với hàng bảng chân trị có giá trị $1$.
- NAND và NOR đều đầy đủ hàm: chỉ cần NAND hoặc chỉ cần NOR có thể biểu diễn mọi hàm Boolean.
- Tối ưu mạch: dùng Karnaugh hoặc Quine-McCluskey khi cần rút gọn biểu thức/mạch.

## Thuật toán và độ phức tạp

- Big-O: $f(x)=O(g(x))$ nếu tồn tại $C,k$ sao cho $|f(x)| \le C|g(x)|$ với mọi $x>k$.
- Big-Omega: $f(x)=\Omega(g(x))$ nếu tồn tại $C,k$ sao cho $|f(x)| \ge C|g(x)|$ với mọi $x>k$.
- Big-Theta: $f(x)=\Theta(g(x))$ nếu vừa là $O(g)$ vừa là $\Omega(g)$.
- Đa thức bậc $n$ thường là $O(x^n)$.
- Nếu $f_1=O(g_1)$ và $f_2=O(g_2)$ thì $f_1+f_2=O(\max(g_1,g_2))$, $f_1f_2=O(g_1g_2)$.

## Số học modulo và RSA

- Đồng dư: $a \equiv b \pmod m$ khi $m \mid (a-b)$.
- Nếu $a \equiv b \pmod m$ và $c \equiv d \pmod m$ thì $a+c \equiv b+d \pmod m$, $ac \equiv bd \pmod m$.
- Bézout: tồn tại $s,t$ sao cho $\gcd(a,b)=sa+tb$.
- Nghịch đảo modulo của $a$ theo modulo $m$ tồn tại khi $\gcd(a,m)=1$.
- RSA: chọn $n=pq$, chọn $e$ nguyên tố cùng nhau với $(p-1)(q-1)$, mã hóa $C=M^e \bmod n$, giải mã $M=C^d \bmod n$ với $de \equiv 1 \pmod{(p-1)(q-1)}$.
- Lũy thừa modulo nhanh: bình phương liên tiếp theo biểu diễn nhị phân của số mũ.

## Quy nạp và đệ quy

- Quy nạp thường: chứng minh bước cơ sở, rồi chứng minh $P(n) \to P(n+1)$.
- Quy nạp mạnh: giả sử $P(1),...,P(n)$ để chứng minh $P(n+1)$.
- Định nghĩa đệ quy cần có điều kiện cơ sở và quy tắc sinh giá trị/đối tượng tiếp theo.
- Ví dụ chuẩn: $0!=1$, $n!=n(n-1)!$; Fibonacci; độ dài xâu $l(\lambda)=0$, $l(wx)=l(w)+1$.

## Đếm tổ hợp

- Quy tắc cộng: các trường hợp rời nhau thì cộng số cách.
- Quy tắc nhân: các bước độc lập theo chuỗi thì nhân số cách.
- Bao hàm - loại trừ hai tập: $|A \cup B|=|A|+|B|-|A \cap B|$.
- Nguyên lý chia: nếu mỗi kết quả bị đếm đúng $d$ lần thì số kết quả là $n/d$.
- Tổ bồ câu: đưa $k+1$ vật vào $k$ hộp thì có hộp chứa ít nhất $2$ vật; dạng tổng quát có hộp chứa ít nhất $\lceil N/k \rceil$ vật.
- Chỉnh hợp không lặp: $P(n,r)=n(n-1)\cdots(n-r+1)=\frac{n!}{(n-r)!}$.
- Tổ hợp: $C(n,r)=\frac{n!}{r!(n-r)!}$.
- Tổ hợp lặp: số nghiệm nguyên không âm của $x_1+\cdots+x_n=r$ là $C(n+r-1,r)$.
- Hoán vị lặp: $\frac{n!}{n_1!n_2!\cdots n_k!}$.
- Nhị thức Newton: $(x+y)^n=\sum_{k=0}^n C(n,k)x^{n-k}y^k$.
- Truy hồi hay gặp: Fibonacci, tháp Hà Nội $T_n=2T_{n-1}+1=2^n-1$, xâu nhị phân không có hai bit $1$ kề nhau.
- Hàm sinh thường: $G(x)=\sum_{k\ge0} a_kx^k$.

## Đồ thị

- Đồ thị $G=(V,E)$ gồm tập đỉnh và tập cạnh.
- Đơn đồ thị: không khuyên, không cạnh bội.
- Bậc trong đồ thị vô hướng: vòng lặp tính hai vào bậc.
- Định lý bắt tay: $\sum_{v\in V}\deg(v)=2|E|$; số đỉnh bậc lẻ là số chẵn.
- Đồ thị có hướng: tổng bậc vào bằng tổng bậc ra bằng số cạnh.
- Ma trận kề $A$: phần tử $(i,j)$ cho biết cạnh giữa $v_i,v_j$; $(A^r)_{ij}$ đếm số đường đi độ dài $r$ từ $v_i$ đến $v_j$.
- Đẳng cấu: song ánh bảo toàn kề nhau.
- Liên thông: mọi cặp đỉnh phân biệt có đường đi nối nhau.
- Chu trình Euler tồn tại trong đa đồ thị liên thông khi và chỉ khi mọi đỉnh có bậc chẵn.
- Hamilton: không có tiêu chuẩn cần và đủ đơn giản; dùng bậc 1, bậc 2, Dirac, Ore và lập luận loại cạnh.
- Đồ thị phân đôi: tương đương không có chu trình lẻ.
- Đồ thị phẳng liên thông: $v-e+r=2$; với đơn đồ thị phẳng $v\ge3$, $e\le3v-6$; nếu không có chu trình độ dài 3 thì $e\le2v-4$.
- Tô màu: sắc số là số màu ít nhất để hai đỉnh kề khác màu.

## Cây

- Cây là đồ thị vô hướng liên thông không có chu trình đơn.
- Một cây có $n$ đỉnh thì có $n-1$ cạnh.
- Một đồ thị vô hướng là cây khi và chỉ khi giữa hai đỉnh bất kỳ có đúng một đường đi.
- Cây $m$-phân đầy đủ với $i$ đỉnh trong có $n=mi+1$ đỉnh và $l=(m-1)i+1$ lá.
- Cây $m$-phân cao $h$ có nhiều nhất $m^h$ lá.
- DFS và BFS dùng để dựng cây khung; DFS đi sâu trước, BFS đi theo lớp.
- MST: Prim thêm cạnh nhỏ nhất nối cây hiện tại với đỉnh ngoài; Kruskal thêm cạnh nhỏ nhất không tạo chu trình.
- Huffman: ghép hai cây có trọng số nhỏ nhất lặp lại để tạo mã tiền tố tối ưu theo tần suất.

## Văn phạm, ngôn ngữ, ôtômát và Turing

- Văn phạm cấu trúc đoạn $G=(V,T,S,P)$: $V$ từ vựng, $T$ terminal, $S$ ký hiệu bắt đầu, $P$ luật sinh.
- Ngôn ngữ $L(G)$ là tập các xâu terminal dẫn xuất được từ $S$.
- Cây dẫn xuất biểu diễn dẫn xuất của văn phạm phi ngữ cảnh.
- Phân loại Chomsky: loại 0, loại 1 cảm ngữ cảnh, loại 2 phi ngữ cảnh, loại 3 chính quy.
- DFA: $M=(S,I,f,s_0,F)$, xâu được nhận nếu trạng thái sau khi đọc toàn xâu thuộc $F$.
- NFA: hàm chuyển trả về tập trạng thái; NFA và DFA tương đương về ngôn ngữ nhận.
- Biểu thức chính quy xây từ $\emptyset$, $\lambda$, ký hiệu đơn, phép hợp, ghép và Kleene star.
- Kleene: một tập là chính quy khi và chỉ khi được nhận bởi máy hữu hạn.
- Văn phạm chính quy có luật dạng $S\to\lambda$, $A\to a$, $A\to aB$.
- Máy Turing: $T=(S,I,f,s_0)$, chuyển theo bộ năm $(s,x,s',x',d)$; nếu không có chuyển thì dừng.
- Máy Turing nhận xâu nếu dừng ở trạng thái kết thúc.
- Tập $\{0^n1^n\}$ không chính quy nhưng có thể nhận bởi mô hình mạnh hơn máy hữu hạn.

