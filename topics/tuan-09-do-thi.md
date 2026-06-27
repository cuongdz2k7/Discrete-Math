# Tuần 09. Lý thuyết đồ thị

## Vai trò trong đề thi

Thuộc cả trắc nghiệm và tự luận. Đây là trọng tâm lớn của đề năm nay.

## Nguồn đã nạp

- `materials/raw/lectures/Tuan09.pdf`
- `materials/extracted/lectures/Tuan09.txt`
- `materials/raw/homework/hw09.pdf`

## Kiến thức cốt lõi

- Đồ thị $G=(V,E)$ mô hình hóa quan hệ giữa các đối tượng.
- Cần phân biệt đồ thị vô hướng, có hướng, đơn đồ thị, đa đồ thị và khuyên.
- Bậc, lân cận, bậc vào/bậc ra là công cụ mở đầu nhiều bài.
- Ma trận kề biểu diễn đồ thị và lũy thừa ma trận kề đếm đường đi.
- Đẳng cấu yêu cầu song ánh bảo toàn quan hệ kề.
- Liên thông, đường đi, chu trình là nền cho Euler, Hamilton, phân đôi.
- Euler có tiêu chuẩn bậc rõ; Hamilton không có tiêu chuẩn cần và đủ đơn giản.

## Định nghĩa/công thức/định lý cần nhớ

- Định lý bắt tay: $\sum_v \deg(v)=2|E|$.
- Số đỉnh bậc lẻ trong đồ thị vô hướng là số chẵn.
- Với đồ thị có hướng: $\sum_v \deg^-(v)=\sum_v \deg^+(v)=|E|$.
- $(A^r)_{ij}$ là số đường đi độ dài $r$ từ $v_i$ tới $v_j$.
- Chu trình Euler tồn tại khi đồ thị liên thông và mọi đỉnh bậc chẵn.
- Đồ thị phân đôi khi và chỉ khi không chứa chu trình lẻ.
- Dirac/Ore là điều kiện đủ cho Hamilton, không phải điều kiện cần.

## Dạng bài hay ra

- Tính bậc, lân cận, số cạnh.
- Vẽ/mô hình hóa quan hệ bằng đồ thị.
- Nhận dạng $K_n$, $K_{m,n}$, $C_n$, $W_n$, $Q_n$.
- Ma trận kề và dựng lại đồ thị từ ma trận.
- Kiểm tra đẳng cấu bằng bậc, đường đi, chu trình.
- Chứng minh phân đôi, Euler, Hamilton hoặc không Hamilton.

## Quy trình giải chung

1. Xác định loại đồ thị và giả thiết: đơn/đa, hướng/vô hướng, liên thông hay không.
2. Tính bậc và các bất biến cơ bản.
3. Nếu hỏi Euler, kiểm tra liên thông và bậc chẵn/lẻ.
4. Nếu hỏi phân đôi, thử chia 2 phía hoặc tìm chu trình lẻ.
5. Nếu hỏi đẳng cấu, so số đỉnh, số cạnh, dãy bậc, số chu trình/đường đi đặc biệt.
6. Nếu hỏi Hamilton, dùng điều kiện loại trừ và thử dựng chu trình.

## Lỗi sai thường gặp

- Dùng tiêu chuẩn Euler cho Hamilton.
- Quên điều kiện liên thông khi xét Euler.
- Nhầm đồ thị phân đôi đầy đủ với đồ thị đầy đủ.
- Ma trận kề của đa đồ thị có thể có phần tử lớn hơn 1.

## Bài đại diện nên xem lại

- `hw09`: Bài 4, 8 cho định lý bắt tay và bậc.
- `hw09`: Bài 9-13 cho ma trận kề và số đường đi.
- `hw09`: Bài 16-19 cho phân đôi, Euler, Hamilton.

