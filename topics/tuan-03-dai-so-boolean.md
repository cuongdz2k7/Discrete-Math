# Tuần 03. Đại số Boolean, mạch logic và độ phức tạp thuật toán

## Vai trò trong đề thi

Đại số Boolean và thuật toán thuộc phần trắc nghiệm. Đây là chương dễ có bẫy vì ký hiệu giống số học nhưng phép toán là Boolean.

## Nguồn đã nạp

- `materials/raw/lectures/Tuan03.pdf`
- `materials/extracted/lectures/Tuan03.txt`
- `materials/raw/homework/hw03.pdf`

## Kiến thức cốt lõi

- Đại số Boolean làm việc trên $\{0,1\}$ với bù, tổng Boolean và tích Boolean.
- Hàm Boolean bậc $n$ là hàm từ $\{0,1\}^n$ vào $\{0,1\}$.
- Hai biểu thức Boolean tương đương nếu cho cùng giá trị với mọi bộ đầu vào.
- Mọi hàm Boolean có thể biểu diễn dạng tổng-các-tích bằng các minterm.
- NAND và NOR là các tập đầy đủ hàm.
- Mạch logic là cách triển khai biểu thức Boolean bằng NOT/AND/OR hoặc NAND/NOR.
- Phần thuật toán đi kèm gồm greedy, Big-O, Big-Omega, Big-Theta và một số thuật toán tìm kiếm/sắp xếp.

## Định nghĩa/công thức/thuật toán cần nhớ

- Thứ tự ưu tiên: phủ định, tích, tổng.
- Minterm ứng với đúng một hàng bảng chân trị có giá trị 1.
- Tổng-các-tích: cộng tất cả minterm ứng với output 1.
- $x|x=\bar{x}$ với NAND; $(x|y)|(x|y)=xy$.
- $x\downarrow x=\bar{x}$ với NOR; $(x\downarrow y)\downarrow(x\downarrow y)=x+y$.
- $f(x)=O(g(x))$ nếu $f$ bị chặn trên bởi hằng số nhân của $g$ khi $x$ đủ lớn.

## Dạng bài hay ra

- Tính giá trị biểu thức Boolean.
- Lập bảng chân trị và tìm tổng-các-tích.
- Rút gọn bằng luật Boolean.
- Dựng mạch từ biểu thức hoặc từ mô tả bài toán.
- Dùng K-map/Quine-McCluskey để tối giản.
- Ước lượng Big-O cho hàm hoặc giả mã.

## Lỗi sai thường gặp

- Tính $1+1=2$ thay vì $1+1=1$ trong Boolean.
- Quên mỗi minterm phải chứa đủ mọi biến.
- Nhầm “ít nhất 2 phiếu đồng ý” với XOR.
- Với Big-O, giữ hệ số/hạng thấp không cần thiết hoặc nhầm $O$ với $\Theta$.

## Bài đại diện nên xem lại

- `hw03`: Bài 1-5 cho hàm Boolean và luật.
- `hw03`: Bài 6-8 cho tổng-các-tích.
- `hw03`: Bài 9-14 cho mạch, Karnaugh, Quine-McCluskey.
- `hw03`: Bài 15-22 cho thuật toán và tìm kiếm.

