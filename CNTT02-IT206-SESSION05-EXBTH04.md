# Bài thực hành 4: Phân tích kết quả học tập và đề xuất giải pháp cải thiện

## 1. Prompt hoàn chỉnh

```
Bạn là trợ lý phân tích dữ liệu giáo dục.

DỮ LIỆU (chỉ dùng dữ liệu này):
Sinh viên | Tuần 1 | Tuần 2 | Tuần 3
An   | 8 | 7 | 5
Bình | 7 | 6 | 4
Chi  | 9 | 8 | 8
Dũng | 6 | 5 | 3
Hà   | 8 | 8 | 7

NHIỆM VỤ: Phân tích kết quả học tập 3 tuần và hỗ trợ giảng viên.

QUY TẮC:
- Chỉ dùng dữ liệu đã cho, không bịa thêm thông tin.
- KHÔNG suy đoán nguyên nhân khiến sinh viên giảm điểm.
- Mọi nhận định phải kèm số liệu chứng minh.

HÃY SUY LUẬN TỪNG BƯỚC (Chain-of-Thought) và trình bày rõ từng bước:

Bước 1 - TÍNH TOÁN: Với mỗi sinh viên, tính mức thay đổi Tuần 1→2,
Tuần 2→3, tổng thay đổi Tuần 1→3 và điểm trung bình. Trình bày phép tính.

Bước 2 - SO SÁNH: So sánh các sinh viên về điểm trung bình, mức giảm
tổng và xu hướng. Xếp hạng theo mức giảm.

Bước 3 - NHẬN ĐỊNH: Xác định sinh viên có dấu hiệu sa sút (nêu tiêu chí,
ví dụ: giảm liên tiếp 2 tuần và tổng giảm ≥ 2 điểm). Đưa ra 3 nhận định
quan trọng, mỗi nhận định có dữ liệu chứng minh. Nêu các điểm giảng viên
cần xác minh thêm (không tự suy đoán nguyên nhân).

Bước 4 - ĐỀ XUẤT: Đưa ra 3 giải pháp hỗ trợ học tập cụ thể, mỗi giải pháp
gắn với nhóm sinh viên và dữ liệu liên quan.

ĐỊNH DẠNG: Có bảng phân tích, rồi lần lượt Bước 1 → 4.
```

## 2. Bảng phân tích

| Sinh viên | T1→T2 | T2→T3 | Tổng T1→T3 | Điểm TB | Xu hướng |
|---|---|---|---|---|---|
| An | −1 | −2 | **−3** | 6,67 | Giảm liên tục |
| Bình | −1 | −2 | **−3** | 5,67 | Giảm liên tục |
| Chi | −1 | 0 | **−1** | 8,33 | Giảm nhẹ rồi ổn định |
| Dũng | −1 | −2 | **−3** | 4,67 | Giảm liên tục |
| Hà | 0 | −1 | **−1** | 7,67 | Giảm nhẹ |

*Ví dụ tính An: 8→7 = −1; 7→5 = −2; tổng 5−8 = −3; TB = (8+7+5)/3 = 6,67.*

## 3. Nhóm có dấu hiệu sa sút

**Tiêu chí:** giảm điểm cả 2 giai đoạn và tổng giảm ≥ 3 điểm.

**An, Bình, Dũng** thuộc nhóm sa sút (đều giảm 3 điểm, giảm mạnh hơn ở tuần 3).
Chi và Hà giảm ít (1 điểm), chưa đáng lo.

## 4. Ba nhận định quan trọng

1. **Cả 5 sinh viên đều giảm điểm** từ tuần 1 đến tuần 3 (không ai tăng), nên có thể liên quan đến độ khó nội dung hoặc đề kiểm tra, cần xác minh.
2. **Mức giảm tăng dần ở nhóm sa sút:** An, Bình, Dũng giảm 1 điểm (T1→T2) rồi giảm 2 điểm (T2→T3), tức giảm nhanh hơn.
3. **Có khoảng cách lớn giữa các sinh viên:** Chi có TB 8,33 so với Dũng 4,67 (chênh 3,66 điểm); Dũng còn 3 điểm ở tuần 3, thấp nhất lớp.

**Cần giảng viên xác minh thêm:**
- Độ khó đề từng tuần có tăng không.
- Nội dung tuần 3 là gì.
- Sinh viên có vắng mặt hay nộp thiếu bài không.

*(Không suy đoán nguyên nhân khi chưa có dữ liệu.)*

## 5. Ba giải pháp hỗ trợ

1. **Gặp riêng An, Bình, Dũng** để xác định phần kiến thức bị hổng ở tuần 3, vì điểm của họ giảm mạnh nhất (−2).
2. **Tổ chức buổi ôn tập/bài tập bổ trợ** cho nội dung tuần 2–3, ưu tiên Dũng (3 điểm) và Bình (4 điểm).
3. **Ghép nhóm học tập** giữa Chi, Hà (điểm ổn định, 8 và 7) với nhóm sa sút để hỗ trợ nhau, đồng thời theo dõi điểm tuần 4 để đánh giá hiệu quả.
