# Tuần 12. Văn phạm và ngôn ngữ hình thức - bài tập ưu tiên

## Vai trò trong đề thi

Ngôn ngữ hình thức thuộc trắc nghiệm năm nay và hỗ trợ tự luận ôtômát hữu hạn. Tuần 12 cần nắm sinh chuỗi, cây dẫn xuất, phân loại Chomsky và thiết kế văn phạm.

## Nguồn bài tập

- `materials/raw/homework/hw12.pdf`
- `materials/extracted/homework/hw12.txt`
- Lý thuyết liên quan: `topics/tuan-12-van-pham-ngon-ngu-hinh-thuc.md`

## Bảng lọc bài tập

| Bài | Dạng bài | Mức độ | Khả năng ra thi | Ưu tiên | Ghi chú A+ |
| --- | --- | --- | --- | --- | --- |
| 1-2 | Dẫn xuất câu, kiểm tra câu không sinh được | Vừa | Cao | Bắt buộc | Phải phân biệt "có dẫn xuất" và "không thể dẫn xuất". |
| 3-4 | Kiểm tra chuỗi thuộc ngôn ngữ, mô tả ngôn ngữ | Vừa | Cao | Bắt buộc | Rèn đọc production và pattern chuỗi. |
| 5-6 | Xây văn phạm cho ngôn ngữ cho trước | Vừa - khó | Cao | Bắt buộc A+ | Dạng sát đề cũ, nhưng chỉ dùng để luyện kỹ năng. |
| 7 | Phân loại Chomsky | Vừa | Trung bình cao | Nên làm | Dễ ra trắc nghiệm lý thuyết. |
| 8 | Hợp/nối hai CFG | Khó vừa | Trung bình | A+ | Hiểu thao tác đóng của CFG. |
| 9 | Cây dẫn xuất | Vừa | Cao | Bắt buộc | Hỗ trợ kiểm tra nhập nhằng và parser. |
| 10 | Phân tích cú pháp top-down | Khó vừa | Trung bình | A+ | Làm nếu muốn chắc cơ chế sinh chuỗi. |

## Công cụ bắt buộc

| Nội dung | Dùng khi nào | Bẫy |
| --- | --- | --- |
| Văn phạm \(G=(V,T,S,P)\) | Mọi bài về grammar | Nhầm biến và ký hiệu kết thúc. |
| Dẫn xuất | Chứng minh chuỗi thuộc ngôn ngữ | Bỏ bước hoặc thay ký hiệu không hợp lệ. |
| Cây dẫn xuất | Mô tả cấu trúc sinh chuỗi | Lá phải ghép thành chuỗi terminal. |
| Phân loại Chomsky | Nhận dạng loại grammar | Nhầm chính quy với phi ngữ cảnh. |

## Khung tư duy

### Kiểm tra chuỗi

- Từ production, đoán dạng tổng quát của chuỗi.
- Thử sinh chuỗi theo từng bước hợp lệ.
- Nếu chứng minh không sinh được, tìm bất biến: thứ tự ký tự, số lượng, cặp ký tự.

### Xây văn phạm

- Tách ngôn ngữ thành phần lặp lại và điều kiện số lượng.
- Chọn biến cho từng phần.
- Kiểm tra chuỗi nhỏ nhất và chuỗi biên.

## Thứ tự làm đề xuất

1. Làm 1-4 để chắc đọc văn phạm.
2. Làm 9 để gắn dẫn xuất với cây.
3. Làm 5-6 để luyện xây grammar.
4. Làm 7-8-10 để lên mức A+.

## Lỗi dễ mất điểm

- Dùng terminal như nonterminal trong bước dẫn xuất.
- Thiết kế văn phạm sinh thừa chuỗi ngoài ngôn ngữ.
- Không kiểm tra chuỗi rỗng nếu ngôn ngữ có/không có \(\lambda\).
- Nhầm grammar chính quy phải tuyến tính trái/phải, không được trộn tùy ý.
