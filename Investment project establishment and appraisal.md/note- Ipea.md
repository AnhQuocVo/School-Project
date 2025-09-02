# Tổng Hợp Các Công Thức Tài Chính Doanh Nghiệp

## 1. Các Công Thức Liên Quan Đến Giá Trị Tiền Tệ

### 1.1. Giá Trị Tương Lai (FV) – Lãi Đơn
**Mô tả:** Số tiền gốc cộng với tiền lãi trong tương lai, với lãi suất chỉ tính trên vốn gốc.

**Công thức:**
$$FV = P + (P \times r \times n)$$
**Ví dụ:** Tính lãi cho số tiền gốc 100 (đơn vị tiền) với lãi suất 10% năm, thời gian 2 năm.
- Tiền lãi mỗi năm = 100 * 10% = 10
- Giá trị đến cuối năm 2 = 100 + (10 * 2) = 120

### 1.2. Giá Trị Tương Lai (FV) – Lãi Kép
**Mô tả:** Số tiền gốc cộng với tiền lãi trong tương lai, với lãi suất tính trên lãi.

**Công thức:**
$$FV = P \times (1 + r)^n$$
**Ví dụ:** FV của 100 (đơn vị tiền) sau 2 năm (n=2) là bao nhiêu với lãi suất 10% năm (r=10%) tính theo lãi kép?
- FV = 100 * (1 + 10%)^2 = 100 * (1.1)^2 = 100 * 1.21 = 121

### 1.3. Giá Trị Hiện Tại (PV) – Một Khoản Tiền Đơn
**Mô tả:** Là giá trị đồng tiền dự tính có trong tương lai quy về giá trị hiện tại.

**Công thức:**
$$PV = \frac{FV}{(1 + r)^n}$$
**Ví dụ 1:** PV của 1,21 đồng sẽ nhận sau 2 năm (n=2) là bao nhiêu với suất chiết khấu 10% năm (r=10%) tính theo lãi kép?
- PV = 1.21 / (1 + 10%)^2 = 1.21 / (1.1)^2 = 1.21 / 1.21 = 1

**Ví dụ 2:** Dự án đặt mua một hệ thống chữa cháy với giá 1.210 đô-la sẽ giao vào 2 năm sau. Lãi suất là 10%?
- PV = 1210 / (1 + 10%)^2 = 1210 / 1.21 = 1000

### 1.4. Giá Trị Hiện Tại (PV) – Dòng Tiền Vĩnh Viễn (Perpetuity)
**Mô tả:** Tính giá trị hiện tại của một chuỗi dòng tiền bằng nhau và không có giới hạn cuối cùng.

**Công thức:**
$$PV = \frac{A}{r}$$
Trong đó:
- **A:** số tiền đều hàng năm
- **r:** suất chiết khấu (lãi suất)

**Ví dụ:** Một khách sạn nhỏ dự kiến có dòng tiền thu ròng ổn định hàng năm là 10.000 USD. Nếu cơ hội sinh lời đồng vốn là 10% năm, bạn sẽ trả giá mua bao nhiêu?
- PV = 10000 / 10% = 100000 USD

### 1.5. Giá Trị Hiện Tại (PV) – Dòng Tiền Đều (Annuity) Có Thời Hạn n
**Mô tả:** Tính giá trị hiện tại của một loạt dòng tiền bằng nhau, có thời hạn xác định.

**Công thức:**
$$PV = A \times \left[ \frac{1 - (1 + r)^{-n}}{r} \right]$$
Trong đó:
- **A:** số tiền đều (PMT)
- **r:** lãi suất
- **n:** số kỳ

**Ví dụ:** PV của loạt tiền đều nhau là 100 USD với thời gian 2 năm, lãi suất 10% năm là bao nhiêu?
- PV = 100 * [ (1 - (1 + 10%)^-2) / 10% ] = 173.55

### 1.6. Giá Trị Tương Lai (FV) – Dòng Tiền Đều (Annuity) Có Thời Hạn n
**Mô tả:** Tính giá trị tương lai của một loạt dòng tiền bằng nhau, có thời hạn xác định.

**Công thức:**
$$FV = A \times \left[ \frac{(1 + r)^n - 1}{r} \right]$$
**Ví dụ:** FV của loạt tiền đều nhau là 100 USD với thời gian 2 năm, lãi suất 10% năm là bao nhiêu?
- FV = 100 * [ ((1 + 10%)^2 - 1) / 10% ] = 210

### 1.7. Số Tiền Trả Đều Hàng Năm Cho Khoản Vay (PMT)
**Mô tả:** Tính số tiền trả đều hàng năm cho một khoản vay trong một số kỳ nhất định.

**Công thức:**
$$A = PV \times \left[ \frac{r \times (1 + r)^n}{(1 + r)^n - 1} \right]$$
**Ví dụ:** Lập lịch trả nợ cho khoản vay 100 USD, lãi suất 10%, thời hạn 2 năm, phương thức trả mỗi năm số tiền đều nhau?
- A = 100 * [ 10% * (1 + 10%)^2 / ((1 + 10%)^2 - 1) ] = 57.62

**Lịch trả nợ mẫu:**
| Năm | Dư nợ đầu kỳ | Lãi phát sinh | Trả đều | Nợ gốc | Dư nợ cuối kỳ |
|---|---|---|---|---|---|
| 0 | - | - | - | - | 100 |
| 1 | 100 | 10 | 58 | 48 | 52 |
| 2 | 52 | 5 | 58 | 52 | 0 |

---

## 2. Các Chỉ Tiêu Đánh Giá Hiệu Quả Dự Án

### 2.1. Giá Trị Hiện Tại Ròng (NPV)
**Mô tả:** Đo lường sự gia tăng giá trị ròng của dự án bằng cách chiết khấu tất cả các dòng ngân lưu về hiện tại.

**Công thức:**
$$NPV = \sum_{t=1}^{n} \frac{NCF_t}{(1 + r)^t} - I_0$$
Trong đó:
- **NCFt:** Dòng ngân lưu ròng tại thời điểm t
- **r:** Suất chiết khấu
- **I0:** Khoản đầu tư ban đầu

**Ví dụ:** Đầu tư 3.000 triệu. Dòng thu cuối năm: Năm 1: 400; Năm 2: 400; Năm 3: 3.400. Suất chiết khấu r = 20%.
- Tổng PV dòng thu = 400/(1.2)^1 + 400/(1.2)^2 + 3400/(1.2)^3 = 2579 triệu
- NPV = 2579 - 3000 = -421 triệu đồng (Dự án không đáng giá)

### 2.2. Suất Sinh Lời Nội Tại (IRR)
**Mô tả:** Là suất chiết khấu mà tại đó giá trị hiện tại ròng (NPV) của dự án bằng 0.

**Công thức:**
$$\sum_{t=1}^{n} \frac{NCF_t}{(1 + IRR)^t} - I_0 = 0$$
**Ví dụ:** Đầu năm bỏ ra 100 triệu, cuối năm mang về 120 triệu.
- -100 + 120 / (1 + IRR) = 0
- IRR = 20%

### 2.3. Khả Năng Sinh Lời (PI)
**Mô tả:** So sánh giá trị hiện tại dòng thu với giá trị hiện tại dòng chi.

**Công thức:**
$$PI = \frac{\text{Tổng PV dòng thu}}{\text{Tổng PV dòng chi}}$$
**Ví dụ:** Với dự án trên:
- PI = 2579 / 3000 = 0.86 (Dự án không đáng giá vì PI < 1)

### 2.4. Kỳ Hoàn Vốn Không Chiết Khấu (PP)
**Mô tả:** Thời gian cần thiết để dòng thu tích lũy đủ bù đắp dòng chi, không tính giá trị thời gian của tiền.

**Công thức:**
$$PP = \text{Năm trước hòa vốn} + \frac{|\text{Ngân lưu ròng lũy kế âm cuối cùng}|}{\text{Ngân lưu ròng của năm kế tiếp}}$$

### 2.5. Kỳ Hoàn Vốn Có Chiết Khấu (DPP)
**Mô tả:** Thời gian cần thiết để dòng thu chiết khấu tích lũy đủ bù đắp dòng chi chiết khấu.

**Công thức:**
$$DPP = \text{Năm trước hòa vốn} + \frac{|\text{PV ngân lưu ròng lũy kế âm cuối cùng}|}{\text{PV ngân lưu ròng của năm kế tiếp}}$$

---

## 3. Các Công Thức Liên Quan Đến Lạm Phát

### 3.1. Chỉ số giá (Price Index)
$$I_t = \frac{PL_t}{PL_0}$$

### 3.2. Chỉ số lạm phát (Inflation Index)
$$I_n = (1 + g)^n$$

### 3.3. Giá danh nghĩa (Nominal Price)
$$P_n = P_0 \times I_n$$

### 3.4. Giá thực (Real Price)
$$P_R = \frac{P_N}{I}$$

### 3.5. Suất chiết khấu danh nghĩa (Nominal Discount Rate)
$$r_N = r_R + g + (r_R \times g)$$

### 3.6. Suất chiết khấu thực (Real Discount Rate)
$$r_R = \frac{r_N - g}{1 + g}$$

### 3.7. Chỉ số lạm phát tương đối (Relative Inflation Index)
$$I_R = \frac{I_D}{I_F} = \frac{(1 + g_D)^n}{(1 + g_F)^n}$$

### 3.8. Tỉ giá hối đoái danh nghĩa (Nominal Exchange Rate)
$$E_n = E_0 \times I_{Rn}$$

---

## 4. Điểm Hòa Vốn (Break-Even Point)

### 4.1. Điểm hòa vốn kế toán
**Mô tả:** Điểm mà tại đó lợi nhuận ròng của dự án bằng 0.
**Công thức:** Lợi nhuận ròng = 0

### 4.2. Điểm hòa vốn tài chính
**Mô tả:** Điểm mà tại đó giá trị hiện tại ròng (NPV) của dự án bằng 0.
**Công thức:** NPV = 0

---

## 5. Chi phí sử dụng vốn bình quân gia quyền (WACC)

### 5.1. WACC (chưa tính lá chắn thuế)
$$WACC = (\%E \times r_E) + (\%D \times r_D)$$

### 5.2. WACC (có tính lá chắn thuế)
$$WACC = (\%E \times r_E) + (\%D \times r_D \times (1 - t))$$

---

## 6. Dòng Ngân Lưu Tự Do (Free Cash Flow - FCF)

### 6.1. FCF cơ bản
$$FCF = EBIT \times (1 - t)$$

### 6.2. FCF điều chỉnh
FCF = EBIT * (1 - t) - Đầu tư + Khấu hao - Thay đổi vốn lưu động ròng

---

## 7. Các Chỉ Tiêu Đánh Giá Lợi Ích Kinh Tế - Xã Hội

### 7.1. Lợi nhuận gộp trên vốn cố định
$$I_1 = \frac{\text{Lợi nhuận gộp}}{\text{Tổng vốn đầu tư cố định}}$$

### 7.2. Doanh thu hàng năm trên tổng vốn đầu tư
$$I_2 = \frac{\text{Doanh thu hàng năm}}{\text{Tổng vốn đầu tư hàng năm}}$$

### 7.3. Kim ngạch xuất khẩu trên vốn đầu tư
$$I_x = \frac{\text{Tổng kim ngạch xuất khẩu của dự án}}{\text{Tổng vốn đầu tư}}$$

### 7.4. Vốn đầu tư cho một lao động làm việc
$$I_v = \frac{\text{Tổng vốn đầu tư}}{\text{Số lao động}}$$

### 7.5. Thu nhập bình quân lao động của dự án
$$I_{pi} = \frac{\text{Thu nhập của dự án}}{\text{Số lượng lao động dự án}}$$

### 7.6. Tỉ lệ đóng góp ngân sách
$$I_f = \frac{\text{Mức đóng góp vào ngân sách}}{\text{Tổng vốn đầu tư}}$$

### 7.7. Giá trị gia tăng trong nước thuần
Giá trị gia tăng trong nước thuần = Giá trị đầu ra - Giá trị đầu vào

### 7.8. Giá trị gia tăng quốc dân thuần (NNVA)
NNVA = Giá trị gia tăng trong nước thuần + Các khoản chuyển ra nước ngoài

### 7.9. Giá trị thặng dư xã hội
Giá trị thặng dư xã hội = Giá trị gia tăng quốc dân thuần + Tiền lương lao động trong nước

### 7.10. Suất sinh lợi kinh tế (ERR)
**Mô tả:** Tương tự IRR nhưng tính cho toàn xã hội, sử dụng lợi ích (B) và chi phí (C) kinh tế.

$$\sum_{t=0}^{n} \frac{B_t - C_t}{(1 + ERR)^t} = 0$$
