# Tuần 01. Logic mệnh đề, logic vị từ và lượng từ

## Vai trò trong đề thi

Thuộc phần trắc nghiệm. Đây là nền cho câu logic, bảng chân trị, phủ định lượng từ và suy diễn. Đề cũ cho thấy logic có thể xuất hiện dưới dạng tình huống tự nhiên hoặc chọn mệnh đề tương đương.

## Nguồn đã nạp

- `materials/raw/lectures/Tuan01.pdf`
- `materials/extracted/lectures/Tuan01.txt`
- `materials/raw/homework/hw01.pdf`

## Kiến thức cốt lõi

- Mệnh đề là phát biểu có giá trị đúng hoặc sai; câu hỏi, câu chứa biến chưa xác định thường chưa là mệnh đề.
- Các phép nối chính: phủ định, hội, tuyển, XOR, kéo theo, hai chiều.
- $p \to q$ chỉ sai khi $p$ đúng và $q$ sai; đây là bẫy rất hay ra.
- Biểu diễn tri thức tự nhiên bằng logic: xác định mệnh đề cơ sở trước, rồi gắn kết nối logic.
- Logic vị từ mở rộng logic mệnh đề bằng biến, vị từ và lượng từ $\forall,\exists$.
- Phủ định lượng từ phải đổi lượng từ và phủ định vị từ bên trong.

## Định nghĩa/công thức/thuật toán cần nhớ

- $\neg(p\land q)\equiv \neg p\lor \neg q$.
- $\neg(p\lor q)\equiv \neg p\land \neg q$.
- $p\to q\equiv \neg p\lor q$.
- $p\leftrightarrow q\equiv (p\to q)\land(q\to p)$.
- Phản đảo $\neg q\to \neg p$ tương đương với $p\to q$.
- $\neg\forall xP(x)\equiv \exists x\neg P(x)$.
- $\neg\exists xP(x)\equiv \forall x\neg P(x)$.

## Dạng bài hay ra

- Dịch câu tự nhiên sang biểu thức logic.
- Lập bảng chân trị cho mệnh đề phức.
- Xác định mệnh đề đảo, phản đề, phản đảo.
- Chứng minh tương đương logic bằng bảng chân trị hoặc luật tương đương.
- Dịch vị từ/lượng từ và phủ định biểu thức lượng từ lồng nhau.

## Quy trình giải chung

1. Tách câu thành các mệnh đề/vị từ cơ sở.
2. Nhận diện từ khóa: “và”, “hoặc”, “nếu”, “chỉ nếu”, “khi và chỉ khi”, “mọi”, “tồn tại”.
3. Với bảng chân trị, chia cột theo biểu thức con.
4. Với phủ định lượng từ, đẩy phủ định vào trong cho tới vị từ.
5. Với tương đương, ưu tiên dùng $p\to q\equiv \neg p\lor q$ và De Morgan.

## Lỗi sai thường gặp

- Hiểu “p chỉ nếu q” thành $q\to p$ thay vì $p\to q$.
- Quên rằng kéo theo đúng khi giả thiết sai.
- Phủ định $\forall$ nhưng không đổi thành $\exists$.
- Nhầm XOR với tuyển thường.

## Bài đại diện nên xem lại

- `hw01`: Bài 1-6 cho logic mệnh đề và bảng chân trị.
- `hw01`: Bài 7-10 cho tương đương logic.
- `hw01`: Bài 11-20 cho vị từ, lượng từ và phủ định lượng từ.

