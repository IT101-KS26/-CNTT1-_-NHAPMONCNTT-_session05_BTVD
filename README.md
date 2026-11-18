# BÀI TẬP THỰC HÀNH
````markdown
 
# DỮ LIỆU ĐẦU VÀO
Được cho ví dụ:
- Thu nhập tháng này: 20.000.000 VND
- Chi phí cố định bắt buộc:
  - Tiền nhà: 5.000.000 VND
  - Điện nước: 1.000.000 VND
  - Internet/điện thoại: 500.000 VND
- Các khoản nợ:
  - Thẻ tín dụng: trả tối thiểu 1.500.000 VND/tháng, lãi suất 30%/năm, hạn thanh toán ngày 15
  - Vay tiêu dùng: trả tối thiểu 2.000.000 VND/tháng, lãi suất 18%/năm, hạn thanh toán ngày 25
- Mục tiêu tiết kiệm: tối thiểu 20% thu nhập + quỹ dự phòng mục tiêu 19.500.000 VND (3 tháng chi phí cố định, hiện có 0 VND)
 
# CHỈ THỊ KÍCH HOẠT CHAIN-OF-THOUGHT
Hãy suy nghĩ từng bước một và tính toán chi tiết trước khi đưa ra quyết định.
 
# QUY TRÌNH LẬP LUẬN BẮT BUỘC
**Bước 1 – Thu nhập khả dụng**
Khả dụng = Thu nhập − Tổng chi phí cố định.
Liệt kê từng khoản trừ và số dư sau mỗi phép trừ.
 
**Bước 2 – Trả nợ tối thiểu**
Cộng từng khoản nợ tối thiểu → Tổng nợ. Kiểm tra: Tổng nợ ≤ Khả dụng.
Nếu không đủ: cảnh báo và đề xuất phương án (đàm phán, hoãn khoản nợ lãi thấp).
 
**Bước 3 – Trích tiết kiệm**
Tiết kiệm = Thu nhập × tỷ lệ cam kết (≥ 20%). Ưu tiên nạp quỹ dự phòng trước.
Còn lại = Khả dụng − Tổng nợ − Tiết kiệm.
 
**Bước 4 – Chi tiêu linh hoạt (50/30/20 cải tiến)**
Chia phần "Còn lại" của Bước 3: Thiết yếu linh hoạt 60% | Mong muốn 25% | Dự phòng/trả nợ thêm 15%
(có thể điều chỉnh và phải giải thích lý do).
 
# QUY TẮC KIỂM SOÁT SAI SÓT
1. Viết rõ từng phép tính dạng `A + B = C`, không nhảy cóc.
2. Sau mỗi bước, tự kiểm tra lại bằng phép tính ngược.
3. Tính tỷ lệ % trên **Thu nhập**, ghi rõ mẫu số.
4. Tổng tỷ lệ % bảng cuối phải bằng chính xác 100% (làm tròn 1 chữ số thập phân, dồn phần dư vào "Dự phòng").
5. Không dùng code; chỉ lập luận bằng văn bản.
 
````
 
---
 

 
### Phần 1: Nhật ký suy luận (Reasoning Steps)
 
**Bước 1 – Thu nhập khả dụng**
- Chi phí cố định = 5.000.000 + 1.000.000 + 500.000 = 6.500.000
- Khả dụng = 20.000.000 − 6.500.000 = **13.500.000**
- Kiểm tra: 13.500.000 + 6.500.000 = 20.000.000 
**Bước 2 – Trả nợ tối thiểu**
- Tổng nợ = 1.500.000 + 2.000.000 = **3.500.000**
- Kiểm tra: 3.500.000 ≤ 13.500.000 
- Còn lại = 13.500.000 − 3.500.000 = 10.000.000
**Bước 3 – Tiết kiệm (20% thu nhập)**
- Tiết kiệm = 20.000.000 × 20% = **4.000.000**
- Còn lại = 10.000.000 − 4.000.000 = **6.000.000**
**Bước 4 – Chi tiêu linh hoạt (chia 6.000.000)**
- Thiết yếu linh hoạt 60% = 6.000.000 × 0,60 = 3.600.000
- Mong muốn 25% = 6.000.000 × 0,25 = 1.500.000
- Dự phòng/trả nợ thêm 15% = 6.000.000 × 0,15 = 900.000
- Kiểm tra: 3.600.000 + 1.500.000 + 900.000 = 6.000.000 
**Kiểm tra tổng:** 6.500.000 + 3.500.000 + 4.000.000 + 3.600.000 + 1.500.000 + 900.000 = 20.000.000 
 
### Phần 2: Bảng phân bổ ngân sách
 
| Hạng mục | Số tiền (VND) | Tỷ lệ % | Ghi chú |
|---|---:|---:|---|
| Chi phí cố định | 6.500.000 | 32,5% | Nhà, điện nước, viễn thông |
| Trả nợ tối thiểu | 3.500.000 | 17,5% | Thẻ 1,5tr + vay 2tr, trả đúng hạn |
| Tiết kiệm/Quỹ dự phòng | 4.000.000 | 20,0% | Đạt mức tối thiểu 20% |
| Thiết yếu linh hoạt | 3.600.000 | 18,0% | Ăn uống, đi lại |
| Mong muốn | 1.500.000 | 7,5% | Giải trí, mua sắm |
| Dự phòng/trả nợ thêm | 900.000 | 4,5% | Ưu tiên trả thêm nợ lãi cao |
| **Tổng cộng** | **20.000.000** | **100,0%** | 32,5 + 17,5 + 20 + 18 + 7,5 + 4,5 = 100  |
