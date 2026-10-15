# HƯỚNG DẪN GIẢI CHI TIẾT CÁC BÀI TẬP NHIỆT HỌC

Dưới đây là phần lời giải chi tiết cho tất cả các bài tập nhiệt học được cung cấp trong tài liệu.

---

## 1. CÁC BÀI TẬP VỀ ĐUN SÔI VÀ CÂN BẰNG NHIỆT CƠ BẢN

### Câu IV: (8 – HD 13/14)
*Đề bài:* Một ấm đun nước bằng nhôm có khối lượng $500\text{ g}$, chứa $2\text{ lit}$ nước ở nhiệt độ $20^\circ\text{C}$. Tính nhiệt lượng cần thiết để đun ấm nước đó sôi. Biết nhiệt dung riêng của Nhôm là $900\text{ J/kg.K}$ và của Nước là $4200\text{ J/kg.K}$.

**Lời giải:**
- Khối lượng nhôm: $m_1 = 500\text{ g} = 0,5\text{ kg}$.
- Khối lượng nước: $m_2 = 2\text{ lit} \implies V_2 = 2\text{ dm}^3 \implies m_2 = 2\text{ kg}$ (vì khối lượng riêng của nước là $1000\text{ kg/m}^3$).
- Nhiệt độ ban đầu của ấm và nước: $t_1 = 20^\circ\text{C}$.
- Nhiệt độ sôi của nước: $t_2 = 100^\circ\text{C}$.
- Độ tăng nhiệt độ: $\Delta t = t_2 - t_1 = 100 - 20 = 80^\circ\text{C}$.

Nhiệt lượng cần cung cấp để ấm nhôm nóng lên từ $20^\circ\text{C}$ đến $100^\circ\text{C}$:
$$Q_1 = m_1 \cdot c_1 \cdot \Delta t = 0,5 \cdot 900 \cdot 80 = 36000\text{ J}$$

Nhiệt lượng cần cung cấp để nước nóng lên từ $20^\circ\text{C}$ đến $100^\circ\text{C}$:
$$Q_2 = m_2 \cdot c_2 \cdot \Delta t = 2 \cdot 4200 \cdot 80 = 672000\text{ J}$$

Tổng nhiệt lượng cần thiết để đun ấm nước sôi là:
$$Q = Q_1 + Q_2 = 36000 + 672000 = 708000\text{ J} = 708\text{ kJ}$$

---

### Bài 5: (8 – CK 13/14)
*Đề bài:* Một bình cách nhiệt chứa $5\text{ lit}$ nước ở $40^\circ\text{C}$; thả đồng thời vào đó một khối nhôm nặng $5\text{ kg}$ đang ở $100^\circ\text{C}$ và một khối đồng nặng $3\text{ kg}$ đang ở $10^\circ\text{C}$. Tính nhiệt độ cân bằng. Cho nhiệt dung riêng của nước, nhôm, đồng lần lượt là $4200\text{ J/kg.K}$; $880\text{ J/kg.K}$; $380\text{ J/kg.K}$.

**Lời giải:**
- Khối lượng và nhiệt độ ban đầu của nước: $m_n = 5\text{ kg}$, $t_n = 40^\circ\text{C}$.
- Khối lượng và nhiệt độ ban đầu của nhôm: $m_{al} = 5\text{ kg}$, $t_{al} = 100^\circ\text{C}$.
- Khối lượng và nhiệt độ ban đầu của đồng: $m_{cu} = 3\text{ kg}$, $t_{cu} = 10^\circ\text{C}$.
- Gọi nhiệt độ cân bằng của hệ là $t^\circ\text{C}$ (với $10^\circ\text{C} < t < 100^\circ\text{C}$).

Nhiệt lượng do nhôm tỏa ra khi hạ nhiệt độ từ $100^\circ\text{C}$ xuống $t^\circ\text{C}$:
$$Q_{\text{tỏa}} = m_{al} \cdot c_{al} \cdot (100 - t) = 5 \cdot 880 \cdot (100 - t) = 4400(100 - t)$$

Nhiệt lượng do nước và đồng thu vào khi tăng nhiệt độ từ $40^\circ\text{C}$ và $10^\circ\text{C}$ lên $t^\circ\text{C}$:
$$Q_{\text{thu}} = [m_n \cdot c_n \cdot (t - 40)] + [m_{cu} \cdot c_{cu} \cdot (t - 10)]$$
$$Q_{\text{thu}} = [5 \cdot 4200 \cdot (t - 40)] + [3 \cdot 380 \cdot (t - 10)]$$
$$Q_{\text{thu}} = 21000(t - 40) + 1140(t - 10)$$

Áp dụng phương trình cân bằng nhiệt ($Q_{\text{tỏa}} = Q_{\text{thu}}$):
$$4400(100 - t) = 21000(t - 40) + 1140(t - 10)$$
$$440000 - 4400t = 21000t - 840000 + 1140t - 11400$$
$$440000 + 840000 + 11400 = (21000 + 1140 + 4400)t$$
$$1291400 = 26540t \implies t \approx 48,66^\circ\text{C}$$

---

## 2. BÀI TẬP VỀ PHA TRỘN VÀ ĐỔI NHIỆT ĐỘ NƯỚC

### BÀI 1: (9 – DH)
*Đề bài:*
1. Nước máy có nhiệt độ $22^\circ\text{C}$. Muốn có $20\text{ lit}$ nước ở nhiệt độ $35^\circ\text{C}$, để tắm cho con, một chị đã mua $4\text{ lit}$ nước có nhiệt độ $99^\circ\text{C}$. Hỏi:
a. Lượng nước nóng đó có đủ không? Thừa hay thiếu bao nhiêu?
b. Nếu dùng hết cả $4\text{ lit}$ nước sôi, thì được bao nhiêu nước ấm?
2. Người ta pha $3\text{ lit}$ nước ở $15^\circ\text{C}$ với $1\text{ lit}$ nước ở $35^\circ\text{C}$ tìm nhiệt độ cuối cùng của hỗn hợp (bỏ qua sự trao đổi nhiệt với môi trường và bình chứa).

**Lời giải:**
**Phần 1:**
a) Gọi khối lượng nước máy là $m_1$, nhiệt độ $t_1 = 22^\circ\text{C}$. Nước nóng $m_2 = 4\text{ kg}$, nhiệt độ $t_2 = 99^\circ\text{C}$. Hướng tới tổng khối lượng $m = 20\text{ kg}$ ở nhiệt độ $t = 35^\circ\text{C}$.
Ta có phương trình cân bằng nhiệt:
$$m_2 \cdot c \cdot (t_2 - t) = m_1 \cdot c \cdot (t - t_1)$$
$$4 \cdot (99 - 35) = m_1 \cdot (35 - 22) \implies 4 \cdot 64 = 13m_1 \implies m_1 = \frac{256}{13} \approx 19,69\text{ kg}$$
Tổng lượng nước yêu cầu là $m_1 + m_2 = 19,69 + 4 = 23,69\text{ kg} > 20\text{ kg}$. Vậy lượng nước nóng đó là <u>đủ</u>.

b) Nếu dùng hết $4\text{ lit}$ nước sôi ($m_2 = 4\text{ kg}$) pha với nước ở $22^\circ\text{C}$ để tạo tổng khối lượng $20\text{ kg}$ nước ấm, gọi nhiệt độ cân bằng là $t'$:
$$m_2 \cdot (t_2 - t') = m_1 \cdot (t' - t_1) \implies 4(99 - t') = 16(t' - 22)$$
$$396 - 4t' = 16t' - 352 \implies 20t' = 748 \implies t' = 37,4^\circ\text{C}$$

**Phần 2:**
Pha $3\text{ lit}$ nước ($m_1 = 3\text{ kg}$, $t_1 = 15^\circ\text{C}$) với $1\text{ lit}$ nước ($m_2 = 1\text{ kg}$, $t_2 = 35^\circ\text{C}$):
$$m_1 \cdot (t - t_1) = m_2 \cdot (t_2 - t)$$
$$3 \cdot (t - 15) = 1 \cdot (35 - t) \implies 3t - 45 = 35 - t \implies 4t = 80 \implies t = 20^\circ\text{C}$$

---

### Câu 4: (8- BM 13/14 và 8 – CD 13/14)
*Đề bài:* Có hai bình cách nhiệt. Bình 1 chứa $m_1 = 2\text{ kg}$ nước ở $t_1 = 20^\circ\text{C}$, bình 2 chứa $m_2 = 4\text{ kg}$ nước ở $t_2 = 60^\circ\text{C}$. Người ta rót một lượng nước $m$ từ bình 1 sang bình 2, sau khi cân bằng nhiệt, người ta lại rót một lượng nước $m$ như thế từ bình 2 sang bình 1. Nhiệt độ cân bằng ở bình 1 lúc này là $t = 22^\circ\text{C}$.
a) Tính lượng nước $m$ trong mỗi lần rót và nhiệt độ cân bằng ở bình 2.
b) Ngay sau đó trút toàn bộ nước ở bình 1 vào bình 2 thì nhiệt độ cân bằng của nước trong bình 2 là bao nhiêu?

**Lời giải:**
- **Lần 1:** Rót $m$ kg nước từ bình 1 ($20^\circ\text{C}$) sang bình 2 chứa $4\text{ kg}$ nước ở $60^\circ\text{C}$.
Gọi nhiệt độ cân bằng ở bình 2 sau lần 1 là $t_{21}$.
Phương trình cân bằng nhiệt cho bình 2:
$$m \cdot (t_{21} - 20) = 4 \cdot (60 - t_{21})$$

- **Lần 2:** Rót ngược lại lượng nước $m$ từ bình 2 (đang ở nhiệt độ $t_{21}$) về bình 1 (đang chứa $2 - m$ kg nước ở $20^\circ\text{C}$). Nhiệt độ cân bằng ở bình 1 lúc này là $t_1' = 22^\circ\text{C}$.
Phương trình cân bằng nhiệt cho bình 1:
$$m \cdot (t_{21} - 22) = (2 - m) \cdot (22 - 20) \implies m(t_{21} - 22) = 2(2 - m)$$

Giải hệ phương trình ta thu được lượng nước rót mỗi lần là **$m = 0,5\text{ kg}$** và nhiệt độ cân bằng bình 2 sau lần 1 là **$t_{21} = 52^\circ\text{C}$**.

---

## 3. BÀI TẬP VỀ HỢP KIM VÀ ĐO NHIỆT LƯỢNG KẾ

### Câu 4: (8 – CV 13/14 & 8 - TT)
*Đề bài:* Người ta bỏ một miếng hợp kim chì và kẽm có khối lượng $50\text{ g}$ ở nhiệt độ $136^\circ\text{C}$ vào một nhiệt lượng kế chứa $50\text{ g}$ nước ở $14^\circ\text{C}$. Biết nhiệt độ khi có cân bằng nhiệt là $18^\circ\text{C}$ và muốn cho riêng nhiệt lượng kế nóng thêm lên $1^\circ\text{C}$ thì cần $65,1\text{ J}$; nhiệt dung riêng của nước, chì và kẽm lần lượt là $4190\text{ J/(kg.K)}$, $130\text{ J/(kg.K)}$ và $210\text{ J/(kg.K)}$. Bỏ qua sự trao đổi nhiệt với môi trường bên ngoài. Hỏi có bao nhiêu gam chì và bao nhiêu gam kẽm trong miếng hợp kim?

**Lời giải:**
- Gọi khối lượng của chì là $m_{Pb}$ và khối lượng của kẽm là $m_{Zn}$. Ta có:
$$m_{Pb} + m_{Zn} = 50\text{ g} = 0,05\text{ kg} \implies m_{Zn} = 0,05 - m_{Pb}$$
- Nhiệt độ ban đầu của hợp kim: $t_1 = 136^\circ\text{C}$.
- Nhiệt độ ban đầu của nước và nhiệt lượng kế: $t_2 = 14^\circ\text{C}$.
- Nhiệt độ cân bằng: $t = 18^\circ\text{C}$.
- Nhiệt dung của nhiệt lượng kế: $C_{nlk} = 65,1\text{ J/K}$ (vì cần $65,1\text{ J}$ để nhiệt lượng kế tăng $1^\circ\text{C}$).

Nhiệt lượng do miếng hợp kim tỏa ra:
$$Q_{\text{tỏa}} = (m_{Pb} \cdot c_{Pb} + m_{Zn} \cdot c_{Zn}) \cdot (t_1 - t)$$
$$Q_{\text{tỏa}} = [m_{Pb} \cdot 130 + (0,05 - m_{Pb}) \cdot 210] \cdot (136 - 18) = [130m_{Pb} + 10,5 - 210m_{Pb}] \cdot 118$$
$$Q_{\text{tỏa}} = (10,5 - 80m_{Pb}) \cdot 118 = 1239 - 9440m_{Pb}$$

Nhiệt lượng do nước và nhiệt lượng kế thu vào:
$$Q_{\text{thu}} = (m_n \cdot c_n + C_{nlk}) \cdot (t - t_2)$$
$$Q_{\text{thu}} = (0,05 \cdot 4190 + 65,1) \cdot (18 - 14) = (209,5 + 65,1) \cdot 4 = 274,6 \cdot 4 = 1098,4\text{ J}$$

Áp dụng phương trình cân bằng nhiệt ($Q_{\text{tỏa}} = Q_{\text{thu}}$):
$$1239 - 9440m_{Pb} = 1098,4 \implies 9440m_{Pb} = 140,6 \implies m_{Pb} \approx 0,0149\text{ kg} \approx 14,9\text{ g}$$
Khối lượng kẽm:
$$m_{Zn} = 50 - 14,9 = 35,1\text{ g}$$

---

## 4. BÀI TẬP NÂNG CAO VỀ LỰC ĐẨY ARCHIMEDES VÀ ĐÒN BẨY TRONG NHIỆT HỌC

### Câu 2 (9 – CK):
*Đề bài:* Một bình hình trụ có bán kính đáy $R_1 = 20\text{ cm}$ được đặt thẳng đứng chứa nước ở nhiệt độ $t_1 = 20^\circ\text{C}$. Người ta thả một quả cầu bằng nhôm có bán kính $R_2 = 10\text{ cm}$ ở nhiệt độ $t_2 = 40^\circ\text{C}$ vào bình thì khi cân bằng mực nước trong bình ngập chính giữa quả cầu. Cho khối lượng riêng của nước $D_1 = 1000\text{ kg/m}^3$, của nhôm $D_2 = 2700\text{ kg/m}^3$, nhiệt dung riêng của nước $C_1 = 4200\text{ J/kg.K}$ và của nhôm $C_2 = 880\text{ J/kg.K}$. Bỏ qua sự trao đổi nhiệt với bình và với môi trường.
a. Tìm nhiệt độ của nước khi cân bằng nhiệt.
b. Đổ thêm dầu ở nhiệt độ $t_3 = 15^\circ\text{C}$ vào bình cho vừa đủ ngập quả cầu. Biết khối lượng riêng và nhiệt dung riêng của dầu $D_3 = 800\text{ kg/m}^3$ và $C_3 = 2800\text{ J/kg.K}$. Xác định: Nhiệt độ của hệ khi cân bằng nhiệt? Áp lực của quả cầu lên đáy bình?

**Lời giải tóm tắt:**
- Thể tích quả cầu nhôm bán kính $R_2 = 0,1\text{ m}$:
$$V = \frac{4}{3}\pi R_2^3 = \frac{4}{3}\pi (0,1)^3 = \frac{4\pi}{3000}\text{ m}^3$$
- Khối lượng quả cầu nhôm:
$$m_2 = V \cdot D_2 = \frac{4\pi}{3000} \cdot 2700 = 3,6\pi\text{ kg}$$
- Do ngập chính giữa quả cầu nên thể tích phần ngập trong nước bằng nửa thể tích quả cầu: $V_{nc} = \frac{V}{2}$.
- Tính toán khối lượng nước chiếm chỗ và lập phương trình cân bằng nhiệt cho hệ thu - tỏa để tìm nhiệt độ cân bằng $t$.

---

Chúc bạn học tập thật tốt và đạt kết quả cao với các bài tập nhiệt học này!