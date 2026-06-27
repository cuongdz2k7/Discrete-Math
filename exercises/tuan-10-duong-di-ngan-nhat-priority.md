# Tuần 10. Đường đi ngắn nhất, phẳng, tô màu - bài tập ưu tiên

## Vai trò trong đề thi

Tuần 10 mở rộng tự luận đồ thị: Dijkstra/Floyd, đồ thị phẳng và tô màu. Đề cũ thường dùng phần này để kiểm tra thuật toán và lập luận, nhưng năm nay vẫn phải ưu tiên cấu trúc: đồ thị là trọng tâm tự luận.

## Nguồn bài tập

- `materials/raw/homework/hw10.pdf`
- `materials/extracted/homework/hw10.txt`
- Lý thuyết liên quan: `topics/tuan-10-duong-di-ngan-nhat.md`

## Bảng lọc bài tập

| Bài | Dạng bài | Mức độ | Khả năng ra thi | Ưu tiên | Ghi chú A+ |
| --- | --- | --- | --- | --- | --- |
| 1-2 | Dijkstra/đường đi ngắn nhất một nguồn | Vừa | Cao | Bắt buộc | Trình bày bảng khoảng cách gọn, không nhảy bước. |
| 3 | Floyd-Warshall | Vừa - khó | Trung bình cao | A+ | Có thể ra trắc nghiệm thuật toán hoặc tự luận nhỏ. |
| 4 | Vẽ lại đồ thị phẳng | Vừa | Trung bình | Nên làm | Hữu ích để trực quan hóa nhưng khó chấm nếu chỉ hỏi trắc nghiệm. |
| 5 | Chứng minh \(e \le 2v-4\) cho đồ thị phẳng lưỡng phân | Khó vừa | Cao | Bắt buộc A+ | Dạng chứng minh ngắn, rất đáng luyện. |
| 6 | Kuratowski, nhận dạng không phẳng | Khó vừa | Cao | Bắt buộc A+ | Cần biết \(K_5\), \(K_{3,3}\) và phép chia cạnh. |
| 7-9 | Số sắc, tô màu đồ thị chuẩn | Vừa | Cao | Bắt buộc | Dạng trắc nghiệm/tự luận ngắn rất sát. |
| 10 | Chu trình lẻ không 2-tô màu | Vừa | Cao | Bắt buộc | Liên hệ trực tiếp với lưỡng phân. |
| 11 | Lập lịch bằng tô màu | Vừa - khó | Trung bình cao | A+ | Dạng ứng dụng hay, không quá nặng tính toán. |

## Công cụ bắt buộc

| Nội dung | Dùng khi nào | Bẫy |
| --- | --- | --- |
| Dijkstra | Trọng số không âm, đường đi ngắn nhất một nguồn | Chốt đỉnh quá sớm hoặc quên cập nhật cạnh. |
| Floyd-Warshall | Đường đi ngắn nhất mọi cặp | Nhầm chỉ số trung gian. |
| Euler phẳng \(v-e+f=2\) | Bài đồ thị phẳng liên thông | Dùng sai cho đồ thị không liên thông mà không chỉnh. |
| Số sắc | Tô màu đỉnh | Nhầm tô màu cạnh. |

## Khung tư duy

### Đường đi ngắn nhất

- Ghi bảng gồm đỉnh đã chốt và khoảng cách tạm.
- Mỗi bước chọn khoảng cách tạm nhỏ nhất.
- Lưu tiền nhiệm nếu đề hỏi đường đi, không chỉ độ dài.

### Đồ thị phẳng

- Kiểm tra số cạnh với các chặn phẳng.
- Tìm hoặc loại trừ \(K_5\), \(K_{3,3}\) subdivision.
- Với lưỡng phân phẳng, mọi mặt có độ dài ít nhất 4 nên suy ra \(2e \ge 4f\).

### Tô màu

- Tìm clique hoặc chu trình lẻ để có cận dưới.
- Tô thử để có cận trên.
- Nếu hai cận bằng nhau thì kết luận số sắc.

## Thứ tự làm đề xuất

1. Làm 1-2 để chắc Dijkstra.
2. Làm 7-10 để khóa tô màu/lưỡng phân.
3. Làm 5-6 để luyện A+ phần phẳng.
4. Làm 3 và 11 nếu muốn phủ sâu thuật toán/ứng dụng.

## Lỗi dễ mất điểm

- Dijkstra trên cạnh âm.
- Không ghi đường đi khi đề hỏi đường đi, chỉ ghi độ dài.
- Dùng \(e \le 3v-6\) cho đồ thị phẳng lưỡng phân mà bỏ qua chặn mạnh hơn.
- Kết luận số sắc chỉ từ một cách tô màu mà không có cận dưới.
