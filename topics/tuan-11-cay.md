# Tuần 11. Cây, cây khung và cây khung nhỏ nhất

## Vai trò trong đề thi

Thuộc cả trắc nghiệm và tự luận. Cây, DFS/BFS và cây khung là trọng tâm tự luận năm nay.

## Nguồn đã nạp

- `materials/raw/lectures/Tuan11.pdf`
- `materials/extracted/lectures/Tuan11.txt`
- `materials/raw/homework/hw11.pdf`

## Kiến thức cốt lõi

- Cây là đồ thị vô hướng liên thông không có chu trình đơn.
- Cây có gốc tạo quan hệ cha, con, lá, đỉnh trong, mức và chiều cao.
- Cây $m$-phân và cây nhị phân có công thức đếm lá/đỉnh quan trọng.
- Cây quyết định, mã tiền tố, Huffman và cây biểu thức là ứng dụng của cây.
- Cây khung tồn tại khi và chỉ khi đồ thị liên thông.
- DFS/BFS tạo cây khung; Prim/Kruskal tạo cây khung nhỏ nhất trong đồ thị có trọng số.

## Định nghĩa/công thức/thuật toán cần nhớ

- Cây có $n$ đỉnh thì có $n-1$ cạnh.
- Cây $m$-phân đầy đủ với $i$ đỉnh trong: $n=mi+1$, $l=(m-1)i+1$.
- Cây $m$-phân cao $h$ có tối đa $m^h$ lá.
- DFS: đi sâu theo đỉnh kề chưa thăm, quay lui khi hết đường.
- BFS: dùng hàng đợi, thăm theo từng lớp.
- Prim: thêm cạnh nhẹ nhất nối cây hiện tại với đỉnh ngoài.
- Kruskal: thêm cạnh nhẹ nhất không tạo chu trình.
- Huffman: lặp lại ghép hai trọng số nhỏ nhất.

## Dạng bài hay ra

- Chứng minh đồ thị là cây hoặc dùng tính chất $n-1$ cạnh.
- Đếm lá/đỉnh trong cây $m$-phân.
- Duyệt tiền tự/trung tự/hậu tự.
- Dựng cây biểu thức và đổi trung tố/tiền tố/hậu tố.
- Chạy DFS/BFS để tìm cây khung.
- Chạy Prim/Kruskal để tìm MST.

## Lỗi sai thường gặp

- Nhầm “cây khung” với “cây khung nhỏ nhất”.
- BFS/DFS không tuân thủ thứ tự đỉnh đề cho.
- Kruskal thêm cạnh tạo chu trình.
- Prim chọn cạnh nhỏ nhất toàn đồ thị thay vì cạnh nối từ cây hiện tại ra ngoài.

## Bài đại diện nên xem lại

- `hw11`: phần Duyệt cây cho DFS/BFS.
- `hw11`: phần Cây khung cho Prim, Kruskal và minimum spanning forest.

