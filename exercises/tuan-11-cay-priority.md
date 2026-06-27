# Tuần 11. Cây - bài tập ưu tiên

## Vai trò trong đề thi

Cây thuộc cả trắc nghiệm và tự luận năm nay. Cần thành thạo cây khung, DFS/BFS, Prim, Kruskal và nhận dạng cây/rừng.

## Nguồn bài tập

- `materials/raw/homework/hw11.pdf`
- `materials/extracted/homework/hw11.txt`
- Lý thuyết liên quan: `topics/tuan-11-cay.md`

## Bảng lọc bài tập

| Bài | Dạng bài | Mức độ | Khả năng ra thi | Ưu tiên | Ghi chú A+ |
| --- | --- | --- | --- | --- | --- |
| 1 | Cây khung bằng DFS | Vừa | Cao | Bắt buộc | Trình bày thứ tự duyệt và cạnh được chọn. |
| 2 | Cây khung bằng BFS | Vừa | Cao | Bắt buộc | Phân biệt rõ hàng đợi BFS với ngăn xếp/đệ quy DFS. |
| 3 | Cây khung nhỏ nhất bằng Prim | Vừa - khó | Cao | Bắt buộc | Ghi cạnh chọn từng bước và trọng số tổng. |
| 4 | Cây khung nhỏ nhất bằng Kruskal | Vừa - khó | Cao | Bắt buộc | Chọn cạnh tăng dần, bỏ cạnh tạo chu trình. |
| 5 | Rừng khung nhỏ nhất | Khó vừa | Trung bình cao | A+ | Biết sửa Prim/Kruskal khi đồ thị không liên thông. |

## Công cụ bắt buộc

| Nội dung | Dùng khi nào | Bẫy |
| --- | --- | --- |
| Cây có \(n-1\) cạnh | Kiểm tra cây/cây khung | Cần thêm liên thông và không chu trình. |
| DFS | Duyệt sâu, cây khung DFS | Phụ thuộc thứ tự xét đỉnh nếu đề không cố định. |
| BFS | Duyệt theo lớp, cây khung BFS | Nhầm thứ tự lớp. |
| Prim/Kruskal | MST | Prim mở rộng từ một cây; Kruskal xét cạnh toàn cục. |

## Khung tư duy

### DFS/BFS

- Ghi quy ước thứ tự xét đỉnh nếu đề không cho.
- DFS: đi sâu đến khi kẹt rồi quay lui.
- BFS: duyệt theo lớp khoảng cách cạnh từ đỉnh gốc.

### MST

- Prim: bắt đầu từ một đỉnh, mỗi bước chọn cạnh nhẹ nhất nối cây hiện tại ra ngoài.
- Kruskal: sắp cạnh tăng dần, thêm cạnh nếu không tạo chu trình.
- Luôn ghi tổng trọng số cuối cùng.

## Thứ tự làm đề xuất

1. Làm 1-2 để phân biệt DFS/BFS.
2. Làm 3-4 đến khi không nhầm Prim/Kruskal.
3. Làm 5 để đạt mức A+ và xử lý đồ thị không liên thông.

## Lỗi dễ mất điểm

- Không ghi thứ tự xét đỉnh làm đáp án cây khung mơ hồ.
- Kruskal chọn cạnh tạo chu trình.
- Prim chọn cạnh nhẹ nhất toàn đồ thị thay vì nhẹ nhất nối từ cây hiện tại ra ngoài.
- Quên rằng rừng khung nhỏ nhất áp dụng cho đồ thị không liên thông.
