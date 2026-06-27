# Tuần 10. Đường đi ngắn nhất, đồ thị phẳng và tô màu

## Vai trò trong đề thi

Liên quan trực tiếp tới tự luận đồ thị và trắc nghiệm thuật toán/đồ thị.

## Nguồn đã nạp

- `materials/raw/lectures/Tuan10.pdf`
- `materials/extracted/lectures/Tuan10.txt`
- `materials/raw/homework/hw10.pdf`

## Kiến thức cốt lõi

- Dijkstra tìm đường đi ngắn nhất từ một đỉnh nguồn trong đồ thị có trọng số dương.
- Floyd-Warshall tìm khoảng cách giữa mọi cặp đỉnh.
- Đồ thị phẳng là đồ thị vẽ được trên mặt phẳng không có cạnh cắt nhau ngoài đầu mút.
- Công thức Euler và các hệ quả là công cụ chứng minh không phẳng.
- Tô màu đồ thị gán màu cho đỉnh sao cho hai đỉnh kề khác màu; sắc số là số màu ít nhất.

## Định nghĩa/công thức/thuật toán cần nhớ

- Dijkstra: luôn chọn đỉnh ngoài tập đã chốt có nhãn nhỏ nhất, rồi cập nhật lân cận.
- Euler cho đồ thị phẳng liên thông: $v-e+r=2$.
- Đơn đồ thị phẳng $v\ge3$: $e\le3v-6$.
- Đơn đồ thị phẳng liên thông không có chu trình độ dài 3: $e\le2v-4$.
- $K_5$ và $K_{3,3}$ là mẫu không phẳng quan trọng; Kuratowski dùng đồng phôi với hai đồ thị này.
- Sắc số của $K_n$ là $n$, của $K_{m,n}$ là $2$ nếu $m,n>0$, của chu trình lẻ là $3$, chu trình chẵn là $2$.

## Dạng bài hay ra

- Chạy Dijkstra hoặc Floyd theo bảng bước.
- Chứng minh phẳng bằng cách vẽ lại.
- Chứng minh không phẳng bằng bất đẳng thức Euler hoặc Kuratowski.
- Tìm sắc số của đồ thị cụ thể.
- Mô hình hóa lập lịch bằng tô màu đồ thị.

## Lỗi sai thường gặp

- Dijkstra không áp dụng khi có cạnh trọng số âm.
- Chứng minh “không vẽ được như hình” không đủ để kết luận không phẳng.
- Dùng $e\le3v-6$ cho đồ thị có cạnh bội/khuyên mà chưa kiểm tra điều kiện.
- Tô màu không chứng minh tối thiểu: cần cả cận trên và cận dưới.

## Bài đại diện nên xem lại

- `hw10`: Bài 1-3 cho đường đi ngắn nhất.
- `hw10`: Bài 4-6 cho phẳng/không phẳng.
- `hw10`: Bài 7-11 cho tô màu và ứng dụng lịch họp.

