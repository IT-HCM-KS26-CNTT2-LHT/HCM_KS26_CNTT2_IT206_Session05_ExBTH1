# [Bài thực hành 1] Lập kế hoạch tài chính cá nhân bằng Chain-of-Thought

 ## Thiết kế prompt yêu cầu AI lập kế hoạch tài chính hàng tháng từ dữ liệu đầu vào gồm: Thu nhập, Chi phí cố định, Các khoản nợ, Mục tiêu tiết kiệm :

Bạn là trợ lý tài chính cá nhân. Hãy lập kế hoạch tài chính hàng tháng dựa trên dữ liệu:

- Thu nhập: [Số tiền]
- Thuế: [Số tiền]
- Chi phí cố định: [Số tiền]
- Các khoản nợ: [Số tiền và hạn trả]
- Mục tiêu tiết kiệm: Tối thiểu 20%.

**Yêu cầu thực hiện:**

Hãy suy nghĩ từng bước một và tính toán chi tiết trước khi đưa ra quyết định.

1. Tính thu nhập sau thuế và chi phí cố định.
2. Xác định khoản tiền trả nợ tối thiểu.
3. Trích lập tiết kiệm tối thiểu 20%.
4. Phân bổ tiền còn lại theo quy tắc 50/30/20 cải tiến.

**Kết quả gồm 2 phần:**

- Phần 1: Các bước tính toán, công thức và số liệu trung gian.
- Phần 2: Bảng ngân sách:

| Hạng mục | Số tiền | Tỷ lệ % | Ghi chú |
|--|--|--|--|
| Chi phí cố định | | | |
| Trả nợ | | | |
| Tiết kiệm | | | |
| Chi tiêu linh hoạt | | | |
| Tổng cộng | | 100% | |

**Lưu ý:** Tính toán chính xác, không bỏ qua phép tính trung gian. Tổng tỷ lệ phân bổ phải bằng 100%.

## Kết quả AI Promt ra : 

Kế hoạch Tài chính Cá nhân Hàng tháng

Dữ liệu đầu vào (Số liệu minh họa)
* **Thu nhập gộp (Gross):** $25.000.000\text{ đ/tháng}$
* **Thuế TNCN & Bảo hiểm bắt buộc:** $2.500.000\text{ đ/tháng}$
* **Chi phí cố định** (Tiền nhà, điện, nước, internet, đi lại cơ bản): $8.000.000\text{ đ/tháng}$
* **Các khoản nợ** (Trả góp tiêu dùng/thẻ tín dụng): $2.000.000\text{ đ/tháng}$ (hạn trả ngày 15 hàng tháng)
* **Mục tiêu tiết kiệm:** Tối thiểu $20\%$ thu nhập sau thuế

---

Phần 1: Các bước tính toán chi tiết & công thức

Bước 1: Tính thu nhập thực nhận (sau thuế) và số dư sau chi phí cố định
* **Công thức:**
  $$\text{Thu nhập sau thuế (Net)} = \text{Thu nhập gộp} - \text{Thuế}$$
  $$\text{Số dư bước 1} = \text{Thu nhập sau thuế} - \text{Chi phí cố định}$$
* **Tính toán:**
  $$\text{Thu nhập sau thuế} = 25.000.000 - 2.500.000 = 22.500.000\text{ đ}$$
  $$\text{Số dư bước 1} = 22.500.000 - 8.000.000 = 14.500.000\text{ đ}$$

 Bước 2: Xác định khoản tiền trả nợ tối thiểu
* **Nguyên tắc:** Ưu tiên thanh toán đúng hạn các khoản nợ bắt buộc để tránh phí phạt và lãi suất quá hạn.
* **Tính toán:**
  $$\text{Tiền trả nợ} = 2.000.000\text{ đ}$$
  $$\text{Số dư bước 2} = 14.500.000 - 2.000.000 = 12.500.000\text{ đ}$$

 Bước 3: Trích lập tiết kiệm tối thiểu 20%
* **Công thức:** Mức tiết kiệm tối thiểu được tính trên **Thu nhập sau thuế** (dòng tiền thực tế bạn cầm về):
  $$\text{Tiết kiệm tối thiểu} = \text{Thu nhập sau thuế} \times 20\%$$
* **Tính toán:**
  $$\text{Tiết kiệm tối thiểu} = 22.500.000 \times 20\% = 4.500.000\text{ đ}$$
  $$\text{Số dư bước 3} = 12.500.000 - 4.500.000 = 8.000.000\text{ đ}$$

Bước 4: Phân bổ tiền còn lại theo quy tắc 50/30/20 cải tiến
Theo quy tắc 50/30/20 tiêu chuẩn trên tổng thu nhập sau thuế ($22.500.000\text{ đ}$):
* **Nhóm Nhu cầu thiết yếu (50%):** Giới hạn tối đa là $22.500.000 \times 50\% = 11.250.000\text{ đ}$. Hiện tại **Chi phí cố định** đã chiếm $8.000.000\text{ đ}$ ($35,56\%$), nên bạn còn dư $3.250.000\text{ đ}$ ($14,44\%$) cho các chi phí sinh hoạt thiết yếu biến đổi (ăn uống hàng ngày, nhu yếu phẩm).
* **Nhóm Mong muốn cá nhân (30%):** Giới hạn tối đa là $22.500.000 \times 30\% = 6.750.000\text{ đ}$. Tuy nhiên, vì bạn phải trích $2.000.000\text{ đ}$ ($8,89\%$) để **Trả nợ**, quỹ cho mong muốn cá nhân (giải trí, mua sắm, hiếu hỉ) sẽ điều chỉnh giảm tương ứng còn $4.750.000\text{ đ}$ ($21,11\%$) để đảm bảo không lạm vào quỹ tiết kiệm $20\%$.
* **Tổng quỹ Chi tiêu linh hoạt** (bao gồm Ăn uống/sinh hoạt biến đổi + Mong muốn cá nhân):
  $$\text{Chi tiêu linh hoạt} = 3.250.000 + 4.750.000 = 8.000.000\text{ đ}$$

---

 Phần 2: Bảng ngân sách hàng tháng

| Hạng mục | Số tiền | Tỷ lệ % | Ghi chú |
| :--- | :--- | :--- | :--- |
| Chi phí cố định | 8.000.000 đ | 35,56% | Thuê nhà, điện, nước, internet, xăng xe cố định |
| Trả nợ | 2.000.000 đ | 8,89% | Thanh toán đúng hạn ngày 15 hàng tháng |
| Tiết kiệm | 4.500.000 đ | 20,00% | Trích lập tự động ngay khi nhận lương |
| Chi tiêu linh hoạt | 8.000.000 đ | 35,55% | Gồm 3.250.000 đ ăn uống thiết yếu + 4.750.000 đ cá nhân |
| **Tổng cộng** | **22.500.000 đ** | **100%** | **Tính trên tổng thu nhập sau thuế** |
