# Tuần 02. Logic và chứng minh - bài tập ưu tiên

## Vai trò trong đề thi

Tuần 2 củng cố luật suy luận và phương pháp chứng minh. Trong đề năm nay phần này chủ yếu xuất hiện ở trắc nghiệm, nhưng cũng là nền để đọc hiểu tự luận đồ thị, cây và ôtômát.

## Nguồn bài tập

- `materials/raw/homework/hw02.pdf`
- `materials/extracted/homework/hw02.txt`
- Lý thuyết liên quan: `topics/tuan-02-logic-chung-minh.md`

## Bảng lọc bài tập

| Bài | Dạng bài | Mức độ | Khả năng ra thi | Ưu tiên | Ghi chú A+ |
| --- | --- | --- | --- | --- | --- |
| 1-4 | Nhận dạng và áp dụng luật suy luận | Vừa | Cao | Bắt buộc | Phải biết chỉ ra rule: modus ponens, modus tollens, syllogism, resolution. |
| 5-8 | Chứng minh trực tiếp/gián tiếp | Vừa | Cao | Bắt buộc | Tập trình bày ngắn, đủ giả thiết và kết luận. |
| 9-10 | Phản chứng và phản đảo | Vừa - khó | Trung bình cao | Bắt buộc A+ | Hợp với câu trắc nghiệm hỏi phương pháp chứng minh đúng. |
| 11-12 | Chứng minh hiển nhiên, rỗng, tồn tại | Vừa | Trung bình | Nên làm | Dễ bị xem nhẹ nhưng hay xuất hiện trong câu lý thuyết. |
| 13-14 | Chứng minh theo trường hợp | Khó vừa | Trung bình cao | A+ | Luyện chia case đủ và không trùng/lọt trường hợp. |

## Công cụ bắt buộc

| Nội dung | Dùng khi nào | Bẫy |
| --- | --- | --- |
| Modus ponens/tollens | Suy ra kết luận từ kéo theo | Không được đảo chiều kéo theo. |
| Hypothetical syllogism | Nối chuỗi \(p \to q, q \to r\) | Cần cùng mệnh đề trung gian. |
| Proof by contraposition | Chứng minh \(p \to q\) qua \(\neg q \to \neg p\) | Không nhầm với inverse. |
| Proof by contradiction | Giả sử phủ định kết luận | Phải dẫn đến mâu thuẫn rõ ràng. |

## Khung tư duy

### Bài suy luận

- Chuẩn hóa giả thiết thành ký hiệu.
- Tìm kết luận cần chứng minh.
- Mỗi dòng suy luận phải dựa vào giả thiết trước đó hoặc luật đã biết.

### Bài chứng minh

- Nếu kết luận là kéo theo, thử chứng minh trực tiếp trước.
- Nếu có phủ định, chia hết, bất đẳng thức hoặc "không tồn tại", cân nhắc phản đảo/phản chứng.
- Nếu có trị tuyệt đối, chẵn/lẻ, dấu, hoặc miền rời rạc, cân nhắc chia trường hợp.

## Thứ tự làm đề xuất

1. Làm 1-4 để chắc luật suy luận.
2. Làm 5-10 để luyện chọn phương pháp chứng minh.
3. Làm 11-14 khi muốn lên mức A+ và kiểm tra độ chặt trình bày.

## Lỗi dễ mất điểm

- Dùng kết luận làm giả thiết mà không nói đang phản chứng.
- Chia trường hợp thiếu một case.
- Viết "hiển nhiên" ở chỗ cần chứng minh một bước logic.
- Không phân biệt phản đảo hợp lệ với đảo/đảo ngược không tương đương.
