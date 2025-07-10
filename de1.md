#### **Câu 1: Tìm kích thước hình chữ nhật để chu vi nhỏ nhất**

Để một hình chữ nhật có diện tích không đổi là $100 \text{ cm}^2$ mà chu vi nhỏ nhất, thì hình chữ nhật đó phải là **hình vuông**.

* **Giải thích:**
    * Gọi chiều dài là $l$ và chiều rộng là $w$.
    * Diện tích: $S = l \times w = 100 \Rightarrow w = \frac{100}{l}$.
    * Chu vi: $P = 2(l + w) = 2(l + \frac{100}{l})$.
    * Để tìm chu vi nhỏ nhất, ta khảo sát hàm số $P(l)$ và tìm cực tiểu. Đạo hàm $P'(l) = 2(1 - \frac{100}{l^2})$.
    * $P'(l) = 0 \Leftrightarrow l^2 = 100 \Leftrightarrow l = 10$ cm.
    * Khi đó, $w = \frac{100}{10} = 10$ cm.

* **Đáp án:** Kích thước của hình chữ nhật là **10 cm x 10 cm**.

---

#### **Câu 2: Tìm cạnh huyền của tam giác có diện tích lớn nhất**

* **Phân tích:**
    * Gọi một cạnh góc vuông là $a$ và cạnh huyền là $c$. Ta có $a + c = 120$ cm.
    * Cạnh góc vuông còn lại, $b$, được tính bằng định lý Pytago: $b = \sqrt{c^2 - a^2}$.
    * Diện tích tam giác: $A = \frac{1}{2}ab = \frac{1}{2}a\sqrt{c^2 - a^2}$.
    * Thay $c = 120 - a$ vào, ta có $A(a) = \frac{1}{2}a\sqrt{(120-a)^2 - a^2} = \frac{1}{2}a\sqrt{14400 - 240a}$.
    * Để $A$ lớn nhất, ta tìm giá trị của $a$ để $A^2(a) = \frac{1}{4}a^2(14400 - 240a)$ lớn nhất.
    * Xét hàm $f(a) = 14400a^2 - 240a^3$. Lấy đạo hàm và cho bằng 0, ta tìm được $a=40$ cm.

* **Tính cạnh huyền:**
    * Khi cạnh góc vuông $a = 40$ cm, cạnh huyền $c = 120 - a = 120 - 40 = 80$ cm.

* **Đáp án:** Cạnh huyền của tấm gỗ là **80 cm**.

---

#### **Câu 3: Tìm diện tích lớn nhất của mảnh đất**

* **Phân tích:**
    * Gọi chiều rộng của mảnh đất là $w$ (hai cạnh cần rào) và chiều dài là $l$ (cạnh song song với bờ giậu).
    * Chiều dài hàng rào: $L = l + 2w = 180$ m $\Rightarrow l = 180 - 2w$.
    * Diện tích mảnh đất: $A = l \times w = (180 - 2w)w = 180w - 2w^2$.
    * Đây là một parabol có bề lõm quay xuống, diện tích $A$ lớn nhất tại đỉnh.

* **Tính toán:**
    * Hoành độ đỉnh: $w = -\frac{b}{2a} = -\frac{180}{2(-2)} = 45$ m.
    * Chiều dài tương ứng: $l = 180 - 2(45) = 90$ m.
    * Diện tích lớn nhất: $A_{max} = 90 \times 45 = 4050 \text{ m}^2$.

* **Đáp án:** Mảnh đất có diện tích lớn nhất bằng **4050 m²**.

---

#### **Câu 4: Tìm kích thước mảnh đất để diện tích lớn nhất**

Để một hình chữ nhật có chu vi không đổi là $800$ m mà diện tích lớn nhất, thì hình chữ nhật đó phải là **hình vuông**.

* **Giải thích:**
    * Gọi chiều dài là $l$ và chiều rộng là $w$.
    * Chu vi: $P = 2(l+w) = 800 \Rightarrow l+w=400 \Rightarrow l=400-w$.
    * Diện tích: $A = l \times w = (400-w)w = 400w - w^2$.
    * Hàm diện tích $A(w)$ là một parabol có bề lõm quay xuống, đạt giá trị lớn nhất tại đỉnh.
    * $w = -\frac{b}{2a} = -\frac{400}{2(-1)} = 200$ m.
    * Khi đó, $l = 400 - 200 = 200$ m.

* **Đáp án:** Anh ta nên chọn mảnh đất hình vuông có kích thước **200 m x 200 m**.

---

#### **Câu 5: Tìm kích thước mương "Thủy động học"**

Dạng "Thủy động học" có nghĩa là với một diện tích tiết diện ngang $S$ cho trước, chu vi phần mương tiếp xúc với nước ($f$) là nhỏ nhất để giảm thiểu sự thấm nước.

* **Phân tích:**
    * Tiết diện là hình chữ nhật có đáy $x$ và chiều cao $h$.
    * Diện tích: $S = x \times h$ (hằng số).
    * Chu vi thấm nước (đáy và 2 thành bên): $f = x + 2h$.
    * Từ $S = xh \Rightarrow x = S/h$.
    * Thay vào chu vi: $f(h) = \frac{S}{h} + 2h$.
    * Lấy đạo hàm $f'(h) = -\frac{S}{h^2} + 2$.
    * $f'(h) = 0 \Leftrightarrow \frac{S}{h^2} = 2 \Leftrightarrow S = 2h^2$.
    * Mà $S = xh$, nên $xh = 2h^2$.

* **Đáp án:** Để có dạng thủy động học, **chiều rộng đáy (x) phải bằng hai lần chiều cao (h)**, tức là $x = 2h$.

---

#### **Câu 6: Tìm cạnh đáy hộp để diện tích nhỏ nhất**

* **Phân tích:**
    * Hộp đáy vuông cạnh $x$, chiều cao $h$.
    * Thể tích: $V = x^2h = 500 \text{ cm}^3 \Rightarrow h = \frac{500}{x^2}$.
    * Hộp không nắp nên diện tích vật liệu bao gồm diện tích đáy và 4 mặt bên.
    * Diện tích: $A = S_{đáy} + S_{xq} = x^2 + 4xh$.
    * Thay $h$ vào: $A(x) = x^2 + 4x(\frac{500}{x^2}) = x^2 + \frac{2000}{x}$.

* **Tính toán:**
    * Lấy đạo hàm: $A'(x) = 2x - \frac{2000}{x^2}$.
    * $A'(x) = 0 \Leftrightarrow 2x = \frac{2000}{x^2} \Leftrightarrow 2x^3 = 2000 \Leftrightarrow x^3 = 1000$.
    * $x = 10$ cm.

* **Đáp án:** Giá trị của $x$ để diện tích mảnh các tông nhỏ nhất là **10 cm**.

---

#### **Câu 7: Tìm thể tích lớn nhất của hình trụ nội tiếp hình cầu**

* **Phân tích:**
    * Gọi hình cầu có bán kính $R$. Hình trụ nội tiếp có bán kính đáy $r$ và chiều cao $h$.
    * Mối liên hệ giữa $R, r, h$ (xét tam giác vuông trong mặt cắt): $R^2 = r^2 + (\frac{h}{2})^2$.
    * Thể tích hình trụ: $V = \pi r^2 h$.
    * Từ mối liên hệ trên, ta có $r^2 = R^2 - \frac{h^2}{4}$.
    * Thay vào thể tích: $V(h) = \pi (R^2 - \frac{h^2}{4})h = \pi(R^2h - \frac{h^3}{4})$.

* **Tính toán:**
    * Lấy đạo hàm theo $h$: $V'(h) = \pi(R^2 - \frac{3h^2}{4})$.
    * $V'(h) = 0 \Leftrightarrow R^2 = \frac{3h^2}{4} \Leftrightarrow h = \frac{2R}{\sqrt{3}}$.
    * Khi đó, $r^2 = R^2 - \frac{1}{4}(\frac{4R^2}{3}) = \frac{2R^2}{3}$.
    * Thể tích lớn nhất: $V_{max} = \pi \times (\frac{2R^2}{3}) \times (\frac{2R}{\sqrt{3}}) = \frac{4\pi R^3}{3\sqrt{3}}$.

* **Đáp án:** Hình trụ có thể tích lớn nhất bằng $$V_{max} = \frac{4\pi R^3\sqrt{3}}{9}$$

---

#### **Câu 8: Tìm kích thước tấm tôn để thể tích thùng lớn nhất**

* **Phân tích:**
    * Gọi chiều dài và chiều rộng tấm tôn là $L$ và $W$.
    * Chu vi tấm tôn: $2(L+W) = 120 \Rightarrow L+W=60$.
    * Có hai trường hợp để cuốn tôn thành hình trụ:
        1.  Chiều cao $h=W$, chu vi đáy $C=L$.
        2.  Chiều cao $h=L$, chu vi đáy $C=W$.

* **Tính toán:**
    * **Trường hợp 1:** $h=W, C=L=2\pi r \Rightarrow r = \frac{L}{2\pi}$.
        * $V_1 = \pi r^2 h = \pi (\frac{L}{2\pi})^2 W = \frac{L^2 W}{4\pi}$.
        * Thay $W=60-L$, ta có $V_1(L) = \frac{L^2(60-L)}{4\pi}$.
        * $V_1$ lớn nhất khi $L^2(60-L)$ lớn nhất. Khảo sát hàm số này ta được $L=40$ cm.
        * Khi đó $W = 20$ cm.
    * **Trường hợp 2:** $h=L, C=W=2\pi r \Rightarrow r = \frac{W}{2\pi}$.
        * $V_2 = \pi r^2 h = \pi (\frac{W}{2\pi})^2 L = \frac{W^2 L}{4\pi}$.
        * Thay $L=60-W$, ta có $V_2(W) = \frac{W^2(60-W)}{4\pi}$.
        * Tương tự, $V_2$ lớn nhất khi $W=40$ cm.
        * Khi đó $L = 20$ cm.

* **Kết luận:** Cả hai trường hợp đều cho cùng một thể tích lớn nhất. Kích thước tấm tôn là 40 cm và 20 cm.

* **Đáp án:** Chiều dài và chiều rộng của mảnh tôn lần lượt là **40 cm và 20 cm** (hoặc ngược lại).
Chào bạn, đây là lời giải chi tiết cho các bài toán còn lại trong đề. Các bài toán này đều là dạng tối ưu hóa, yêu cầu tìm giá trị lớn nhất hoặc nhỏ nhất bằng cách sử dụng đạo hàm.

***

### **Câu 9: Tìm thể tích lớn nhất của cái gàu**

Để tìm thể tích lớn nhất của cái gàu hình nón, ta cần xác định bán kính đáy và chiều cao của nón sao cho thể tích là cực đại, dựa trên các thông số của tấm tôn ban đầu.

* **Bước 1: Tìm thông số của hình nón**
    * Diện tích tấm tôn tròn là $A = \pi R^2 = 4\pi \text{ dm}^2 \Rightarrow R = 2 \text{ dm}$.
    * Bán kính $R=2$ dm của tấm tôn sẽ trở thành **đường sinh ($l$)** của hình nón. Vậy $l=2$ dm.
    * Gọi $r$ và $h$ lần lượt là bán kính đáy và chiều cao của hình nón. Ta có hệ thức: $l^2 = r^2 + h^2 \Rightarrow 4 = r^2 + h^2$.

* **Bước 2: Lập hàm số thể tích**
    * Thể tích hình nón: $V = \frac{1}{3}\pi r^2 h$.
    * Từ $r^2 = 4 - h^2$, ta thay vào công thức thể tích để được hàm số theo biến $h$:
        $V(h) = \frac{1}{3}\pi (4-h^2)h = \frac{\pi}{3}(4h - h^3)$, với điều kiện $0 < h < 2$.

* **Bước 3: Tìm thể tích lớn nhất**
    * Để tìm giá trị lớn nhất, ta lấy đạo hàm của $V(h)$:
        $V'(h) = \frac{\pi}{3}(4 - 3h^2)$.
    * Cho $V'(h) = 0 \Rightarrow 4 - 3h^2 = 0 \Rightarrow h^2 = \frac{4}{3} \Rightarrow h = \frac{2}{\sqrt{3}} = \frac{2\sqrt{3}}{3}$ dm.
    * Khi đó $r^2 = 4 - h^2 = 4 - \frac{4}{3} = \frac{8}{3}$.
    * Thể tích lớn nhất là:
        $V_{max} = \frac{1}{3}\pi r^2 h = \frac{1}{3}\pi \left(\frac{8}{3}\right) \left(\frac{2\sqrt{3}}{3}\right) = \frac{16\pi\sqrt{3}}{27} \text{ dm}^3$.

* **Đáp án:** Thể tích lớn nhất của cái gàu là $$V_{max} = \frac{16\pi\sqrt{3}}{27} \text{ dm}^3$$

---

### **Câu 10: Tối ưu chi phí làm đường ống**

Đây là bài toán tìm điểm C trên bờ để tổng chi phí xây dựng đường ống theo đường gấp khúc ACB là thấp nhất. 💰

* **Bước 1: Thiết lập mô hình và hàm chi phí**
    * Đặt một hệ trục tọa độ với điểm B' tại gốc (0,0). Khi đó, A ở vị trí (-9, 0) và B ở vị trí (0, 6).
    * Gọi C là điểm trên đoạn AB' có tọa độ $(-x, 0)$, với $x$ là khoảng cách từ C đến B' ($0 \le x \le 9$).
    * Đoạn đường đi trên bờ: $AC = 9 - x$ (km).
    * Đoạn đường đi dưới nước: $CB = \sqrt{(0-(-x))^2 + (6-0)^2} = \sqrt{x^2 + 36}$ (km).
    * Tổng chi phí (đơn vị 10.000 USD): $T(x) = 5 \times AC + 13 \times CB = 5(9-x) + 13\sqrt{x^2 + 36}$.

* **Bước 2: Tìm giá trị nhỏ nhất của hàm chi phí**
    * Ta cần tìm $x$ để hàm $T(x)$ đạt giá trị nhỏ nhất. Lấy đạo hàm của $T(x)$:
        $T'(x) = -5 + \frac{13x}{\sqrt{x^2+36}}$.
    * Cho $T'(x) = 0 \Rightarrow 5 = \frac{13x}{\sqrt{x^2+36}}$.
    * Bình phương hai vế: $25(x^2 + 36) = 169x^2 \Rightarrow 25x^2 + 900 = 169x^2$.
    * $144x^2 = 900 \Rightarrow x^2 = \frac{900}{144} = \frac{25}{4} \Rightarrow x = 2.5$ km.

* **Bước 3: Xác định vị trí của C**
    * Bài toán hỏi khoảng cách từ C đến A.
    * Khoảng cách AC = $9 - x = 9 - 2.5 = 6.5$ km.

* **Đáp án:** Vị trí C cách A một đoạn **6.5 km**.

---

### **Câu 11: Tìm vị trí cho góc nhìn lớn nhất**

Bài toán này yêu cầu tìm khoảng cách đứng xem $x$ để góc nhìn $\theta$ lên màn ảnh là lớn nhất. 👀

* **Bước 1: Thiết lập mô hình hình học**
    * Gọi $x$ là khoảng cách từ tầm mắt của người xem đến bức tường có treo màn ảnh.
    * Gọi B là mép dưới và C là mép trên của màn ảnh.
    * Khoảng cách từ tầm mắt đến mép dưới: $AB = 1.8$ m.
    * Khoảng cách từ tầm mắt đến mép trên: $AC = 1.8 + 1.4 = 3.2$ m.
    * Góc nhìn là $\theta$. Ta có:
        $\tan(\angle AOB) = \frac{1.8}{x}$
        $\tan(\angle AOC) = \frac{3.2}{x}$
    * Sử dụng công thức trừ của tan, ta có:
        $\tan(\theta) = \tan(\angle AOC - \angle AOB) = \frac{\tan(\angle AOC) - \tan(\angle AOB)}{1 + \tan(\angle AOC) \cdot \tan(\angle AOB)}$
        $\tan(\theta) = \frac{\frac{3.2}{x} - \frac{1.8}{x}}{1 + \frac{3.2}{x} \cdot \frac{1.8}{x}} = \frac{\frac{1.4}{x}}{1 + \frac{5.76}{x^2}} = \frac{1.4x}{x^2 + 5.76}$.

* **Bước 2: Tìm giá trị lớn nhất của góc nhìn**
    * Để góc $\theta$ lớn nhất thì $\tan(\theta)$ phải lớn nhất. Ta khảo sát hàm số $f(x) = \frac{1.4x}{x^2 + 5.76}$.
    * Lấy đạo hàm $f'(x)$ và cho bằng 0:
        $f'(x) = \frac{1.4(x^2 + 5.76) - 1.4x(2x)}{(x^2+5.76)^2} = \frac{1.4(5.76 - x^2)}{(x^2+5.76)^2}$.
    * $f'(x) = 0 \Leftrightarrow 5.76 - x^2 = 0 \Rightarrow x^2 = 5.76$.
    * $x = \sqrt{5.76} = 2.4$ m.

* **Đáp án:** Vị trí đứng cách màn ảnh để có góc nhìn lớn nhất là **2.4 m**.
