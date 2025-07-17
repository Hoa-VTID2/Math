---
## **Câu 7**

**1. Thiết lập bài toán:**
* **Tọa độ:** Đặt điểm D ở gốc tọa độ (0, 0). Khi đó, A = (0, 400), C = (800, 0).
* **Vận tốc:**
    * Vận tốc chạy: `v_chay = 30 km/h = 25/3` m/s.
    * Vận tốc bơi: `v_boi = 6 km/h = 5/3` m/s.
* **Lộ trình:** Vận động viên chạy từ A đến một điểm X trên cạnh DC, sau đó bơi từ X đến C.
    * Gọi khoảng cách DX là `x` (với `0 ≤ x ≤ 800`). Tọa độ của X là `(x, 0)`.
* **Phân tích các phương án di chuyển:**
    * **Phương án 1: Chạy thẳng từ A đến X, rồi bơi từ X đến C.**
        * Quãng đường chạy `d_chay` = `AX` = `sqrt((x-0)^2 + (0-400)^2) = sqrt(x^2 + 400^2)`.
        * Quãng đường bơi `d_boi` = `XC` = `800 - x`.
        * Tổng thời gian di chuyển là: `T(x) = d_chay / v_chay + d_boi / v_boi`
            `T(x) = (sqrt(x^2 + 160000)) / (25/3) + (800 - x) / (5/3)`
            `T(x) = (3/25) * sqrt(x^2 + 160000) + (3/5) * (800 - x)`
    * **Phương án 2: Chạy dọc bờ A → D → X, rồi bơi dọc bờ X → C.**
        * Quãng đường chạy `d_chay` = `AD + DX = 400 + x`.
        * Quãng đường bơi `d_boi` = `XC = 800 - x`.
        * Tổng thời gian di chuyển là: `T(x) = (400 + x) / (25/3) + (800 - x) / (5/3)`
            `T(x) = (1200 + 3x)/25 + (2400 - 3x)/5 = (13200 - 12x)/25`.

**2. Tìm thời gian ngắn nhất:**
* Đối với **Phương án 1**, để tìm giá trị nhỏ nhất của `T(x)`, ta lấy đạo hàm:
    `T'(x) = (3/25) * (x / sqrt(x^2 + 160000)) - 3/5 = (3/5) * [x / (5*sqrt(x^2 + 160000)) - 1]`
    Vì `sqrt(x^2 + 160000) > sqrt(x^2) = x`, nên `x / (5*sqrt(x^2 + 160000)) < 1/5`. Do đó, `T'(x)` luôn âm. Hàm số `T(x)` luôn nghịch biến. Thời gian ngắn nhất đạt được khi `x` lớn nhất, tức `x = 800`.
* Đối với **Phương án 2**, `T(x)` là một hàm tuyến tính có hệ số góc âm `(-12/25)`. Do đó, hàm số luôn nghịch biến. Thời gian ngắn nhất cũng đạt được khi `x` lớn nhất, tức `x = 800`.

Cả hai phương án đều cho kết quả tối ưu là chọn **`x = 800` m**, nghĩa là **điểm X trùng với điểm C**. Lộ trình nhanh nhất là chạy toàn bộ quãng đường.

**3. Trả lời câu hỏi:**
Câu hỏi là: "Hỏi nên chọn điểm X cách A gần bằng bao nhiêu mét".
* Vì điểm X tối ưu trùng với C, ta cần tính khoảng cách từ C đến A.
* Khoảng cách `AC = sqrt((800-0)^2 + (0-400)^2) = sqrt(800^2 + 400^2) = sqrt(640000 + 160000) = sqrt(800000)`.
* `AC = 400 * sqrt(5) ≈ 894.4` mét.

**Đáp án:** Nên chọn điểm X cách A khoảng **894 mét**.

---
## **Câu 8**

Câu hỏi này có cách diễn đạt khá khó hiểu và có thể chứa các dữ kiện thừa hoặc bị lỗi in. Tuy nhiên, có thể suy luận câu hỏi chính dựa trên các con số được cung cấp.

**Phân tích:**
* Các dữ kiện về điểm C, vận tốc `v1`, `v2`, và mối quan hệ thời gian giữa các hành trình khác nhau (`đi bộ A->B` và `chèo A->C rồi đi bộ C->B`) dường như không liên quan đến câu hỏi cuối cùng hoặc tạo thành một bài toán không thể giải được với thông tin đã cho.
* Câu hỏi cuối cùng là: "Hỏi người đó đi bộ theo đường thẳng đã quay về A với vận tốc 3 km/h trong bao lâu?".
    * "Đi bộ theo đường thẳng đã quay về A" khả năng cao nhất là nói đến việc đi bộ trên quãng đường thẳng từ B trở về A, tức là đi dọc theo đường kính AB.

**Giải:**
1.  **Quãng đường:** Quãng đường đi bộ từ B về A là đường kính AB = **150 m**.
2.  **Vận tốc:** Vận tốc đi bộ được cho là `3 km/h`.
3.  **Đổi đơn vị vận tốc:** `3 km/h = 3000 m / 3600 s = 5/6` m/s.
4.  **Tính thời gian:**
    * Thời gian = Quãng đường / Vận tốc
    * Thời gian = `150 / (5/6) = 150 * 6 / 5 = 30 * 6 = 180` giây.

**Đáp án:** Người đó đi bộ quay về A trong **180 giây** (tức 3 phút).

---
## **Câu 9**

Đây là bài toán tìm cực trị của hàm vận tốc.

**1. Thiết lập các hàm số:**
* **Ly độ:** `s(t) = (1/3)t^3 - t^2 + ln(t^2 - t + 1)`
* **Vận tốc `v(t)`** là đạo hàm của ly độ `s(t)`:
    `v(t) = s'(t) = t^2 - 2t + (2t - 1) / (t^2 - t + 1)`
* Để tìm vận tốc lớn nhất và nhỏ nhất trên đoạn `[0, 1.6]`, ta cần xét các giá trị của `v(t)` tại hai đầu mút (`t=0`, `t=1.6`) và tại các điểm cực trị (nơi đạo hàm của vận tốc bằng 0).

**2. Tìm các điểm cực trị:**
* **Gia tốc `a(t)`** là đạo hàm của vận tốc `v(t)`:
    `a(t) = v'(t) = 2t - 2 + (-2t^2 + 2t + 1) / (t^2 - t + 1)^2`
* Điểm cực trị của vận tốc xảy ra khi `a(t) = 0`. Phương trình `a(t) = 0` là một phương trình bậc 5 phức tạp và không có nghiệm đại số đơn giản. Điều này cho thấy bài toán được thiết kế để giải bằng máy tính hoặc phương pháp số.

**3. Phân tích và kết luận:**
* **Vận tốc lớn nhất (`t_1`):** Bằng cách khảo sát hàm số (hoặc vẽ đồ thị), ta có thể thấy rằng trên đoạn `[0, 1.6]`, vận tốc đạt giá trị lớn nhất tại điểm cuối của khoảng thời gian.
    * Vậy **`t_1 = 1.6`** s.
* **Vận tốc nhỏ nhất (`t_2`):**
    * `a(0) = -1 < 0` và `a(1) = 1 > 0`, do đó có một điểm cực tiểu của vận tốc nằm trong khoảng `(0, 1)`.
    * Tại `t=0`, vận tốc đang giảm (`a(0) < 0`), nên `v(0)` không phải là giá trị nhỏ nhất.
    * Giá trị nhỏ nhất của vận tốc xảy ra tại điểm `t_2` là nghiệm của phương trình `a(t) = 0`.
* Do không thể tìm được `t_2` một cách chính xác bằng phương pháp đại số thông thường, bài toán này không thể giải quyết trọn vẹn nếu không có công cụ tính toán.

**Kết luận:** Dựa trên phân tích, `t_1 = 1.6`. Tuy nhiên, `t_2` là nghiệm của một phương trình phức tạp cần được giải bằng phương pháp số, do đó không thể cung cấp giá trị chính xác cho `t_1 - t_2`.

---
## **Câu 12**

Ta sẽ phân tích tính đúng sai của từng phát biểu.
* `s_1(t) = sin(t)`
* `s_2(t) = sin(t + pi/3)`

**a) Tại thời điểm ban đầu hai chất điểm cách nhau một khoảng bằng 50 cm.**
* Thời điểm ban đầu là `t = 0`.
* `s_1(0) = sin(0) = 0`.
* `s_2(0) = sin(pi/3) = sqrt(3)/2`.
* Khoảng cách `D = |s_2(0) - s_1(0)| = sqrt(3)/2` m ≈ `0.866` m = `86.6` cm.
* `86.6 cm ≠ 50 cm`.
* ➡️ **Phát biểu (a) là Sai.**

**b) Khoảng cách giữa hai chất điểm được xác định bởi hằng số `d = s_1 - s_2` (m).**
* Khoảng cách `D(t) = |s_1(t) - s_2(t)| = |sin(t) - sin(t + pi/3)|`.
* Sử dụng công thức biến đổi tổng thành tích: `sin(A) - sin(B) = 2*cos((A+B)/2)*sin((A-B)/2)`.
* `D(t) = |2 * cos(t + pi/6) * sin(-pi/6)| = |2 * cos(t + pi/6) * (-1/2)| = |-cos(t + pi/6)| = |cos(t + pi/6)|`.
* Khoảng cách này là một hàm số theo thời gian `t`, không phải là hằng số.
* ➡️ **Phát biểu (b) là Sai.**

**c) Trong 6 giây đầu tiên, có hai thời điểm mà vận tốc của hai chất điểm bằng nhau.**
* Vận tốc: `v_1(t) = s_1'(t) = cos(t)` và `v_2(t) = s_2'(t) = cos(t + pi/3)`.
* Cho `v_1(t) = v_2(t)` ⇒ `cos(t) = cos(t + pi/3)`.
* Điều này xảy ra khi `t = -(t + pi/3) + 2kπ` ⇒ `2t = -pi/3 + 2kπ` ⇒ `t = -pi/6 + kπ`.
* Ta tìm các giá trị của `t` trong khoảng `[0, 6]`:
    * `k = 1`: `t = -pi/6 + π = 5π/6 ≈ 2.62` s (thuộc khoảng [0, 6]).
    * `k = 2`: `t = -pi/6 + 2π = 11π/6 ≈ 5.76` s (thuộc khoảng [0, 6]).
    * `k = 3`: `t = -pi/6 + 3π ≈ 8.9` s (không thuộc khoảng).
* Có đúng 2 thời điểm vận tốc bằng nhau.
* ➡️ **Phát biểu (c) là Đúng.**

**d) Trong 6 giây đầu tiên, khoảng cách xa nhất của hai chất điểm là 100 cm.**
* Khoảng cách `D(t) = |cos(t + pi/6)|`.
* Giá trị lớn nhất của hàm `|cos(x)|` là 1.
* Do đó, khoảng cách xa nhất có thể là 1 m = 100 cm.
* Ta cần kiểm tra xem giá trị này có đạt được trong 6 giây đầu tiên không. Khoảng cách bằng 1 khi `cos(t + pi/6) = ±1`, tức là `t + pi/6 = nπ`.
* `t = nπ - pi/6`.
    * `n = 1`: `t = π - pi/6 = 5π/6 ≈ 2.62` s (thuộc khoảng [0, 6]).
    * `n = 2`: `t = 2π - pi/6 = 11π/6 ≈ 5.76` s (thuộc khoảng [0, 6]).
* Vì khoảng cách lớn nhất (1m = 100cm) đạt được trong 6 giây đầu tiên.
* ➡️ **Phát biểu (d) là Đúng.**
