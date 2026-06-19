# NGUYỄN HÀM. TÍCH PHÂN

## §1

# NGUYÊN HÀM

### A. KIẾN THỨC CẤN NHỚ

Cho K là một khoảng, đoạn hoặc nữa khoảng của tập số thực.

### 1. Khái niệm nguyên hàm

• Cho hàm số $f(x)$ xác định trên K. Hàm số $F(x)$ được gọi là nguyên hàm của hàm số $f(x)$ trên K nếu $F'(x) = f(x)$ với mọi x thuộc K.

- Già sử hàm số  $ F(x) $ là một nguyên hàm của hàm số  $ f(x) $ trên K. Khi đó:

- Với mỗi hàng số C, hàm số G(x) = F(x) + C cũng là một nguyên hàm của hàm số f(x) trên K.

- Ngược lại, với mỗi nguyên hàm  $ H(x) $ của hàm số  $ f(x) $ trên K thời tồn tại hàng số C sao cho  $ H(x) = F(x) + C $ với mọi x thuộc K.

Họ (hay tập hợp) tất cả các nguyên hàm của hàm số  $ f(x) $ trên K được ki hiệu là  $ \int f(x)dx $.

##### Nhận xét

• Nếu  $ F(x) $ là một nguyên hàm của hàm số  $ f(x) $ trên K thì mọi nguyên hàm của hàm số  $ f(x) $ trên K đều có dạng  $ F(x) + C $ với C là một hãng số.

Vi vây,  $ \int f(x)dx = F(x) + C. $

Mọi hàm số liên tục trên K đều có nguyên hàm trên K.

 $$ \bullet \quad \int F^{\prime}(x)\mathrm{d}x=F(x)+C. $$ 

•  $ \int 0 \, dx = C $ và khi quy ước  $ \int 1 \, dx = \int dx $, ta có  $ \int dx = x + C $.

Chú ý: Biểu thức  $ f(x) $ dx gọi là vi phần của nguyên hàm  $ F(x) $, ki hiệu là  $ dF(x) $. Vậy  $ dF(x) = F'(x)dx = f(x)dx $.

### 2. Tính chất của nguyên hàm

Cho các hàm số y = f(x), y = g(x) liên tục trên K.

• ∫ kf(x)dx = k ∫ f(x)dx với k là hẳng số khác 0.

•  $ \int[f(x)+g(x)]\mathrm{d}x=\int f(x)\mathrm{d}x+\int g(x)\mathrm{d}x. $

 $$ \bullet \quad \int[f(x)-g(x)]\mathrm{d}x=\int f(x)\mathrm{d}x-\int g(x)\mathrm{d}x. $$ 

## B. ví dụ

#### Vấn đề 1. Kiểm tra một hàm số là nguyên hàm của hàm số cho trước

Phương pháp: Sử dụng khái niệm nguyên hàm.

Ví dụ 1) Hàm số  $ F(x) = x^2 + x + 1 $ có là một nguyên hàm của hàm số  $ f(x) = 2x + 1 $ trên Ứ hay không? Vì sao?

Giải

Ta có:  $ F'(x) = (x^2 + x + 1)' = 2x + 1 $. Suy ra  $ F'(x) = f(x) $ với mọi x thuộc. Vây  $ F(x) = x^2 + x + 1 $ là một nguyên hàm của hàm số  $ f(x) = 2x + 1 $ trên.

Ví dụ 2) Hàm số  $ F(x) = \cos x $ có là một nguyên hàm của hàm số  $ f(x) = \sin x $ trên Ả hay không? Vì sao?

Giải

Ta có:  $ F'(x) = (\cos x)' = -\sin x \operatorname{khác} f(x) = \sin x. $ Vậy hàm số  $ F(x) = \cos x \operatorname{không là một nguyên hàm của hàm số  $ f(x) = \sin x \operatorname{trên} \mathbb{R}. $

##### Vấn đề 2. Tìm nguyên hàm của một hàm số

Phương pháp: Sử dụng công thức ∫F'(x)dx = F(x) + C với F(x) là hàm số có đạo hàm liên tục và các tính chất của nguyên hàm.

 $ \underline{\text{Vi du 3}} $  $ \int \cos xdx \ \text{bàng} $

A.  $ -\cos x + C. $ B.  $ -\sin x + C. $ C.  $ \cos x + C. $ D.  $ \sin x + C. $

Giải

Ta có:  $ \int \cos x \, dx = \int (\sin x)' \, dx = \sin x + C $. Chọn D.

Ví dụ 4) Tim nguyên hàm của các hàm số sau:

a)  $ x^{4} $;

b)  $ 6x^{5} + 5x^{4} $;

c)  $ \cos x - \sin x $.

Giải

Ta có:

 $$ \int x^{4}\mathrm{d}x=\int\frac{1}{5}(5x^{4})\mathrm{d}x=\frac{1}{5}\int(x^{5})^{\prime}\mathrm{d}x=\frac{1}{5}x^{5}+C\;. $$ 

 $$ \begin{aligned}b)\int(6x^{5}+5x^{\widetilde{4}})\mathrm{d}x=\int6x^{\widetilde{5}}\mathrm{d}x+\int5x^{4}\mathrm{d}x=\int(x^{6})^{\prime}\mathrm{d}x+\int(x^{5})^{\prime}\mathrm{d}x=x^{6}+x^{5}+C.\end{aligned} $$ 

 $$ \begin{aligned}&c)\int(\cos x-\sin x)\mathrm{d}x=\int\cos x\mathrm{d}x-\int\sin x\mathrm{d}x=\int\cos x\mathrm{d}x+\int(-\sin x)\mathrm{d}x\\ &=\int(\sin x)^{\prime}\mathrm{d}x+\int(\cos x)^{\prime}\mathrm{d}x=\sin x+\cos x+C.\\ \end{aligned} $$ 

Ví dụ 5) Tim nguyên hàm  $ F(x) $ của hàm số  $ f(x) = 2x + 3x^2 $, biết  $ F(0) = 1 $. Giải

 $$ \mathrm{Ta}\ \mathrm{c}\dot{\mathrm{o}};\ \int(2x+3x^{2})\mathrm{d}x=\int2x\mathrm{d}x+\int3x^{2}\mathrm{d}x=\int(x^{2})^{\prime}\mathrm{d}x+\int(x^{3})^{\prime}\mathrm{d}x=x^{2}+x^{3}+C\ . $$ 

 $$ \mathrm{Vi~F}(0)=1~\mathrm{n\hat{e}n~}0^{2}+0^{3}+C=1,\mathrm{suy~ra~}C=1. $$ 

 $$ \mathrm{V}\hat{\mathrm{a}}\mathrm{y}\;F(x)=x^{2}+x^{3}+1. $$ 

### Vấn đề 3. Ứng dụng

Trong mỗi ý a), b), c), d) ở Ví dụ 6, 7, chọn phương án: đùng (B) hoặc sai (S).

Ví dụ 6) Một vườn ươm cây cành bán một cây sau 6 năm trồng và uốn tạo dáng. Tốc độ tăng trưởng của cây đó trong suốt 6 năm được tính xấp xỉ bởi công thức h' (t) = 1,5t + 5, trong đó h(t) (cm) là chiều cao của cây sau t (năm).

(Nguồn: R. Larson and B. Edwards, Calculus 10e, Cengage 2014).

Cây con khi được trồng cao 12 cm.

a)  $ h(t) $ là một nguyên hàm của hàm số  $ h'(t) = 1, 5t + 5 $.

b)  $ h(t) = \frac{3}{4}t^{2} + 5t + C $ với C là một hằng số.

Chịu cao của cây đỏ không đổi trong 6 năm được trồng.

d) Chiều cao của cây đó khi được bán là 70 cm.

Gidi

Ta có h(t) là một nguyên hàm của hàm số h'(t) = 1,5t + 5.

nên  $ h(t) = \frac{3}{4}t^{2} + 5t + C. $

Vì cây con khi được trồng cao 12 cm nên h(0) = 12, suy ra C = 12.

 $$ \mathrm{V}\hat{\mathrm{a}}\mathrm{y}\ h(t)=\frac{3}{4}t^{2}+5t+12. $$

Sau 6 năm, chiều cao của cây đó là:  $ h(6) = \frac{3}{4} \cdot 6^2 + 5 \cdot 6 + 12 = 69 $ (cm).

Đáp án: a) Đ, b) Đ, c) S, d) S.

Ví dụ 7 Đối với các dự án xây dựng, chi phi nhân công lao động được tính theo sổ ngày công. Gọi m(t) là số lượng công nhân được sử dụng ở ngày thứ t (kể từ khi khởi công dự án). Gọi M(t) là số ngày công được tính đến hết ngày thứ t (kể từ khi khởi công dự án). Trong kinh tế xây dựng, người ta đã biết rằng M'(t) = m(t).

Một công trình xây dựng dự kiến hoàn thành trong 400 ngày. Số lượng công nhân được sử dụng cho bởi hàm số  $ m(t) = 800 - 2t $, trong đó  $ t $ tính theo ngày  $ (0 \leq t \leq 400) $,  $ m(t) $ tính theo người.

(Nguồn: A. Bigalke et al., Mathematik, Grundkurs ma-1, Cornelsen 2016).

Đơn giá cho một ngày công lao động là 400 000 đồng.

a)  $ M(t) $ là một nguyên hàm của hàm số  $ m(t) = 800 - 2t $.

 $$ b)M(t)=800t-t^{2}+C\mathrm{v o i}0\leq t\leq400\mathrm{v a}C\mathrm{l a}\mathrm{m o t}\mathrm{h a n g}\mathrm{s o}. $$ 

Số ngày công được tính đến hết ngày thứ 400 là 160 000.

d) Chi phi nhân công lao động của công trình đó (cho đến lúc hoàn thành) là 640 000 000 đồng.

Giải

Vì M'(t) = m(t) nên ta có M(t) là một nguyên hàm của hàm số m(t) = 800 - 2t.

 $$  Do\int(800-2t)dt=800\int dt-\int2t dt=800t-t^{2}+C $$ 

nên  $ M(t) = 800t - t^2 + C $ với  $ 0 \leq t \leq 400 $. Vi  $ M(0) = 0 $ nên  $ C = 0 $.

 $$ \operatorname{Vay}M(t)=800t-t^{2}. $$ 

Số ngày công được tính đến hết ngày thứ 400 là:

 $$ M(400)=800.400-400^{2}=160\ 000. $$ 

Chỉ phi nhân công lao động của công trình đó (cho đến lúc hoàn thành) là:

 $$ 400\ 000\ ,160\ 000=64\ 000\ 000\ 000\ (dòng). $$ 

Đáp án: a) Đ, b) Đ, c) Đ, d) S.

Ví dụ 8) Tại một lễ hội dân gian, tốc độ thay đổi lượng khách tham dự được biểu diễn bằng hàm số B' (t) = 20t³ - 300t² + 1 000t, trong đó t tinh bằng giờ (0 ≤ t ≤ 15), B' (t) tính bằng khách/giờ.

(Nguồn: A. Bigalke et al., Mathematik, Grundkurs ma-1, Cornelsen 2016).

Sau một giờ, 500 người đã có mặt tại lễ hội.

a) Viết công thức của hàm số B(t) biểu diễn số lượng khách tham dự lễ hội với 0 ≤ t ≤ 15.

Sau 3 giờ sẽ có bao nhiêu khách tham dự lễ hội?

Số lượng khách tham dự lễ hội lớn nhất là bao nhiêu?

d) Tại thời điểm nào thì tốc độ thay đổi lượng khách tham dự lễ hội là lớn nhất?

Giải

a) Ta có $B(t)$ là một nguyên hàm của hàm số $B'(t) = 20t^3 - 300t^2 + 1000t$.

Do $\int(20t^3 - 300t^2 + 1000t)dt = 5\int4t^3 dt - 100\int3t^2 dt + 500\int2t dt$

$= 5t^4 - 100t^3 + 500t^2 + C$

nên $B(t) = 5t^4 - 100t^3 + 500t^2 + C$.

Vì sau một giờ, 500 người đã có mặt tại lễ hội nên $B(1) = 405 + C = 500$.

Suy ra $C = 95$. Vây $B(t) = 5t^4 - 100t^3 + 500t^2 + 95$ với $0 \leq t \leq 15$.

b) Số khách tham dự lễ hội sau 3 giờ là:

 $$ B(3)=5\ ,3^{4}-100\ .3^{3}+500\ .3^{2}+95=2\ 300\ (khách). $$ 

Tại tìm giá trị lớn nhất của hàm số B(t) trên đoạn [0 ; 15]. Ta có:

 $$ B^{\prime}(t)=20t^{3}-300t^{2}+1\ 000t=20t(t^{2}-15t+50)=20t(t-5)(t-10). $$ 

Suy ra B'(t) = 0 khi t bằng 0, 5 hoặc 10.

 $$ \mathrm{Ta~c0:}\;B(0)=95,\;B(5)=3\;220,\;B(10)=95,\;B(15)=28\;220. $$ 

Khi đó, giá trị lớn nhất của hàm số B(t) trên đoạn [0 ; 15] bằng 28 220 tại t = 15. Vậy số lượng khách tham dự lễ hội lớn nhất là 28 220 khách sau 15 giờ.

d) Ta tìm t (để hàm số B'(t) đạt giá trị lớn nhất trên đoạn [0 ; 15]. Ta có:

 $$ B^{~}(t)=60t^{2}-600t+1\ 000.\  Suy ra B^{~}(t)=0\  khi t\ ḿ\ \mathrm{b}\ \mathrm{a}\ \mathrm{ng}\ \frac{15-5\sqrt{3}}{3}\ \mathrm{h}\ \mathrm{o}\ \mathrm{a}\ \mathrm{c}\ \frac{15+5\sqrt{3}}{3}. $$ 

 $$ \mathrm{Ta}\ \mathrm{c}\dot{\mathrm{o}}:B^{\prime}(0)=0;\ B^{\prime}\left(\frac{15-5\sqrt{3}}{3}\right)\approx962,25;\ B^{\prime}\left(\frac{15+5\sqrt{3}}{3}\right)\approx-962,25; $$ 

 $$ B^{\prime}(15)=15\ 000. $$ 

Khi đó, giá trị lớn nhất của hàm số B'(t) trên đoạn [0 ; 15] bằng 15 000 tại t = 15. Vậy tốc độ thay đổi lượng khách tham dự lễ hội là lớn nhất tại thời điểm 15 giờ.

## C. BÀI TẬP

1. Hàm số  $ y = x^{20} $ là nguyên hàm của hàm số:

A.  $ y = x^{19} $. B.  $ y = 20x^{21} $. C.  $ y = 20x^{19} $. D.  $ y = \frac{x^{21}}{21} $.

2. Hàm số y = sin 2x là nguyên hàm của hàm số:

A.  $ y = \cos 2x $. B.  $ y = 2\cos 2x $. C.  $ y = -\cos 2x $. D.  $ y = \frac{-\cos 2x}{2} $.

3. Hàm số  $  y = \ln(x^2 + 1)  $ là nguyên hàm của hàm số:

A.  $  y = \frac{1}{x^2 + 1}  $.

B.  $  y = \frac{1}{2x(x^2 + 1)}  $.

C.  $  y = \frac{2x}{x^2 + 1}  $.

D.  $  y = \frac{2}{x^2 + 1}  $.

4. Hàm số $y = e^{-5x + 4}$ là nguyên hàm của hàm số:

A. $y = \frac{1}{e^{-5x + 4}}$, B. $y = e^{-5x + 4}$, C. $y = \frac{e^{-5x + 4}}{-5}$, D. $y = -5e^{-5x + 4}$.

5. Hàm số  $ y = \log x $ là nguyên hàm của hàm số:

A.  $ y = \frac{1}{x} $. B.  $ y = \frac{1}{x \ln 10} $. C.  $ y = \frac{\ln 10}{x} $. D.  $ y = \frac{1}{x \log 10} $.

Trong mỗi ý a), b), c), d) ở câu 6, 7, 8, chọn phương án: đùng (Đ) hoặc sai (S).

6. Cho hàm số  $ f(x) = 4x^3 - 3x^2 $.

a)  $ \int f(x) \, dx = \int 4x^3 \, dx - \int 3x^2 \, dx $.

b)  $ f'(x) = 12x^2 - 6x $.

c)  $ f'(x) = x^4 - x^3 $.

d)  $ \int f(x) \, dx = x^4 + x^3 + C $.

7. Cho hàm số $f(x) = \sin x + \cos x$.

a) $\int f(x) \, dx = \int \sin x \, dx + \int \cos x \, dx$.

b) $f'(x) = \cos x - \sin x$.

c) $f'(x) + f(x) = \cos x$.

d) $\int f(x) \, dx = -\cos x + \sin x + C$.

8. Cho hàm số $f(x)=(x+2)(x+1)$.

a) $f(x)=x^{2}+3x+2$.

b) $f'(x)=2x+3$.

c) $\int f(x)dx=\int(x+2)dx\cdot\int(x+1)dx$.

d) $\int f(x)dx=\frac{1}{3}x^{3}+\frac{3}{2}x^{2}+2x+C$.

9. Tim nguyên hàm của các hàm số sau:

a)  $ f(x) = 2x^2 - 4x^5 + 6 $;

b)  $ f(x) = (x + 3)(-2 - x) $;

c)  $ f(x) = \frac{x^6 - 7x^3}{x} (x > 0) $.

10. Tim nguyên hàm của các hàm số sau:

a) $f(x) = 2\sin x$;

b) $f(x) = \cos x + x^3$;

c) $f(x) = -\frac{x^4}{2} - 3\cos x$.

11*. Tim:

a) $\int 2^x \ln 2 \, dx$;

b) $\int 2x\cos(x^2) \, dx$;

c) $\int \cos^2\left(\frac{x}{2}\right) \, dx$.

$G\phi_1 y$:

a) $(2^x)' = 2^x \ln 2$;

b) $\left[\sin(x^2)\right]' = 2x\cos(x^2)$;

c) $\cos^2\left(\frac{x}{2}\right) = \frac{1 + \cos x}{2}$.

12. Tim $\int \frac{x^2 + 7x + 12}{2} \, dx$ trên $(0; +\infty)$.

13. Tim nguyên hàm $F(x)$ của hàm số $f(x)=3x^{2}-2x$, biết $F(1)=5$.

14. Tìm nguyên hàm $F(x)$ của hàm số $f(x)=4x^{3}+3x^{2}$, biết $F(1)-f'(1)=-16$.

15. Xét dao động điều hoà của một chất điểm có vận tốc tức thời tại thời điểm t là:  $ v(t) = -0.2\pi\sin(\pi t) $, trong đó, t tính bằng giây,  $ v(t) $ tính bằng m/s. Tim phương trình li độ  $ x(t) $, biết  $ v(t) $ là đạo hàm của  $ x(t) $ và  $ x(0) = 0.2 $ (m).

### §2

## NGUYỄN HÀM CỦA MỘT SỐ HÀM SỐ SỐ CẤP

## A. KIẾN THỨC CẤN NHỚ

Băng nguyên hàm của một số hàm số sơ cấp:

## B. ví dụ

Vấn đề 1. Tìm nguyên hàm của hàm số

Ví dụ 1) Tìm:

 $$ \int x^{\sqrt{2}}\mathrm{d}x; $$ 

 $$ \int\frac{4}{x^{3}}\mathrm{d}x; $$ 

 $$ \int\frac{-2}{3}\sqrt{x^{\frac{3}{4}}}\mathrm{d}x; $$ 

 $$ \int\left(x^{\frac{1}{4}}+\frac{1}{2}x^{-2}\right)\mathrm{d}x. $$ 

a)  $ \int x^{\sqrt{2}}dx = \frac{x^{\sqrt{2}+1}}{\sqrt{2}+1} + C. $

 $$ \int\frac{4}{x^{3}}\mathrm{d}x=4\int x^{-3}\mathrm{d}x=4\cdot\frac{x^{-2}}{-2}+C=-\left.2x^{-2}+C\right. $$ 

 $$ \int\frac{-2}{3}\sqrt{x^{\frac{3}{4}}}\mathrm{d}x=\frac{-2}{3}\int x^{\frac{3}{8}}\mathrm{d}x=\frac{-2}{3}\cdot\frac{x^{\frac{11}{8}}}{\frac{11}{8}}+C=\frac{-16x^{\frac{11}{8}}}{33}+C. $$ 

 $$ \mathrm{d)}\int\left(x^{\frac{1}{4}}+\frac{1}{2}x^{-2}\right)\mathrm{d}x=\int x^{\frac{1}{4}}\mathrm{d}x+\frac{1}{2}\int x^{-2}\mathrm{d}x=\frac{x^{\frac{5}{4}}}{\frac{5}{4}}+\frac{1}{2}\cdot\frac{x^{-1}}{-1}+C=\frac{4}{5}x^{\frac{5}{4}}-\frac{1}{2x}+C. $$

$ \frac{\overline{Vi}du2}{a)\int\frac{1}{-x}dx; $ b) $ \int\frac{4}{11x}dx; $ c) $ \int\frac{x^{3}-1}{x}dx. $

a)  $ \int \frac{1}{x} dx = -\int \frac{1}{x} dx = -\ln|x| + C. $

b)  $ \int\frac{4}{11x}dx=\frac{4}{11}\int\frac{1}{x}dx=\frac{4}{11}\ln|x|+C. $

 $$ \int\frac{x^{3}-1}{x}\mathrm{d}x=\int\left(x^{2}-\frac{1}{x}\right)\mathrm{d}x=\int x^{2}\mathrm{d}x-\int\frac{1}{x}\mathrm{d}x=\frac{x^{3}}{3}-\ln|x|+C. $$ 

 $ \overline{Vi du 3} $ Tim:

a)  $ \int(-\cos x)dx, $

b)  $ \int\frac{1-\cos^{2}x}{\cos^{2}x}dx, $

c)  $ \int(3\sin x - 4\cos x)dx $; d)  $ \int(7 + 5\cot^{2}x)dx $.

Giải

a)  $ \int (-\cos x)dx = -\int \cos xdx = -\sin x + C. $

 $$ \int\frac{1-\cos^{2}x}{\cos^{2}x}\mathrm{d}x=\int\left(\frac{1}{\cos^{2}x}-1\right)\mathrm{d}x=\int\frac{1}{\cos^{2}x}\mathrm{d}x-\int\mathrm{d}x=\tan x-x+C. $$ 

c)  $ \int(3\sin x - 4\cos x)dx = \int3\sin xdx - \int4\cos xdx = 3\int\sin xdx - 4\int\cos xdx = 3(-\cos x) - 4\sin x + C = -3\cos x - 4\sin x + C. $

d)  $ \int(7 + 5\cot^2 x)dx = \int[2 + 5(1 + \cot^2 x)]dx = \int(2 + 5 \cdot \frac{1}{\sin^2 x})dx = 2\int dx + 5\int \frac{1}{\sin^2 x}dx = 2x - 5\cot x + C. $

 $ \overline{Vi \, du \, 4} $ Tim:

a)  $ \int e^{4x+1} \, dx $, b)  $ \int 2^{4x+3} \, dx $, c)  $ \int \frac{1}{7^{x+1}} \, dx $, d)  $ \int (e^x + x^e) \, dx $.

 $$ \begin{align*}\int e^{4x+1}\mathrm{d}x=e\int(e^4)^x\mathrm{d}x=e\ .\frac{(e^4)^x}{\ln e^4}+C=\frac{e^{4x+1}}{4}+C.\end{align*} $$ 

 $$ \int2^{4x+3}\mathrm{d}x=8\int2^{4x}\mathrm{d}x=8\int(2^{4})^{x}\mathrm{d}x=8\int16^{x}\mathrm{d}x=8\cdot\frac{16^{x}}{\ln16}+C=\frac{2^{4x+1}}{\ln2}+C. $$

$$ \begin{aligned}c)\int\frac{1}{7^{x+1}}\mathrm{d}x=\frac{1}{7}\int\frac{1}{7^{x}}\mathrm{d}x=\frac{1}{7}\int\left(\frac{1}{7}\right)^{x}\mathrm{d}x=\frac{1}{7}\cdot\frac{\left(\frac{1}{7}\right)^{x}}{\ln\frac{1}{7}}+C=\frac{-1}{7^{x+1}\ln7}+C.\end{aligned} $$ 

 $$ \mathrm{d})\int(e^{x}+x^{e})\mathrm{d}x=\int e^{x}\mathrm{d}x+\int x^{e}\mathrm{d}x=e^{x}+\frac{x^{e+1}}{e+1}+C. $$ 

##### Vấn đề 2. Ứng dụng

Ví dụ 5) Cây cả chua khi trồng có chiều cao 5 cm. Tốc độ tăng chiều cao của cây cả chua sau khi trồng được cho bối hàm số v(t) = -0,1t³ + t², trong đó t tính theo tuần, v(t) tính bằng centimet/tuần. Gọi h(t) (tính bằng centimet) là độ cao của cây cả chua ở tuần thứ t (Nguồn: A. Bigalke et al., Mathematik, Grundkurs ma-1, Cornelsen 2016).

a) Viết công thức xác định hàm số h(t) (t≥ 0).

Giai đoan tăng trưởng của cây cà chua đó kéo dài bao lâu?

Chịu cao tối đa của cây cà chua đó là bao nhiêu centimet? (Làm tròn kết quả đến hàng phần mười).

Vào thời điểm cây của chua đó phát triển nhanh nhất thi cây của chua cao bao nhiêu centimet? (Làm tròn kết quả đến hàng phần mười).

Giải

a) Ta có:  $ \int(-0,1t^{3} + t^{2})dt = \int-0,1t^{3}dt + \int t^{2}dt = \frac{-t^{4}}{40} + \frac{t^{3}}{3} + C. $

Do  $ h(t) $ là một nguyên hàm của  $ v(t) $ nên  $ h(t) = \frac{-t^{4}}{40} + \frac{t^{3}}{3} + C $

Cây cả chua khi trồng có chiều cao 5 cm nên  $ h(0) = 5 $, suy ra  $ C = 5. $

Vây  $ h(t) = \frac{-t^{4}}{40} + \frac{t^{3}}{3} + 5 $,  $ t \geq 0. $

b) Cây tăng trưởng khi  $ v(t) > 0 $. Xét bất phương trình  $ -0,1t^{3} + t^{2} > 0 $.

Ta có:  $ t^{2}(-0,1t+1)>0 $, suy ra  $ -0,1t+1>0 $ nên  $ t<10 $.

Vây giai đoạn tăng trưởng của cây kéo dài 10 tuần.

c) Ta chi cần tim giá trị lớn nhất của  $ h(t) = \frac{-t^4}{40} + \frac{t^5}{3} + 5 $ với  $ t \in [0, 10] $.

Ta có:  $ h'(t) = \frac{-t^3}{10} + t^2 = \frac{t^2}{10}(-t + 10) $, suy ra  $ h'(t) = 0 $ khi t bằng 0 hoặc 10.

Ta thấy  $ h(0) = 5 $,  $ h(10) = \frac{265}{3} $. Khi đó,  $ h(t) $ đạt giá trị lớn nhất bằng  $ \frac{265}{3} $ trên đoạn [0; 10].

Vậy chiều cao tối da của cây cả chua đó là  $ \frac{265}{3} \approx 88.3 $ (cm).

d) Ta chi cần tìm giá trị lớn nhất của hàm số v(t) = -0,1t3 + t2 với t ∈ [0 ; 10].

Ta có:  $ v'(t) = -0.3t^2 + 2t = -0.3t\left(t - \frac{20}{3}\right) $, suy ra  $ v'(t) = 0 $ khi t bằng 0 hoặc  $ \frac{20}{3} $.

Ta thấy  $ v(0) = 0 $,  $ v\left(\frac{20}{3}\right) = \frac{400}{27} $,  $ v(10) = 0 $. Khi đó,  $ v(t) $ đạt giá trị lớn nhất bằng  $ \frac{400}{27} $ trên đoạn  $ [0; 10] $ tại  $ t = \frac{20}{3} $. Ta có:  $ h\left(\frac{20}{3}\right) = \frac{4405}{81} \approx 54.4 $.

Vây vào thời điểm cây cá chua đó phát triển nhanh nhất thì cây cá chua cao 54,4 cm.

Ví dụ 6) Trong mỗi ý a), b), c), d), chọn phương án: đùng (Đ) hoặc sai (S).

Một quần thể vi khuẩn ban đầu gồm 500 vi khuẩn, sau đó bắt đầu tăng trưởng. Gọi P(t) là số lượng vi khuẩn của quần thể đó tại thời điểm t, trong đó t tính theo ngày (0 ≤ t ≤ 10). Tốc độ tăng trưởng của quần thể vi khuẩn đó cho bởi hàm số P'(t) = k√t, trong đó k là hằng số. Sau 1 ngày, số lượng vi khuẩn của quần thể đó đã tăng lên thành 600 vi khuẩn.

(Nguồn: R. Larson and B. Edwards, Calculus 10e, Cengage 2014).

a)  $ P(t) $ là một nguyên hàm của hàm số  $ f(t) = k\sqrt{t} $.

b)  $ P(t) = \frac{2k}{3} \sqrt{t^3} + C $ với  $ 0 \leq t \leq 10 $ và  $ k, C $ là hằng số.

 $$ P(t)=100\sqrt{t^{3}}+500\mathrm{~v~o~i~}0\leq t\leq10. $$ 

d) Số lượng vi khuẩn của quần thể đó sau 7 ngày là 3 352 con. Giải

Ta có:  $ \int k\sqrt{t}dt = k\int\sqrt{t}dt = k\int t^{\frac{1}{2}}dt = \frac{2k}{3}t^{\frac{3}{2}} + C. $

Vì  $ P'(t) = k\sqrt{t} $ nên  $ P(t) $ là một nguyên hàm của hàm số  $ f(t) = k\sqrt{t} $, suy ra

 $$ P(t)=\frac{2k}{3}t^{\frac{3}{2}}+C=\frac{2k}{3}\sqrt{t^{3}}+C(0\leq t\leq10). $$ 

Do quản thế vi khuẩn ban đầu gồm 500 vi khuẩn nên  $ P(0) = 500 $, suy ra

 $$ P(t)=\frac{2k}{3}\sqrt{t^{3}}+500. $$ 

Sau 1 ngày, số lượng vi khuẩn của quần thế đó đã tăng lên thành 600 vi khuẩn, suy ra

 $$ \frac{2k}{3}\cdot\sqrt{1^{3}}+500=600\Leftrightarrow k=150. $$

Từ đó, ta có:  $ P(t) = 100\sqrt{t^3} + 500 $ ( $ 0 \leq t \leq 10 $). Vậy số lượng vi khuẩn của quần thế đó sau 7 ngày là  $ P(7) = 100 $.  $ \sqrt{7^3} + 500 \approx 2352 $ (vi khuẩn).

Đáp án: a) Đ, b) Đ, c) Đ, d) S.

## C. BÀI TẬP

16.  $ \int \sin(-x)dx $ bǎng:

A.  $ \sin x + C. $ B.  $ \cos x + C. $ C.  $ -\sin x + C. $ D.  $ -\cos x + C. $

17.  $ \int \cos(-x)dx $ bǎng:

A.  $ \sin x + C. $ B.  $ \cos x + C. $ C.  $ -\sin x + C. $ D.  $ -\cos x + C. $

18.  $ \int_{\sin^2(-x)}^{\frac{1}{2}} dx $ bǎng:

A.  $ \tan x + C. $ B.  $ \cot x + C. $ C.  $ -\tan x + C. $ D.  $ -\cot x + C. $

19.  $ \int \frac{1}{\cos^2(-x)} dx $ bǎng:

A.  $ \tan x + C. $

B.  $ \cot x + C. $

C.  $ -\tan x + C. $

D.  $ -\cot x + C. $

20.  $ \int 17^{x} dx $ bǎng:

A.  $ 17^{x}\ln17. $ B.  $ \frac{17^{x}}{\ln17}. $ C.  $ 17^{x}\ln17+C. $ D.  $ \frac{17^{x}}{\ln17}+C. $

21. Cho hàm số $f(x)=\frac{x^7+8}{x}$

a) $f(x)=x^6+\frac{8}{x}$

b) $\int f(x)dx=\int x^6dx-\int\frac{8}{x}dx$

c) $\int f(x)dx=\int x^6dx+\int\frac{8}{x}dx$

d) $\int f(x)dx=\frac{x^7}{7}+8\ln|x|$

22. Cho hàm số  $ f(x) = \frac{\sin 3x + \sin x}{\sin 2x} $.

b)  $  f(x) = 2\cos x  $.

c)  $ \int f(x)dx = 2\int \cos xdx. $

d)  $ \int f(x)dx = -2\sin x + C. $

23. Tim:

a)  $ \int x^{\frac{1}{3}}dx; $

b)  $ \int\sqrt{\frac{1}{x^{7}}}dx; $

c)  $ \int\frac{1}{\sqrt[3]{x^{\frac{4}{5}}}}dx; $

d)  $ \int\left(x-\frac{1}{x}\right)^{2}dx; $

e)  $ \int\frac{(x-3)(x+1)}{x}dx; $

g)  $ \int\left(3x^{2}-\frac{4}{x}\right)(2x+5)dx. $

24. Tim:

a)  $ \int e^{5x} \, dx; $

b)  $ \int \frac{1}{2024^x} \, dx; $

c)  $ \int (2^x + x^2) \, dx; $

d)  $ \int (2^x \cdot 3^{2x+1}) \, dx; $

e)  $ \int \frac{3^x + 4^x + 1}{5^x} \, dx. $

25. Tim:

a)  $ \int(5\sin x - 6\cos x)dx $;

b)  $ \int\sin^{2}2xdx + \int\cos^{2}2xdx $;

c)  $ \int\sin^{2}\frac{x}{2}dx $;

d)  $ \int\left(\sin\frac{x}{2} + \cos\frac{x}{2}\right)^{2}dx $;

e*)  $ \int\cos^{4}\frac{x}{2}dx - \int\sin^{4}\frac{x}{2}dx $;

g*)  $ \int\tan^{2}xdx $.

## §3 TÍCH PHÂN

## A. KIẾN THỨC CẤN NHỚ

### 1. Định nghĩa tích phần

Cho $f(x)$ là hàm số liên tục trên đoạn [a ; b]. Giả sử $F(x)$ là một nguyên hàm của $f(x)$ trên đoạn [a ; b].

Hiệu số  $ F(b) - F(a) $ được gọi là tích phân từ  $ a $ đến  $ b $ của hàm số  $ f(x) $, ki hiệu là  $ \int\limits_{a}^{b} f(x) \, dx $.

Chú ý

- Kí hiệu $F(x)\Big|_{a}^{b}=F(b)-F(a)$ và độc là $F(x)$ thể cận từ $a$ đến $b$.

Vây $\int\limits_{a}^{b}f(x)\mathrm{d}x=F(x)\Big|_{a}^{b}=F(b)-F(a)$

• Ta quy ước:  $ \int\limits_{a}^{a}f(x)dx = 0 $;  $ \int\limits_{a}^{b}f(x)dx = -\int\limits_{b}^{a}f(x)dx $.

### 2. Tính chất của tích phân

Cho các hàm số y = f(x), y = g(x) liên tục trên đoạn [a ; b]. Ta có:

 $$ \bullet \int\limits_{a}^{b}kf(x)\mathrm{d}x=k\int\limits_{a}^{b}f(x)\mathrm{d}x\ (k\mathrm{~là~hàng~sô}). $$ 

 $$ \bullet \int\limits_{a}^{b}[f(x)+g(x)]\mathrm{d}x=\int\limits_{a}^{b}f(x)\mathrm{d}x+\int\limits_{a}^{b}g(x)\mathrm{d}x. $$ 

 $$ \bullet \quad \int\limits_{a}^{b}[f(x)-g(x)]\mathrm{d}x=\int\limits_{a}^{b}f(x)\mathrm{d}x-\int\limits_{a}^{b}g(x)\mathrm{d}x. $$ 

• Với c là số thực tuy ý thuộc đoạn [a; b], ta có:  $ \int\limits_{a}^{b}f(x)dx = \int\limits_{a}^{c}f(x)dx + \int\limits_{c}^{b}f(x)dx. $

### 3. Tích phân của một số hàm số sơ cấp

• Với α ≠ -1, ta có:  $ \int_{a}^{b} x^{\alpha} \, dx = \frac{x^{\alpha+1}}{\alpha+1}\bigg|_{a}^{b} = \frac{b^{\alpha+1} - a^{\alpha+1}}{\alpha+1} $.

• Với hàm số  $ f(x)=\frac{1}{x} $ liên tục trên đoạn  $ [a;b] $, ta có:

 $$ \int\limits_{a}^{b}\frac{1}{x}\mathrm{d}x=\ln\left|x\right|_{a}^{b}=\ln\left|b\right|-\ln\left|a\right|. $$ 

•  $ \int\limits_{a}^{b}\sin x dx = -\left.\cos x\right|_{a}^{b} = \cos a - \cos b. $

 $$ \bullet \quad \int\limits_{a}^{b}\cos x\mathrm{d}x=\sin x\Big|_{a}^{b}=\sin b-\sin a. $$ 

- Với hàm số  $ f(x) = \frac{1}{\sin^2 x} $ liên tục trên  $ [a; b] $, ta có:

$$ \int\limits_{a}^{b}\frac{1}{\sin^{2}x}\mathrm{d}x=-\left.\cot x\right|_{a}^{b}=\cot a-\cot b. $$ 

• Với hàm số $f(x)=\frac{1}{\cos^{2}x}$ liên tục trên $[a;b]$, ta có:

 $$ \int\limits_{a}^{b}\frac{1}{\cos^{2}x}\mathrm{d}x=\left.\tan x\right|_{a}^{b}=\tan b-\tan a. $$ 

• Với  $ a > 0 $,  $ a \neq 1 $, ta có:  $ \int_{\alpha}^{\beta} a^{x} \, dx = \frac{a^{x}}{\ln a} \bigg|_{\alpha}^{\beta} = \frac{a^{\beta} - a^{\alpha}}{\ln a} $.

Đặc biệt  $ \int\limits_{a}^{b}e^{x}dx=e^{x}\bigg|_{a}^{b}=e^{b}-e^{a} $.

## B. ví dụ

##### Vấn đề 1. Tính tích phân

 $ \overline{Vi \, du \, I} $ Tính:

a)  $ \int_{0}^{1} x^{6} \, dx $;

b)  $ \int_{1}^{4} \frac{x^{3}}{\sqrt{x}} \, dx $.

Giải

a)  $ \int_{0}^{1}x^{6}dx=\frac{x^{7}}{7}\bigg|_{0}^{1}=\frac{1}{7}. $

b)  $ \int_{1}^{4}\frac{x^{3}}{\sqrt{x}}dx=\int_{1}^{4}x^{\frac{5}{2}}dx=\left.\frac{2}{7}x^{\frac{7}{2}}\right|_{1}^{4}=\frac{256}{7}-\frac{2}{7}=\frac{254}{7}. $

Vi dụ 2 Tính:

a)  $ \int_{2}^{4}\frac{2}{x}dx; $

b)  $ \int_{\frac{\pi}{6}}^{\frac{\pi}{3}}(\sin x + \cos x)dx; $

c)  $ \int_{-\frac{\pi}{4}}^{\frac{\pi}{4}}\frac{-1}{\cos^{2}x}dx. $

Giải

 $$ \begin{aligned}&\text{Ⅲ }\int_{2}^{4}\frac{2}{x}\mathrm{d}x=2\int_{2}^{4}\frac{1}{x}\mathrm{d}x=2\ln\left|x\right|_{2}^{4}=2(\ln4-\ln2)=2\ln2.\end{aligned} $$ 

 $$ \begin{aligned}b)\int_{\frac{\pi}{6}}^{\frac{\pi}{3}}(\sin x+\cos x)d x&=(-\cos x+\sin x)\Bigg|_{\frac{\pi}{6}}^{\frac{\pi}{3}}=\left(-\frac{1}{2}+\frac{\sqrt{3}}{2}\right)-\left(-\frac{\sqrt{3}}{2}+\frac{1}{2}\right)=\sqrt{3}-1.\end{aligned} $$

$$ \begin{aligned}&c)\int\frac{\frac{\pi}{4}}{-\frac{\pi}{4}}\frac{-1}{\cos^{2}x}\mathrm{d}x=-\int\frac{\frac{\pi}{4}}{-\frac{\pi}{4}}\frac{1}{\cos^{2}x}\mathrm{d}x=-\tan x\bigg|_{-\frac{\pi}{4}}^{\frac{\pi}{4}}=-1-1=-2.\end{aligned} $$ 

Ví dụ 3 Tính:

 $$ \int\limits_{0}^{1}e^{-2x}\mathrm{d}x; $$ 

 $$ \int_{-1}^{0}\frac{1}{2^{3x}}\mathrm{d}x $$ 

 $$ \int\limits_{0}^{1}(2^{2x}\cdot3^{x-1})\mathrm{d}x $$ 

 $$ \int\limits_{0}^{1}\frac{2^{x+1}}{3^{x}}\mathrm{d}x. $$ 

 $$ \int\limits_{0}^{1}e^{-2x}\mathrm{d}x=\int\limits_{0}^{1}\left(e^{-2}\right)^{x}\mathrm{d}x=\left.\frac{\left(e^{-2}\right)^{x}}{\ln(e^{-2})}\right|_{0}^{1}=-\frac{1}{2}e^{-2x}\bigg|_{0}^{1}=-\frac{1}{2e^{2}}+\frac{1}{2}. $$ 

 $$ \int_{-1}^{0}\frac{1}{2^{3x}}\mathrm{d}x=\int_{-1}^{0}\left(2^{-3}\right)^{x}\mathrm{d}x=\frac{\left(2^{-3}\right)^{x}}{\ln(2^{-3})}\bigg|_{-1}^{0}=\frac{-2^{-3x}}{3\ln2}\bigg|_{-1}^{0}=\frac{-1}{3\ln2}+\frac{8}{3\ln2}=\frac{7}{3\ln2}. $$ 

 $$ \begin{aligned}c)\int_{0}^{1}(2^{2x}\cdot3^{x-1})\mathrm{d}x=\frac{1}{3}\int_{0}^{1}12^{x}\mathrm{d}x=\left.\frac{1}{3}\cdot\frac{12^{x}}{\ln12}\right|_{0}^{1}=\frac{4}{\ln12}-\frac{1}{3\ln12}=\frac{11}{3\ln12}.\end{aligned} $$ 

 $$ \mathrm{d})\int_{0}^{1}\frac{2^{x+1}}{3^{x}}\mathrm{d}x=2\int_{0}^{1}\left(\frac{2}{3}\right)^{x}\mathrm{d}x=2\cdot\left.\frac{\left(\frac{2}{3}\right)^{x}}{\ln\frac{2}{3}}\right|_{0}^{1}=\frac{\frac{4}{3}}{\ln\frac{2}{3}}-\frac{2}{\ln\frac{2}{3}}=-\frac{2}{3(\ln2-\ln3)}. $$ 

 $$ \underbrace{\overline{Vi}\;d\mu\;4}_{}\;\mathrm{C h o}\;\int\limits_{-2}^{1}f(x)\mathrm{d}x=-\;4,\;\int\limits_{1}^{5}f(x)\mathrm{d}x=6\;.{\mathrm{T i n h}}\;\int\limits_{-2}^{5}f(x)\mathrm{d}x. $$ 

 $$ \begin{aligned}c\dot{0}:\int\limits_{-2}^{5}f(x)d x=\int\limits_{-2}^{1}f(x)d x+\int\limits_{1}^{5}f(x)d x=-4+6=2.\end{aligned} $$ 

### Vấn đề 2. Ứng dụng

Ví dụ 5) Một vật chuyển động với vận tốc v(t) = 5 - 2cos t (m/s). Tinh quãng đường vật chuyển động trong khoảng thời gian từ lúc t = 0 (s) đến t =  $ \frac{\pi}{2} $ (s). Giải

Ta có công thức tính quãng đường vật đi được là  $ s = \int_{0}^{\frac{\pi}{2}} v(t)dt $.

Vậy quăng đường vật chuyển động được là:

 $$ s=\int\limits_{0}^{\frac{\pi}{2}}(5-2\cos t)\mathrm{d}t=\left(5t-2\sin t\right)\Bigg|_{0}^{\frac{\pi}{2}}=\frac{5\pi}{2}-2\ \left(\mathrm{m}\right). $$ 

Ví dụ 6) Một vật chuyển động với vận tốc v(t) được cho bởi đồ thị như Hình 1.

a) Tinh quăng đường vật đi được từ lúc t = 1 (s) đến lúc t = 3 (s).

b) Tính quăng đường vật đi được trong 4 giây đâu tiền.

Giải. (Hình 2)

<div style="text-align: center;">Hình 1</div>

a) Dựa vào đồ thị, hàm số biểu diễn vận tốc của vật từ lúc t = 1 đến lúc t = 3 là v(t) = 1. Suy ra quăng đường vật đi được trong khoảng thời gian đó là:

 $$ s=\int\limits_{1}^{3}v(t)\mathrm{d}t=\int\limits_{1}^{3}1\mathrm{d}t=\left.t\right|_{1}^{3}=2\left(\mathrm{m}\right). $$ 

b) Quăng dường vật di được trong 4 giấy đâu tiên là:

<div style="text-align: center;">Hinh 2</div>

 $$ \begin{aligned}g&=\int\limits_{0}^{4}v(t)\mathrm{d}t=\int\limits_{0}^{1}v(t)\mathrm{d}t+\int\limits_{1}^{3}v(t)\mathrm{d}t+\int\limits_{3}^{4}v(t)\mathrm{d}t\\&=\int\limits_{0}^{1}t\mathrm{d}t+\int\limits_{1}^{3}1\mathrm{d}t+\int\limits_{3}^{4}(-t+4)\mathrm{d}t\\&=\left.\frac{t^{2}}{2}\right|_{0}^{1}+t\left|_{1}\right|^{3}+\left(\frac{-t^{2}}{2}+4t\right)\left|_{3}\right|^{4}=\frac{1}{2}+2+\frac{1}{2}=3(m).\end{aligned} $$ 

## C. BÀI TẬP

26. Cho $f(x)$ là hàm số liên tục trên đoạn [a; b]. Giá sử $F(x)$, $G(x)$ là các nguyên hàm của $f(x)$ trên đoạn [a; b]. Trong các phát biểu sau, phát biểu nào sai?

A. $F(a) - F(b) = G(a) - G(b)$.

B. $\int\limits_{a}^{b} f(x) \, dx = F(b) - F(a)$.

C. $\int\limits_{a}^{b} f(x) \, dx = f(b) - f(a)$.

D. $\int\limits_{a}^{b} f(x) \, dx = G(b) - G(a)$.

27. Phát biểu nào sau đây là đúng?

A.  $ \int_{a}^{b} x^{\alpha} \, dx = b^{\alpha+1} - a^{\alpha+1} $.

B.  $ \int_{a}^{b} x^{\alpha} \, dx = \alpha(b^{\alpha-1} - a^{\alpha-1}) $.

C.  $ \int_{a}^{b} x^{\alpha} \, dx = \frac{b^{\alpha+1} - a^{\alpha+1}}{\alpha+1} \quad (\alpha \neq -1) $.

D.  $ \int_{a}^{b} x^{\alpha} \, dx = \frac{b^{\alpha+1} - a^{\alpha+1}}{\alpha} \quad (\alpha \neq 0) $.

28. Phát biểu nào sau đây là đúng?

A.  $ \int_{a}^{b}\sin x dx = \sin a - \sin b. $

B.  $ \int_{a}^{b}\sin x dx = \sin b - \sin a. $

C.  $ \int_{a}^{b}\sin x dx = \cos a - \cos b. $

D.  $ \int_{a}^{b}\sin x dx = \cos b - \cos a. $

29. Phát biểu nào sau đây là đúng? Biết $f(x)=\frac{1}{\sin^{2}x}$ liên tục trên [a; b].

A. $\int\limits_{a}^{b}\frac{1}{\sin^{2}x}dx=\cot a-\cot b$.

B. $\int\limits_{a}^{b}\frac{1}{\sin^{2}x}dx=\cot b-\cot a$.

C. $\int\limits_{a}^{b}\frac{1}{\sin^{2}x}dx=\tan a-\tan b$.

D. $\int\limits_{a}^{b}\frac{1}{\sin^{2}x}dx=\tan b-\tan a$.

30. Phát biểu nào sau đây là đúng?

A.  $ \int e^{x}dx = e^{b+1} - e^{a+1} $.

B.  $ \int e^{x}dx = e^{a+1} - e^{b+1} $.

C.  $ \int e^{x}dx = e^{b} - e^{a} $.

D.  $ \int e^{x}dx = e^{a} - e^{b} $.

31. Tich phân  $ \int_{a}^{b}\frac{1}{x}dx $ bằng:

A.  $ \ln b - \ln a. $ B.  $ |\ln b| - |\ln a|. $ C.  $ \ln |b| - \ln |a| $ D.  $ \ln |a| - \ln |b| $

32. Tich phân  $ \int_{1}^{2}-3\frac{x^{3}}{x^{3}}dx $ có giá trị bằng:

A.  $ \frac{9}{8} $. B.  $ -\frac{45}{64} $. C.  $ \frac{15}{8} $. D.  $ -\frac{9}{8} $.

33. Tich phân  $ \int_{1}^{2} \frac{1}{x\sqrt{x}} dx $ có giá trị bằng:

A.  $ 2 - \sqrt{2} $. B.  $ 2 + \sqrt{2} $. C.  $ \frac{-\sqrt{2} + 8}{20} $. D.  $ \frac{-\sqrt{2} - 8}{20} $.

34. Nếu  $ \int\limits_{0}^{1}f(x)dx = 4 $ thi  $ \int\limits_{0}^{1}2f(x)dx $ bằng:

A. 16. B. 4. C. 2. D. 8.

35. Nếu  $ \int_{1}^{2} f(x) \, dx = -2 $ và  $ \int_{2}^{3} f(x) \, dx = 1 $ thì  $ \int_{1}^{3} f(x) \, dx $ bằng:

A. -3. B. -1. C. 1. D. 3.

36. Cho  $ \int\limits_{2}^{3}f(x)dx = 3 $ và  $ \int\limits_{2}^{3}g(x)dx = 1 $. Khi đó  $ \int\limits_{2}^{3}[f(x) + g(x)]dx $ bằng:

A. 4.

B. 2.

C. -2.

D. 3.

37. Trong mỗi ý a), b), c), d), chọn phương đàn: đùng (Đ) hoặc sai (S

Cho f(x) là hàm số có đạo hàm cấp hai liên tục trên đoạn [a; b].

a)  $ \int\limits_{a}^{b}f''(x)dx = f'(b) - f'(a) $.

b)  $ \int\limits_{a}^{b}f''(x)dx = f(b) - f(a) $.

c)  $ \int\limits_{a}^{b}f''(x)dx = f'(a) - f'(b) $.

d)  $ \int\limits_{a}^{b}f''(x)dx = f(a) - f(b) $.

38. Nêu một vi dụ chi ra rằng  $ \int\limits_{a}^{b}\frac{f(x)}{g(x)}dx \neq \frac{a}{b} $ với  $ f(x) $ và  $ g(x) $ liên tục trên

đoạn [a; b],  $ g(x) \neq 0 \forall x \in [a; b] $.

39. Cho $\int\limits_{-1}^{2}g(x)dx=6$, $G(x)$ là một nguyên hàm của hàm số $g(x)$ trên đoạn $[-1;2]$ và $G(-1)=8$. Tính $G(2)$.

40. Cho $\int_{-2}^{1}f(x)\mathrm{d}x=5$ và $\int_{-2}^{1}g(x)\mathrm{d}x=-4$. Tinh:

a) $\int_{-1}^{2}f(x)\mathrm{d}x$, b) $\int_{-2}^{1}-4f(x)\mathrm{d}x$, c) $\int_{-2}^{1}\frac{-2g(x)}{3}\mathrm{d}x$, d) $\int_{-2}^{1}[f(x)+g(x)]\mathrm{d}x$, e) $\int_{-2}^{1}[f(x)-g(x)]\mathrm{d}x$, g) $\int_{-2}^{1}[3f(x)-5g(x)]\mathrm{d}x$.

41. Cho $\int_{-1}^{3}f(x)dx=2$, $\int_{-2}^{3}f(x)dx=-5$. Tinh tích phân $\int_{-1}^{2}f(x)dx$.

42. Một ô tô đang chay với vận tốc 18 m/s thi người lái ô tô đap phanh, từ thời điểm đó, ô tô chuyển động chăm dần đều với vận tốc v(t) = -6t + 18 (m/s), trong đó tô là thời gian tính bằng giấy. Hỏi từ lúc đap phanh đến khi dùng hắn, ô tô di chuyển được quãng đường bằng bao nhiêu mét?

43. Một vật chuyển động với vận tốc được cho bởi đồ thị ở Hình 3.

a) Tính quảng đường mà vật di chuyển được trong 5 giây đầu tiên.

b) Tính quảng đường mà vật di chuyển được từ thời điểm 1 giây đến 5 giây.

44. Một con lắc lò xo dao động điều hoà theo phương ngang trên mặt phẳng không ma sát như Hình 4, có vận tốc tức thời cho bởi v(t) = 2cos t, trong đó t tính bằng giấy và v(t) tính bằng cm/s. Tại thời điểm t = 0, con lắc đó vị trí cân bằng.

Tinh quăng đường mà con lắc lò xo di chuyển được sau 1 giấy kế từ vị trí cân bằng theo đơn vị centimet (làm tròn kết quả đến hàng phần trăm).

<div style="text-align: center;">Hinh 3</div>

### §4

## ỨNG DỤNG HÌNH HỌC CỦA TÍCH PHÂN

### A. KIẾN THỨC CẤN NHỚ

### 1. Tính diện tích hình phẳng

• Cho hàm số y = f(x) liên tục trên đoạn [a ; b]. Khi đó, diện tích hình phẳng giới hạn bởi đồ thị hàm số y = f(x), trực hoành và hai đường thẳng x = a, x = b là:

 $$ \begin{align*}S=\int\limits_{\alpha}^b|f(x)|\mathrm{d}x.\end{align*} $$ 

• Cho các hàm số y = f(x), y = g(x) liên tục trên đoạn [a ; b]. Khi đó, diễn tích hình phảng giới hạn bởi đồ thị của các hàm số y = f(x), y = g(x) và hai đường thẳng x = a, x = b là:

 $$ S=\int\limits_{a}^{b}\left|f(x)-g(x)\right|\mathrm{d}x. $$ 

### 2. Tính thể tích hình khối

- Cắt một vật thể bởi hai mặt phẳng vương góc với trục Ox tại x = a và x = b (a < b). Một mặt phẳng tụy ý vương góc với Ox tại x (a ≤ x ≤ b) cắt vật thể đó theo hình phẳng có diện tích là S(x). Giả sử hàm số S(x) liên tục trên [a; b]. Khi đó, thể tích V của phần vật thể giới hạn bởi hai mặt phẳng trên được tính bởi công thức:

 $$ V=\int\limits_{a}^{b}S(x)\mathrm{d}x. $$ 

Chú ý: Nếu  $ S(x) = S \text{ không đổi với mỗi } x \in [a; b] \text{ thi } V = (b - a)S. $

• Cho hàm số y = f(x) liên tục, không âm trên đoạn [a; b]. Hình phảng (H) giới hạn bởi đồ thị hàm số y = f(x), trục hoành và hai đường thẳng x = a, x = b quay quanh trục Ox tạo thành một khối tròn xoay có thể tích bằng:

 $$ V=\pi\int\limits_{a}^{b}\left[f(x)\right]^{2}\mathrm{d}x. $$ 

## B. ví dụ

##### Vấn đề 1. Xác định các đường giới hạn của hình phẳng

Ví dụ 1) Cho đồ thị hàm số y = 2^{-2} và hình phẳng được tô màu như Hình 5. Hình phẳng đó được giới hạn bởi các đường nào?

##### Giải

Hình phẳng đã cho được giới hạn bởi đồ thị hàm số y = 2^{-\frac{x}{2}}, trực hoành và hai đường thẳng x = -2, x = 0.

Ví dụ 2) Cho đồ thị hàm số y = x² và hình phẳng được tô màu như Hình 6. Hình phẳng đó được giới hạn bởi các đường nào?

Giải

Đường thẳng đi qua các điểm có toạ độ (0 ; - 2) và (2 ; 0) có phương trình y = x - 2.

Hình phẳng đã cho được giới hạn bởi các đồ thị hàm số y = x², y = x - 2 và hai đường thẳng x = 0, x = 2.

#### Vấn đề 2. Tính diện tích hình phẳng

Ví dụ 3) Cho đồ thị hàm số y = e^{-2/3} và hình phẳng được tô màu như Hình 7.

a) Hình phẳng đó được giới hạn bởi các đường nào?

b) Viết công thức tính diện tích hình phẳng đó.

c) Tính diện tích hình phẳng đó.

Giải

a) Hình phẳng đã cho được giới hạn bởi đồ thi hàm số y = e^{-\frac{x}{2}}, trục hoành và hai đường thẳng x = -1, x = 0.

Hình 5

Hinh 6

<div style="text-align: center;">Hinh 7</div>

b) Diện tích hình phẳng đó được tính theo công thức  $ S = \int\limits_{-1}^{0}\left|e^{-\frac{x}{2}}\right|dx = \int\limits_{-1}^{0}e^{-\frac{x}{2}}dx. $

c) Diện tích hình phẳng đỏ là:

 $$ \mathcal{S}=\int\limits_{-1}^{0}e^{-\frac{x}{2}}\mathrm{d}x=\int\limits_{-1}^{0}\left(e^{-\frac{1}{2}}\right)^{x}\mathrm{d}x=\frac{\left(e^{-\frac{1}{2}}\right)^{x}}{\left.\ln e^{-\frac{1}{2}}\right|_{-1}^{0}}=-\left.2\left(1-e^{\frac{1}{2}}\right)\right. $$

Ví dụ 4 Cho các đồ thị hàm số y = 3ᵃ, y = x và hình phẳng được tô màu như Hình 8.

Hình phẳng đó được giới hạn bởi các đường nào?

b) Viết công thức tính diện tích hình phẳng đó.

c) Tính diện tích hình phẳng đó.

Giải

a) Hình phẳng đã cho được giới hạn bởi các đồ thị hàm số y = 3x, y = x và hai đường thẳng x = 0, x = 1.

b) Diện tích hình phẳng đó được tính theo công thức

<div style="text-align: center;">Hình 8</div>

 $$ S=\int\limits_{0}^{1}\left|3^{x}-x\right|\mathrm{d}x=\int\limits_{0}^{1}(3^{x}-x)\mathrm{d}x(v\dot{1}3^{x}>x,\forall x\in[0;1]). $$ 

c) Diện tích hình phẳng đó là:  $  S = \int_{0}^{1} (3^{x} - x) \, dx = \left( \frac{3^{x}}{\ln 3} - \frac{x^{2}}{2} \right|_{0}^{1} = \frac{2}{\ln 3} - \frac{1}{2}  $.

#### Vân dễ 3. Xác định hình phẳng quay quanh trục Ox dễ tạo thành khối tròn xoay

Ví dụ 5 Cho khối tròn xoay như Hinh 9. Hai dường cong cắt trục Oy biểu diễn bề mặt của khối là một phần của dường tròn tâm 0 bán kinh 60 cm. Hình phẳng được giới hạn bởi các đường nào để khi quay quanh trục Ox ta được khối tròn xoay như Hinh 9?

##### Giải

Vì hai đường cong cắt trục Oy biểu diễn bề mặt của khối là một phần của đường tròn tâm O bán kính 60 cm và hai mặt phẳng cắt khối vuông góc với trục Ox đi qua hai điểm có toạ độ (-40; 0), (40; 0) nên hình phẳng được giới hạn bởi đồ thị hàm số y =  $ \sqrt{3600 - x^2} $, trục hoành và hai đường thẳng x = -40, x = 40.

##### Vấn đề 4. Tính thể tích khối tròn xoay

Ví dụ 6 Cho đồ thi hàm số y = (1,5)x và khối tròn xoay như Hình 10.

a) Hình phảng được giới hạn bởi các đường nào để khi quay quanh trục Ox ta được khói tròn xoay như Hình 10?

b) Tình thế tích khói tròn xoay đó.

<div style="text-align: center;">Hình 10</div>

a) Hình phẳng được giới hạn bởi đồ thị hàm số  $ y = (1,5)^x $, trục hoành và các đường thẳng  $ x = 1 $,  $ x = 2 $.

b) Thế tích khối tròn xoay đổ là:

 $$ V=\pi\int\limits_{1}^{2}[(1,5)^{x}]^{2}\mathrm{d}x=\pi\int\limits_{1}^{2}[(1,5)^{2}]^{x}\mathrm{d}x=\frac{1,5^{2x}\pi}{2\ln(1,5)}\bigg|_{1}^{2}=\frac{45\pi}{32\ln(1,5)}. $$ 

## C. BÀI TẬP

45. Diện tích hình phẳng giới hạn bởi độ thị các hàm số $y = x^{3}$, $y = x^{2}$ và hai đường thẳng $x = 1$, $x = 3$ là:

A. $\int\limits_{1}^{3}(x^{3} - x^{2})dx$.

B. $\int\limits_{1}^{3}(x^{2} - x^{3})dx$.

C. $\int\limits_{1}^{3}x^{2}dx - \int\limits_{1}^{3}x^{3}dx$.

D. $\int\limits_{1}^{3}x^{2}dx + \int\limits_{1}^{3}x^{3}dx$.

46. Cho các hàm số $y = f(x)$, $y = g(x)$ có đồ thi lần lượt là $(P)$, $(C)$ và hình phẳng được tô màu như Hinh 11. Công thức tính diễn tích hình phẳng được tô màu là:

A. $S = \int_{-1}^{1} [g(x) - f(x)] \, dx + \int_{-1}^{2} [g(x) - f(x)] \, dx$.

B. $S = \int_{-1}^{1} [g(x) - f(x)] \, dx - \int_{-1}^{2} [g(x) - f(x)] \, dx$.

C. $S = \int_{-1}^{2} [g(x) - f(x)] \, dx$.

D. $S = \int_{-1}^{2} [f(x) - g(x)] \, dx$.

<div style="text-align: center;">Hinh II</div>

47. Cho hình phẳng giới hạn bởi đồ thị hàm số y = x, trực hoành và hai đường thẳng x = 0, x = 2 quay quanh trục Ox được khối tròn xoay có thể tích tính theo công thức là:

A.  $ \int_{0}^{\frac{\pi}{2}} x \, dx. $

B.  $ \pi \int_{0}^{\frac{\pi}{2}} x^{2} \, dx. $

C.  $ \int_{0}^{\frac{\pi}{2}} x^{2} \, dx. $

D.  $ \pi \int_{0}^{\frac{\pi}{2}} x \, dx. $

48. Trong mỗi y a, b), c), d), chọn phương án: đùng (D) hoặc sai (S).

Cho hình phẳng được tỗ màu như Hình 12. Diện tích hình phẳng được kí hiệu là S.

a) Hình phẳng đó được giới hạn bởi độ thị y = f(x), trục hoành và hai đường thẳng x = -1, x = 5.

<div style="text-align: center;">Hinh 12</div>

b)  $  S = \int_{-1}^{5} |f(x)| dx  $

c)  $  S = \int_{-1}^{1} f(x) \, dx + \int_{-1}^{5} f(x) \, dx  $

d)  $  S = \int_{-1}^{1} f(x) \, dx - \int_{-1}^{5} f(x) \, dx  $

49. Cho hình phẳng được tô màu như Hình 13.

a) Hình phẳng đó được giới hạn bởi các đường nào?

50. Cho hình phẳng được tô màu như Hình 14.

b) Tình diện tích hình phẳng đó.

a) Hình phảng đó được giới hạn bởi các đường nào?

Tình diện tích hình phẳng đó.

51. Cho hình phẳng giới hạn bởi đồ thị hàm số $y = \cos \frac{x}{2}$, trực hoành và hai đường thẳng $x = 0$, $x = \frac{\pi}{2}$. Tính thể tích khối tròn xoay tạo thành khi cho hình phẳng đó quay quanh trực Ox.

<div style="text-align: center;">Hinh 13</div>

<div style="text-align: center;">Hinh 14</div>

# BÀI TẬP CUỐI CHƯỜNG IV

52. Biết $F(x) = e^x$ là một nguyên hàm của hàm số $f(x)$ trên $\mathbb{R}$. Giá trị của $\int\limits_{0}^{1}[3 + f(x)]\,dx$ bằng:

A. $2 + e$.

B. $3 + e$.

C. $3$.

D. $3x + e^x$.

53. Phát biểu nào sau đây là đúng?

A.  $ \int_{a}^{b}\cos xdx = \sin a - \sin b. $

B.  $ \int_{a}^{b}\cos xdx = \sin b - \sin a. $

C.  $ \int_{a}^{b}\cos xdx = \cos a - \cos b. $

D.  $ \int_{a}^{b}\cos xdx = \cos b - \cos a. $

54. Phát biểu nào sau đây là dùng? Biết $f(x)=\frac{1}{\cos^{2}x}$ liên tục trên $[a;b].$

A. $\int\limits_{a}^{b}\frac{1}{\cos^{2}x}dx=\cot a-\cot b.$

B. $\int\limits_{a}^{b}\frac{1}{\cos^{2}x}dx=\cot b-\cot a.$

C. $\int\limits_{a}^{b}\frac{1}{\cos^{2}x}dx=\tan a-\tan b.$

D. $\int\limits_{a}^{b}\frac{1}{\cos^{2}x}dx=\tan b-\tan a.$

55. Cho m thoả mãn  $ m > 0 $,  $ m \neq 1 $. Phát biểu nào sau đây là dùng?

A.  $ \int_{a}^{b} m^{x} dx = m^{b} - m^{a} $.

B.  $ \int_{a}^{b} m^{x} dx = m^{a} - m^{b} $.

C.  $ \int_{a}^{b} m^{x} dx = \frac{m^{b}}{\ln m} - \frac{m^{a}}{\ln m} $.

D.  $ \int_{a}^{b} m^{x} dx = \frac{m^{a}}{\ln m} - \frac{m^{b}}{\ln m} $.

Strong mỗi ý a), b), c), d) ở câu 56, 57, 58, chọn phương án: đùng (D) hoặc sai (S).

56. Cho các hàm số y = f(x), y = g(x) liên tục trên K.

a)  $ \int[f(x) \cdot g(x)] \, dx = \int f(x) \, dx \cdot \int g(x) \, dx. $

b)  $ \int[f(x) + g(x)] \, dx = \int f(x) \, dx + \int g(x) \, dx. $

c)  $ \int[f(x) - g(x)] \, dx = \int f(x) \, dx - \int g(x) \, dx. $

d)  $ \int\frac{f(x)}{g(x)}dx = \int\frac{f(x)dx}{\int g(x)dx}. $

57. Cho đồ thị hàm số y = f(x) và gọi S là diện tích hình phẳng được tô màu như Hình 15.

<div style="text-align: center;">Hình 15</div>

58. Cho đồ thi các hàm số $y=f(x)$, $y=g(x)$ và gọi $S$ diễn tích hình phăng được tố màu như Hình 16.

a) $S=\int[f(x)-g(x)]\,dx$.

b) $S=\int[f(x)-g(x)]\,dx$.

c) $S=\int[g(x)-f(x)]\,dx$.

d) $S=\int[g(x)-f(x)]\,dx$.

<div style="text-align: center;">Hình 16</div>

59. Tim:

59. 1m:

a)  $ \int(x+1)(x^{2}-x+1)\mathrm{d}x, $

b)  $ \int x\left(2-\frac{3}{x^{3}}\right)\mathrm{d}x, $

c)  $ \int e^{-3x}\mathrm{d}x, $

d)  $ \int(2-3\tan^{2}x)\mathrm{d}x, $

e)  $ \int\frac{1}{2^{-x+1}}\mathrm{d}x; $

g)  $ \int\frac{3^{2x+1}}{2^{x}}\mathrm{d}x. $

60. Cho  $ \int\limits_{0}^{1}\left[2f(x)-1\right]\mathrm{d}x=3 $. Tinh  $ \int\limits_{0}^{1}f(x)\mathrm{d}x $.

61. Nêu một ví dụ chỉ ra rằng  $ \int[f(x) \cdot g(x)] dx \neq \int f(x) dx \cdot \int g(x) dx $ với  $ f(x) $ và  $ g(x) $ liên tục trên  $ \mathbb{R} $.

62. Cho hàm số $f(x) = 2^x$. Tim nguyên hàm $F(x)$ của hàm số $f(x)$ trên $\mathbb{R}$ sao cho $F(0) = \log_2(2e)$.

63. Tinh:

a)  $ \int\limits_{0}^{1}-2dx; $

d)  $ \int\limits_{1}^{3}2\sqrt[3]{x}dx; $

 $ \int_{0}^{1}\frac{2x}{3}dx; $

c)  $ \int_{0}^{1}x^{4}dx; $

g) $ \int\limits_{1}^{9}(x\sqrt{x}-2)dx. $

 $ \int_{1}^{2}\frac{2}{3x}dx; $

64. Tinh:

a)  $ \int_{0}^{\frac{\pi}{2}}\sin x dx $;

b)  $ \int_{0}^{\frac{\pi}{4}}\cos x dx $;

c)  $ \int_{-\frac{\pi}{4}}^{\frac{\pi}{2}}\sin^2 x dx $;

d)  $ \int_{0}^{\frac{\pi}{4}}\cos^2 x dx $;

e)  $ \int_{0}^{\frac{\pi}{2}}(\sin x - 2) dx $;

g)  $ \int_{0}^{\frac{\pi}{4}}(3\cos x + 2) dx $

65. Tinh:

a)  $ \int e^{-5x}dx; $

b)  $ \int 3^{x+2}dx; $

c)  $ \int 3^{2x}dx. $

66. Gọi H là hình phẳng giới hạn bởi đồ thị hàm số y = 2, trục hoành và hai đường thẳng x = 1, x = 2.

a) Tính diện tích S của hình phẳng H.

b) Tính thể tích V của khối tròn xoay tạo thành khi cho hình phẳng H quay quanh trục Ox.

67. Gọi H là hình phẳng giới hạn bởi đồ thị y = x² - 2x, trục hoành và hai đường thẳng x = 0, x = 2.

Tình diện tích S của hình phẳng H.

b) Tinh thế tích V của khối tròn xoay tạo thành khi cho hình phẳng H quay quanh trục Ox.

68. Một vật chuyển động với vận tốc  $ v(t) = 3 - 2\sin t \, (\text{m/s}) $, trong đó t là thời gian tính bằng giây. Tinh quăng đường vật di chuyển trong khoảng thời gian từ thời điểm  $ t = 0 \, (\text{s}) $ đến thời điểm  $ t = \frac{\pi}{4} \, (\text{s}) $.

69. Một xe ô tô đang chạy với tốc độ 72 km/h thì người lái xe bất ngờ phát hiện chương ngại vật trên đường cách đó 110 m. Người lái xe phân ứng một giây sau đó bằng cách đập phanh khẩn cấp. Kế từ thời điểm này, ô tô chuyển động chậm đần đều với tốc độ v(t) = -20t + 40 (m/s), trong đó t là thời gian tính bằng giây kế từ lúc đập phanh. Gọi s(t) là quãng đường xe ô tô đi được trong t giây kế từ lúc đập phanh.

Lập công thức biểu diễn hàm số s(t).

b) Thời gian kế từ lúc đáp phanh đến khi xe ô tô dùng hắn là bao nhiêu giấy?

c) Quảng đường xe ô tô đã di chuyển kế từ lúc người lái xe phát hiện chương ngại vật trên đường đến khi xe ô tô dùng hắn là bao nhiêu mét? Xe ô tô có va chạm với chương ngại vật trên đường hay không?

### LỜI GIẢI - HƯỚNG DẦN - ĐẠP SỐ

#### S1 NGUYÊN HÀM

1. C. 2. B. 3. C. 4. D. 5. B.

6. a) D, b) D, c) S, d) S.

7. a) D, b) D, c) S, d) D.

8. a) D, b) D, c) S, d) D.

9. a)  $ \int(2x^2 - 4x^5 + 6)dx = \int2x^2dx - \int4x^5dx + \int6dx = \frac{2}{3}x^3 - \frac{2}{3}x^6 + 6x + C $

b)  $ \int(x + 3)(-2 - x)dx = \int(-x^2 - 5x - 6)dx = -\int x^2dx - \int5xdx - \int6dx = \frac{-x^3}{3} - \frac{5x^2}{2} - 6x + C. $

c)  $ \int\frac{x^6 - 7x^3}{x}dx = \int(x^5 - 7x^2)dx = \int x^5dx - 7\int x^2dx = \frac{x^6}{6} - \frac{7x^3}{3} + C. $

10. a)  $ \int 2\sin xdx = 2\int \sin xdx = -2\cos x + C. $

b)  $ \int(\cos x + x^{3})dx = \int\cos xdx + \int x^{3}dx = \sin x + \frac{x^{4}}{4} + C. $

$$ \mathrm{c})\int\left(\frac{-x^{4}}{2}-3\cos x\right)\mathrm{d}x=-\frac{1}{2}\int x^{4}\mathrm{d}x-3\int\cos x\mathrm{d}x=-\frac{x^{5}}{10}-3\sin x+C. $$ 

11*. a)  $ \int 2^x \ln 2 \, dx = \int (2^x)' \, dx = 2^x + C $.

b)  $ \int 2x \cos(x^2) \, dx = \int [\sin(x^2)]' \, dx = \sin(x^2) + C $.

c)  $ \int \cos^2\left(\frac{x}{2}\right) \, dx = \int \frac{1 + \cos x}{2} \, dx = \frac{1}{2} \int dx + \frac{1}{2} \int \cos x \, dx = \frac{x + \sin x}{2} + C $.

12.  $ \int\frac{x^{2}+7x+12}{x+3}dx=\int\frac{(x+3)(x+4)}{x+3}dx=\int(x+4)dx=\frac{x^{2}}{2}+4x+C. $

13. Ta có:  $ \int(3x^{2}-2x)dx=\int3x^{2}dx-\int2xdx=x^{3}-x^{2}+C. $

Vi  $ F(1)=5\ln1^{3}-1^{2}+C=5, $ suy ra C=5. Vây  $ F(x)=x^{3}-x^{2}+5. $

14. Ta có:

 $$ \begin{aligned}&\int(4x^{3}+3x^{2})\mathrm{d}x=\int4x^{3}\mathrm{d}x+\int3x^{2}\mathrm{d}x=x^{4}+x^{3}+C\mathrm{\  và \ }f^{\prime}(x)=12x^{2}+6x.\\ &Vi F(1)-f^{\prime}(1)=-16\mathrm{n}\mathrm{en}1^{4}+1^{3}+C-12.1^{2}-6.1=-16,\mathrm{s u y}\mathrm{r a}C=0.\\ &V\mathrm{a}y F(x)=x^{4}+x^{3}.\\ \end{aligned} $$ 

15. Ta có:  $ \int v(t)dt = \int -0.2\pi\sin(\pi t)dt = -0.2\pi\int\sin(\pi t)dt = 0.2\cos(\pi t) + C $.

Do  $ x'(t) = v(t) $ nên  $ x(t) $ là một nguyên hàm của  $ v(t) $. Vi  $ x(0) = 0.2 $ nên  $ C = 0 $.

Vây  $ x(t) = 0.2\cos(\pi t) $.

#### S2 NGUYÊN HÀM CỦA MỘT SỐ HÀM SỐ SỐ CẤP

16. B. 17. A. 18. D. 19. A. 20. D.

21. a) D, b) S, c) D, d) S.

22. a) D, b) D, c) D, d) S.

23. a)  $ \int x^{\frac{1}{3}}dx = \frac{3}{4}x^{\frac{4}{3}} + C. $

b)  $ \int\sqrt{\frac{1}{x^{7}}}dx=\int x^{\frac{-7}{2}}dx=\frac{-2}{5}x^{\frac{-5}{2}}+C. $

$$ \begin{aligned}&c)\int\frac{1}{\sqrt[3]{x^{\frac{4}{5}}}}\mathrm{d}x=\int x^{\frac{-4}{15}}\mathrm{d}x=\frac{15}{11}x^{\frac{11}{15}}+C.\\ &d)\int\left(x-\frac{1}{x}\right)^{2}\mathrm{d}x=\int\left(x^{2}+\frac{1}{x^{2}}-2\right)\mathrm{d}x=\frac{x^{3}}{3}-\frac{1}{x}-2x+C.\\ &e)\int\frac{(x-3)(x+1)}{x}\mathrm{d}x=\int\left(x-2-\frac{3}{x}\right)\mathrm{d}x=\frac{x^{2}}{2}-2x-3\ln|x|+C.\\ &g)\int\left(3x^{2}-\frac{4}{x}\right)(2x+5)\mathrm{d}x=\int\left(6x^{3}+15x^{2}-8-\frac{20}{x}\right)\mathrm{d}x\\ &=\frac{3}{2}x^{4}+5x^{3}-8x-20\ln|x|+C.\\ \end{aligned} $$ 

 $$ \begin{aligned}&24.\text{a)}\int e^{5x}\mathrm{d}x=\int(e^{5})^{\mathrm{x}}\mathrm{d}x=\frac{(e^{5})^{\mathrm{x}}}{\ln e^{2}}+C=\frac{e^{5x}}{5}+C.\\ &\begin{aligned}\\ &b)\int\frac{1}{2\ 024^{\mathrm{x}}}\mathrm{d}x=\int\left(\frac{1}{2\ 024}\right)^{\mathrm{x}}\mathrm{d}x=\frac{\left(\frac{1}{2\ 024}\right)^{\mathrm{x}}}{\ln\frac{1}{2\ 024}}+C=\frac{-1}{2\ 024^{\mathrm{x}}\ln2\ 024}+C.\\&c)\int(2^{\mathrm{x}}+x^{2})^{\mathrm{x}}=\frac{2^{\mathrm{x}}}{\ln2}+\frac{x^{3}}{3}+C.\\&d)\int(2^{\mathrm{x}}\cdot3^{2x+1})^{\mathrm{d}}x=3\int18^{\mathrm{x}}d x=\frac{3\cdot18^{\mathrm{x}}}{\ln18}+C.\\&e)\int\frac{3^{\mathrm{x}}+4^{\mathrm{x}}+1}{5^{\mathrm{x}}}\mathrm{d}x=\int\left[\left(\frac{3}{5}\right)^{\mathrm{x}}+\left(\frac{4}{5}\right)^{\mathrm{x}}+\left(\frac{1}{5}\right)^{\mathrm{x}}\right]\mathrm{d}x\\&=\frac{3^{\mathrm{x}}}{5^{\mathrm{x}}\left(\ln3-\ln5\right)}+\frac{4^{\mathrm{x}}}{5^{\mathrm{x}}\left(\ln4-\ln5\right)}-\frac{1}{5^{\mathrm{x}}\ln5}+C.\\ &\end{aligned}\\ \end{aligned} $$ 

25. a)  $ \int(5\sin x - 6\cos x)dx = -5\cos x - 6\sin x + C. $

 $$ \begin{aligned}&b)\int\sin^{2}2x\mathrm{d}x+\int\cos^{2}2x\mathrm{d}x=\int(\sin^{2}2x+\cos^{2}2x)\mathrm{d}x=\int\mathrm{d}x=x+C.\\ &c)\int\sin^{2}\left(\frac{x}{2}\right)\mathrm{d}x=\int\frac{1-\cos x}{2}\mathrm{d}x=\frac{1}{2}\int\mathrm{d}x-\frac{1}{2}\int\cos x\mathrm{d}x=\frac{x-\sin x}{2}+C.\\ &d)\int\left(\sin\frac{x}{2}+\cos\frac{x}{2}\right)^{2}\mathrm{d}x=\int\left(\sin^{2}\frac{x}{2}+\sin x+\cos^{2}\frac{x}{2}\right)\mathrm{d}x=\int(1+\sin x)\mathrm{d}x\\ &=x-\cos x+C.\\ \end{aligned} $$

$$ \begin{aligned}&\mathrm{e}^{*})\int\cos^{4}\frac{x}{2}\mathrm{d}x-\int\sin^{4}\frac{x}{2}\mathrm{d}x=\int\left(\cos^{2}\frac{x}{2}+\sin^{2}\frac{x}{2}\right)\left(\cos^{2}\frac{x}{2}-\sin^{2}\frac{x}{2}\right)\mathrm{d}x\\ &=\int\cos x\mathrm{d}x=\sin x+C.\\ \end{aligned} $$ 

 $$ \mathrm{g}^{*})\int\tan^{2}x\mathrm{d}x=\int\left[\left(\tan^{2}x+1\right)-1\right]\mathrm{d}x=\int\left(\frac{1}{\cos^{2}x}-1\right)\mathrm{d}x=\tan x-x+C. $$ 

##### S3 TÍCH PHÂN

26. C. 27. C. 28. C. 29. A. 30. C. 31. C. 32. D. 33. A. 34. D.

35. B. 36. A.

37. a) D, b) S, c) S, d) S.

 $$ \begin{array}{l}\mathrm{L}\dot{\mathrm{a}}\mathrm{y}f(x)=1,g(x)=x,a=1,b=2.\mathrm{T a}\mathrm{c}\mathrm{o}\end{array} $$ 

 $$ \int_{1}^{2}\frac{1}{x}\mathrm{d}x=\left.\ln\left|x\right|\right|_{1}^{2}=\ln2-\ln1=\ln2,\begin{aligned}\int_{1}^{2}\mathrm{d}x&=\frac{x_{1}^{2}}{\int_{1}^{2}x\mathrm{d}x}=\frac{x_{1}^{2}}{\left.\frac{x^{2}}{2}\right|_{1}^{2}}=\frac{2-1}{2-\frac{1}{2}}=\frac{2}{3}.\end{aligned} $$ 

 $$ \mathrm{S u y~r a}\int_{\frac{1}{1}}^{\frac{2}{x}}\mathrm{d}x\neq\frac{\int_{1}^{2}\mathrm{d}x}{\int_{1}^{2}\mathrm{d}x}. $$ 

39. Vì  $ G(x) $ là một nguyên hàm của  $ g(x) $ nên ta có  $ \int g(x)dx = G(2) - G(-1) $ hay  $ 6 = G(2) - 8 $. Suy ra  $ G(2) = 14 $.

40. a)  $ \int\limits_{1}^{-2}f(x)dx=-\int\limits_{-2}^{1}f(x)dx=-5. $

b)

 $$ \int_{-2}^{1}-4f(x)\mathrm{d}x=-\left.4\int_{-2}^{1}f(x)\mathrm{d}x=-4\right..5=-\left.20\right.. $$ 

 $$ \mathrm{c)}\int_{-2}^{1}\frac{-2g(x)}{3}\mathrm{d}x=\frac{-2}{3}\int_{-2}^{1}g(x)\mathrm{d}x=\frac{-2}{3}\cdot(-4)=\frac{8}{3}. $$

$$ \mathrm{d})\int\limits_{-2}^{1}[f(x)+g(x)]\mathrm{d}x=\int\limits_{-2}^{1}f(x)\mathrm{d}x+\int\limits_{-2}^{1}g(x)\mathrm{d}x=5+(-4)=1. $$ 

 $$ \begin{aligned}\text{e)}\quad\int\limits_{-2}^{1}[f(x)-g(x)]\mathrm{d}x&=\int\limits_{-2}^{1}f(x)\mathrm{d}x-\int\limits_{-2}^{1}g(x)\mathrm{d}x=5-(-4)=9.\end{aligned} $$ 

 $$ \mathrm{g)}\int\limits_{-2}^{1}[3f(x)-5g(x)]\mathrm{d}x=3\int\limits_{-2}^{1}f(x)\mathrm{d}x-5\int\limits_{-2}^{1}g(x)\mathrm{d}x=3.5-5.(-4)=35. $$ 

41. Ta có:  $ \int\limits_{-1}^{3}f(x)dx=\int\limits_{-1}^{2}f(x)dx+\int\limits_{2}^{3}f(x)dx $ hay  $ 2=\int\limits_{-1}^{2}f(x)dx+(-5) $.

Suy ra  $ \int\limits_{-1}^{2}f(x)dx=7 $.

42. Xe ô tô dùng hắn khi v(t) = 0, tức là -6t + 18 = 0 hay t = 3 (s).

Quảng đường mà ô tô đi được từ lúc đáp phanh đến khi dùng hắn là:

 $$ \int\limits_{0}^{3}(-6t+18)\mathrm{d}t=\left(-3t^{2}+18t\right)\bigg|_{0}^{3}=27\ (\mathrm{m}). $$ 

43. Đồ thị hàm số biểu diễn vận tốc theo thời gian là một đường thẳng qua gốc toạ độ, nên ta có:  $ v(t) = at (a \in \mathbb{R}) $.

Vì khi $t = 5$ thì $v = 10$ nên ta có: $10 = a$. $5$ hay $a = 2$. Vây $v(t) = 2t$.

a) Quăng đường mà vật di chuyển được trong 5 giây đầu tiên là:

 $$ \int\limits_{0}^{5}v(t)\mathrm{d}t=\int\limits_{0}^{5}2t\mathrm{d}t=\left.t^{2}\right|_{0}^{5}=25(m). $$ 

b) Quảng đường mà vật di chuyển được từ thời điểm 1 giây đến 5 giây là:

 $$ \int\limits_{1}^{3}v(t)\mathrm{d}t=\int\limits_{1}^{3}2t\mathrm{d}t=\left.t^{2}\right|_{1}^{5}=25-1=24(m). $$ 

44. Quăng đường mà con lắc di chuyển sau 1 giấy kế từ vị trí cân bằng là:

 $$ S=\int\limits_{0}^{1}\nu(t)\mathrm{d}t=\int\limits_{0}^{1}2\cos t\mathrm{d}t=2\sin t\Big|_{0}^{1}=2\sin1\approx1,68(cm). $$ 

#### S4 ỨNG DỤNG HÌNH HỌC CỦA TÍCH PHÂN

45. A. 46. B. 47. B.

48. a) D, b) D, c) S, d) D.

49. a) Hình phẳng đó được giới hạn bởi các đồ thị hàm số  $ y=\left(\frac{1}{3}\right)^x $,  $ y=-2x+1 $ và hai đường thẳng  $ x=-1 $,  $ x=0 $.

b) Diện tích hình phẳng đỏ là:

 $$ \begin{aligned}S&=\int_{-1}^{0}\left(\frac{1}{3}\right)^{x}-(-2x+1)\left|\mathrm{d}x=\int_{-1}^{0}\left[-2x+1-\left(\frac{1}{3}\right)^{x}\right]\mathrm{d}x=\left[-x^{2}+x+\frac{\left(\frac{1}{3}\right)^{x}}{\ln3}\right]\right|_{-1}^{0}\\&=\frac{1}{\ln3}-\left(-2+\frac{3}{\ln3}\right)=2-\frac{2}{\ln3}.\end{aligned} $$ 

50. a) Hình phảng đó được giới hạn bởi các đồ thị hàm số  $ y = x^{2} - 2x - 1 $,  $ y = -x^{2} + 3 $ và hai đường thẳng  $ x = -1 $,  $ x = 2 $.

b) Diện tích hình phẳng đó là:

 $$ \begin{aligned}S&=\int\limits_{-1}^{2}\left|(-x^{2}+3)-(x^{2}-2x-1)\right|\mathrm{d}x=\int\limits_{-1}^{2}\left[(-x^{2}+3)-(x^{2}-2x-1)\right]\mathrm{d}x\\&=\int\limits_{-1}^{2}(-2x^{2}+2x+4)\mathrm{d}x=\left(-\frac{2}{3}x^{3}+x^{2}+4x\right)\bigg|_{-1}^{2}=9.\end{aligned} $$ 

51. Thế tích khối tròn xoay đó là:

 $$ V=\pi\int_{0}^{\frac{\pi}{2}}\cos^{2}\frac{x}{2}\mathrm{d}x=\pi\int_{0}^{\frac{\pi}{2}}\frac{1+\cos x}{2}\mathrm{d}x=\left.\frac{\pi(x+\sin x)}{2}\right|_{0}^{\frac{\pi}{2}}=\frac{\pi^{2}+2\pi}{4}. $$ 

#### BÀI TẬP CUỐI CHƯƠNG IV

52. A. 53. B. 54. D. 55. C.

56. a) S, b) D, c) D, d) S.

57. a) D, b) S, c) S, d) D.

58. a) D, b) S, c) S, d) D.

 $$ \begin{aligned}59.\ a)\int(x+1)(x^{2}-x+1)d x=\int(x^{3}+1)d x=\frac{x^{4}}{4}+x+C.\end{aligned} $$ 

b)

 $$ \int x\Bigg(2-\frac{3}{x^{3}}\Bigg)\mathrm{d}x=\int\Bigg(2x-\frac{3}{x^{2}}\Bigg)\mathrm{d}x=x^{2}+\frac{3}{x}+C. $$

$$ \int e^{-3x}\mathrm{d}x=\int\left(e^{-3}\right)^{x}\mathrm{d}x=\frac{\left(e^{-3}\right)^{x}}{\ln e^{-3}}+C=-\frac{e^{-3x}}{3}+C. $$ 

 $$ \int(2-3\tan^{2}x)\mathrm{d}x=\int\left(5-\frac{3}{\cos^{2}x}\right)\mathrm{d}x=5x-3\tan x+C. $$ 

e)  $ \int \frac{1}{2^{-x+1}} dx = \int \frac{2^x}{2} dx = \frac{2^x}{2 \ln 2} + C. $

 $$ \begin{aligned})&\int\frac{3^{2x+1}}{2^{x}}\mathrm{d}x=3\int\left(\frac{9}{2}\right)^{x}\mathrm{d}x=3\cdot\frac{\left(\frac{9}{2}\right)^{x}}{\ln\frac{9}{2}}+C=\frac{3^{2x+1}}{2^{x}(2\ln3-\ln2)}+C.\end{aligned} $$ 

60. Ta có:  $ \int_{0}^{1}[2f(x)-1]dx = 2\int_{0}^{1}f(x)dx - \int_{0}^{1}dx = 3\ \text{mà}\int_{0}^{1}dx = 1\ \text{nên}\ 2\int_{0}^{1}f(x)dx - 1 = 3 $

hay  $ \int_{0}^{1}f(x)dx = 2 $.

61. Lấy $f(x) = 2x$, $g(x) = 3$. Khi đồ, $\int[f(x) \cdot g(x)]\,dx = \int6x\,dx = 3x^2 + C$;

$\int f(x)\,dx \cdot \int g(x)\,dx = \int 2x\,dx \cdot \int 3\,dx = (x^2 + D)(3x + E)$

$= 3x^3 + Ex^2 + 3Dx + DE$ ($C$, $D$, $E$ là các hàng số).

Suy ra $\int[f(x) \cdot g(x)]\,dx \neq \int f(x)\,dx \cdot \int g(x)\,dx$.

62. Ta có:  $ \int 2^x \, dx = \frac{2^x}{\ln 2} + C $. Vi  $ F(0) = \log_2(2e) $ nên  $ \frac{1}{\ln 2} + C = 1 + \frac{1}{\ln 2} $, suy ra  $ C = 1 $. Vây  $ F(x) = \frac{2^x}{\ln 2} + 1 $.

63. a)  $ \int_{0}^{1}-2dx=-2x_{0}^{1}=-2. $

b)  $ \int_{0}^{1}\frac{2x}{3}\mathrm{d}x=\frac{x^{2}}{3}\bigg|_{0}^{1}=\frac{1}{3}. $

c)  $ \int_{0}^{1}x^{4}dx=\frac{x^{5}}{5}\bigg|_{0}^{1}=\frac{1}{5}. $

d)  $ \int_{1}^{3}2\sqrt[3]{x}dx = 2\int_{1}^{3}x^{\frac{1}{3}}dx = \frac{3}{2}x^{\frac{4}{3}}\bigg|_{1}^{3} = \frac{9\sqrt[3]{3} - 3}{2}. $

e)

 $$ \left.\int\limits_{1}^{2}\frac{2}{3x}\mathrm{d}x=\frac{2}{3}\int\limits_{1}^{2}\frac{1}{x}\mathrm{d}x=\frac{2}{3}\ln\left|x\right|\right|_{1}^{2}=\frac{2}{3}\ln2. $$ 

g)

 $$ \int\limits_{1}^{9}(x\sqrt{x}-2)\mathrm{d}x=\int\limits_{1}^{9}\left(x^{\frac{3}{2}}-2\right)\mathrm{d}x=\left(\frac{2}{5}x^{\frac{5}{2}}-2x\right)\Bigg|_{1}^{9}=\frac{404}{5}. $$ 

64. a)

 $$ \int\limits_{0}^{\frac{\pi}{2}}\sin x\mathrm{d}x=-\left.\cos x\right|_{0}^{\frac{\pi}{2}}=1. $$ 

b)

 $$ \int_{0}^{\frac{\pi}{4}}\cos x\mathrm{d}x=\sin x\left|\begin{matrix}\frac{\pi}{4}\\ 0\end{matrix}\right|_{0}=\frac{\sqrt{2}}{2}. $$ 

c)

 $$ \int_{\frac{\pi}{4}}^{\frac{\pi}{2}}\frac{1}{\sin^{2}x}\mathrm{d}x=-\cot x\bigg|_{\frac{\pi}{4}}^{\frac{\pi}{2}}=1. $$ 

d)

 $$ \int_{0}^{\frac{\pi}{4}}\frac{1}{\cos^{2}x}\mathrm{d}x=\tan x\bigg|_{0}^{\frac{\pi}{4}}=1. $$ 

e)

 $$ \int\limits_{0}^{\frac{\pi}{2}}(\sin x-2)\mathrm{d}x=(-\cos x-2x)\Bigg|_{0}^{\frac{\pi}{2}}=1-\pi. $$ 

g)

 $$ \int_{0}^{\frac{\pi}{4}}(3\cos x+2)\mathrm{d}x=(3\sin x+2x)\Bigg|_{0}^{\frac{\pi}{4}}=\frac{3\sqrt{2}}{2}+\frac{\pi}{2}. $$ 

65. a)

 $$ \int_{0}^{\frac{2}{}}e^{-5x}\mathrm{d}x=\int_{0}^{\frac{2}{}}(e^{-5})^{x}\mathrm{d}x=\frac{(e^{-5})^{x}}{\ln e^{-5}}\bigg|_{0}^{2}=-\frac{e^{-5x}}{5}\bigg|_{0}^{2}=-\frac{1}{5e^{10}}+\frac{1}{5}. $$ 

b)

 $$ \int\limits_{0}^{1}3^{x+2}\mathrm{d}x=9\int\limits_{0}^{1}3^{x}\mathrm{d}x=\left.\frac{3^{x+2}}{\ln3}\right|_{0}^{1}=\frac{18}{\ln3}. $$ 

c)

 $$ \begin{aligned}\left.\right)\quad\int_{-1}^{1}3^{2x}\mathrm{d}x&=\int_{-1}^{1}9^{x}\mathrm{d}x=\left.\frac{9^{x}}{\ln9}\right|_{-1}^{1}=\frac{80}{9\ln9}.\end{aligned} $$

66. a)  $ S = \int_{1}^{2} 2^{x} \, dx = \frac{2^{x}}{\ln 2}\bigg|_{1}^{2} = \frac{2}{\ln 2} $

 $$ \mathrm{b})\ V=\pi\int\limits_{1}^{2}(2^{x})^{2}\mathrm{d}x=\pi\int\limits_{1}^{2}4^{x}\mathrm{d}x=\frac{4^{x}\pi}{2\ln2}\bigg|_{1}^{2}=\frac{12\pi}{2\ln2}=\frac{6\pi}{\ln2}. $$ 

 $$ \begin{aligned}S=\int\limits_{0}^{\frac{2}{3}}|x^{2}-2x|\mathrm{d}x=\int\limits_{0}^{\frac{2}{3}}(2x-x^{2})\mathrm{d}x=\left.\left(x^{2}-\frac{x^{3}}{3}\right)\right|_{0}^{2}=\frac{4}{3}.\end{aligned} $$ 

 $$ \begin{aligned}b)V=\pi\int_{0}^{2}(x^{2}-2x)^{2}\mathrm{d}x=\pi\int_{0}^{2}(x^{4}-4x^{3}+4x^{2})\mathrm{d}x=\pi\left(\frac{x^{5}}{5}-x^{4}+\frac{4x^{3}}{3}\right)\bigg|_{0}^{2}=\frac{16\pi}{15}.\end{aligned} $$ 

68. Quảng dường vật di chuyển trong khoảng thời gian từ thời điểm t = 0 (s) đến thời điểm t =  $ \frac{\pi}{4} $ (s) là:

 $$ S=\int\limits_{0}^{\frac{\pi}{4}}(3-2\sin t)\mathrm{d}t=(3t+2\cos t)\Bigg|_{0}^{\frac{\pi}{4}}=\frac{3\pi}{4}+\sqrt{2}-2\ \mathrm{(m)}. $$ 

69. a) Ta có:  $ \int (-20t + 40)dt = -10t^2 + 40t + C $.

Do  $ s(0) = 0 $ nên  $ C = 0 $. Suy ra  $ s(t) = -10t^2 + 40t $.

b) Xe ô tô dùng hắn khi v(t) = 0, tức là -20t + 40 = 0 hay t = 2.

Vậy thời gian kế từ lúc đáp phanh đến khi xe ô tô dùng hàn là 2 giấy.

c) Ta có: 72 km/h = 20 m/s.

Quãng đường xe ô tô còn di chuyển được kê từ lúc đáp phanh đến khi xe dùng hắn là:

 $$ s(2)=-10\ .2^{2}+40\ .2=40\ (m). $$ 

Vậy quăng đường xe ô tô đã di chuyển kế từ lúc người lái xe phát hiện chương ngại vật trên đường đến khi xe ô tô dùng hắn là: 20 + 40 = 60 (m).

Do 60 < 110 nên xe ô tô đã dùng hàn trước khi và chạm với chương ngại vật trên đường. Vì thế, ô tô đó không và chạm với chương ngại vật.

### §1

## PHƯỜNG TRÌNH MẸT PHẢNG

## A. KIẾN THỨC CẤN NHỚ

### 1. Phương trình mặt phẳng

## a) Vecto pháp tuyến và cặp vecto chi phương của mặt phẳng

• Cho mặt phẳng (P). Nếu vẹo ở khác ở và có giá vương góc với mặt phẳng (P) thì nọ được gọi là vẹo pháp tuyến của mặt phẳng (P).

Nhận xét: Nếu Ấ là vẹt pháp tuyến của một mặt phẳng thì kĩ (k ≠ 0) cũng là vẹt pháp tuyến của mặt phẳng đó.

• Cho mặt phẳng (P). Hai vectơ không cùng phương có giá song song hoặc nằm trong mặt phẳng (P) được gọi là cặp vectơ chi phương của mặt phẳng (P).

##### Chú ý

Xác định vectơ pháp tuyến của mặt phẳng khi biết cặp vectơ chỉ phương:

Nếu hai vectơ $\vec{a} = (a_{1}; a_{2}; a_{3})$. $\vec{b} = (b_{1}; b_{2}; b_{3})$ là cặp vectơ chi phương của mặt phẳng (P) thì $\vec{n} = \left[\vec{a}, \vec{b}\right] = \left(\begin{matrix} a_{2} & a_{3} \\ b_{2} & b_{3} \end{matrix}\right); \left|\begin{matrix} a_{3} & a_{1} \\ b_{3} & b_{1} \end{matrix}\right|; \left|\begin{matrix} a_{1} & a_{2} \\ b_{1} & b_{2} \end{matrix}\right|\right)$ là một vectơ pháp tuyển của mặt phẳng (P).

##### Phương trình tổng quát của mặt phẳng

Phương trình Ax + By + Cz + D = 0 (A, B, C không đồng thời bằng 0) là phương trình tổng quát của mặt phẳng. Hệ số D gọi là hệ số tự do của phương trình tổng quát.

Nhận xét: Nếu mặt phẳng (P) có phương trình tổng quát là  $ Ax + By + Cz + D = 0 $, trong đó A, B, C không đồng thời bằng 0, thì vectơ  $ \vec{n} = (A; B; C) $ là một vectơ pháp tuyến của mặt phẳng (P).

## Lập phương trình tổng quát của mặt phẳng

- Lập phương trình tổng quát của mặt phẳng đi qua một điểm và biết vector pháp tuyển

Mặt phẳng (P) đi qua điểm  $ I(x_0; y_0; z_0) $ và nhận  $ \vec{n} = (A; B; C) $ làm vectơ pháp tuyến có phương trình tổng quát là:  $ Ax + By + Cz + D = 0 $ với  $ D = -Ax_0 - By_0 - Cz_0 $.

Lập phương trình tổng quát của mặt phẳng đi qua một điểm và biết cặp vectơ chi phương

Đê lập phương trình mặt phẳng (P) đi qua điểm  $ I(x_0; y_0; z_0) $ có cặp vector chi phương là  $ \vec{u} $,  $ \vec{v} $, ta có thể làm như sau:

Buóc 1. Tim Ŋ = [u, v].

Bước 2. Lập phương trình mặt phẳng (P) đi qua điểm I(x₀; y₀; z₀) nhận Ấn làm vẹo pháp tuyến.

Lập phương trình tổng quát của mặt phẳng đi qua ba điểm không thẳng hàng

Để lập phương trình mặt phẳng (P) đi qua ba điểm  $ H(a_1; b_1; c_1) $,  $ I(a_2; b_2; c_2) $,  $ K(a_3; b_3; c_3) $ không thẳng hàng, ta có thể làm như sau:

Bước 1. Tìm cấp vệ tố chỉ phương của mặt phẳng (P) là:

 $$ \overrightarrow{HI}=(a_{2}-a_{1}\;;\;b_{2}-b_{1}\;;\;c_{2}-c_{1}),\;\overrightarrow{HK}=(a_{3}-a_{1}\;;\;b_{3}-b_{1}\;;\;c_{3}-c_{1}). $$ 

Buóc 2. Tim ∇ = [∇H, ∇HK].

Bước 3. Lập phương trình mặt phẳng (P) đi qua điểm  $ H(a_1; b_1; c_1) $ nhận Ấn làm vẹt pháp tuyến.

Chú ý: Mặt phẳng đi qua ba điểm  $ A(a;0;0) $,  $ B(0;b;0) $,  $ C(0;0;c) $ với  $ abc \neq 0 $ có phương trình là  $ \frac{x}{a} + \frac{y}{b} + \frac{z}{c} = 1 $. Phương trình đó còn được gọi là phương trình mặt phẳng theo đoạn chắn.

## 2. Điều kiện song song, vương góc của hai mặt phẳng

### Điều kiện song song của hai mặt phẳng

Cho mặt phẳng (P₁) có phương trình tổng quát là  $ A_1x + B_2y + C_3z + D_4 = 0 $ và mặt phẳng (P₂) có phương trình tổng quát là  $ A_2x + B_3y + C_4z + D_5 = 0 $.

Gọi  $  \vec{n}_{1} = (A_{1}; B_{1}; C_{1}), \vec{n}_{2} = (A_{2}; B_{2}; C_{2})  $ lần lượt là vẹo pháp tuyên của hai mặt phẳng  $  (P_{1}), (P_{2})  $.

Khi đó:  $ (P_{1}) \parallel (P_{2}) $ khi và chi khi tồn tại số thực  $ k \neq 0 $ sao cho  $ \begin{cases} \vec{n}_{1} = k\vec{n}_{2} \\ D_{1} \neq kD_{2} \end{cases} $

### Điều kiện vương góc của hai mặt phẳng

Cho mặt phẳng (P₁) có phương trình tổng quát là A₁x + B₁y + C₁z + D₁ = 0 và mặt phẳng (P₂) có phương trình tổng quát là A₂x + B₂y + C₂z + D₂ = 0.

Khi đó: (P₁) ⊥ (P₂) ⇔ A₁A₂ + B₁B₂ + C₁C₂ = 0.

## 3. Khoảng cách từ một điểm đến một mặt phẳng

Khoảng cách từ điểm  $ M_0(x_0; y_0; z_0) $ đến mặt phẳng (P):  $ Ax + By + Cz + D = 0 $ ( $ A^2 + B^2 + C^2 > 0 $) được tính theo công thức:  $ d(M_0, (P)) = \frac{|Ax_0 + By_0 + Cz_0 + D|}{\sqrt{A^2 + B^2 + C^2}} $.

### B. ví dụ

Vấn đề 1. Xác định phương trình tổng quát và vectơ pháp tuyến của mặt phẳng

 $ \overline{Vi} $ đụ 1) Phương trình nào sau đây là phương trình tổng quát của mặt phẳng?

A.  $ 2x - y + z^{2} - 1 = 0. $

B.  $ x - y^{2} + z - 1 = 0. $

C.  $ x^{2} - y + z - 1 = 0. $

D.  $ 2x + 3y + z - 1 = 0. $

Phương trình tổng quát của mặt phẳng có dạng  $ Ax + By + Cz + D = 0 $ với A, B, C không đồng thời bằng 0 và x, y, z có số mũ bằng 1.

Nhận thấy chi có phương trình 2x + 3y + z - 1 = 0 đúng dạng phương trình tổng quát của mặt phẳng. Chọn D.

 $ \frac{\vec{V}i \, d\mu \, 2}{\ddot{d}\dot{a}y \, \dot{a}} \text{Cho mặt phẳng (P)} \text{có phương trình } -2x + 4y + 9z + 1 = 0. \text{Vecto nào sau đấy là vecto pháp tuyến của mặt phẳng (P)} $?

A.  $ \vec{n}_1 = (2; 4; 9). $

B.  $ \vec{n}_2 = (-2; 4; 9). $

C.  $ \vec{n}_3 = (4; 9; 1). $

D.  $ \vec{n}_4 = (-2; 4; 1). $

#### Giải

Phương trình - 2x + 4y + 9z + 1 = 0 có A = -2, B = 4, C = 9. Vây Ấn₂ = (-2; 4; 9) là một vectơ pháp tuyển của mặt phẳng (P). Chọn B.

Ví dụ 3) Trong mỗi ý a), b), c), d), chọn phương án: đùng (D) hoặc sai (S).

Cho điểm I(1 ; 2 ; 3) và mặt phẳng (P): 2x + 2y - z + 15 = 0. Gọi H(x_{H}; y_{H}; z_{H}) là hình chiều vuông góc của I trên (P).

a) Vectơ Ấn = (2 ; 2 ; - 1) là một vectơ pháp tuyến của mặt phẳng (P).

b) Vecto ỈH không cùng phương với vecto Ấn = (2 ; 2 ; - 1).

c) ỈH = tẵn với t là một số thực nào đó.

d) Toa độ của điểm H là (5 ; 6 ; - 2).

Giải

Phương trình 2x + 2y - z + 15 = 0 có A = 2, B = 2, C = -1 nên vẹo Ấn = (2; 2; -1) là một vẹo pháp tuyến của mặt phẳng (P).

Vi IH ⊥ (P) nên hai vectơ ỈH và Ấn có giá song song hoặc trùng nhau. Suy ra ỈH và Ấn cùng phương.

Khi đó,  $  \overrightarrow{IH} = t\overrightarrow{n}  $ với t là một số thực nào đó. Với  $  \overrightarrow{IH} = (x_H - 1; y_H - 2; z_H - 3)  $,  $  t\overrightarrow{n} = (2t; 2t; -t)  $, ta có:

 $$ \overrightarrow{IH}=t\overrightarrow{n}\Leftrightarrow\begin{cases}x_{H}-1=2t\\y_{H}-2=2t\\z_{H}-3=-t\end{cases}\Leftrightarrow\begin{cases}x_{H}=1+2t\\y_{H}=2+2t\\z_{H}=3-t.\end{cases} $$ 

Suy ra  $ H(1+2t;2+2t;3-t) $. Mà H thuộc  $ (P) $:  $ 2x+2y-z+15=0 $ nên

 $$ 2(1+2t)+2(2+2t)-(3-t)+15=0\Leftrightarrow t=-2. $$ 

Vây H(-3; -2; 5).

Đáp án: a) Đ, b) S, c) Đ, d) S.

## Vấn đề 2. Lập phương trình mặt phẳng

Phương pháp: Để lập phương trình mặt phẳng, ta thường chỉ ra toạ độ một điểm thuộc mặt phẳng và một vectơ pháp tuyến của mặt phẳng đó (riêng trường hợp mặt phẳng cắt ba trục toạ độ tại ba điểm cho trước, ta có thể lập phương trình mặt phẳng theo đoạn chắn).

Ví dụ 4) Lập phương trình mặt phẳng (P) trong mỗi trường hợp sau:

a) (P) đi qua điểm I(-2; 3; 0) và nhận Ấn = (4; -1; 5) làm vẹt ở pháp tuyến;

b) (P) đi qua ba điểm A(2; 0; 0), B(0; 3; 0), C(0; 0; 1).

Giải

a) Phương trình mặt phẳng (P) là:

 $$ 4\ .(x+2)+(-1)\ .(y-3)+5\ .\ (z-0)=0\Leftrightarrow4x-y+5z+11=0. $$

b) Phương trình mặt phẳng (P) là:

 $$ \frac{x}{2}+\frac{y}{3}+\frac{z}{1}=1\Leftrightarrow3x+2y+6z-6=0. $$ 

## Vấn đề 3. Chứng minh hai mặt phẳng song song hoặc vuông góc

 $ \underline{\text{Vi du 5}} $ Cho hai mặt phẳng  $ (P_{1}) $:  $ 3x + 2y - z + 1 = 0 $,  $ (P_{2}) $:  $ 6x + 4y - 2z + 3 = 0 $.

 $ \underline{\text{Chúng minh rằng}} $  $ (P_{1}) $ //  $ (P_{2}) $.

Giải

Hai mặt phẳng (P₁), (P₂) có vectơ pháp tuyến lần lượt là Ấn₁ = (3 ; 2 ; -1), Ấn₂ = (6 ; 4 ; -2). Vì Ấn₂ = 2Ấn₁ và 3 ≠ 2 . 1 nên (P₁) // (P₂).

 $ \underline{\text{Vi du 6}} $ Cho hai mặt phẳng  $ (P_{1}) $:  $ 4x - 3y - 2z + 4 = 0 $,  $ (P_{2}) $:  $ 5x - 2y + 13z + 9 = 0 $.

 $ \underline{\text{Chúng minh rằng}} $  $ (P_{1}) $  $ \perp $ $ (P_{2}) $.

Giải

Các vectơ  $  \vec{n}_{1} = (4; -3; -2)  $,  $  \vec{n}_{2} = (5; -2; 13)  $ lần lượt là vectơ pháp tuyến của hai mặt phẳng  $  (P_{1})  $ và  $  (P_{2})  $.

 $$ \mathrm{V i~}\vec{n}_{1}~,~\vec{n}_{2}=4~,~5+(-3)~.,~(-2)+(-2)~.~13=0~\mathrm{n e n}~\vec{n}_{1}\perp\vec{n}_{2}~,~\mathrm{V a y}~(P_{1})\perp(P_{2}). $$ 

## Vấn đề 4. Tính khoảng cách từ một điểm đến một mặt phẳng

Ví dụ 7 Cho mặt phẳng (P): 2x - 3y + 6z - 7 = 0 và điểm M(5 ; 2 ; - 3). Tinh khoảng cách từ điểm M đến mặt phẳng (P).

Giải

Khoảng cách từ điểm M đến mặt phẳng (P) là:

 $$ d(M,\left(P\right))=\frac{\left|2\cdot5-3\cdot2+6\cdot\left(-3\right)-7\right|}{\sqrt{2^{2}+\left(-3\right)^{2}+6^{2}}}=3. $$ 

## Vấn đề 5. Ứng dụng

Vĩ dụ 8 Hình 1 minh hoạ hình ảnh một toà nhà trong không gian với hệ toạ độ Oxyz (đơn vị trên mỗi trục toạ độ là mét). Biết A(50; 0; 0), D(0; 20; 0), B(4k; 3k; 2k) với k > 0 và mặt phẳng (CBEF) có phương trình là z = 3.

a) Tìm toạ độ của điểm B.

b) Lập phương trình mặt phẳng (AOBC).

c) Lập phương trình mặt phẳng (DOBE).

d) Chỉ ra một vectơ pháp tuyến của mỗi mặt phẳng (AOBC) và (DOBE).

a) Vi $B(4k; 3k; 2k)$ thuộc mặt phẳng (CBEF): $z = 3$ nên $2k = 3$, suy ra $k = \frac{3}{2}$. Vây $B\left(6; \frac{9}{2}; 3\right)$.

b) Ta có:  $ \overrightarrow{OA} = (50; 0; 0) $,  $ \overrightarrow{OB} = \left(6; \frac{9}{2}; 3\right) $ nên

 $$ \left[\overrightarrow{OA},\overrightarrow{OB}\right]=\left(\begin{vmatrix}{{{0}}}&{{{0}}} \\{{{\frac{9}{2}}}}&{{{3}}}\end{vmatrix};\begin{vmatrix}{{{0}}}&{{{50}}} \\{{{3}}}&{{{6}}}\end{vmatrix};\begin{vmatrix}{{{50}}}&{{{0}}} \\{{{6}}}&{{{\frac{9}{2}}}}\end{vmatrix}=(0;-150;225). $$ 

Suy ra Ấn = (0 ; - 2 ; 3) là một vectơ pháp tuyến của mặt phẳng (AOBC).

Vậy phương trình mặt phẳng (AOBC) là:

 $$ 0,(x-0)+(-2),(y-0)+3,(z-0)=0\Leftrightarrow2y-3z=0. $$ 

c) Ta có:  $ \overrightarrow{OD} = (0; 20; 0) $,  $ \overrightarrow{OB} = \left(6; \frac{9}{2}; 3\right) $ nên

 $$ \left[\overrightarrow{OD},\overrightarrow{OB}\right]=\left(\begin{vmatrix}{{{20}}}&{{{0}}} \\{{{\frac{9}{2}}}}&{{{3}}}\end{vmatrix};\left|\begin{matrix}{{{0}}}&{{{0}}} \\{{{3}}}&{{{6}}}\end{matrix}\right|;\left|\begin{matrix}{{{0}}}&{{{20}}} \\{{{6}}}&{{{\frac{9}{2}}}}\end{matrix}\right|\right)=(60;0;-120). $$ 

Suy ra Ứ = (1 ; 0 ; - 2) là một vẹo pháp tuyến của mặt phẳng (DOBE).

Vậy phương trình mặt phẳng (DOBE) là:

 $$ 1\ .(x-0)+0\ .(y-0)+(-2)\ .(z-0)=0\Leftrightarrow x-2z=0. $$ 

d) Một vectơ pháp tuyến của mỗi mất phảng (AOBC) và (DOBE) lần lượt là:

 $ \vec{p} = (0; 2; -3) $ và  $ \vec{q} = (-1; 0; 2) $.

 $ \underline{\text{Ví dụ 9}} $ Hình 2 minh hoạ một khu nhà đang xây dựng được gắn hệ trục toa đô Oxyz (đơn vị trên các trục là mét).

Mỗi cột bề tông có dạng hình lăng trụ từ giác đều và tâm của mặt đáy trên lần lượt là các điểm A(2; 1; 3), B(4; 3; 3), C(6; 3; 2,5), D(4; 0; 2,8).

<div style="text-align: center;">Hình 2</div>

Lập phương trình mặt phẳng (ABC).

Bón điểm A, B, C, D có đồng phẳng hay không?

a) Ta có:  $ \overrightarrow{AB} = (2; 2; 0) $,  $ \overrightarrow{AC} = (4; 2; -0.5) $ nên

 $$ \left[\overrightarrow{AB},\overrightarrow{AC}\right]=\left(\begin{vmatrix}{{{2}}}&{{{0}}} \\{{{2}}}&{{{-0,5}}}\end{vmatrix};\begin{vmatrix}{{{0}}}&{{{2}}} \\{{{-0,5}}}&{{{4}}}\end{vmatrix};\begin{vmatrix}{{{2}}}&{{{2}}} \\{{{4}}}&{{{2}}}\end{vmatrix}=(-1;1;-4) $$ 

là một vệ tụ pháp tuyến của mặt phẳng (ABC).

Vây phương trình mặt phẳng (ABC) là:

 $ (-1) $,  $ (x-2)+1 $,  $ (y-1)+(-4) $,  $ (z-3)=0 \Leftrightarrow x-y+4z-13=0. $

b) Vi 4 - 0 + 4 . 2,8 - 13 = 2,2 ≠ 0 nên điểm D(4 ; 0 ; 2,8) không thuộc mặt phẳng (ABC). Vậy bốn điểm A, B, C, D không đồng phẳng.

### C. BÀI TẬP

1. Phương trình nào sau đây là phương trình tổng quát của mặt phẳng?

A.  $ x - y^2 - 2 = 0. $

B.  $ x + z^2 - 3 = 0. $

C.  $ x - z - 4 = 0. $

D.  $ x^2 + y^2 + z^2 - 1 = 0. $

2. Cho mặt phẳng (P):  $ -x + 2y + 3 = 0 $. Vecto nào sau đây là vecto pháp tuyến của mặt phẳng (P)?

A.  $ \vec{n}_{1} = (-1, 2, 3) $.

B.  $ \vec{n}_{2} = (1, 2, 3) $.

C.  $ \vec{n}_{3} = (-1, 2, 0) $.

D.  $ \vec{n}_{4} = (-x, 2y, 3) $.

3. Cho mặt phẳng (P):  $ 3x - 6y + 12z - 13 = 0 $. Vector nào sau đây là vector pháp tuyến của mặt phẳng (P)?

A.  $ \vec{n}_{1} = (3; 6; 12) $.

B.  $ \vec{n}_{2} = (3x; 6y; 12z) $.

C.  $ \vec{n}_{3} = (3x; -6y; 12z) $.

D.  $ \vec{n}_{4} = (-1; 2; -4) $.

4. Cho mặt phẳng (P):  $ 3x + 4y - z + 5 = 0 $. Vecto nào sau đây là vecto pháp tuyến của mặt phẳng (P)?

A.  $ \vec{n}_{1} = (3; 4; 1) $.

B.  $ \vec{n}_{2} = (3; 4; -1) $.

C.  $ \vec{n}_{3} = (3; 4; 5) $.

D.  $ \vec{n}_{4} = (3; 4; -5) $.

5. Mặt phẳng di qua điểm  $ M(x_0; y_0; z_0) $ và vương góc với Ox có phương trình là:

A.  $ x - x_0 = 0. $

B.  $ y - y_0 = 0. $

C.  $ z - z_0 = 0. $

D.  $ x + y + z - x_0 - y_0 - z_0 = 0. $

6. Khoảng cách từ điểm  $ M(x_0; y_0; z_0) $ đến mặt phẳng (Oxy) bằng:

A.  $ |x_0| $.

B.  $ |y_0| $.

C.  $ |z_0| $.

D.  $ |x_0 + y_0 + z_0| $.

7. Khoảng cách từ điểm  $ M(x_{0};y_{0};z_{0}) $ đến mặt phẳng  $ (P) $:  $ ay + bz + c = 0 $ bằng:

A.  $ \frac{|ax_{0} + by_{0} + c|}{\sqrt{a^{2} + b^{2}}} $

B.  $ \frac{|ax_{0} + by_{0} + cz_{0}|}{\sqrt{a^{2} + b^{2} + c^{2}}} $

C.  $ \frac{|ay_{0} + bz_{0} + c|}{\sqrt{a^{2} + b^{2} + c^{2}}} $

D.  $ \frac{|ay_{0} + bz_{0} + c|}{\sqrt{a^{2} + b^{2}}} $

Trong mỗi ý a), b), c), d) ở câu 8, 9, chọn phương án: đúng (Đ) hoặc sai (S).

8. Cho mặt phẳng (P):  $ -3x + y - 2z + 5 = 0. $

8. Chọ mạ phàng (P): - 5x + y - 22 + 3 = 0.

a) Nếu Ấ là một vecto pháp tuyến của (P) thì kĩ là một vecto pháp tuyến của (P) với kệ 0.

b) Nếu Ấ và Ấi, đều là vecto pháp tuyến của (P) thì Ấ và Ấi không cùng phương.

c) Vecto Ấ = (-3; 1; -2) không là một vecto pháp tuyến của mất phảng (P).

d) Mọi vecto pháp tuyến của mất phảng (P) có toa độ (-3k; k; -2k) với kệ 0.

9. Cho điểm I(-3; 0; 1) và mặt phẳng (P):  $ x - 3y - 4z + 1 = 0 $.

a) Điểm I(-3; 0; 1) không thuộc mặt phẳng (P).

b) Vector  $ \vec{n} = (1; -3; 4) $ là một vector pháp tuyến của mặt phẳng (P).

c) Nếu mặt phẳng (Q) song song với mặt phẳng (P) thi vector  $ \vec{n} = (1; -3; 4) $ là một vector pháp tuyến của mặt phẳng (Q).

d) Mặt phẳng (R) đi qua điểm I và song song với (P) có phương trình là:  $ x - 3y - 4z - 7 = 0 $.

10. Lập phương trình mặt phẳng (P) trong mỗi trường hợp sau:

a) (P) đi qua điểm I(2; 1; -4) và có vectơ pháp tuyến là $\vec{n} = (3; -4; 5)$;

b) (P) đi qua điểm I(5; -2; 1) và có cặp vectơ chi phương là $\vec{a} = (3; -1; 4)$, $\vec{b} = (0; 2; -1)$;

c) (P) đi qua ba điểm A(0 ; 3 ; 7), B(2 ; - 5 ; 4) và C(1 ; - 4 ; - 1).

11. Lập phương trình mặt phẳng đi qua ba điểm A(5; 0; 0), B(0; 7; 0), C(0; 0; 9).

12. Cho ba điểm A(3; -4; 2), B(1; 2; 3), C(0; 1; 5). Lập phương trình mặt phẳng (P) đi qua điểm A và vương góc với đường thẳng BC.

13. Lập phương trình mặt phẳng (P) đi qua điểm K(4; -3; 7) và song song với mặt phẳng (Q): 3x - 2y + 4z + 7 = 0.

14. Lập phương trình mặt phẳng (P) đi qua điểm I(1; -2; 4) và vương góc với hai mặt phẳng (Q): x - y - 2 = 0, (R): y + z + 3 = 0.

15. Cho điểm  $ M(x_{0}; y_{0}; z_{0}) $. Tinh khoảng cách từ M đến các mặt phẳng  $ x - a = 0 $,  $ y - b = 0 $,  $ z - c = 0 $.

16. Cho hai mặt phẳng  $ (P_{1}) $:  $ x + 2y - 3z + 5 = 0 $ và  $ (P_{2}) $:  $ -4x - 8y + 12z + 3 = 0 $.

a) Chứng minh rằng  $ (P_{1}) \parallel (P_{2}) $.

b) Tinh khoảng cách giữa hai mặt phẳng  $ (P_{1}) $,  $ (P_{2}) $.

17. Cho hình chóp S.ABC thoả măn ASB = BSC = CSA = 90°. Gọi H là hình chiếu vuông góc của S trên mặt phẳng (ABC). Chứng minh rằng

 $$ \frac{1}{SH^{2}}=\frac{1}{SA^{2}}+\frac{1}{SB^{2}}+\frac{1}{SC^{2}}. $$ 

18. Cho bốn điểm A(1; 0; 0), B(0; 2; 0), C(0; 0; 3) và D(1; 2; 3). Chúng minh rằng

A, B, C, D không đồng phẳng.

19. Cho hình hộ chủ nhật ABCD.A’B’C’D’ có AB = 2a, AD = 3a, AA’ = 4a (a > 0). Gọi M, N, P là lượt là các điểm thuộc các tia AB, AD, AA’ sao cho AM = a, AN = 2a, AP = 3a. Tinh khoáng cách từ điểm C’ đến mặt phẳng (MNP).

20. Trong không gian với hệ tạo đó, Oxyz, cho hình chóp S.ABCD có dày là hình chữ nhất và các điểm A(0 ; 0 ; 0), B(a ; 0 ; 0), D(0 ; b ; 0), S(0 ; 0 ; c) với a, b, c là các số dương (Hinh 3).

a) Tìm toa độ của điểm C, trung điểm M của BC, trong tâm G của tam giác SCD.

b) Lấp phương trình mất phẳng (SBD).

c) Tinh khoáng cách từ điểm G đến mặt phẳng (SBD).

<div style="text-align: center;">Hình 3</div>

21. Khi gắn hệ trục toạ độ Oxyz (đơn vị trên mỗi trục toạ độ là decimét) vào một ngôi nhà 1 tầng, người ta thấy rằng mặt trên và mặt dưới của mái nhà thuộc các mặt phẳng vuông góc với trục Oz. Biết rằng các vị trí A(3 ; 4 ; 33), D(9 ; 8 ; 35) lần lượt thuộc mặt dưới, mặt trên của mái nhà. Độ dày của mái nhà được tính bằng khoảng cách giữa mặt trên và mặt dưới của mái nhà đó. Hãy cho biết độ dày của mái nhà đó là bao nhiêu decimét?

## PHƯỜNG TRÌNH ĐƯỜNG THẰNG

### A. KIẾN THỨC CẤN NHỚ

### 1. Phương trình dường thẳng

## a) Vecto chỉ phương của dường thắng

Cho đường thẳng Δ và vẹo Ứ khác Ứ. Vẹo Ứ được gọi là vẹo chi phương của đường thẳng Δ nếu giá của Ứ song song hoặc trùng với Δ.

Nhận xét: Nếu đi là vẹt chi phương của một đường thẳng thì kĩ (k ≠ 0) cũng là vẹt chi phương của đường thẳng đó.

#### Phương trình tham số của đường thẳng

Hệ phương trình  $ \begin{cases} x = x_0 + at \\ y = y_0 + bt, \text{ trong đó } a, b, c \text{ không đồng thời bằng } 0, t \text{ là tham } z = z_0 + ct \end{cases} $

số, được gọi là phương trình tham số của đường thẳng Δ đi qua  $ M_{0}(x_{0};y_{0};z_{0}) $ và có vectơ chỉ phương  $ \vec{u}=(a;b;c) $.

Nhận xét: Nếu đường thẳng d có phương trình tham số là  $ \begin{cases} x = x_0 + at \\ y = y_0 + bt \\ z = z_0 + ct \end{cases} $, trong đó

a, b, c không động thời bằng 0, t là tham số, thì vẹt ơ ũ = (a ; b ; c) là một vẹt ơ chi phương của đường thẳng d.

#### Phương trình chính tắc của đường thẳng

Trong không gian với hệ toạ độ Oxyz, cho đường thẳng Δ đi qua  $ M_{0}(x_{0};y_{0};z_{0}) $ và có vectơ chỉ phương  $ \vec{u}=(a;b;c) $.

Nếu  $ abc \neq 0 $ thì hệ phương trình  $ \frac{x - x_0}{a} = \frac{y - y_0}{b} = \frac{z - z_0}{c} $ được gọi là phương trình chính tắc của đường thẳng  $ \Delta $.

## d) Lập phương trình đường thẳng di qua hai điểm cho trước

Đường thẳng Δ đi qua hai điểm  $ A(x_{0};y_{0};z_{0}),B(x_{1};y_{1};z_{1}) $ có:

• Phương trình tham số là:  $ \begin{cases} x = x_0 + (x_1 - x_0)t \\ y = y_0 + (y_1 - y_0)t \quad (t\,\text{là}\,\text{tham}\,\text{sô}) \\ z = z_0 + (z_1 - z_0)t \end{cases} $

• Phương trình chính tắc là:  $ \frac{x - x_{0}}{x_{1} - x_{0}} = \frac{y - y_{0}}{y_{1} - y_{0}} = \frac{z - z_{0}}{z_{1} - z_{0}} $ ( $ x_{0} \neq x_{1}, y_{0} \neq y_{1}, z_{0} \neq z_{1} $).

### 2. Vị trí tương đối của hai đường thẳng

• Trong không gian với hệ trục toạ độ Oxyz, cho ba vectơ Ấu₁ = (a₁ ; b₁ ; c₁); Ấu₂ = (a₂ ; b₂ ; c₂); Ấu₃ = (a₃ ; b₃ ; c₃).

- Hai vectơ Ấu, Ấu, là cùng phương khi và chi khi [u, u] = 0.

- Ba vectơ Ấu, Ấu, Ấu, là động phẳng khi và chi khi [u, u], Ấu, Ấu.

* Trong không gian với hệ toạ độ Oxyz, cho hai đường thẳng phân biệt  $ \Delta_{1} $,  $ \Delta_{2} $ là lượt đi qua các điểm  $ M_{1} $,  $ M_{2} $ và tương ứng có  $ \vec{u}_{1} $,  $ \vec{u}_{2} $ là hai vectơ chi phương. Khi đó, ta có:

 $$ \Delta_{1}//\Delta_{2}\Leftrightarrow\begin{cases}\vec{u}_{1},\vec{u}_{2}\text{cùng phương}\\\vec{u}_{1},\overrightarrow{M_{1}M_{2}}\text{không cùng phương}\end{cases} $$ 

 $$ \begin{align*}\Leftrightarrow\begin{cases}\left[\vec{u}_1,\ \vec{u}_2\right]=\vec{0}\\\left[\vec{u}_1,\ \overrightarrow{M_1M_2}\right]\neq\vec{0}.\end{cases}\end{align*} $$ 

 $$ \Delta_{1}\stackrel{\cdot}{c\dot{a}t}\Delta_{2}\Leftrightarrow\begin{cases}\vec{u}_{1},\vec{u}_{2}\mathrm{~k h o\bar{o}n g~c\dot{u}n g~p h u r o n g~}\\\vec{u}_{1},\vec{u}_{2},\overrightarrow{M_{1}M_{2}}\mathrm{~d\dot{o}n g~p h\bar{a}n g~}\end{cases} $$ 

 $$ \begin{align*}\Leftrightarrow\begin{cases}\left[\vec{u}_1,\vec{u}_2\right]\neq\vec{0}\\\left[\vec{u}_1,\vec{u}_2\right].\overrightarrow{M_1M_2}=0.\end{cases}\end{align*} $$ 

 $$ \Delta_{1}\mathrm{v a}\Delta_{2}\mathrm{c h e o n h a u}\Leftrightarrow\left[\vec{u}_{1},\vec{u}_{2}\right].\overrightarrow{M_{1}M_{2}}\neq0. $$ 

Chú ý: Trong một số trường hợp, để xét vị trí tương đối của hai đường thẳng, ta có thể giải hệ phương trình được lập từ những phương trình xác định hai đường thẳng đó, sau đó xét cặp vectơ chỉ phương của hai đường thẳng đó có cùng phương hay không (nếu cần thiết).

### 3. Góc

#### Góc giữa hai đường thẳng

Trong không gian với hệ toạ độ Oxyz, cho hai đường thẳng Ả, và Ả, có vẹt chị phương lần lượt là Ả; (a₁; b₁; c₁), Ả₂ = (a₂; b₂; c₂). Khi đó, ta có:

$$ \cos(\Delta_{1},\Delta_{2})=\frac{\left|a_{1}a_{2}+b_{1}b_{2}+c_{1}c_{2}\right|}{\sqrt{a_{1}^{2}+b_{1}^{2}+c_{1}^{2}}\cdot\sqrt{a_{2}^{2}+b_{2}^{2}+c_{2}^{2}}}. $$ 

Nhận xét:  $ \Delta_{1} \perp \Delta_{2} \Leftrightarrow a_{1}a_{2} + b_{1}b_{2} + c_{1}c_{2} = 0. $

## b) Góc giữa đường thẳng và mặt phẳng

Trong không gian với hệ toa độ Oxyz, cho đường thẳng Δ có vectơ chi phương ũ = (a₁ ; b₁ ; c₁) và mặt phẳng (P) có vectơ pháp tuyển Ấn = (a₂ ; b₂ ; c₂). Gọi (Δ, (P)) là góc giữa đường thẳng Δ và mặt phẳng (P). Khi đó, ta có:

 $$ \sin(\Delta,\ (P))=\left|\cos(\vec{u},\ \vec{n})\right|=\frac{\left|\vec{u}\right.\ .\left.\vec{n}\right|}{\left|\vec{u}\right|\ .\left|\vec{n}\right|}=\frac{\left|a_{1}a_{2}+b_{1}b_{2}+c_{1}c_{2}\right|}{\sqrt{a_{1}^{2}+b_{1}^{2}+c_{1}^{2}}\ .\sqrt{a_{2}^{2}+b_{2}^{2}+c_{2}^{2}}}. $$ 

#### Góc giữa hai mặt phẳng

- Góc giữa hai mặt phẳng (P₁), (P₂) là góc giữa hai đường thẳng lần lượt vuông góc với hai mặt phẳng đó, kí hiệu là ((P₁), (P₂)).

• Trong không gian với hệ toạ độ Oxyz, cho hai mặt phẳng (P₁), (P₂) có vectơ pháp tuyến lần lượt là Ấn₁ = (A₁; B₁; C₁), Ấn₂ = (A₂; B₂; C₂). Khi đó, ta có:

 $$ \cos((P_{1}),(P_{2}))=\frac{\left|A_{1}A_{2}+B_{1}B_{2}+C_{1}C_{2}\right|}{\sqrt{A_{1}^{2}+B_{1}^{2}+C_{1}^{2}}\cdot\sqrt{A_{2}^{2}+B_{2}^{2}+C_{2}^{2}}}. $$ 

### B. ví dụ

#### Vấn đề 1. Xác định vector chỉ phương của đường thẳng

 $ \underline{\text{Vi du 1}} $ Vecto não sau dây là vecto chi phương của đường thẳng  $ \Delta $:  $ \begin{cases} x = 2 + 3t \\ y = -1 + 6t \\ z = 5 - 9t \end{cases} $

A.  $ \vec{u}_{1} = (2; -1; 5) $. B.  $ \vec{u}_{2} = (3; 6; 9) $. C.  $ \vec{u}_{3} = (1; 2; -3) $. D.  $ \vec{u}_{4} = (2; 1; 5) $.

Giải

Ta có vectơ Ấ = (3 ; 6 ; - 9) là một vectơ chi phương của đường thẳng Ấ, mà Ấ =  $ \frac{1}{3} \vec{u} $ nên vectơ Ấ = (1 ; 2 ; - 3) là một vectơ chi phương của đường thẳng Ấ. Chọn C.

#### Vấn đề 2. Lập phương trình dường thẳng

Phương pháp: Để lập phương trình đường thẳng, ta thường chỉ ra toạ độ một điểm thuộc đường thẳng và một vệ tố chỉ phương của đường thẳng đó.

Ví dụ 2) Lập phương trình tham số và phương trình chính tắc của đường thẳng Ả, biết Ả đi qua hai điểm A(2; -1; 4) và B(5; -10; -7).

Giải

Ta có:  $ \overrightarrow{AB} = (3; -9; -11) $ là một vectơ chi phương của đường thẳng ∆. Vây,

phương trình tham số của đường thẳng Δ là:  $ \begin{cases} x = 2 + 3t \\ y = -1 - 9t \quad (t là tham số); \\ z = 4 - 11t \end{cases} $

phương trình chính tắc của đường thẳng Δ là:  $ \frac{x-2}{3}=\frac{y+1}{-9}=\frac{z-4}{-11} $.

#### Vấn đề 3. Xét vị trí tương đối của hai đường thẳng

Ví dụ 3) Xác định vị trí tương đối của hai đường thẳng Ả₁, Ả₂ trong mỗi trường hợp sau:

 $$ \begin{aligned}a)\Delta_{1}:\begin{cases}x=-2+3t_{1}\\y=4+6t_{1}\\z=-1-12t_{1}\end{cases},\Delta_{2}:\begin{cases}x=5-t_{2}\\y=-1-2t_{2}\\z=3+4t_{2}\end{cases}(t_{1},t_{2}la tham só);\end{aligned} $$ 

b)

 $$ \begin{aligned}\text{Ⅲ }\Delta_{1}\because\frac{x+3}{2}=\frac{y-1}{-1}=\frac{z+4}{3},\Delta_{2}\therefore\frac{x-6}{-5}=\frac{y+5}{4}=\frac{z+5}{7};\end{aligned} $$ 

 $$ \begin{aligned}&c)\Delta_{1}\colon\frac{x+1}{1}=\frac{y-4}{-2}=\frac{z}{3},\Delta_{2}\colon\begin{cases}x=-11+5t\\y=-2+3t\quad(t là tham số ).\\z=3-2t\end{cases}\end{aligned} $$ 

Giải

a) Đường thẳng  $ \Delta_1 $ đi qua điểm  $ M_1(-2;4;-1) $ và có  $ \vec{u}_1=(3;6;-12) $ là vectơ chi phương. Đường thẳng  $ \Delta_2 $ đi qua điểm  $ M_2(5;-1;3) $ và có  $ \vec{u}_2=(-1;-2;4) $ là vectơ chi phương.

Ta có: Ứ1 = - 3u2, suy ra Ứ1, Ứ2 cùng phương;

 $ \overrightarrow{M_{1}M_{2}} = (7; -5; 4) $ và  $ \frac{3}{7} \neq \frac{6}{-5} $ nên  $ \overrightarrow{u_{1}}, \overrightarrow{M_{1}M_{2}} $ không cùng phương.

Vây  $ \Delta_{1} // \Delta_{2} $

b) Đường thẳng $\Delta_{1}$ đi qua điểm $M_{1}(-3;1,-4)$ và có $\vec{u}_{1}=(2,-1,3)$ là vectơ chi phương. Đường thẳng $\Delta_{2}$ đi qua điểm $M_{2}(6,-5,-5)$ và có $\vec{u}_{2}=(-5,4,7)$ là vectơ chi phương.

Ta có:  $ \frac{2}{-5} \neq \frac{-1}{4} $, suy ra  $ u_{1} $,  $ u_{2} $ không cùng phương.

 $$ \overrightarrow{M_{1}M_{2}}=(9;-6;-1), $$ 

 $$ \left[\vec{u}_{1},\vec{u}_{2}\right]=\left(\begin{vmatrix}{{{-1}}}&{{{3}}} \\{{{4}}}&{{{7}}}\end{vmatrix};\left|\begin{matrix}{{{3}}}&{{{2}}} \\{{{7}}}&{{{-5}}}\end{matrix}\right|;\left|\begin{matrix}{{{2}}}&{{{-1}}} \\{{{-5}}}&{{{4}}}\end{matrix}\right|\right)=(-19;-29;3). $$ 

Do  $ \left[\vec{u}_1, \vec{u}_2\right]. \overrightarrow{M_1M_2} = (-19). 9 + (-29). (-6) + 3. (-1) = 0\vec{n}\vec{n}\vec{u}_1, \vec{u}_2, \overrightarrow{M_1M_2} $

đồng phẳng. Vây  $ \Delta_1 $ cất  $ \Delta_2 $.

c) Đường thẳng $\Delta_{1}$ đi qua điểm $M_{1}(-1;4;0)$ và có $\vec{u}_{1}=(1;-2;3)$ là vectơ chi phương. Đường thẳng $\Delta_{2}$ đi qua điểm $M_{2}(-11;-2;3)$ và có $\vec{u}_{2}=(5;3;-2)$ là vectơ chi phương.

Ta có:  $ \overrightarrow{M_{1}M_{2}}=(-10,-6,3) $,

 $$ \left[\vec{u}_{1},\vec{u}_{2}\right]=\left(\left|\begin{matrix}{{{-2}}}&{{{3}}} \\{{{3}}}&{{{-2}}}\end{matrix}\right|;\left|\begin{matrix}{{{3}}}&{{{1}}} \\{{{-2}}}&{{{5}}}\end{matrix}\right|;\left|\begin{matrix}{{{1}}}&{{{-2}}} \\{{{5}}}&{{{3}}}\end{matrix}\right|\right)=(-5;17;13). $$ 

Do  $ \left[\vec{u}_1, \vec{u}_2\right] \cdot \overrightarrow{M_1M_2} = (-5) \cdot (-10) + 17 \cdot (-6) + 13 \cdot 3 = -13 \neq 0 $ nên  $ \vec{u}_1, \vec{u}_2 $,  $ \overrightarrow{M_1M_2} $ không đồng phẳng. Vây  $ \Delta_1 $ và  $ \Delta_2 $ chéo nhau.

Vấn đề 4. Tính góc giữa hai đường thẳng, góc giữa đường thẳng và mặt phẳng và góc giữa hai mặt phẳng

Ví dụ 4) Tinh góc giữa hai đường thẳng Ả, Ả, biết

 $$ \begin{aligned}\Delta_{1}:\begin{cases}x=7\\y=8+t_{1}\\z=-9+\sqrt{3}t_{1}\end{cases}và \Delta_{2}:\begin{cases}x=-1\\y=-2+t_{2}\quad(t_{1},t_{2} là tham số ).\\z=-\sqrt{3}t_{2}\end{cases}\end{aligned} $$ 

Giải

Hai đường thắng  $ \Delta_1 $ và  $ \Delta_2 $ có vectơ chỉ phương lần lượt là  $ \vec{u}_1 = (0; 1; \sqrt{3}) $,  $ \vec{u}_2 = (0; 1; -\sqrt{3}) $.

 $$ \mathrm{Ta}\mathrm{c}\dot{\mathrm{o}}:\cos(\Delta_{1},\Delta_{2})=\frac{\left|0,0+1,1+\sqrt{3},(-\sqrt{3})\right|}{\sqrt{0^{2}+1^{2}+(\sqrt{3})^{2}}\cdot\sqrt{0^{2}+1^{2}+(-\sqrt{3})^{2}}}=\frac{2}{4}=\frac{1}{2}. $$ 

Suy ra  $ \left(\Delta_{1},\Delta_{2}\right)=60^{\circ} $

Ví dụ 5) Cho hai dường thắng

 $$ \Delta_{1}:\frac{x-12}{9}=\frac{y+7}{-1}=\frac{z-5}{11},\quad\Delta_{2}:\frac{x-6}{-1}=\frac{y+4}{2}=\frac{z-13}{1}. $$ 

Chúng mình  $ \Delta_{1} \perp \Delta_{2} $

### Giải

Hai đường thắng  $ \Delta_{1} $ và  $ \Delta_{2} $ có vectơ chi phương lần lượt là  $ \vec{u}_{1} = (9; -1; 11) $,  $ \vec{u}_{2} = (-1; 2; 1) $.

Ta có:  $ \vec{u}_1 $,  $ \vec{u}_2 = 9 $,  $ (-1) + (-1) $,  $ 2 + 11 $,  $ 1 = 0 $. Suy ra  $ \Delta_1 \perp \Delta_2 $.

Ví dụ 6 Cho mặt phẳng (P) có vectơ pháp tuyến Ấn = (-2; 3; 5) và đường thẳng Ấn (A) có vectơ chi phương Ấn = (3; -1; 4). Tinh sin của góc giữa đường thẳng Ấn và mặt phẳng (P). Góc giữa đường thẳng Ấn và mặt phẳng (P) bằng bao nhiêu độ (làm tròn kết quả đến hàng đơn vị)?

Giải

Ta có:  $ \sin(\Delta, (P)) = \frac{\left|(-2), 3+3, (-1)+5, 4\right|}{\sqrt{(-2)^2 + 3^2 + 5^2}, \sqrt{3^2 + (-1)^2 + 4^2}} = \frac{11}{2\sqrt{247}} $

Suy ra ( \Delta , (P)) ≈ 20°.

Ví dụ 7) Tinh góc giữa hai mặt phẳng (P₁) và (P₂), biết (P₁) và (P₂) có hai vector pháp tuyến lần lượt là  $  \vec{n}_1 = (\sqrt{3}; 0; -1)  $,  $  \vec{n}_2 = (1; 0; -\sqrt{3})  $.

Ta có:  $ \cos((P_{1}),(P_{2}))=\frac{\left|\sqrt{3}\cdot1+0\cdot0+(-1)\cdot(-\sqrt{3})\right|}{\sqrt{(\sqrt{3})^{2}+0^{2}+(-1)^{2}}\cdot\sqrt{1^{2}+0^{2}+(-\sqrt{3})^{2}}}=\frac{\sqrt{3}}{2}. $

Suy ra ((P1), (P2)) = 30°.

Ví dụ 8) Trong mỗi ý a), b), c), d), chọn phương án: đùng (B) hoặc sai (S).

Cho hai đường thẳng $\Delta_{1}:\frac{x-1}{2}=\frac{y+2}{1}=\frac{z}{2},\quad\Delta_{2}:\frac{x-3}{-1}=\frac{y-4}{2}=\frac{z-5}{-2}$. Gọi $\alpha$ là góc giữa hai đường thẳng $\Delta_{1},\Delta_{2}$.

a) Vector $\vec{u}_{1} = (2; 1; 2)$ là một vector chi phương của đường thẳng $\Delta_{1}$.

b) Vecto có toạ độ (3 ; 4 ; 5) là một vecto chỉ phương của đường thẳng Ả.

c)  $ \cos\alpha = \frac{\vec{u}_1 \cdot \vec{u}_2}{|\vec{u}_1| \cdot |\vec{u}_2|} $ với  $ \vec{u}_1, \vec{u}_2 $ lần lượt là vector chi phương của  $ \Delta_1, \Delta_2 $.

d)  $ \alpha \approx 64^{\circ} $ (làm tròn đến hàng đơn vị của độ).

Giải

Ta có:  $ \vec{u}_{1} = (2, 1, 2) $ là một vectơ chi phương của đường thẳng  $ \Delta_{1} $;

 $ \vec{u}_{2}=(-1;2;-2) $ là một vectơ chi phương của đường thẳng  $ \Delta_{2} $.

Vi vectơ có toạ độ (3 ; 4 ; 5) không cùng phương với vectơ Ấu₂ = (-1 ; 2 ; - 2) nên vectơ đó không là một vectơ chi phương của đường thẳng Ấu.

Ta có: cos α =  $ \frac{\left|\vec{u}_{1} \cdot \vec{u}_{2}\right|}{\left|\vec{u}_{1}\right| \cdot \left|\vec{u}_{2}\right|} \neq \frac{\vec{u}_{1} \cdot \vec{u}_{2}}{\left|\vec{u}_{1}\right| \cdot \left|\vec{u}_{2}\right|} $. Ngoài ra,

 $$ \cos\alpha=\frac{\left|\vec{u}_{1}\cdot\vec{u}_{2}\right|}{\left|\vec{u}_{1}\right|\cdot\left|\vec{u}_{2}\right|}=\frac{\left|2\cdot(-1)+1\cdot2+2\cdot(-2)\right|}{\sqrt{2^{2}+1^{2}+2^{2}}\cdot\sqrt{(-1)^{2}+2^{2}+(-2)^{2}}}=\frac{4}{9}\Longrightarrow\alpha\approx64^{\circ}. $$ 

Đáp án: a) Đ, b) S, c) S, d) Đ.

## Vấn đề 5. Ứng dụng

Ví dụ 9) Trong không gian với hệ toạ độ Oxyz (đơn vị trên mỗi trục toạ độ là kilômet), một máy bay đang ở vị trí A(3,5; -2; 0,4) và sẽ ha cánh ở vị trí B(3,5; 5,5; 0) trên đường băng EG (Hinh 4).

Lập phương trình đường thẳng AB.

b) Hãy cho biết góc trượt (góc giữa đường bay AB và mặt phẳng nằm ngang (Oxy)) có nằm trong phạm vi cho phép từ 2,5° đến 3,5° hay không.

c) Có một lớp mây được mô phóng bởi một mặt phẳng (α) đi qua ba điểm M(5 ; 0 ; 0), N(0 ; −5 ; 0), P(0 ; 0 ; 0,5). Tìm toạ độ của điểm C là vị trí mà máy bay xuyên qua đám mây để hạ cánh.

d) Tìm toạ độ của điểm D trên đoạn thắng AB là vị trí mà máy bay ở độ cao 120 m.

e) Theo quy định an toàn bay, người phi công phải nhìn thấy điểm đầu E(3,5 : 4,5 : 0) của đường bằng ở độ cao tối thiểu là 120 m. Hỏi sau khi ra khỏi đảm mây, người phi công có đạt được quy định an toàn đồ hay không? Biết rằng tầm nhìn của người phi công sau khi ra khỏi đảm mây là 900 m (Người: R. Larson and B. Edwards, Calculus 10e, Cengage 2014).

Giải

a) Ta có:  $ \overrightarrow{AB} = (0, 7, 5; -0, 4) $.

Phương trình đường thẳng AB là:  $ \begin{cases} x = 3,5 \\ y = -2 + 7,5t \quad (t là tham số). \\ z = 0,4 - 0,4t \end{cases} $

b) Phương trình mặt phẳng (Oxy) là z = 0. Ta có:

 $ \sin(AB,(Oxy)) = \frac{\left|0,0+7,5,0+(-0,4),1\right|}{\sqrt{0^2+7,5^2+(-0,4)^2}, \sqrt{0^2+0^2+1^2}} = \frac{0,4}{\sqrt{56,41}} \Rightarrow (\Delta,(P)) \approx 3^\circ. $

Vi 2,5° < 3° < 3,5° nên góc trượt của máy bay nằm trong phạm vi cho phép.

c) Phương trình mặt phẳng (MNP) là:  $ \frac{x}{5} + \frac{y}{-5} + \frac{z}{0.5} = 1 \Leftrightarrow x - y + 10z - 5 = 0 $.

Vi C thuộc đường thẳng AB nên  $ C(3,5; -2 + 7,5c; 0,4 - 0,4c) (c \in \mathbb{R}) $.

Mà C thuộc mặt phẳng (MNP) nên

3,5 - (-2 + 7,5c) + 10 \cdot (0,4 - 0,4c) - 5 = 0 \Leftrightarrow c = \frac{9}{23} $.

Suy ra  $ C\left(\frac{7}{2}; \frac{43}{46}; \frac{28}{115}\right) $.

d) Vì D thuộc AB nên $D(3,5; -2+7,5d; 0,4-0,4d)$ ($d \in \mathbb{R}$). Mà $D$ có cao độ là 0,12 nên $0,4-0,4d=0,12 \Leftrightarrow d=0,7$. Vậy $D(3,5; 3,25; 0,12)$.

e) Ta có:  $ DE = \sqrt{(3, 5 - 3, 5)^2 + (4, 5 - 3, 25)^2 + (0 - 0, 12)^2} \approx 1,26 $ (km).

Vi 900 m = 0,9 km < 1,26 km nên phi công không nhìn thấy điểm E và không đạt được quy định an toàn bay.

## C. BÀI TẬP

22. Vector nào sau đây là một vector chi phương của đường thẳng

 $ \begin{cases} x = 7 \\ y = -9 + t \\ z = 16 \end{cases} $

A.  $ \vec{u_1} = (7; 9; -16) $.

B.  $ \vec{u_2} = (7; -9; 16) $.

C.  $ \vec{u_3} = (0; 1; 0) $.

D.  $ \vec{u_4} = (-7; 9; -16) $.

23. Đường thẳng đi qua điểm A(-8; -3; 7) và nhân ủi = (3; -4; 2) làm vecto chi phương có phương trình tham số là:

A.  $ \begin{cases} x = 3 - 8t \\ y = -4 - 3t \\ z = 2 + 7t \end{cases} $

B.  $ \begin{cases} x = -8 + 3t \\ y = -3 + 4t \\ z = 7 + 2t \end{cases} $

C.  $ \begin{cases} x = 3 + 8t \\ y = -4 + 3t \\ z = 2 + 7t \end{cases} $

D.  $ \begin{cases} x = -8 + 3t \\ y = -3 - 4t \\ z = 7 + 2t \end{cases} $

24. Dương thắng đi qua điểm  $ B(5; -2; 9) $ nhận  $ \vec{u} = (-17; 2; -11) $ làm vectơ chi phương có phương trình chính tắc là:

A.  $ \frac{x+5}{-17}=\frac{y-2}{2}=\frac{z+9}{-11}. $

B.  $ \frac{x-17}{5}=\frac{y+2}{-2}=\frac{z-11}{9}. $

C.  $ \frac{x-5}{-17}=\frac{y+2}{2}=\frac{z-9}{-11}. $

D.  $ \frac{x+17}{5}=\frac{y-2}{-2}=\frac{z+11}{9}. $

25. Đường thẳng Δ có phương trình chính tắc là:  $ \frac{x+1}{-7} = \frac{y+3}{-8} = \frac{z-2}{1} $. Phương trình tham số của Δ là:

A.  $ \begin{cases} x = 1 - 7t \\ y = 3 - 8t \\ z = -2 + t \end{cases} $

B.  $ \begin{cases} x = -1 + 7t \\ y = -3 + 8t \\ z = 2 + t \end{cases} $

C.  $ \begin{cases} x = -1 - 7t \\ y = 3 - 8t \\ z = 2 + t \end{cases} $

D.  $ \begin{cases} x = -1 - 7t \\ y = -3 - 8t \\ z = 2 + t \end{cases} $

26. Đường thắng Δ có phương trình tham số là:  $ \begin{cases} x = -2 - 21t \\ y = 3 + 5t \\ z = -6 - 19t \end{cases} $

Phương trình chính tác của Δ là:

A.  $ \frac{x + 21}{-2} = \frac{y - 5}{3} = \frac{z + 19}{-6} $.

B.  $ \frac{x + 2}{-21} = \frac{y - 3}{5} = \frac{z + 6}{-19} $.

C.  $ \frac{x + 2}{21} = \frac{y - 3}{5} = \frac{z + 6}{19} $.

D.  $ \frac{x - 2}{-21} = \frac{y + 3}{5} = \frac{z - 6}{-19} $.

27. Dường thắng đi qua điểm  $ M(x_0; y_0; z_0) $ và vương góc với mặt phẳng (Oxy) có phương trình tham số là:

A.  $ \begin{cases} x = x_0 \\ y = y_0 \\ z = t. \end{cases} $

B.  $ \begin{cases} x = t \\ y = y_0 \\ z = z_0. \end{cases} $

C.  $ \begin{cases} x = x_0 \\ y = t \\ z = z_0. \end{cases} $

D.  $ \begin{cases} x = x_0 + t \\ y = y_0 + t \\ z = z_0 + t. \end{cases} $

28. Cho đường thẳng Δ có phương trình tham số  $ \begin{cases} x = at \\ y = bt \quad với \quad a^2 + b^2 + c^2 > 0 \\ z = ct \end{cases} $

Côs in của góc giữa đường thẳng Δ và trục Oz bằng:

A.  $ \frac{c}{\sqrt{a^{2}+b^{2}+c^{2}}} $

B.  $ \frac{|a|}{\sqrt{a^{2}+b^{2}+c^{2}}} $

C.  $ \frac{|b|}{\sqrt{a^{2}+b^{2}+c^{2}}} $

D.  $ \frac{|c|}{\sqrt{a^{2}+b^{2}+c^{2}}} $

29. Cho đường thẳng Δ có phương trình tham số  $ \begin{cases} x = at \\ y = bt \quad v\dot{o}i \quad a^{2} + b^{2} + c^{2} > 0 \\ z = ct \end{cases} $

Sin của góc giữa đường thẳng Δ và mặt phẳng (Oyz) bằng:

A.  $ \frac{|a + b + c|}{\sqrt{a^{2} + b^{2} + c^{2}}} $.

B.  $ \frac{|a|}{\sqrt{a^{2} + b^{2} + c^{2}}} $.

C.  $ \frac{|b|}{\sqrt{a^{2} + b^{2} + c^{2}}} $.

D.  $ \frac{|c|}{\sqrt{a^{2} + b^{2} + c^{2}}} $.

30. Cho $a, b$ và $c$ khác $0$, cõsin của góc giữa hai mặt phẳng ($P$): $ax + by + c = 0$ và ($Q$): $by + cz + d = 0$ bằng:

A. $\frac{b^{2}}{\sqrt{(a^{2} + b^{2} + c^{2})(b^{2} + c^{2} + d^{2})}}$

B. $\frac{|b|}{\sqrt{(a^{2} + b^{2})(b^{2} + c^{2})}}$

C. $\frac{|b|}{\sqrt{(a^{2} + b^{2} + c^{2})(b^{2} + c^{2} + d^{2})}}$

D. $\frac{b^{2}}{\sqrt{(a^{2} + b^{2})(b^{2} + c^{2})}}$

Trong mỗi ý a), b), c), d) ở câu 31, 32, chọn phương án: đùng (Đ) hoặc sai (S).

31. Cho đường thẳng $\Delta: \frac{x + 2024}{2} = \frac{y + 2025}{3} = \frac{z + 2026}{6}$ và mặt phẳng (P):

$x - 2y - 2z + 1 = 0$. Gọi $\alpha$ là góc giữa đường thẳng $\Delta$ và mặt phẳng (P).

a) V Sector $\vec{u} = (2024; 2025; 2026)$ là một vector chi phương của đường thẳng $\Delta$

b) Vector có toạ độ (1; 2; 2) là một vector pháp tuyến của mặt phẳng (P).

c) $\sin \alpha = \frac{\vec{u} \cdot \vec{n}}{|\vec{u}| \cdot |\vec{n}|}$ với $\vec{u}$ là một vector chi phương của đường thẳng $d$, $\vec{n}$ là một vector pháp tuyến của mặt phẳng (P).

d) $\alpha \approx 50^\circ$ (làm tròn đến hàng đơn vị của độ).

32. Cho hai mặt phẳng (P₁): 2x - 3y - 6z + 7 = 0, (P₂): 2x + 2y + z + 8 = 0. Gọi Ở là góc giữa hai mặt phẳng (P₁) và (P₂).

a) Vectơ Ấn₁ = (2; -3; -6) là một vectơ pháp tuyến của mặt phẳng (P₁).

b) Vecto có toạ độ (2 ; - 2 ; 1) là một vecto pháp tuyến của mặt phẳng (P₂).

c)  $ \cos\alpha = \frac{\left|\vec{n}_{1} \cdot \vec{n}_{2}\right|}{\left|\vec{n}_{1}\right| \cdot \left|\vec{n}_{2}\right|} $ với  $ \vec{n}_{1}, \vec{n}_{2} $ lần lượt là vectơ pháp tuyến của mặt phẳng  $ (P_{1}), (P_{2}) $.

d)  $ \alpha \approx 69^{\circ} $ (làm tròn đến hàng đơn vị của độ).

33. Cho đường thẳng Δ có phương trình tham số:  $ \begin{cases} x = 2 - 3t \\ y = 4 + t \\ z = 5 - 2t \end{cases} $ (t là tham số).

a) Tim toa độ của điểm M thuộc đường thẳng Ả, biết M có hoành độ bằng 5.

b) Chứng minh rằng điểm N(8; 2; 9) thuộc đường thẳng

c) Chứng minh rằng điểm P(-1; 5; 4) không thuộc đường thẳng Δ. Lập phương trình tham số của đường thẳng Δ', biết Δ' đi qua P và song song với Δ.

d) Tìm toạ độ của điểm I, biết I là giao điểm của đường thẳng Δ và mặt phẳng (P):

 $ x - y + z + 9 = 0. $

34. Lập phương trình tham số và phương trình chính tắc của đường thẳng ở trong mỗi trường hợp sau:

a) Δ đi qua điểm A(2; -5; 7) và có vẹt chỉ phương Ấu = (-2; 3; 4);

b) Δ đi qua hai điểm M(-1; 0; 4) và N(2; 5; 3).

c) Δ đi qua điểm B(3 ; 2 ; - 1) và vương góc với mặt phẳng (P): 2x - 5y + 6z - 7 = 0.

35. Xác định vị trí tương đối của hai đường thẳng Ả, Ả, trong mỗi trường hợp sau:

a)  $ \Delta_1: \frac{x + 7}{5} = \frac{y - 1}{-7} = \frac{z + 2}{-2} $ và  $ \Delta_2: \begin{cases} x = -5 - 3t \\ y = -10 - 4t \\ z = 3 + 7t \end{cases} $ ( $ t $ là tham số);

b)  $ \Delta_1: \begin{cases} x = -2 + 5t \\ y = 1 - t \\ z = 3t \end{cases} \quad (t \text{ là tham số}) \text{ và } \Delta_2: \frac{x + 2}{4} = \frac{y - 1}{5} = \frac{z - 1}{-6}; $

c)

 $$ \text{Ⅲ }\Delta_{1}\frac{x}{3}=\frac{y+5}{2}=\frac{z-1}{-3}\text{ và }\Delta_{2}\frac{x-1}{-6}=\frac{y-3}{-4}=\frac{z-1}{6}. $$ 

36. Tính góc giữa hai đường thẳng  $ \Delta_{1} $,  $ \Delta_{2} $ trong mỗi trường hợp sau (làm tròn kết quả đến hàng đơn vị của độ nếu cần):

 $$ \Delta_{1}:\begin{cases}x=3+2t_{1}\\ y=-2+t_{1}\text{ⅵ }\Delta_{2}\\\ z=0\end{cases}\begin{cases}x=7+t_{2}\\ y=-3-t_{2}\text{ⅰ }(t_{1},t_{2}\text{ⅲ tham so};\\ z=2t_{2}\end{cases} $$ 

 $$ \Delta_{1}:\begin{cases}x=3+t\\ y=5-2t\ (t\ là\ tham\ sô)\ và\ \Delta_{2}:\ \dfrac{x+4}{2}=\dfrac{y+6}{2}=\dfrac{z-10}{-1};\\ z=7-2t\end{cases} $$ 

c)

 $$ \Delta_{1}:\frac{x+1}{-1}=\frac{y+4}{2}=\frac{z-5}{-3}\text{và }\Delta_{2}:\frac{x}{2}=\frac{y-3}{-1}=\frac{z+2}{-1}. $$ 

37. Tinh góc giữa đường thàng Δ và mặt phẳng (P) trong mối trường hợp sau (làm tròn kết quả đến hàng đơn vị của đô):

a)  $ \Delta: \begin{cases} x = 18 - \sqrt{3}t \\ y = 11 \\ z = 5 + t \end{cases} $ (t là tham số) và (P):  $ x - \sqrt{3}y - z - 3 = 0 $;

b)  $ \Delta: \frac{x-8}{2} = \frac{y-7}{-3} = \frac{z-6}{3} $ và (P):  $ 3x - 4y + 5z - 6 = 0 $.

38. Tính góc giữa hai mặt phẳng (làm tròn kết quả đến hàng đơn vị của độ):

 $$ (P_{1}):5x+12y-13z+14=0\mathrm{~và~}(P_{2}):3x+4y+5z-6=0. $$ 

39. Tình góc giữa mặt phẳng (P): x - y = 0 và mặt phẳng (Oyz).

40*. Cho hai đường thẳng $\Delta_{1}$: $\begin{cases} x = 11 - 3t_{1} \\ y = -5 + 4t_{1} \text{ và } \Delta_{2} \\ z = m t_{1} \end{cases}$ $\begin{cases} x = -4 + 5t_{2} \\ y = 2 + 3t_{2} \\ z = 2t_{2} \end{cases}$ với m là tham số thực; $t_{1}, t_{2}$ là tham số của phương trình đường thẳng. Tìm m để hai đường thẳng đó vuông góc với nhau.

## §3

# PHƯỜNG TRÌNH MẸT CẦU

### A. KIẾN THỨC CẤN NHỚ

### 1. Định nghĩa mặt cầu

Cho trước điểm I và số dương R. Mặt cầu tâm I bán kinh R là tập hợp tất cả các điểm trong không gian cách điểm I một khoảng bằng R.

Bán kinh

Nhận xét

Điểm M thuộc mặt cầu tấm I bán kinh R khi và chi khi IM = R.

• Diểm M nằm trong mặt cầu tăm I bán kinh R khi và chi khi IM < R.

Điểm M nằm ngoài mặt cầu tầm I bán kinh R khi và chi khi IM > R.

### 2. Phương trình mặt cầu

Phương trình của mặt cầu tâm I(a ; b ; c) bán kinh R là:

 $$ (x-a)^{2}+(y-b)^{2}+(z-c)^{2}=R^{2}. $$ 

Nhận xét

- Mỗi mặt cầu đều có phương trình đang:  $ x^{2} + y^{2} + z^{2} - 2ax - 2by - 2cz + d = 0 $.

• Phương trình  $ x^2 + y^2 + z^2 - 2ax - 2by - 2cz + d = 0 $ xác định một mặt cầu khi và chi khi  $ a^2 + b^2 + c^2 - d > 0 $. Ngoài ra, nếu  $ a^2 + b^2 + c^2 - d > 0 $ thì phương trình đó xác định mặt cầu tâm  $ I(a; b; c) $ và bán kính  $ R = \sqrt{a^2 + b^2 + c^2 - d} $.

### B. ví dụ

### Vấn đề 1. Xác định phương trình mặt cầu

 $ \underline{\text{Ví dụ I}} $ Phương trình nào sau đây là phương trình mặt cầu?

A.  $ (x-1)^2+(2y-3)^2+(z-4)^2=19^2. $

B.  $ (2x-1)^2+(y-3)^2+(z-4)^2=19^2. $

C.  $ (x-1)^2+(y-3)^2+(3z-4)^2=19^2. $

D.  $ (x-1)^2+(y-3)^2+(z-4)^2=19^2. $

Giải

Phương trình  $ (x-1)^{2}+(y-3)^{2}+(z-4)^{2}=19^{2} $ có dạng phương trình mặt cầu.

Chon D.

Ví dụ 2) Phương trình nào sau đây là phương trình mặt cầu?

A.  $ x^2 + y^2 + z^2 - 6x - 2y - 4z + 35 = 0. $

B.  $ x^2 + y^2 + z^2 - 8x - 4y - 6z + 29 = 0. $

C.  $ x^2 + y^2 + z^2 - 4x - 6y + 1 = 0. $

D.  $ x^2 + y^2 + z^2 - 6z + 10 = 0. $

Giải

Trong các phương trình, chi có  $ x^2 + y^2 + z^2 - 4x - 6y + 1 = 0 $ thoả măn điều kiện  $ a^2 + b^2 + c^2 - d > 0 $ với  $ a = 2 $,  $ b = 3 $,  $ c = 0 $,  $ d = 1 $. Suy ra phương trình đó là phương trình mất câu. Chọn C.

#### Vấn đề 2. Xác định tâm, bán kinh của mặt cầu

Ví dụ 3) Cho mất cầu có phương trình  $ (x - 8)^2 + (y + 7)^2 + z^2 = 4 $. Tìm tâm và bán kinh của mất cầu đó.

Giải

lạ có:

 $$ (x-8)^{2}+(y+7)^{2}+z^{2}=4\Leftrightarrow(x-8)^{2}+[y-(-7)]^{2}+(z-0)^{2}=2^{2}. $$ 

Vậy mặt cầu đã cho có tâm I(8 ; - 7 ; 0) và bán kinh R = 2.

Ví dụ 4 Cho mặt cầu có phương trình  $ x^{2} + y^{2} + z^{2} - 10x + 6z + 5 = 0 $. Xác định tâm và bán kinh của mặt cầu đó.

Giải

Ta có:  $ x^{2} + y^{2} + z^{2} - 10x + 6z + 5 = 0 $

 $$ \Leftrightarrow x^{2}-2\text{．}5\text{．}x+25+y^{2}+z^{2}+2\text{．}3\text{．}z+9=25+9-5 $$ 

 $$ \Leftrightarrow(x-5)^{2}+y^{2}+(z+3)^{2}=29. $$ 

Vậy mặt cầu đã cho có tâm I(5 ; 0 ; - 3) và bán kinh R =  $ \sqrt{29} $.

Ví dụ 5 Cho hai điểm A(6 ; - 8 ; 1) và B(0 ; 6 ; 3). Xác định tâm I của mặt cầu đường kinh AB.

Giải

Tâm I(x; y; z) là trung điểm của đoạn thắng AB nên

 $$ x=\frac{6+0}{2}=3,\ y=\frac{-8+6}{2}=-1,\ z=\frac{1+3}{2}=2. $$ 

Vây I(3 ; - 1 ; 2).

Ví dụ 6 Cho hai điểm I(-2; 4; 5) và M(1; 2; 7). Xác định bán kinh của mặt cầu tâm I, biết mặt cầu đi qua điểm M.

Giải

Bán kính của mặt cầu đó bằng: IM = √[1 - (-2)]^2 + (2 - 4)^2 + (7 - 5)^2 = √17.

#### Vấn đề 3. Lập phương trình mặt cầu

Ví dụ 7 Lập phương trình mặt cầu có tâm I(0; -12; 3) và bán kinh 4. Giải

Phương trình mặt cầu đó là:  $ (x - 0)^{2} + [y - (-12)]^{2} + (z - 3)^{2} = 4^{2} $

 $$ \Leftrightarrow x^{2}+(y+12)^{2}+(z-3)^{2}=16. $$ 

Ví dụ 8) Lập phương trình mặt cầu tâm I(-3; -7; 8), biết mặt cầu đi qua điểm A(-2; -5; 7).

Giải

Bán kính của mặt cầu đó bằng:

 $$ IA=\sqrt{\left[-2-(-3)\right]^{2}+\left[-5-(-7)\right]^{2}+(7-8)^{2}}=\sqrt{6}. $$ 

Vậy phương trình mặt cầu đó là:  $ (x + 3)^2 + (y + 7)^2 + (z - 8)^2 = 6 $.

Ví dụ 9) Trong mỗi ý a), b), c), d), chọn phương án: đúng (Đ) hoặc sai (S). Cho hai điểm A(1; -2; 3), B(2; 0; 1) và mặt cầu (S) tâm A đi qua B.

a) Mặt cầu (S) có bán kinh R = AB.

b) AB = 9.

c) Phương trình mặt cầu (S) là:  $ (x - 1)^{2} + (y + 2)^{2} + (z - 3)^{2} = 81 $.

d) Phương trình mặt cầu (S) là:  $ x^{2} + y^{2} + z^{2} - 2x + 4y - 6z + 5 = 0 $.

Giải

Mặt cầu (S) tâm A đi qua B nên có bán kinh bằng AB.

Ta có:  $ AB = \sqrt{(2 - 1)^2 + [0 - (-2)]^2 + (1 - 3)^2} = 3. $

Vây phương trình mặt cầu (S) là:

 $$ (x-1)^{2}+(y+2)^{2}+(z-3)^{2}=9\Leftrightarrow x^{2}+y^{2}+z^{2}-2x+4y-6z+5=0. $$ 

Đáp án: a) Đ, b) S, c) S, d) Đ.

### Vấn đề 4. Ứng dụng

Ví dụ 10) Hệ thống định vị toàn cầu (tên tiếng Anh là: Global Positioning System, viết tắt là GPS) là một hệ thống cho phép xác định chính xác vị trí của một vật thể trong không gian (Hình 5).

Ta có thể mô phỏng cơ chế hoạt động của hệ thống GPS trong không gian như sau: Trong cùng một thời điểm, toạ độ của một điểm M trong không gian sẽ được xác định bởi bốn vệ tinh cho trước, trên mỗi vệ tinh có một máy thu tin hiệu. Bảng cách so sánh sự sai lệch về thời gian từ lúc tín hiệu được phát đi với thời gian nhận phân hồi tín hiệu đó.

<div style="text-align: center;">Ánh: Vệ tinh GPS đang bay trên quý đạo quanh Trái Đất. (Nguồn: https://vi.wikipedia.org) Hình 5</div>

mỗi máy thu tín hiệu xác định được khoảng cách từ vệ tinh đến vị trí M cần tìm toạ độ. Như vậy, điểm M là giao điểm của bốn mặt cầu với tâm lân lượt là bốn vệ tinh đã cho.

Giả sử trong không gian với hệ toạ độ Oxyz, cho bốn vệ tinh A(3; - 1; 6), B(1; 4; 8), C(7; 9; 6), D(7; - 15; 18). Tìm toạ độ của điểm M trong không gian, biết khoảng cách từ các vệ tinh đến điểm M lần lượt là MA = 6, MB = 7, MC = 12, MD = 24.

##### Giải

Gọi toạ độ của M là (a ; b ; c). Khi đó, các số a, b, c thoả mãn các phương trình:

 $$ (a-3)^{2}+(b+1)^{2}+(c-6)^{2}=6^{2}\Leftrightarrow a^{2}+b^{2}+c^{2}-6a+2b-12c+10=0 $$ 

 $$ (a-1)^{2}+(b-4)^{2}+(c-8)^{2}=7^{2}\Leftrightarrow a^{2}+b^{2}+c^{2}-2a-8b-16c+32=0 $$ 

 $$ (a-7)^{2}+(b-9)^{2}+(c-6)^{2}=12^{2}\Leftrightarrow a^{2}+b^{2}+c^{2}-14a-18b-12c+22=0 $$ 

 $$ (a-7)^{2}+(b+15)^{2}+(c-18)^{2}=24^{2}\Leftrightarrow a^{2}+b^{2}+c^{2}-14a+30b-36c+22=0\ (4) $$

Trừ tương ứng theo từng về của (4) cho (3), (3) cho (1), (2) cho (1), ta có:

 $$ 48b-24c=0\Leftrightarrow c=2b $$ 

 $$ -8a-20b+12=0\Leftrightarrow a=\frac{-5b+3}{2} $$ 

 $$ 4a-10b-4c+22=0 $$ 

Thế (5) và (6) vào (7), ta có: - 10b + 6 - 10b - 8b + 22 = 0 ⇔ b = 1.

Suy ra a = -1, c = 2. Vây M(-1; 1; 2).

### C. BÀI TẬP

41. Phương trình nào sau đây là phương trình mặt cầu?

A.  $ (-3x-1)^{2}+(y-3)^{2}+(z-4)^{2}=12^{2} $.

B.  $ x^{2}+(y+5)^{2}+(7z-9)^{2}=11^{2} $.

C.  $ (x-2)^{2}+(5y-1)^{2}+(z-8)^{2}=19^{2} $.

D.  $ x^{2}+(y+5)^{2}+(z-18)^{2}=14^{2} $.

42. Phương trình nào sau đây là phương trình mặt cầu?

A.  $ x^{2} + y^{2} + z^{2} - 2y - 4z + 20 = 0. $

B.  $ x^{2} + y^{2} + z^{2} - 6x - 2y + 2z + 2 = 0. $

C.  $ x^{2} + y^{2} + z^{2} + 2x - 6y + 54 = 0. $

D.  $ x^{2} + y^{2} + z^{2} - 4x + 2y - 2z + 40 = 0. $

43. Tầm của mặt cầu (S):  $ (x + 5)^2 + (y - 6)^2 + (z + 7)^2 = 64 $ có toa độ là:

A.  $ (-5; 6; -7) $.

B.  $ (5; -6; 7) $.

C.  $ (-5; -6; 7) $.

D.  $ (5; -6; -7) $.

44. Tâm của mặt câu (S):  $ x^2 + y^2 + z^2 - x - 10z - 6 = 0 $ có toạ độ là:

A.  $ \left(-\frac{1}{2}; 0; -5\right) $.

B.  $ \left(\frac{1}{2}; 0; 3\right) $.

C.  $ \left(\frac{1}{2}; 0; 5\right) $.

D.  $ \left(-\frac{1}{2}; 0; -3\right) $.

45. Bán kinh của mặt cầu (S):  $ (x + 9)^2 + (y - 16)^2 + (z + 25)^2 = 16 $ bằng:

A. 4.

B. 256.

C. 8.

D. 16.

46. Bán kinh của mặt cầu (S):  $ x^{2} + y^{2} + z^{2} - 10x - 4y - 2z + 5 = 0 $ bằng:

A. 25. B. 10. C. 5. D. 225.

47. Phương trình của mặt cầu tâm  $ I(-11; -13; 15) $ bán kính 9 là:

A.  $ (x+11)^{2}+(y+13)^{2}+(z-15)^{2}=9. $

B.  $ (x+11)^{2}+(y+13)^{2}+(z-15)^{2}=81. $

C.  $ (x-11)^{2}+(y-13)^{2}+(z+15)^{2}=9. $

D.  $ (x-11)^{2}+(y-13)^{2}+(z+15)^{2}=81. $

48. Cho hai điểm  $ I(-2; 4; 5) $ và  $ M(1; 2; 7) $. Mặt cầu tâm  $ I $ di qua điểm  $ M $ có phương trình là:

A.  $ (x-2)^2 + (y+4)^2 + (z+5)^2 = \sqrt{17} $.

B.  $ (x+2)^2 + (y-4)^2 + (z-5)^2 = \sqrt{17} $.

C.  $ (x-2)^2 + (y+4)^2 + (z+5)^2 = \sqrt{17} $.

D.  $ (x+2)^2 + (y-4)^2 + (z-5)^2 = 17 $.

49. Cho hai điểm A(-12; 3; 7) và B(-10; -1; 5). Mất câu dường kinh AB có phương trình là:

A.  $ (x+11)^2 + (y-1)^2 + (z-6)^2 = 6 $.

B.  $ (x+11)^2 + (y-1)^2 + (z-6)^2 = \sqrt{24} $.

C.  $ (x+11)^2 + (y-1)^2 + (z-6)^2 = 36 $.

D.  $ (x-11)^2 + (y+1)^2 + (z+6)^2 = 24 $.

50. Trong mỗi ý (a), b), c), d), chon phuong ăn: đùng (D) hoặc sai (S).

Cho hai điểm M(0; -1; 1) và N(4; 1; 5).

a) Mất câu dường kinh M/N có tâm là trung điểm của doan thắng M/N.

b) Nếu / là trung điểm của M/N thì I(2; 0; 6).

c) Bàn kinh của mặt cầu dường kinh M/N bằng 3.

d) Phương trình mặt cầu dường kinh M/N là:

 $ (x-2)^2 + y^2 + (z-3)^2 = 9 $.

51. Cho mặt cầu (S) có phương trình:  $ x^{2} + (y + 4)^{2} + (z + 5)^{2} = 49 $.

a) Xác định toạ độ tâm I và tính bán kinh R của mặt cầu (S).

b) Điểm A(0 ; 3 ; - 5) có thuộc mặt cầu (S) hay không?

c) Điểm B(1 ; - 4 ; - 1) năm trong hay năm ngoài mặt cầu (S)?

d) Điểm C(7 ; 3 ; - 5) năm trong hay năm ngoài mặt cầu (S)?

e) Lập phương trình tham số của đường thẳng IC.

g) Xác định toạ độ các giao điểm M, N của đường thẳng IC và mặt cầu.

52. Lập phương trình mặt cầu (S) trong mỗi trường hợp sau:

a) (S) có tâm I(3; -4; 5) bán kinh 9.

b) (S) có tâm K(-4; 6; 7) và đi qua điểm H(-5; 4; 5).

c) (S) có đường kinh AB với A(1; 3; -1) và B(-1; -1; -5).

53. Cho mặt cầu (S) có tâm O(0 ; 0 ; 0) và bán kính 2.

a) Lập phương trình mặt cầu (S).

b) Lấy các điểm A(1 ; 0 ; -1) và B(1 ; 1 ; 0). Lập phương trình đường thẳng AB.

Tìm toạ độ các điểm C và D là giao điểm của đường thẳng AB và mặt cầu (S).

54. Tại một thời điểm có bão, khi đặt hệ trục toa độ Oxyz (đơn vị trên mỗi trục là kilômet) ở một vị trí phù hợp thì tâm bão có toa độ (300 ; 200 ; 1) (Hinh 6).

a) Lập phương trình mặt cầu để mô tả ranh giới bên ngoài vùng ảnh hưởng của bão ở cấp độ: bán kính gió mạnh từ cấp 10, giật từ cấp 12 trở lên khoảng 100 km tính từ tâm bão.

b) Tại một vị trí có toạ độ (350 ; 245 ; 1) thì có bị ảnh hưởng bởi con bão được mô tả ở câu a hay không?

(Nguồn: https://istockphoto.com) Hình 6

### BÀI TẬP CUỐI CHƯỚNG V

55. Vector nào sau đây là vector pháp tuyến của mặt phẳng (P):  $ -x + 2y - 9z + 7 = 0 $?

A.  $ \vec{n}_{1} = (1; 2; 9) $.

B.  $ \vec{n}_{2} = (1; -2; 9) $.

C.  $ \vec{n}_{3} = (1; 2; -9) $.

D.  $ \vec{n}_{4} = (-1; 2; 9) $.

56. Vector nào sau đây là vector pháp tuyến của mặt phẳng (Q):  $ 5x - 6z + 4 = 0 $?

A.  $ \vec{n}_{1} = (5; 0; -6) $.

B.  $ \vec{n}_{2} = (5; -6; 4) $.

C.  $ \vec{n}_{3} = (5; 0; 6) $.

D.  $ \vec{n}_{4} = (5; 6; 4) $.

57. Vecto nào sau đây là vector pháp tuyến của mặt phẳng (R): z - 2 = 0?

A.  $ \vec{n}_{1} = (1; -2; 0) $.

B.  $ \vec{n}_{2} = (1; 0; -2) $.

C.  $ \vec{n}_{3} = (0; 0; 1) $.

D.  $ \vec{n}_{4} = (1; 2; 0) $.

58. Vector nào sau đây là vector chi phương của đường thẳng d:  $ \begin{cases} x = 9 + 6t \\ y = -10 - 7t \\ z = 11 + 8t \end{cases} $

A.  $ \vec{u}_1 = (9; -10; 11) $.

B.  $ \vec{u}_2 = (6; 7; 8) $.

C.  $ \vec{u}_3 = (9; 10; 11) $.

D.  $ \vec{u}_4 = (6; -7; 8) $.

59. Vector nào sau đây là vector chi phương của đường thẳng d:  $ \begin{cases} x = 8 - t \\ y = 7 \\ z = -6 + 9t \end{cases} $?

A.  $ \vec{u}_1 = (-1; 0; 9) $.

B.  $ \vec{u}_2 = (8; 7; 6) $.

C.  $ \vec{u}_3 = (1; 0; 9) $.

D.  $ \vec{u}_4 = (8; 7; -6) $.

60. Vecto não sau dây là vecto chi phương của đường thẳng

 $ d:\frac{x-2}{15}=\frac{y+9}{-10}=\frac{z-7}{5} $?

A.  $ \vec{u}_{1}=(2,-9;7) $.

B.  $ \vec{u}_{2}=(-2;9;-7) $.

C.  $ \vec{u}_{3}=(15;10;5) $.

D.  $ \vec{u}_{4}=(3;-2;1) $.

61. Mặt cầu (S):  $ (x - 23)^2 + (y - 8)^2 + (z - 44)^2 = 81 $ có bản kính bằng:

A. 23.

B. 9.

C. 8.

D. 44.

62. Toạ độ tâm của mặt cầu (S):  $ (x + 19)^2 + (y - 20)^2 + (z + 21)^2 = 22 $ là:

A.  $ (-19; 20; -21) $.

B.  $ (19; 20; -21) $.

C.  $ (-19; 20; 21) $.

D.  $ (19; 20; 21) $.

63. Cho  $ a + b + c \neq 0 $.

Khoàng cách từ góc toạ độ O đến mặt phẳng  $ x + a + b + c = 0 $ bằng:

A.  $ |a + b + c| $.

B.  $ \frac{|a + b + c|}{a^2 + b^2 + c^2} $.

C.  $ \frac{\sqrt{a^2 + b^2 + c^2}}{|a + b + c|} $.

D.  $ \frac{|a + b + c|}{\sqrt{a^2 + b^2 + c^2}} $.

Trong mỗi ý a), b), c), d) ở câu 64, 65, 66, chọn phương án: đúng (Đ) hoặc sai (S).

64. Cho điểm I(1; 2; 3) và đường thẳng  $ \Delta: \frac{x-1}{2} = \frac{y}{1} = \frac{z+1}{-1} $. Gọi (P) là mặt phẳng đi qua I và vuông góc với đường thẳng  $ \Delta $.

a) Nếu ủ là một vectơ chỉ phương của đường thẳng Δ thì ủ là vectơ pháp tuyến của mặt phẳng (P).

b) Vecto có toạ độ (2 ; 1 ; - 1) là một vecto chi phương của đường thẳng Ấ.

c) Vecto có toạ độ (2 ; 1 ; 1) là một vecto pháp tuyến của mặt phẳng (P).

d) Phương trình mặt phẳng (P) là:  $ 2x + y + z - 9 = 0 $.

65. Cho hai mặt phẳng  $ (P_1) $:  $ x + 4y - 2z + 2 = 0 $,  $ (P_2) $:  $ -2x + y + z + 3 = 0 $.

a) Vectơ  $ n_1 = (1; 4; -2) $ là một vectơ pháp tuyến của mặt phẳng  $ (P_1) $.

b) Vectơ  $  \vec{n}_2 = (2; 1; 1)  $ là một vectơ pháp tuyến của mặt phẳng ( $ P_2 $).

c)  $ \vec{n}_{1} \cdot \vec{n}_{2} = 0 $ với  $ \vec{n}_{1} $,  $ \vec{n}_{2} $ là lượt là vẹo pháp tuyến của mặt phẳng  $ (P_{1}) $,  $ (P_{2}) $.

d) Hai mặt phẳng (P₁) và (P₂) vương góc với nhau.

66. Cho hai điểm A(0; 2; 0) và B(2; -4; 0).

a) Trung điểm I của đoạn thẳng AB có toạ độ là (1; -1; 0).

b) AB = 40.

c) Mặt cầu (S) tâm A và đi qua B có bán kinh R =  $ \sqrt{10} $.

d) Phương trình mặt cầu (S) tâm A và đi qua B là:

 $$ (x-1)^{2}+(y+2)^{2}+z^{2}=10. $$ 

67. Cho bốn điểm A(0 ; 1 ; 1), B(- 1 ; 0 ; 3), C(0 ; 0 ; 2) và D(1 ; 1 ; - 2).

a) Tìm toạ độ của các vẹt ơ ẤB, ẤC, [ẤB, ẤC].

b) Lập phương trình tham số của các đường thẳng AB và AC.

Lập phương trình tổng quát của mặt phẳng (ABC).

d) Chứng minh rằng bốn điểm A, B, C, D không đồng phẳng.

Tình khoảng cách từ điểm D đến mặt phẳng (ABC).

68. Lập phương trình tổng quát của mặt phẳng (P) trong mỗi trường hợp sau:

a) (P) đi qua điểm M(6; -7; 10) và có một vectơ pháp tuyến là Ấn = (1; -2; 1);

b) (P) đi qua điểm N(-3; 8; -4) và có một cặp vẹo chi phương là

 $$ \vec{u}=(3;-2;-1),\vec{v}=(1;4;-5); $$ 

c) (P) đi qua điểm I(1; -4; 0) và song song với mặt phẳng (Q):

 $$ 5x+6y-7z-8=0; $$ 

d) (P) đi qua điểm K(0; -3; 4) và vương góc với đường thẳng

 $$ \Delta:\frac{x-4}{-1}=\frac{y}{3}=\frac{z-7}{2}. $$ 

69. Lập phương trình của mặt cầu (S) trong mỗi trường hợp sau:

a) (S) có tâm I(-2; 3; 8) bán kinh R = 100;

b) (S) có tâm I(3; -4; 0) và đi qua điểm M(2; -3; 1);

c) (S) có đường kinh là AB với A(-1; 0; 4) và B(1; 0; 2).

70. Xác định vị trí tương đối của hai đường thẳng $\Delta_{1}$ và $\Delta_{2}$ trong mỗi trưởng hợp sau:

a) $\Delta_{1}:\frac{x+2}{9}=\frac{y-1}{27}=\frac{z-3}{-27}$ và $\Delta_{2}:\frac{x+1}{-1}=\frac{y-3}{-3}=\frac{z-7}{3}$

b) $\Delta_{1}:\frac{x+1}{-2}=\frac{y-6}{5}=\frac{z+3}{-4}$ và $\Delta_{2}:\frac{x+13}{7}=\frac{y+9}{5}=\frac{z+15}{8}$

c) $\Delta_{1}:\frac{x+3}{2}=\frac{y+6}{3}=\frac{z+3}{2}$ và $\Delta_{2}:\frac{x+17}{2}=\frac{y-33}{-3}=\frac{z+16}{2}$

71. Tình góc giữa hai đường thẳng Ả, và Ả, (làm tròn kết quả đến hàng đơn vị của độ),

 $$ \Delta_{1}:\begin{cases}x=8+\sqrt{2}t_{1}\\ y=9-t_{1}\\ z=10+t_{1}\end{cases}và \Delta_{2}:\begin{cases}x=-7+t_{2}\\ y=-9+\sqrt{2}t_{2}\\ z=11-t_{2}\end{cases}(t_{1},t_{2}là tham số ). $$ 

72. Tính góc giữa đường thẳng Δ và mặt phẳng (P) (làm tròn kết quả đến hàng đơn vị của độ), biết Δ:  $ \begin{cases} x = -1 - 5t \\ y = 4 - 4t \quad (t là tham số) \quad \text{và} \quad (P): 3x + 4y + 5z + 60 = 0. \\ z = -1 + 3t \end{cases} $

73. Tính góc giữa hai mặt phẳng  $ (P_{1}) $ và  $ (P_{2}) $ (làm tròn kết quả đến hàng đơn vị), biết  $ (P_{1}) $:  $ 5x + 12y - 13z - 14 = 0 $ và  $ (P_{2}) $:  $ 13x - 5y - 12z + 7 = 0 $.

74. Cho hai đường thắng  $ \Delta_1 : \begin{cases} x = 1 + 4t_1 \\ y = 9 + t_1 \\ z = 1 - 6t_1 \end{cases} $ và  $ \Delta_2 : \begin{cases} x = -4 + 3t_2 \\ y = 1 - 18t_2 \\ z = -5 - t_2 \end{cases} $ ( $ t_1, t_2 $ là tham số).

Chứng minh rằng  $ \Delta_1 \perp \Delta_2 $.

75. Một nguồn âm phát ra sóng âm là sóng cầu (mặt đầu sóng là mặt cầu). Khi gắn trên hệ trục toạ độ Oxyz với đơn vị trên mỗi trục là mét, vị trí nguồn âm có toạ độ (2 ; 3 ; 1), cường độ âm chuẩn phát ra có bán kinh 10 m.

a) Lập phương trình mặt cầu mô tả ranh giới nhận được cường độ âm chuẩn.

b) Tại một vị trí có toạ độ (5 ; 0 ; 2) có nhân được cường độ âm chuẩn từ nguồn âm trên hay không?

## LỜI GIẢI - HƯỚNG DẦN - ĐẠP SỐ

#### $1 PHƯỚNG TRÌNH MẸT PHẢNG

1. C. 2. C. 3. D. 4. B. 5. A. 6. C. 7. D.

8. a) D, b) S, c) S, d) D.

9. Ta có: (-3) - 3. 0 - 4. 1 + 1 = -6 ≠ 0 nên không thuộc (P).

Vectơ Ấn = (1; -3; 4) không là một vectơ pháp tuyển của mặt phẳng (P).

Vi (P) // (Q) mà n = (1; -3; 4) không là một vectơ pháp tuyến của mặt phẳng (P), tức là giá của nỗ không vương góc với (P) nên giá của nỗ không vương góc với (Q), hay n = (1; -3; 4) không là một vectơ pháp tuyến của mặt phẳng (Q). Ta có: m = (1; -3; -4) là một vectơ pháp tuyến của (P). Vi (R) // (P) nên m cũng là vectơ pháp tuyến của mặt phẳng (R). Phương trình mặt phẳng (R) là:

 $$ 1\ .(x+3)-3\ .(y-0)-4\ .(z-1)=0\Leftrightarrow x-3y-4z+7=0. $$ 

Đáp án: a) Đ, b) S, c) S, d) S.

10. a) Phương trình của mặt phẳng (P) là:

 $$ 3\;,\;(x-2)-4\;,\;(y-1)+5\;,\;(z+4)=0\Leftrightarrow3x-4y+5z+18=0. $$ 

b) Ta có:  $ [\vec{a}, \vec{b}] = (-7; 3; 6) $ là một vectơ pháp tuyến của (P). Phương trình của (P) là:  $ (-7) $,  $ (x-5) + 3 $,  $ (y+2) + 6 $,  $ (z-1) = 0 \Leftrightarrow -7x + 3y + 6z + 35 = 0 $.

c) Ta có:  $ \overrightarrow{AB} = (2; -8; -3) $,  $ \overrightarrow{AC} = (1; -7; -8) $.

Khi đó,  $ \vec{n} = \left[ \overrightarrow{AB}, \overrightarrow{AC} \right] = (43; 13; -6) $ là vectơ pháp tuyến của mặt phẳng (P). Vậy mặt phẳng (P) có phương trình là:

 $$ 43\ ,(x-0)+13\ ,(y-3)-6\ ,(z-7)=0\Leftrightarrow43x+13y-6z+3=0. $$ 

11. Phương trình mặt phẳng đó là:  $ \frac{x}{5} + \frac{y}{7} + \frac{z}{9} = 1 \Leftrightarrow 63x + 45y + 35z - 315 = 0. $

12. Ta có:  $ \overrightarrow{BC}=(-1,-1;2) $ là một vẹo pháp tuyến của (P). Vây phương trình (P) là:

 $ (-1) $.  $ (x-3)-1 $.  $ (y+4)+2 $.  $ (z-2)=0 \Leftrightarrow -x-y+2z-5=0. $

13. Vi (P) // (Q) nên Ấn = (3; - 2; 4) là một vectơ pháp tuyển của (P). Vậy phương trình (P) là:

 $$ 3.\ (x-4)-2.\ (y+3)+4.\ (z-7)=0\Leftrightarrow3x-2y+4z-46=0. $$ 

14. Ta có:  $ \vec{n}_1 = (1; -1; 0) $,  $ \vec{n}_2 = (0; 1; 1) $ là lượt là vẹt pháp tuyến của các mặt phẳng (Ω), (R) và  $ \left[\vec{n}_1, \vec{n}_2\right] = (-1; -1; 1) $.

Vi (P) vương góc với hai mặt phẳng (Ω), (R) nên vẹt pháp tuyến của (P) vương góc với cả  $ \vec{n}_1 $ và  $ \vec{n}_2 $. Suy ra  $ \left[\vec{n}_1, \vec{n}_2\right] $ là một vẹt pháp tuyến của (P).

Vây phương trình (P) là:

 $$ \begin{aligned}(-1),(x-1)-1,(y+2)+1,(z-4)=0\Leftrightarrow-x-y+z-5=0.\end{aligned} $$ 

15. Khoảng cách từ M(x₀; y₀; z₀) đến các mặt phẳng x-a=0, y-b=0, z-c=0 lần lượt bằng |x₀-a|, |y₀-b|, |z₀-c|.

16. a) Ta có $\vec{n}_{1}=(1;2;-3)$, $\vec{n}_{2}=(-4;-8;12)$ lần lượt là vectơ pháp tuyến của các mặt phẳng $(P_{1})$, $(P_{2})$. Do $\vec{n}_{2}=-4\vec{n}_{1}$, $3\neq(-4)$. $5$ nên $(P_{1})//(P_{2})$.

b) Chọn điểm $M_{0}\left(\frac{3}{4};0;0\right)\in(P_{2})$. Suy ra khoảng cách từ điểm $M_{0}$ đến mặt phẳng $(P_{1})$ bằng:

 $$ d(M_{0},(P_{1}))=\frac{\left|\frac{3}{4}+5\right|}{\sqrt{1^{2}+2^{2}+(-3)^{2}}}=\frac{23\sqrt{14}}{56}. $$ 

Vậy khoảng cách giữa hai mặt phẳng (P₁), (P₂) bằng  $ \frac{23\sqrt{14}}{56} $.

17. Đặt SA = a, SB = b, SC = c (a, b, c > 0). Vì các đường thẳng SA, SB, SC đối một vuông góc nên có thể gắn hệ trực toạ độ Oxyz thoả măn S(0 ; 0 ; 0), A(a ; 0 ; 0), B(0 ; b ; 0), C(0 ; 0 ; c).

Phương trình mặt phẳng (ABC) là:  $ \frac{x}{a} + \frac{y}{b} + \frac{z}{c} = 1 \Leftrightarrow \frac{x}{a} + \frac{y}{b} + \frac{z}{c} - 1 = 0. $

Khoảng cách từ điểm S đến mặt phẳng (ABC) là;

 $$ SH=\frac{\left|\frac{0}{a}+\frac{0}{b}+\frac{0}{c}-1\right|}{\sqrt{\left(\frac{1}{a}\right)^{2}+\left(\frac{1}{b}\right)^{2}+\left(\frac{1}{c}\right)^{2}}}=\frac{1}{\sqrt{\left(\frac{1}{a}\right)^{2}+\left(\frac{1}{b}\right)^{2}+\left(\frac{1}{c}\right)^{2}}}. $$ 

 $  \text{Suy ra} \frac{1}{SH^2} = \frac{1}{a^2} + \frac{1}{b^2} + \frac{1}{c^2} = \frac{1}{SA^2} + \frac{1}{SB^2} + \frac{1}{SC^2}  $

18. Phương trình mặt phẳng (ABC) là:  $ \frac{x}{1} + \frac{y}{2} + \frac{z}{3} = 1 $.

Ta có:  $ \frac{1}{1} + \frac{2}{2} + \frac{3}{3} \neq 1 $, suy ra điểm  $ D(1; 2; 3) $ không thuộc mặt phẳng (ABC).

Vãv A. B. C. D không đòng nhăe.

19. Xét hệ trục toạ đồ Oxyz thoà mãn A(0 ; 0 ; 0) trùng gốc O, B(2a ; 0 ; 0), D(0 ; 3a ; 0), A'(0 ; 0 ; 4a) (Hinh 7).

Ta có:  $ M(a;0;0) $,  $ N(0;2a;0) $,  $ P(0;0;3a) $,  $ C'(2a;3a;4a) $.

Phương trình mặt phẳng (MNP) là:

 $$ \frac{x}{a}+\frac{y}{2a}+\frac{z}{3a}=1\Leftrightarrow\frac{x}{a}+\frac{y}{2a}+\frac{z}{3a}-1=0. $$ 

<div style="text-align: center;">Hinh 7</div>

Khoảng cách từ điểm C' đến mặt phẳng (MNP) bằng:

 $$ \frac{\left|\frac{2a}{a}+\frac{3a}{2a}+\frac{4a}{3a}-1\right|}{\sqrt{\left(\frac{1}{a}\right)^{2}+\left(\frac{1}{2a}\right)^{2}+\left(\frac{1}{3a}\right)^{2}}}=\frac{23a}{7}. $$ 

20. a) Ta cò:  $ \overrightarrow{AB} = (a; 0; 0) $ và  $ \overrightarrow{DC} = \overrightarrow{AB} $, suy ra  $ \overrightarrow{DC} = (a; 0; 0) $.

Mà  $ D(0; b; 0) $ nên  $ C(a; b; 0) $.

Vì B(a ; 0 ; 0), C(a ; b ; 0) nên trung điểm M của BC có toạ độ là  $ \left(a ; \frac{b}{2} ; 0\right) $.

Vì S(0 ; 0 ; c), C(a ; b ; 0), D(0 ; b ; 0) nên trọng tâm G của tam giác SCD có toạ độ là  $ \left(\frac{a}{3} ; \frac{2b}{3} ; \frac{c}{3}\right) $.

b) Phương trình mặt phẳng (SBD) là:  $ \frac{x}{a} + \frac{y}{b} + \frac{z}{c} = 1 \Leftrightarrow \frac{x}{a} + \frac{y}{b} + \frac{z}{c} - 1 = 0 $.

c) Khoảng cách từ điểm G đến mặt phẳng (SBD) là:

 $$ \frac{\left|\frac{a}{3}+\frac{2b}{3}+\frac{c}{3}-1\right|}{\sqrt{\frac{1}{a^{2}}+\frac{1}{b^{2}}+\frac{1}{c^{2}}}}=\frac{abc}{3\sqrt{a^{2}b^{2}+b^{2}c^{2}+c^{2}a^{2}}}. $$ 

21. Phương trình mặt phẳng chứa mặt dưới của mái nhà là: z - 33 = 0. Khoảng cách từ điểm D đến mặt phẳng chứa mặt dưới của mái nhà bằng:  $ \frac{|35 - 33|}{\sqrt{0^2 + 0^2 + 1^2}} = 2 $. Vậy độ dày của mái nhà đó là 2 dm.

### $2 PHƯỚNG TRÌNH ĐƯỜNG THẰNG

22. C. 23. D. 24. C. 25. D. 26. B. 27. A. 28. D. 29. B. 30. D.

31. Ta có:  $ \vec{u} = (2, 3, 6) $ là một vectơ chỉ phương của đường thẳng  $ \Delta $,  $ \vec{n} = (1, -2, -2) $ là một vectơ pháp tuyến của mặt phẳng (P).

 $$ \sin\alpha=\frac{\left|\vec{u}\right.\left.\cdot\vec{n}\right|}{\left|\vec{u}\right|\left.\cdot\left|\vec{n}\right|\right.}=\frac{\left|2\cdot1+3\cdot\left(-2\right)+6\cdot\left(-2\right)\right|}{\sqrt{2^{2}+3^{2}+6^{2}}\cdot\sqrt{1^{2}+\left(-2\right)^{2}+\left(-2\right)^{2}}}=\frac{16}{21}. $$ 

Suy ra α ≈ 50°.

Đáp số: a) S, b) S, c) Đ, d) Đ.

32. Ta có:  $ \vec{n}_{1} = (2; -3; -6) $ là một vectơ pháp tuyến của mặt phẳng ( $ P_{1} $),  $ \vec{n}_{2} = (2; 2; 1) $ là một vectơ pháp tuyến của mặt phẳng ( $ P_{2} $).

 $$ \cos\alpha=\frac{\left|\vec{n}_{1}\right|\cdot\vec{n}_{2}}{\left|\vec{n}_{1}\right|\cdot\left|\vec{n}_{2}\right|}=\frac{\left|2\cdot2+(-3)\cdot2+(-6)\cdot1\right|}{\sqrt{2^{2}+(-3)^{2}+(-6)^{2}}\cdot\sqrt{2^{2}+2^{2}+1^{2}}}=\frac{8}{21}. $$ 

Suy ra α ≈ 68°.

Đáp án: a) Đ, b) S, c) Đ, d) S.

33. a) Vi M thuộc Δ nên M(2 - 3t; 4 + t; 5 - 2t) (t ∈ ℝ).

Ta có: 2 - 3t = 5, suy ra t = -1. Do đó 4 + t = 4 + (-1) = 3, 5 - 2t = 5 - 2. (-1) = 7.

Vây M(5 ; 3 ; 7).

b) Xét hệ phương trình  $ \begin{cases} 8 = 2 - 3t \\ 2 = 4 + t \iff t = -2 \\ 9 = 5 - 2t \end{cases} $. Suy ra tồn tại số thực t thoả mãn hệ phương trình đó. Vậy điểm  $ N(8; 2; 9) $ thuộc đường thẳng  $ \Delta $.

c) Xét hệ phương trình $\begin{cases} -1 = 2 - 3t \\ 5 = 4 + t \\ 4 = 5 - 2t \end{cases} \Leftrightarrow \begin{cases} t = 1 \\ t = 1 \\ t = \frac{1}{2} \end{cases}$

măn hệ phương trình đó. Vây điểm $P(-1; 5; 4)$ không thuộc đường thẳng $\Delta$.

Do $\vec{u}=(-3; 1; -2)$ là một vectơ chi phương của $\Delta$ và $\Delta$ // $\Delta'$ nên $\vec{u}=(-3; 1; -2)$ cũng là một vectơ chi phương của $\Delta$.

Phương trình tham số của đường thẳng Δ' là:  $ \begin{cases} x = -1 - 3t' \\ y = 5 + t' \quad (t' là tham số). \\ z = 4 - 2t' \end{cases} $

d) Vi I thuộc Δ nên  $ I(2 - 3a; 4 + a; 5 - 2a) \quad (a \in \mathbb{R}). \text{Mà I thuộc } (P) \text{ nên } (2 - 3a) - (4 + a) + (5 - 2a) + 9 = 0 \Leftrightarrow a = 2. \text{ Vây } I(-4; 6; 1). $

34. a) Phương trình tham số và phương trình chính tắc của Δ lần lượt là:

 $$ \begin{cases}x=2-2t\\y=-5+3t\quad(t là tham số ),\quad\frac{x-2}{-2}=\frac{y+5}{3}=\frac{z-7}{4}.\\z=7+4t\end{cases} $$ 

b) Ta có:  $ \overrightarrow{MN} = (3; 5; -1) $ là một vectơ chi phương của  $ \Delta $ Suy ra phương trình tham số và phương trình chính tắc của  $ \Delta $ lần lượt là:

 $$ \begin{cases}x=-1+3t\\y=5t\\z=4-t\end{cases}(t là tham sô),\frac{x+1}{3}=\frac{y}{5}=\frac{z-4}{-1}. $$ 

c) Vecto  $ \vec{n} = (2; -5; 6) $ là một vecto pháp tuyển của mặt phẳng (P) mà  $ \Delta \perp (P) $ nên  $ \vec{n} = (2; -5; 6) $ là một vecto chi phương của đường thẳng  $ \Delta $. Suy ra phương trình tham số và phương trình chính tắc của  $ \Delta $ lần lượt là:

$$ \begin{cases}x=3+2t\\y=2-5t\quad(t là tham số ),\quad\frac{x-3}{2}=\frac{y-2}{-5}=\frac{z+1}{6}.\\z=-1+6t\end{cases} $$ 

35. a) Dường thẳng $\Delta_{1}$ di qua điểm $M_{1}(-7;1;-2)$ và có $\vec{u}_{1}=(5;-7;-2)$ là vectơ chi phương.

Đường thẳng $\Delta_{2}$ di qua điểm $M_{2}(-5;-10;3)$ và có $\vec{u}_{2}=(-3;-4;7)$ là vectơ chi phương.

Ta có:  $ \frac{5}{-3} \neq \frac{-7}{-4} $, suy ra ũ1, ũ2 không cùng phương;

 $$ \overrightarrow{M_{1}M_{2}}=(2;-11;5), $$ 

 $$ \left[\vec{u}_{1},\vec{u}_{2}\right]=\left(\begin{vmatrix}{{{-7}}}&{{{-2}}} \\{{{-4}}}&{{{7}}}\end{vmatrix};\left|\begin{matrix}{{{-2}}}&{{{5}}} \\{{{7}}}&{{{-3}}}\end{matrix}\right|;\left|\begin{matrix}{{{5}}}&{{{-7}}} \\{{{-3}}}&{{{-4}}}\end{matrix}\right|\right)=(-57;-29;-41). $$ 

Do  $ \left[\vec{u}_1, \vec{u}_2\right]. \overrightarrow{M_1M_2} = (-57). 2 + (-29). (-11) + (-41). 5 = 0 $ nên  $ \vec{u}_1, \vec{u}_2 $,  $ \overrightarrow{M_1M_2} $ đồng phẳng. Vây  $ \Delta_1 $ và  $ \Delta_2 $ cắt nhau.

b) Đường thẳng Δ₁ đi qua điểm  $ M_{1}(-2;1;0) $ và có  $ \vec{u}_{1}=(5;-1;3) $ là vectơ chi phương.

Đường thẳng Δ₂ đi qua điểm M₂(-2; 1; 1) và có ũ₂ = (4; 5; -6) là vectơ chi phương.

Ta có:  $ \frac{5}{4} \neq \frac{-1}{5} $, suy ra ũ₁, ũ₂ không cùng phương;

 $$ \overrightarrow{M_{1}M_{2}}=(0;0;1), $$ 

 $$ \left[\vec{u}_{1},\vec{u}_{2}\right]=\left(\begin{vmatrix}{{{-1}}}&{{{3}}} \\{{{5}}}&{{{-6}}}\end{vmatrix};\left|\begin{matrix}{{{3}}}&{{{5}}} \\{{{-6}}}&{{{4}}}\end{matrix}\right|;\left|\begin{matrix}{{{5}}}&{{{-1}}} \\{{{4}}}&{{{5}}}\end{matrix}\right|\right)=(-9;42;29). $$ 

Do  $ \left[\vec{u}_{1},\vec{u}_{2}\right].\overrightarrow{M_{1}M_{2}}=(-9).0+42.0+29.1=29\neq0 $ nên  $ \vec{u}_{1},\vec{u}_{2},\overrightarrow{M_{1}M_{2}} $ không đồng phẳng.

Vây Ạ, Ạ, chéo nhau.

c) Đường thẳng  $ \Delta_{1} $ đi qua điểm  $ M_{1}(0; -5; 1) $ và có  $ \vec{u}_{1} = (3; 2; -3) $ là vectơ chi phương.

Đường thẳng  $ \Delta_{2} $ đi qua điểm  $ M_{2}(1;3;1) $ và có  $ \vec{u}_{2}=(-6;-4;6) $ là vectơ chi phương.

Ta có: - 2u1 = 2u2, suy ra 2u1, 2u2 cùng phương,

 $$ \overrightarrow{M_{1}M_{2}}=(1;8;0)\mathrm{~và~}\frac{3}{1}\neq\frac{2}{8}\mathrm{~nên~}\overrightarrow{u_{1}},\quad\overrightarrow{M_{1}M_{2}}\mathrm{~không~cùng~phương}. $$ 

Vây △ // Δ.

36. a) Hai đường thẳng  $ \Delta_{1} $ và  $ \Delta_{2} $ có vectơ chi phương lần lượt là  $ \vec{u}_{1} = (2; 1; 0) $,  $ \vec{u}_{2} = (1; -1; 2) $.

Ta có:  $ \cos(\Delta_{1},\Delta_{2})=\frac{\left|2\cdot1+1\cdot(-1)+0\cdot2\right|}{\sqrt{2^{2}+1^{2}+0^{2}}\cdot\sqrt{1^{2}+(-1)^{2}+2^{2}}}=\frac{\sqrt{30}}{30}. $

Suy ra ( \Delta , \Delta ) ≈ 79°.

b) Hai đường thẳng  $ \Delta_{1} $ và  $ \Delta_{2} $ có vectơ chi phương lần lượt là  $ \vec{u}_{1} = (1; -2; -2) $,  $ \vec{u}_{2} = (2; 2; -1) $.

Ta có:  $ \cos(\Delta_1, \Delta_2) = \frac{|1 \cdot 2 + (-2) \cdot 2 + (-2) \cdot (-1)|}{\sqrt{1^2 + (-2)^2 + (-2)^2} \cdot \sqrt{2^2 + 2^2 + (-1)^2}} = 0. $

Suy ra ( \Delta , \Delta ) = 90°.

c) Hai đường thẳng  $ \Delta_{1} $ và  $ \Delta_{2} $ có vecto chi phương lần lượt là  $ \vec{u}_{1}=(-1;2;-3) $,  $ \vec{u}_{2}=(2;-1;-1) $.

 $$ \mathrm{a}\mathrm{c}\mathrm{o}\mathrm{c}\mathrm{o}\mathrm{c}\mathrm{o}(\Delta_{1},\Delta_{2})=\frac{\left|(-1)\cdot2+2\cdot(-1)+(-3)\cdot(-1)\right|}{\sqrt{(-1)^{2}+2^{2}+(-3)^{2}}\cdot\sqrt{2^{2}+(-1)^{2}+(-1)^{2}}}=\frac{\sqrt{21}}{42}. $$ 

Suy ra ( \Delta 1, \Delta 2 ) ≈ 84°.

37. a) Dường thắng Δ có một vectơ chỉ phương là $\vec{u}=(-\sqrt{3}; 0; 1)$ và mặt phẳng (P) có một vectơ pháp tuyến là $\vec{n}=(1;-\sqrt{3};-1)$.

Ta có:  $ \sin(\Delta, (P)) = \frac{\left|(-\sqrt{3}) \cdot 1 + 0 \cdot (-\sqrt{3}) + 1 \cdot (-1)\right|}{\sqrt{(-\sqrt{3})^2 + 0^2 + 1^2} \cdot \sqrt{1^2 + (-\sqrt{3})^2 + (-1)^2}}} = \frac{\sqrt{15} + \sqrt{5}}{10} $.

Suy ra ( \Delta , ( P ) ) ≈ 38°.

b) Đường thẳng Δ có một vectơ chi phương là  $ \vec{u} = (2; -3; 3) $ và mặt phẳng (P) có một vectơ pháp tuyến là  $ \vec{n} = (3; -4; 5) $.

 $$ \mathrm{a}\mathrm{c}\dot{\mathrm{o}}:\sin(\Delta,\ (P))=\frac{\left|2\ .3+(-3)\ .(-4)+3\ .5\right|}{\sqrt{2^{2}+(-3)^{2}+3^{2}}\ .\sqrt{3^{2}+(-4)^{2}+5^{2}}}=\frac{3\sqrt{11}}{10}. $$ 

Suy ra  $ \left(\Delta,\left(P\right)\right)\approx84^{\circ} $

38. Hai mặt phẳng ( $ P_{1} $), ( $ P_{2} $) có vectơ pháp tuyến lần lượt là  $ \vec{n}_{1} = (5; 12; -13) $,  $ \vec{n}_{2} = (3; 4; 5) $.

 $$ \mathrm{Ta}\mathrm{c}\mathrm{o}:\cos((P_{1}),(P_{2}))=\frac{\left|5\cdot3+12\cdot4+(-13)\cdot5\right|}{\sqrt{5^{2}+12^{2}+(-13)^{2}}\cdot\sqrt{3^{2}+4^{2}+5^{2}}}=\frac{1}{65}. $$ 

Suy ra ((P1), (P2) ≈ 89°.

39. Gốc giữa hai mặt phẳng đỏ bằng 45°

40*. Hai đường thắng vuông góc với nhau khi hai vectơ chi phương vuông góc với nhau. Suy ra (-3).  $ 5 + 4.3 + m.2 = 0 \Leftrightarrow m = \frac{3}{2} $.

#### $3 PHƯỚNG TRÌNH MẸT CẤU

41. D. 42. B. 43. A. 44. C. 45. A. 46. C. 47. B. 48. D. 49. A.

50. a) B, b) S, c) D, d) D.

1. a) Tầm I(0 ; - 4 ; - 5), bán kính R = 7.

b) LẠ = 7 = R nền A thuộc mặt cầu.

c) IB =  $ \sqrt{17} < R $ nền B nằm trong mặt cầu.

d) IC =  $ \sqrt{98} > R $ nền C nằm ngoài mặt cầu.

e) Ta có:  $ \overrightarrow{IC} = (7; 7; 0) $, chọn  $ \overrightarrow{i} = \frac{1}{7} \overrightarrow{IC} = (1; 1; 0) $ là một vecto chi phương của đường thẳng IC. Suy ra phương trình tham số của đường thẳng IC là:  $ \begin{cases} x = t \\ y = -4 + t \\ z = -5 \end{cases} $

g) Toạ độ giao điểm của đường thẳng IC và mặt cầu (S) tương ứng với tham số tổ thỏa mãn:

 $ \hat{t}^{2} + (-4 + t + 4)^{2} + (-5 + 5)^{2} = 49 \Leftrightarrow t^{2} = \frac{49}{2} \Leftrightarrow t = \frac{7\sqrt{2}}{2} \text{ hoặc } t = \frac{-7\sqrt{2}}{2}. $

Vây M  $ \left(\frac{7\sqrt{2}}{2}\right. $;  $ -4 + \frac{7\sqrt{2}}{2} $;  $ -5\right) $, N  $ \left(\frac{-7\sqrt{2}}{2}\right. $;  $ -4 - \frac{7\sqrt{2}}{2} $;  $ -5\right) $.

52. a)  $ (x-3)^{2}+(y+4)^{2}+(z-5)^{2}=81. $

b)  $ (x+4)^{2}+(y-6)^{2}+(z-7)^{2}=9. $

c)  $ x^{2}+(y-1)^{2}+(z+3)^{2}=9. $

53. a) Phương trình mặt cầu (S) là:  $ x^2 + y^2 + z^2 = 4 $.

b) Phương trình đường thẳng AB là:  $ \begin{cases} x = 1 \\ y = t \\ z = -1 + t \end{cases} $ (t là tham số).

Toa độ giao điểm của đường thẳng AB và mặt cầu (S) tương ứng với tham số t thỏa

măn:  $ 1^2 + t^2 + (-1 + t)^2 = 4 \Leftrightarrow t = \frac{1 + \sqrt{5}}{2} $ hoặc  $ t = \frac{1 - \sqrt{5}}{2} $.

 $$ \mathrm{V}\hat{\mathrm{a}}\mathrm{y}\;C\Biggl(1;\frac{1+\sqrt{5}}{2};\frac{-1+\sqrt{5}}{2}\Biggr),\;D\Biggl(1;\frac{1-\sqrt{5}}{2};\frac{-1-\sqrt{5}}{2}\Biggr). $$ 

54. a) Phương trình mặt cầu cần tìm là:

 $$ (x-300)^{2}+(y-200)^{2}+(z-1)^{2}=100^{2}. $$ 

b) Khoảng cách từ vị trí có toạ độ (350 ; 245 ; 1) đến tâm bảo là:

 $$ d=\sqrt{(350-300)^{2}+(245-200)^{2}+(1-1)^{2}}=\sqrt{4\ 525}<100. $$ 

Vậy vị trí có toạ độ (350 ; 245 ; 1) bị ảnh hưởng bởi con bão.

## BÀI TẬP CUỐI CHƯƠNG V

55. B. 56. A. 57. C. 58. D. 59. A. 60. D. 61. B. 62. A. 63. A.

64. a) B, b) D, c) S, d) S.

65. a) D, b) S, c) D, d) D.

66. a) D, b) S, c) S, d) S.

67. a) Ta có:  $ \overrightarrow{AB} = (-1; -1; 2) $,  $ \overrightarrow{AC} = (0; -1; 1) $,  $ \overrightarrow{AB} \cdot \overrightarrow{AC} = (1; 1; 1) $.

b) Phương trình tham số của đường thẳng AB là:  $ \begin{cases} x = -t_1 \\ y = 1 - t_1 \\ z = 1 + 2t_1 \end{cases} $ ( $ t_1 $ là tham số).

Phương trình tham số của đường thẳng AC là:  $ \begin{cases} x = 0 \\ y = 1 - t_2 \\ z = 1 + t_2 \end{cases} $ ( $ t_2 $ là tham số).

c) Phương trình mặt phẳng (ABC) là:  $ x + v + z - 2 = 0 $.

d) Ta có:  $ 1 + 1 - 2 - 2 \neq 0 $. Suy ra toạ độ của điểm  $ D(1; 1; -2) $ không thoả mãn phương trình  $ x + y + z - 2 = 0 $. Vậy D không thuộc mặt phẳng (ABC) hay A, B, C, D không đồng phẳng.

e) Khoảng cách từ điểm D đến mặt phẳng (ABC) là:  $ \frac{|1+1-2-2|}{\sqrt{1^2+1^2+1^2}} = \frac{2\sqrt{3}}{3} $.

(a)  $ x - 2y + z - 30 = 0. $

b)  $ x + y + z - 1 = 0. $

c)  $ 5x + 6y - 7z + 19 = 0. $

d)  $ -x + 3y + 2z + 1 = 0. $

69. a)  $ (x + 2)^{2} + (y - 3)^{2} + (z - 8)^{2} = 10000. $

b)  $ (x-3)^{2}+(y+4)^{2}+z^{2}=3. $

c)  $ x^{2} + y^{2} + (z - 3)^{2} = 2. $

b)  $ \Delta_{1}, \Delta_{2} $ cắt nhau. c)  $ \Delta_{1}, \Delta_{2} $ chéo nhau.

71.  $ (\Delta_{1}, \Delta_{2}) \approx 76^{\circ} $

72.  $ (\Delta, (P)) \approx 19^{\circ} $

73.  $ (P_{1}), (P_{2})) \approx 62^{\circ} $

74. Hai đường thẳng $\Delta_{1}$, $\Delta_{2}$ có vector chi phương lần lượt là: $\vec{u}_{1} = (4; 1; -6)$ và $\vec{u}_{2} = (3; -18; -1)$. Ta có:

 $$ \vec{u}_{1}\ ,\vec{u}_{2}=4\ ,3+1\ .(-18)+(-6)\ .(-1)=0, $$ 

Suy ra  $ \Delta_{1} \perp \Delta_{2} $

75. a)  $ (x - 2)^{2} + (y - 3)^{2} + (z - 1)^{2} = 100. $

b) Khoảng cách từ vị trí có toạ độ (5 ; 0 ; 2) đến nguồn âm là:

 $$ d=\sqrt{(5-2)^{2}+(0-3)^{2}+(2-1)^{2}}=\sqrt{19}<10. $$ 

Vậy tại vị trí có toạ độ (5 ; 0 ; 2) có thể nhận được cường độ âm chuẩn từ nguồn âm.

# MỘT SỐ YẾU TỐ XÁC SUẤT

# S1 XÁC SUẤT CÓ ĐIỂU KIỆN

## A. KIẾN THỨC CẦN NHỒ

Trong mục này, ta luôn giả thiết phép thử T có không gian mẫu là tập hợp Ω gồm hữu hạn phần tử và các kết quả của phép thử là đồng khả năng, các biến cố đều liên quan đến phép thử đó.

### 1. Định nghĩa

Cho hai biến có A và B. Xác suất của biến có A với điều kiện biến có B đã xảy ra được gọi là xác suất của A với điều kiện B, kí hiệu là P(A | B).

Nếu P(B) > 0 thì P(A | B) =  $ \frac{P(A \cap B)}{P(B)} $.

### 2. Nhận xét

Từ định nghĩa của xác suất có điều kiện, ta suy ra:

Nếu P(B) > 0 thì P(A ∩ B) = P(B). P(A | B).

Người ta chúng mình được rằng:

Nếu A, B là hai biển cổ bất kì thi

 $$ \mathrm{P}(A\cap B)=\mathrm{P}(A),\mathrm{P}(B\mid A)=\mathrm{P}(B),\mathrm{P}(A\mid B). $$ 

Công thức trên được gọi là công thức nhân xác suất.

• Cho hai biển cổ A và B với P(B) > 0. Khi đó, ta có:

 $$ \mathrm{P}(A\mid B)=\frac{n(A\cap B)}{n(B)}. $$ 

• Cho A và B là hai biển cố với 0 < P(A) < 1, 0 < P(B) < 1. Khi đó, A và B là hai biển cố độc lập khi và chi khi

 $$ \mathrm{P}(A)=\mathrm{P}(A\mid B)=\mathrm{P}(A\mid\overline{B})\mathrm{~v}\dot{\mathrm{a}}\mathrm{~P}(B)=\mathrm{P}(B\mid A)=\mathrm{P}(B\mid\overline{A}). $$

### B. ví dụ

##### Vấn đề 1. Tính xác suất có điều kiện

Ví dụ 1) Cho hai biến cổ A, B có P(A) = 0, 5; P(B) = 0, 8; P(A ∩ B) = 0, 4. Tinh các xác suất sau: P(A | B); P(B | A).

Giải

Ta có:  $ \mathrm{P}(A \mid B) = \frac{\mathrm{P}(A \cap B)}{\mathrm{P}(B)} = \frac{0, 4}{0, 8} = 0, 5; $  $ \mathrm{P}(B \mid A) = \frac{\mathrm{P}(B \cap A)}{\mathrm{P}(A)} = \frac{0, 4}{0, 5} = 0, 8. $

Trong mỗi ý a), b), c), d) ở Vị dụ 2, 3, chọn phương án: đùng (Đ) hoặc sai (S).

Ví dụ 2) Cho hai xúc xắc cân đối và đồng chất. Gieo lần lượt từng xúc xắc trong hai xúc xắc đó.

Xét các biến cố:

A: “Tổng số chấm trên hai xúc xác bằng 5”

B: "Xúc xác thử nhất xuất hiện mặt 2 chấm".

a) Xác suất để tổng số chấm xuất hiện trên hai xúc xác bằng 5, biết rằng xúc xác thứ nhất xuất hiện mặt 2 chấm, là xác suất có điều kiện P(A | B).

b)  $ \mathrm{P}(A \cap B) = \frac{1}{6} $

c)  $ \mathrm{P}(B)=\frac{1}{6} $

d) Xác suất để tổng số chấm xuất hiện trên hai xúc xác bằng 5, biết rằng xúc xác thứ nhất xuất hiện mặt 2 chấm, là  $ \frac{1}{6} $.

Giải

Không gian mẫu có số phần tử là 36.

Xác suất để tổng số chấm xuất hiện trên hai xúc xắc bằng 5, biết rằng xúc xắc thứ nhất xuất hiện mặt 2 chấm, là xúc suất có điều kiện P(A | B). Biến cố A ∩ B chỉ có 1 kết quả thuận lợi là xúc xắc thứ nhất xuất hiện mặt 2 chấm và xúc xắc thứ hai xuất hiện mặt 3 chấm nên P(A ∩ B) =  $ \frac{1}{36} $. Có 6 khả năng xây ra khi xúc xắc thứ nhất xuất hiện mặt 2 chấm nên P(B) =  $ \frac{6}{36} = \frac{1}{6} $. Suy ra

 $$ \begin{aligned}&\textcircled{6} \\ &\mathrm{P}(A\mid B)=\frac{\mathrm{P}(A\cap B)}{\mathrm{P}(B)}=\frac{\frac{1}{36}}{\frac{1}{6}}=\frac{1}{6}.\\ \end{aligned} $$ 

Đáp án: a) Đ, b) S, c) Đ, d) Đ.

Ví dụ 3 Cho hai đồng xu cân đối và đồng chất. Tung lần lượt từng đồng xu trong hai đồng xu đó.

Xét các biến cố:

A: “Đồng xu thứ hai xuất hiện mặt sắp (S)”,

B: “Động xu thứ nhất xuất hiện mặt ngựa (N)”.

Xác suất để động xu thứ hai xuất hiện mặt S, biết rằng động xu thứ nhất xuất hiện mặt N, là xác suất có điều kiện P(A | B).

b)  $ \mathrm{P}(A \cap B) = \frac{1}{4} $.

c)  $ \mathrm{P}(B)=\frac{1}{4} $

d) Xác suất để động xu thứ hai xuất hiện mặt S, biết rằng động xu thứ nhất xuất hiện mặt N, là  $ \frac{1}{2} $.

Giải

Không gian mẫu có số phần tử là 4.

Xác suất đề đồng xu thứ hai xuất hiện mặt S, biết rằng đồng xu thứ nhất xuất hiện mặt N, là xác suất có điều kiện P(A | B). Biến cổ A ∩ B chỉ có 1 kết quả thuận lợi là đồng xu thứ nhất xuất hiện mặt N, đồng xu thứ hai xuất hiện mặt S nên P(A ∩ B) =  $ \frac{1}{4} $. Có 2 khả năng xảy ra khi đồng xu thứ nhất xuất hiện mặt N nên P(B) =  $ \frac{2}{4} = \frac{1}{2} $. Suy ra

 $$ \mathrm{P}(A\mid B)=\frac{\mathrm{P}(A\cap B)}{\mathrm{P}(B)}=\frac{\frac{1}{4}}{\frac{1}{2}}=\frac{1}{2}. $$ 

Đáp án: a) Đ, b) Đ, c) S, d) Đ.

Ví dụ 4) Một nhóm học sinh tham gia một kì thi Olympic Tín học của trường, trong đó có 5 học sinh lớp 12A. Sau khi chấm điểm, có 3 học sinh lớp 12A đạt giải. Chọn ngẫu nhiên 1 học sinh trong nhóm học sinh trên. Tính xác suất chọn được học sinh đạt giải, biết rằng học sinh đó thuộc lớp 12A.

Giải

Xét các biến cố:

A: "Chọn được học sinh đạt giải".

B: “Chọn được học sinh thuộc lớp 12A”

Khi đó, xác suất chọn được học sinh đạt giải, biết rằng học sinh đó thuộc lớp 12A, là xác suất của A với điều kiện B.

Ta có:  $ n(B) = 5 $,  $ n(A \cap B) = 3 $. Suy ra  $ \mathrm{P}(A \mid B) = \frac{n(A \cap B)}{n(B)} = \frac{3}{5} $.

Vậy xác suất chọn được học sinh đạt giải, biết rằng học sinh đó thuộc lớp 12A, là  $ \frac{3}{5} $.

Ví dụ 5) Một hộp có 3 quả bóng màu xanh, 4 quả bóng màu đỏ; các quả bóng có kích thước và khối lượng như nhau. Lấy bóng ngẫu nhiên hai lần liên tiếp, trong đó mỗi lần lấy ngẫu nhiên một quả bóng trong hộp, ghi lại màu của quả bóng lấy ra và bỏ lại quả bóng đó vào hộp. Xét các biến cố:

A: “Quả bóng màu xanh được lấy ra ở lần thứ nhất”,

B: “Quả bóng màu đỏ được lấy ra ở lần thứ hai”.

a) Tính các xác suất P(A), P(A | B), P(A |  $ \overline{B} $), P(B), P(B | A), P(B |  $ \overline{A} $).

b) Chứng minh rằng A, B là hai biến cổ độc lập.

Giải

a) Không gian mẫu có số phần tử là 49.

Một kết quả thuận lợi cho biến cổ A là một cách chọn quả bóng màu xanh ở lần thứ nhất (có 3 khả năng) và chọn quả bóng tuy ý ở lần thứ hai (có 7 khả năng). Do đó  $ n(A) = 3 $. 7 = 21, suy ra  $ n(\overline{A}) = 49 - n(A) = 49 - 21 = 28 $.

Tương tự, ta có:  $ n(B) = 7 $,  $ 4 = 28 $,  $ n(\overline{B}) = 49 - 28 = 21 $.

- Một kết quả thuận lợi cho biển cổ A ∩ B là một cách chọn quả bóng màu xanh ở lần thứ nhất (có 3 khả năng) và chọn quả bóng màu đó ở lần thứ hai (có 4 khả năng). Vì vậy  $ n(A \cap B) = 3 $. 4 = 12. Tương tự, ta có:  $ n(A \cap \overline{B}) = 3 $. 3 = 9,  $ n(B \cap \overline{A}) = 4 $. 4 = 16.

 $$ \mathrm{Ta~c0:~P}(A)=\frac{n(A)}{n(\Omega)}=\frac{21}{49}=\frac{3}{7};\mathrm{P}(A\mid B)=\frac{n(A\cap B)}{n(B)}=\frac{12}{28}=\frac{3}{7}; $$ 

 $$ \mathrm{P}(A\mid\overline{B})=\frac{n(A\cap\overline{B})}{n(\overline{B})}=\frac{9}{21}=\frac{3}{7};\mathrm{P}(B)=\frac{n(B)}{n(\Omega)}=\frac{28}{49}=\frac{4}{7}; $$ 

 $$ \mathrm{P}(B\mid A)=\frac{n(B\cap A)}{n(A)}=\frac{12}{21}=\frac{4}{7};\mathrm{P}(B\mid\overline{A})=\frac{n(B\cap\overline{A})}{n(\overline{A})}=\frac{16}{28}=\frac{4}{7}. $$ 

b) Vi  $ \mathrm{P}(A) = \mathrm{P}(A \mid B) = \mathrm{P}(A \mid \overline{B}) = \frac{3}{7} \mathrm{và} \mathrm{P}(B) = \mathrm{P}(B \mid A) = \mathrm{P}(B \mid \overline{A}) = \frac{4}{7} \mathrm{nên} A, B $ là hai biến cổ độc lập.

#### Vấn đề 2. Tính xác suất có điều kiện bằng sơ đồ hình cây

Vì dự 6) Một hộp có 12 quả bóng bàn màu trắng và 10 quả bóng bàn màu vàng; các quả bóng có kích thước và khối lượng như nhau. Có 10 quả bóng bàn trong hộp được đánh sổ, trong đó có 4 quả bóng bàn màu trắng và 6 quả bóng bàn màu vàng. Lấy ngẫu nhiên một quả bóng bàn trong hộp. Dùng sơ đồ hình cây, tính xác suất để quả bóng bàn được lấy ra có màu trắng, biết rằng quả bóng bàn đó được đánh sổ.

Giải

Xét các biến cố:

A: “Quả bóng bàn lấy ra có màu trắng”,

B: “Quà bóng bàn lấy ra có đánh sổ”.

Khi đó, xác suất để quả bóng bàn được lấy ra có màu trắng, biết rằng quả bóng bàn đó được đánh số, là xác suất có điều kiện P(A | B).

Sơ đồ hình cây biểu thị cách tính xác suất có điều kiện P(A | B) được về như sau:

Vậy xác suất để quả bóng bàn được lấy ra có màu trắng, biết rằng quả bóng đó được đánh số, là  $ \frac{2}{5} $.

### Vấn đề 3. Ứng dụng

Ví dụ 7 J Một doanh nghiệp trước khi xuất khẩu áo sơ mi trong lỗ hàng S phải qua hai lần kiểm tra chất lượng sản phẩm, nếu cả hai lần đều đạt thi chiếc áo trong lỗ hàng đó mới dù tiêu chuẩn xuất khẩu. Biết rằng bình quân 98% sản phẩm làm ra qua được

lần kiểm tra thứ nhất và 95% sản phẩm qua được lần kiểm tra thứ nhất sẽ tiếp tục qua được lần kiểm tra thứ hai. Chọn ra ngẫu nhiên một chiếc áo sơ mi trong lô hàng S. Tỉnh xác suất để một chiếc áo sơ mi đủ tiêu chuẩn xuất khẩu.

Giải

Xét các biến cố:

A: "Chiếc áo sơ mi qua được lần kiểm tra thứ nhất";

B: "Chiếc áo sơ mi qua được lần kiểm tra thứ hai",

C: "Chiếc áo sơ mi đủ tiêu chuẩn xuất khẩu".

Khi đó, xác suất đề chiếc áo sơ mi qua được lần kiểm tra thứ hai, biết rằng đã qua được lần kiểm tra thứ nhất, là xác suất có điều kiện P(B | A) và P(C) = P(B ∩ A).

Ta có: P(B | A) = 0.95; P(A) = 0.98.

 $  \text{Suy ra } \mathrm{P}(C) = \mathrm{P}(B \cap A) = \mathrm{P}(A) \cdot \mathrm{P}(B \mid A) = 0.98 \cdot 0.95 = 0.931  $

Vậy xác suất để một chiếc áo sơ mi đủ tiêu chuẩn xuất khẩu là 0,931.

Ví dụ 8) Một lỗ sản phẩm có 25 sản phẩm, trong đó có 8 sản phẩm chất lượng thấp. Lấy liên tiếp 2 sản phẩm trong lỗ sản phẩm trên, trong đó sản phẩm lấy ra ở lần thứ nhất không được bỏ lại vào lỗ sản phẩm. Tính xác suất để cả hai sản phẩm được lấy ra đều có chất lượng thấp.

Giải

Xét các biến cố:

A: "Lần thứ nhất lấy ra sản phẩm chất lượng thấp";

B: "Lần thứ hai lấy ra sản phẩm chất lượng thấp",

C: “Cà hai lần đều lấy ra sản phẩm chất lượng thấp”.

Khi đó, xác suất để lần thứ hai lấy ra sản phẩm chất lượng thấp, biết lần thứ nhất lấy ra sản phẩm chất lượng thấp, là xác suất có điều kiện P(B |A) và P(C) = P(B ∩ A).

Ta có:  $ \mathrm{P}(A)=\frac{8}{25} $;  $ \mathrm{P}(B\mid A)=\frac{7}{24} $.

Suy ra  $  \mathrm{P}(C) = \mathrm{P}(B \cap A) = \mathrm{P}(A)  $.  $  \mathrm{P}(B \mid A) = \frac{8}{25} \cdot \frac{7}{24} = \frac{7}{75}  $.

Vậy xác suất để cả hai sản phẩm được lấy ra đều có chất lượng thấp là  $ \frac{7}{75} $.

### C. BÀI TẬP

1. Nếu hai biến có A, B thoả mãn P(B) = 0,6; P(A ∩ B) = 0,2 thì P(A | B) bằng:

A.  $ \frac{3}{25} $.

B.  $ \frac{2}{5} $.

C.  $ \frac{1}{3} $.

D.  $ \frac{4}{5} $.

2. Nếu hai biến cổ A, B thoả măn P(B) = 0,3; P(A | B) = 0,5 thì P(A ∩ B) bằng:

A. 0,8.

B. 0,2.

C. 0,6.

D. 0,15.

Trong mỗi ý a), b), c), d) ở câu 3, 4, chọn phương án: đúng (Đ) hoặc sai (S).

3. Lớp 12A có 40 học sinh. Trong một buổi kiểm tra định kì, số học sinh của lớp được chia thành hai phòng như sau:

Chọn ngẫu nhiên một học sinh của lớp 12A.

Xét các biến cố:

A: “Học sinh được chọn ở phòng 2”.

B: "Học sinh được chọn là học sinh nữ"

a) Biến cố học sinh được chọn là học sinh nữ ở phòng 2 là A ∩ B.

b) P(A ∩ B) ≠  $ \frac{3}{10} $.

c)  $ \mathrm{P}(B)=\frac{21}{40} $

 $$ \mathrm{P}(A\mid B)=\frac{4}{7}. $$ 

4. Một doanh nghiệp trước khi xuất khẩu mũ thời trang trong lô hàng X phải qua hai lần kiểm tra chất lượng sản phẩm, nếu cá hai lần đều đạt thi chiếc mũ trong lô hàng đó mới đủ tiêu chuẩn xuất khẩu. Biết rằng binh quân 96% sản phẩm làm ra qua được lần kiểm tra thứ nhất và 91% sản phẩm qua được lần kiểm tra thứ nhất sẽ tiếp tục qua được lần kiểm tra thứ hai. Chọn ra ngẫu nhiên một chiếc mũ thời trang trong lô hàng X.

Xét các biến cố:

A: "Chiếc mũ thời trang chọn ra qua được lần kiểm tra thứ nhất",

B: "Chiếc mũ thời trang chọn ra qua được lần kiểm tra thứ hai".

a) Xác suất để chiếc mũ thời trang qua được lần kiểm tra thứ hai, biết rằng đã qua được lần kiểm tra thứ nhất, là xác suất có điều kiện P(B | A).

b) Xác suất để một chiếc mũ thời trang đủ tiêu chuẩn xuất khẩu là P(B ∩ A).

c)  $ \mathrm{P}(B \mid A) > 0.91 $

d) Xác suất để một chiếc mũ thời trang dữ tiêu chuẩn xuất khẩu là 0,8736.

5. Trong một đợt thi chứng chỉ hành nghề có 160 cán bộ tham gia, trong đó có 84 nam và 76 nữ. Khi công bố kết quả của ki kiểm tra đó, có 59 cán bộ đạt loại giới, trong đó có 30 cán bộ nam và 29 cán bộ nữ. Chọn ra ngẫu nhiên một cán bộ. Tinh xác suất đề cán bộ được chọn ra đạt loại giới, biết rằng cán bộ đó là nữ (làm tròn kết quả đến hàng phần trăm).

6. Một hộp đụng 5 quả bóng màu vàng và 3 quả bóng màu trắng, các quả bóng có kích thước và khối lượng như nhau. Lấy ngẫu nhiên làn thứ nhất một quả bóng (không hoàn lại), rồi lần thứ hai lấy một quả bóng khác. Tình xác suất để lần thứ nhất lấy được quả bóng màu vàng, lần thứ hai lấy được quả bóng màu trắng.

7. Một hộp đụng 24 chai nước giải khát có hình dạng và kích thước như nhau, trong đó có 2 chai nước giải khát ghi giải thưởng “Bạn nhận được thêm một chai nước giải khát”. Chọn ra ngẫu nhiên lần lượt (không hoàn lại) hai chai nước trong hộp. Tinh xác suất để cả hai chai đều ghi giải thưởng.

8. Một công ty có hai chi nhánh. Sản phẩm của chi nhánh I chiếm 54% tổng sản phẩm của công ty. Trong quá trình sản xuất phần loại, có 75% sản phẩm của công ty đạt loại A, trong đó có 65% của chi nhánh I. Chọn ngẫu nhiên một sản phẩm của công ty. Tinh xác suất sản phẩm được chọn đạt loại A, biết rằng sản phẩm được chọn của chi nhánh I (làm tròn kết quả đến hàng phần mười).

9. Một hợp có 12 quả bóng màu xanh, 7 quả bóng màu đỏ; các quả bóng có kích thước và khối lượng như nhau. Lấy ngẫu nhiên lần lượt hai quả bóng trong hộp, lấy không hoàn lại. Dùng sơ đồ hình cây, tính xác suất để lần thứ hai lấy được quả bóng màu đỏ, biết rằng lần thứ nhất đã lấy được quả bóng màu xanh.

# CÔNG THỨC XÁC SUẤT TOÀN PHẦN. CÔNG THỨC BAYES

## A. KIẾN THỨC CẦN NHỚ

Trong mục này, ta luôn giả thiết phép thử T có không gian mẫu là tập hợp Ω gồm hữu hạn phần tử và các kết quả của phép thử là đồng khả năng, các biến cố đều liên quan đến phép thử đó.

### 1. Công thức xác suất toàn phần

Cho hai biển cổ A, B với 0 < P(B) < 1, ta có:

 $  \mathrm{P}(A) = \mathrm{P}(A \cap B) + \mathrm{P}(A \cap \overline{B}) = \mathrm{P}(B)  $.  $  \mathrm{P}(A \mid B) + \mathrm{P}(\overline{B})  $.  $  \mathrm{P}(A \mid \overline{B})  $.

### 2. Công thức Bayes

Với hai biến cố A, B mà P(A) > 0, P(B) > 0, ta có: P(B | A) =  $ \frac{P(B) \cdot P(A \mid B)}{P(A)} $

Nhận xét: Cho hai biến cổ A, B với P(A) > 0, 0 < P(B) < 1.

Do P(A) = P(B). P(A | B) + P(B). P(A | B) nên công thức Bayes còn có dang:

 $$ \mathrm{P}(B\mid A)=\frac{\mathrm{P}(B)\cdot\mathrm{P}(A\mid B)}{\mathrm{P}(B)\cdot\mathrm{P}(A\mid B)+\mathrm{P}(\overline{B})\cdot\mathrm{P}(A\mid\overline{B})}. $$ 

### B. ví dụ

### Vấn đề 1. Tính xác suất bằng cách sử dụng công thức xác suất toàn phần

Ví dụ 1) Một công ty thời trang có hai chi nhánh cùng sản xuất một loại áo thời trang, trong đó có 56% áo thời trang ở chi nhánh I và 44% áo thời trang ở chi nhánh II. Tại chi nhánh I có 75% áo chất lượng cao và tại chi nhánh II có 68% áo chất lượng cao (kich thước và hình dạng bề ngoài của các áo là như nhau). Chọn ngẫu nhiên 1 áo thời trang. Xác suất chọn được áo chất lượng cao là bao nhiêu?

Giải

Xét các biến cố:

A: "Chọn được áo chất lượng cao",

B: "Chọn được áo ở chi nhánh I",

B: Chọn được áo ở chi nhánh II.

Từ giả thiết, ta có:

 $$ \mathrm{P}(B)=0,56;\mathrm{P}(A\mid B)=0,75;\mathrm{P}(\overline{B})=0,44;\mathrm{P}(A\mid\overline{B})=0,68. $$ 

Theo công thức xác suất toàn phần, ta có:

 $$ \mathrm{P}(A)=\mathrm{P}(B).\mathrm{P}(A\mid B)+\mathrm{P}(\overline{B}).\mathrm{P}(A\mid\overline{B})=0.56.0.75+0.44.0.68=0.7192. $$ 

Vậy xác suất chọn được áo chất lượng cao là 0,7192.

Ví dụ 2) Tại một địa phương có 500 người cao tuổi, bao gồm 260 nam và 240 nữ. Trong nhóm người cao tuổi nam và nữ lần lượt có 40% và 55% bị bệnh tiểu dường. Chọn ngẫu nhiên một người. Xác suất để chọn được một người không bị bệnh tiểu dường là bao nhiêu?

Giải

Xét các biến cố:

A: "Chọn được người không bị bệnh tiêu đương",

B: "Chọn được người cao tuổi là nam",

B : "Chọn được người cao tuổi là nữ".

Từ giả thiết, ta có: P(B) =  $ \frac{260}{500} = 0.52 $; P(A | B) = 1 - 0.4 = 0.6;

 $$ \mathrm{P}(\overline{B})=\frac{240}{500}=0,48;\mathrm{P}(A\mid\overline{B})=1-0,55=0,45. $$ 

Theo công thức xác suất toàn phần, ta có:

 $$ \mathrm{P}(A)=\mathrm{P}(B).\mathrm{P}(A\mid B)+\mathrm{P}(\overline{B}).\mathrm{P}(A\mid\overline{B})=0,52.0,6+0,48.0,45=0,528. $$ 

Vậy xác suất để chọn được một người không bị bệnh tiêu dưỡng là 0,528.

Ví dụ 3) Có hai hộp bóng bàn, các quả bóng bàn có kich thước và hình dạng như nhau. Hộp thứ nhất có 3 quả bóng bàn màu trắng và 2 quả bóng bàn màu vàng. Hộp thứ hai có 6 quả bóng bàn màu trắng và 4 quả bóng bàn màu vàng. Lấy ngẫu nhiên 4 quả bóng bàn ở hộp thứ nhất bỏ vào hộp thứ hai rồi lấy ngẫu nhiên 1 quả bóng bàn ở hộp thứ hai ra. Tinh xác suất để lấy được quả bóng bàn màu vàng từ hộp thứ hai.

##### Giải

Vì hộp thứ nhất có 3 quả bóng bàn màu trắng và 2 quả bóng bàn màu vàng nên khi lấy 4 quả bóng bàn ở hộp thứ nhất thì có hai khả năng: khả năng thứ nhất là lấy được 3 quả bóng bàn màu trắng và 1 quả bóng bàn màu vàng; khả năng thứ hai là lấy được 2 quả bóng bàn màu trắng và 2 quả bóng bàn màu vàng.

Xét các biến cố:

A: "Lấy được quả bóng bán màu vàng tử hợp thử hai";

B: "Lấy được 4 quả bóng bàn ở hộp thứ nhất, trong đó có 1 quả bóng bàn màu vàng";

B: "Lấy được 4 quả bóng bàn ở hộp thứ nhất, trong đó có 2 quả bóng bàn màu vàng".

• Xét khả năng thứ nhất: Số cách lấy 4 quả bóng bàn từ hợp thứ nhất là C₅, có 1 cách lấy 3 quả bóng bàn màu trắng và 2 cách lấy 1 quả bóng bàn màu vàng, suy ra P(B) =  $ \frac{1.2}{C_5^4} = \frac{2}{5} $. Vì khi đó hộp thứ hai có 9 quả bóng bàn màu trắng và 5 quả bóng bàn màu vàng nên P(A | B) =  $ \frac{5}{14} $.

- Xét khả năng thứ hai: Số cách lấy 4 quả bóng bàn từ hộp thứ nhất là  $ C_5^4 $, có  $ C_3^2 $ cách lấy 2 quả bóng bàn màu trắng và 1 cách lấy 2 quả bóng bàn màu vàng, suy ra  $ P(\overline{B}) = \frac{C_3^2 \cdot 1}{C_5^4} = \frac{3}{5} $. Vi khi đó hộp thứ hai có 8 quả bóng bàn màu trắng và 6 quả bóng bàn màu vàng nên  $ P(A \mid \overline{B}) = \frac{6}{14} $.

Theo công thức xác suất toàn phần, ta có:

 $$ \mathrm{P}(A)=\mathrm{P}(B)\ ,\mathrm{P}(A\mid B)+\mathrm{P}(\overline{B})\ ,\mathrm{P}(A\mid\overline{B})=\frac{2}{5}\cdot\frac{5}{14}+\frac{3}{5}\cdot\frac{6}{14}=\frac{2}{5}. $$ 

Vậy xác suất để lấy được quả bóng bàn màu vàng từ hộp thứ hai là  $ \frac{2}{5} $.

## Vấn đề 2. Tính xác suất bằng cách sử dụng công thức Bayes

Ví dụ 4:
 Có hai chiếc hộp, hộp I chứa 5 viên bi màu trắng và 5 viên bi màu đen, hộp II chứa 6 viên bi màu trắng và 4 viên bi màu đen, các viên bi có cùng kích thước và khối lượng. Lấy ngẫu nhiên một viên bi từ hộp I bỏ sang hộp II. Sau đó lấy ra ngẫu nhiên một viên bi từ hộp II.

Tính xác suất để viên bi được lấy ra từ hợp II là viên bi màu trắng.

Gia sử viên bi được lấy ra từ hợp II là viên bi màu trắng. Tinh xác suất để viên bi màu trắng đó thuộc hợp I.

Giải

Xét các biến cố:

A: "Lấy được viên bi màu trắng từ hộp II",

B: "Lấy được viên bi màu trắng từ hộp I bỏ sang hộp II",

B: "Lấy được viên bi màu đen từ hộp I bỏ sang hộp II".

Tương tự như Vì dụ 3, theo giả thiết ta có:

 $$ \mathrm{P}(B)=\mathrm{P}(\overline{B})=\frac{5}{10}=\frac{1}{2};\mathrm{P}(A\mid B)=\frac{7}{11};\mathrm{P}(A\mid\overline{B})=\frac{6}{11}. $$ 

Theo công thức xác suất toàn phần, ta có:

 $$ \mathrm{P}(A)=\mathrm{P}(B).\mathrm{P}(A\mid B)+\mathrm{P}(\overline{B}).\mathrm{P}(A\mid\overline{B})=\frac{1}{2}.\frac{7}{11}+\frac{1}{2}.\frac{6}{11}=\frac{13}{22}. $$ 

Vậy xác suất để viên bi được lấy ra từ hộp II là viên bi màu trắng là  $ \frac{13}{22} $.

b) Gọi N là biến cổ "Viên bí được lấy ra từ hộp II là viên bí thuộc hộp I". Khi đó ta cần tính P(N|A).

Ta có: P(N) =  $ \frac{1}{11} $; P(A) =  $ \frac{13}{22} $. Để tính P(A | N), hay xác suất để lấy được viên bi màu trắng từ hợp II, biết rằng viên bi đó thuộc hợp I, ta xét các trường hợp sau:

• Viên bi được lấy từ hợp I bỏ sang hợp II có màu đen. Khi đó xác suất lấy được viên bi trắng thuộc hợp I bằng 0.

- Viên bi được lấy từ hộp I bỏ sang hộp II có màu trắng. Khi đó xác suất lấy được viên bi màu trắng thuộc hộp I bằng P(B) =  $ \frac{1}{2} $.

Do đó,  $ P(A \mid N) = 0 + \frac{1}{2} = \frac{1}{2} $. Theo công thức Bayes, ta có:

 $$ \mathrm{P}(N\mid A)=\frac{\mathrm{P}(A\mid N)\cdot\mathrm{P}(N)}{\mathrm{P}(A)}=\frac{\frac{1}{2}\cdot\frac{1}{11}}{\frac{13}{22}}=\frac{1}{13}. $$ 

Vậy xác suất viên bi được lấy ra từ hợp II là viên bi thuộc hợp I, biết rằng viên bi đó màu trắng, là  $ \frac{1}{13} $.

Ví dụ 5) Một loại linh kiện do hai nhà máy I, II cùng sản xuất. Ti lệ phế phẩm của các nhà máy I, II lần lượt là: 0,04; 0,03. Trong một lỗ linh kiện để lẫn lộn 80 sản phẩm của nhà máy I và 120 sản phẩm của nhà máy II. Một khách hàng lấy ngẫu nhiên một linh kiện từ lỗ hàng đó.

Tình xác suất đề linh kiện được lấy ra không phải là phế phẩm.

Gia sử linh kiện được lấy ra là linh kiện phế phẩm. Hỏi xác suất linh kiện đó do nhà máy nào sản xuất là cao hơn?

Xét các biến cố:

A: "Linh kiện được lấy ra không phải là phế phẩm",

M: "Linh kiện được lấy ra do nhà máy I sản xuất",

M: "Linh kiện được lấy ra do nhà máy II sản xuất".

Theo giả thiết, ta có:

 $$ \mathrm{P}(\mathcal{M})=\frac{80}{200}=0,4;\mathrm{P}(\overline{\mathcal{M}})=\frac{120}{200}=0,6;\mathrm{P}(\overline{A}\mid\mathcal{M})=0,04;\mathrm{P}(\overline{A}\mid\overline{M})=0,03; $$ 

 $$ \mathrm{P}(A\mid M)=1-0,04=0,96;\mathrm{P}(A\mid\overline{M})=1-0,03=0,97. $$ 

Theo công thức xác suất toàn phần, ta có:

 $$ \mathrm{P}(A)=\mathrm{P}(M)\ ,\mathrm{P}(A\mid M)+\mathrm{P}(\overline{M})\ ,\mathrm{P}(A\mid\overline{M})=0,4\ .0,96+0,6\ .0,97=0,966. $$ 

Vậy xác suất để linh kiện được lấy ra không phải là phế phẩm là 0,966.

b) Xác suất linh kiện phế phẩm được lấy ra do nhà máy I sản xuất là:

 $$ \mathrm{P}(M\mid\overline{A})=\frac{\mathrm{P}(M)\cdot\mathrm{P}(\overline{A}\mid M)}{\mathrm{P}(\overline{A})}=\frac{0,4,0,04}{1-0,966}=\frac{8}{17}. $$ 

Xác suất linh kiện phế phẩm được lấy ra do nhà máy II sản xuất là:

 $$ \mathrm{P}(\overline{M}\mid\overline{A})=\frac{\mathrm{P}(\overline{M})\cdot\mathrm{P}(\overline{A}\mid\overline{M})}{\mathrm{P}(\overline{A})}=\frac{0,6,0,03}{1-0,966}=\frac{9}{17}. $$ 

Vây xác suất linh kiện phế phẩm được lấy ra do nhà máy II sản xuất là cao hơn.

Ví dụ 6) Năm 2001, Công đồng châu Âu có làm một đợt kiếm tra rất rộng rãi các con bò để phát hiện những con bị bệnh bò điện. Không có xét nghiệm nào cho kết quả chính xác 100%. Một loại xét nghiệm, mà ở đây ta goi là xét nghiệm A, cho kết quả như sau: Khi con bò bị bệnh bò điện thì xác suất để có phân ứng dương tính trong xét nghiệm A là 70%, còn khi con bò không bị bệnh thì xác suất để có phân ứng dương tính trong xét nghiệm A là 10%. Biết rằng ti lệ bỏ bị mắc bệnh bò điện ở Hà Lan là 13 con trên 1 000 000 con (Người: F.M. Dekking et al., a modern introduction to probability and statistics – Understanding why and how, Springer, 2005). Hỏi khi một con bò ở Hà Lan có phân ứng dương tính với xét nghiệm A thì xác suất để nó bị mắc bệnh bò điện là bao nhiêu?

Giải

Xét các biến cố:

M: "Con bò ở Hà Lan bị bệnh bò điện",

D: "Con bò ở Hà Lan có phần ứng dương tính với xét nghiệm A".

Theo giá thiết, ta có: P(M) = 0,000013; P(D | M) = 0,7; P(D |  $ \overline{M} $) = 0,1.

Theo công thức xác suất toàn phần, ta có:

 $$ \begin{aligned}P(D)&=P(M).P(D\mid M)+P(M).P(D\mid\overline{M})=0,000013.0,7+(1-0,000013).0,1\\&=0,1000078.\end{aligned} $$ 

Theo công thức Bayes, ta có:

 $$ P(M\mid D)=\frac{\mathrm{P}(M)\cdot\mathrm{P}(D\mid M)}{\mathrm{P}(D)}=\frac{0,000013\cdot0,7}{0,1000078}=\frac{91}{1\ 000\ 078}. $$ 

Vậy xác suất dễ một con bò Hà Lan bị bệnh bò diễn nếu nó phản ứng dương tính với xét nghiệm A là  $ \frac{91}{1000\ 078} $.

## C. BÀI TẬP

10. Nếu hai biển có A, B thoả măn P(B) = 0,4; P(A | B) = 0,5; P(A | B) = 0,3 thì P(A) bằng:

A. 0,38. B. 0,8. C. 0,2. D. 0,18.

11. Nếu hai biến có A, B thoả mãn P(A) = 0,3; P(B) = 0,6; P(A | B) = 0,4 thì P(B | A) bằng:

A. 0,5.

B. 0,6.

C. 0,8.

D. 0,2.

12. Trong mỗi ý a, b), c), d), chọn phương án: đúng (Đ) hoặc sai (S).

Một kho hàng có các thùng hàng với bề ngoài giống hết nhau, trong đó có 24 thùng hàng loại I và 26 thùng hàng loại II. Trong số các thùng hàng đó, có 95% thùng hàng loại I và 80% thùng hàng loại II đã được kiểm định. Chon ngẫu nhiên một thùng hàng.

Xét các biến cố:

A: “Chọn được thùng hàng loại I”;

B: “Chọn được thùng hàng đã được kiểm định”.

a) P(A) = 0.48; P(A) = 0.52.

b) P(B | A) = 0.8.

c) P(B | A) = 0.95.

d) P(B) = 0.872.

13. Trước khi đưa ra thị trường một sản phẩm, công ty phóng vấn 800 khách hàng và được kết quả là 550 người nói sẽ mua, còn 250 người nói sẽ không mua. Theo kinh nghiệm của nhà sản xuất thì trong những người nói sẽ mua sẽ có 60% số người chắc chắn mua, còn trong những người nói sẽ không mua lại có 1% người chắc chắn mua. Chọn ngẫu nhiên một khách hàng. Xác suất chọn được khách hàng chắc chắn mua là bao nhiêu?

14. Huy thực hiện liên tiếp hai thí nghiệm. Thí nghiệm thứ nhất có xác suất thành công là 0,6. Nếu thi nghiệm thứ nhất thành công thì xác suất thành công của thí nghiệm thứ hai là 0,8. Nếu thi nghiệm thứ nhất không thành công thì xác suất thành công của thí nghiệm thứ hai là 0,3. Tình xác suất của các biến cố:

A: “Cả hai thi nghiệm đều thành công”,

B: "Thi nghiệm thứ nhất không thành công, còn thi nghiệm thứ hai thành công";

C: "Thi nghiệm thứ hai thành công".

15. Một xí nghiệp mỗi ngày sản xuất ra 1 600 sản phẩm, trong đó có 35 sản phẩm lối. Lần lượt lấy ra ngầu nhiên 2 sản phẩm không hoàn lại để kiểm tra. Tinh xác suất của các biến cỡ:

A: “Sản phẩm lấy ra lần thứ hai không bị lỗi, biết sản phẩm lấy ra lần thứ nhất không bị lỗi”;

B: “Sản phẩm lấy ra lần thứ hai bị lỗi, biết sản phẩm lấy ra lần thứ nhất không bị lỗi”;

C: “Sản phẩm lấy ra lần thứ hai không bị lỗi, biết sản phẩm lấy ra lần thứ nhất bị lỗi”;

D: “Sản phẩm lấy ra lần thứ hai bị lỗi, biết sản phẩm lấy ra lần thứ nhất bị lỗi”;

E: “Sản phẩm lấy ra lần thứ hai bị lỗi”.

16. Một đội tuyền thi bản súng có 10 xa thủ, bao gồm 4 xa thủ hàng I và 6 xa thủ hàng II. Xác suất bản trúng mục tiêu của xa thủ hàng I và hàng II lần lượt là 0,75 và 0,6. Chọn ngẫu nhiên một xa thủ và xa thủ đó chỉ bản 1 viên đạn. Sử dụng sơ đồ hình cây, tính xác suất để viên đạn đó trúng mục tiêu.

### BÀI TẬP CUỐI CHƯỜNG VI

17. Cho hai biến cổ xung khác A, B với P(A) = 0, 15; P(B) = 0, 45. Khi đó, P(A | B) bằng:

A. 0,6.

B. 0,3.

C. 0,0675.

D. 0.

18. Cho hai biến có A, B với 0 < P(B) < 1 và P(A ∩ B) = 0, 2; P(A ∩ B) = 0, 3. Khi đó, P(A) bằng:

A. 0,06. B. 0,5. C. 0,1. D. 0,67.

19. Cho hai biên có A, B sao cho P(A) = 0,5; P(B) = 0,2; P(A) = 1,B = 0,25. Khi đó, P(B) = 1,B = 0,25.

A. 0,1.

B. 0,4.

C. 0,9.

D. 0,625.

20. Trong mỗi ý, b), c), d, chọn phương án: đùng (D) hoặc sai (S).

Cho các biên có A, B thoá măn 0 < P(A) < 1, 0 < P(B) < 1.

a) P(B) = P(A). P(B | A) + P(A) . P(B | A)

b) P(A | B) =  $ \frac{P(A \cap B)}{P(B)} $

c) P(A | B) =  $ \frac{P(B)}{P(A)} $

d) P(A) = P(A | B)

21. Trong một ngày hỏi giao lưu học sinh, chi có 350 học sinh trưởng Hoà Bình và 450 học sinh trưởng Minh Phúc đứng ở hội trưởng. Trong các học sinh giao lưu, ti lệ học sinh trưởng Hoà Bình bị cân thi là 0,2, còn ti lệ học sinh trưởng Minh Phúc bị cân thi là 0,3. Các học sinh của hai trường đứng lần với nhau. Chọn ngẫu nhiên một học sinh. Xác suất chọn được học sinh bị cân thi là bao nhiêu?

22. Trên bản có hai hộp bị với hình dạng và kích thước như nhau. Hộp thứ nhất có 6 viên bị đó, 7 viên bị vàng; còn hộp thứ hai có 10 viên bị đó, 11 viên bị vàng. Các viên bị có hình dạng và kích thước như nhau. Chọn ngẫu nhiên một hộp bị và từ hộp đó lấy ngẫu nhiên một viên bị. Tính xác suất để viên bị được lấy có màu đỏ.

23. Giá sử trong một nhóm 80 người có 69 người không nhiễm bệnh và 11 người nhiễm bệnh. Để phát hiện ra người nhiễm bệnh, người ta tiến hành xét nghiệm tất cả mọi người của nhóm đó. Biết rằng đối với người nhiễm bệnh, xác suất xét nghiệm có kết quả dương tính là 0,9; còn đối với người không nhiễm bệnh, xác suất xét nghiệm có kết quả dương tính là 0,05.

Vẽ sơ đồ hình cây biểu thị tình huống trên.

b) Giả sử X là một người trong nhóm bị xét nghiệm có kết quả dương tính. Tinh xác suất để X là người nhiễm bệnh.

## LỜI GIẢI - HƯỚNG DẦN - ĐẠP SỐ

### S1 XÁC SUẤT CÓ ĐIỂU KIỆN

### 1. C. 2. D.

3. Không gian mẫu có số phần tử là 40. Biến cố học sinh được chọn là học sinh nữ ở phòng 2 là A ◠ B. Ta có:

 $$ \mathrm{P}(A\cap B)=\frac{12}{40}=\frac{3}{10};\mathrm{P}(B)=\frac{9+12}{40}=\frac{21}{40}. $$ 

 $  \text{Suy ra } P(A \mid B) = \frac{P(A \cap B)}{P(B)} = \frac{\overline{10}}{\frac{21}{40}} = \frac{4}{7}  $

Đáp số: a) Đ, b) S, c) Đ, d) Đ.

4. Xác suất để chiếc mũ thòi trang qua được lần kiểm tra thứ hai, biết rằng đã qua được lần kiểm tra thứ nhất, là xác suất có điều kiện P(B |A). Ngoài ra, xác suất để một chiếc mũ thời trang đủ tiêu chuẩn xuất khẩu là P(B ∩ A). Theo giả thiết, ta có: P(B |A) = 0.91; P(A) = 0.96.

Suy ra P(B ∩ A) = P(A) . P(B |A) = 0.96 . 0.91 = 0.8736.

Đáp số: a) Đ. b) Đ. c) S. d) Đ.

### 5. Xét các biến cố:

A: "Cán bộ được chọn ra đặt loại giỏi",

B: “Cán bộ được chọn ra là nữ”

Khi đó, xác suất để cán bộ được chọn ra đặt loại giới, biết rằng cán bộ đó là nữ, là xác suất có điều kiện P(A | B).

 $ \tan \cos n(B) = 76; n(A \cap B) = 29. $  $ \sin \alpha \cos n(A \cap B) = \frac{n(A \cap B)}{n(B)} = \frac{29}{76} \approx 0.38. $

Vây xác suất để cán bộ được chọn ra đặt loại giới, biết rằng cán bộ đó là nữ, là khoảng 0,38.

### 6. Xét các biến cố:

A: “Lần thứ nhất lấy được quá bóng màu vàng”;

B: “Lần thứ hai lấy được quá bóng màu trắng”;

C: “Lần thứ nhất lấy được quá bóng màu vàng, lần thứ hai lấy được quả bóng màu trắng”.

Khi đó, xác suất để lần thứ hai lấy được quả bóng màu trắng, biết lần thứ nhất lấy được quả bóng màu vàng là xác suất có điều kiện P(B |A) và P(C) = P(A ∩ B). Ta có: P(A) =  $ \frac{5}{8} $. Vi sau khi lấy một quả bóng màu vàng ở lần thứ nhất thi trong lần thứ hai chỉ còn 4 quả bóng màu vàng và 3 quả bóng màu trắng.

Do đó,  $ \mathrm{P}(B \mid A) = \frac{3}{7} $.

 $ \text{Suy ra P}(C) = \text{P}(A \cap B) = \text{P}(A) \cdot \text{P}(B \mid A) = \frac{5}{8} \cdot \frac{3}{7} = \frac{15}{56}. $

Vậy xác suất để lần thứ nhất lấy được quả bóng màu vàng, lần thứ hai lấy được quả bóng màu trắng là  $ \frac{15}{56} $.

### 7. Xét các biến cố

A: "Chai được chọn ở lần thứ nhất có ghi giải thưởng",

B: "Chai được chọn ở lần thứ hai có ghi giải thưởng",

C: “Cả hai chai được chọn đều ghi giải thưởng”.

Khi đó, xác suất đề chai được chọn ở lần thứ hai có ghi giải thưởng, biết chai được chọn ở lần thứ nhất có ghi giải thưởng, là xác suất có điều kiện P(B | A) và P(C) = P(A ∩ B).

Ta có: P(A) =  $ \frac{2}{24} = \frac{1}{12} $. Vi sau khi lấy một chai có ghi giải thưởng thì trong làn thứ hai chi còn 1 chai có ghi giải thưởng và tổng số chai là 23. Do đó, P(B | A) =  $ \frac{1}{23} $.

Suy ra P(C) = P(A ∩ B) = P(A). P(B | A) =  $ \frac{1}{12} $.  $ \frac{1}{23} = \frac{1}{276} $.

Vậy xác suất để cả hai chai đều ghi giải thưởng là  $ \frac{1}{276} $.

### 8. Xét các biến cố:

M: "Sản phẩm được chọn đặt loại A",

N: "Sản phẩm được chọn của chi nhánh I"

Khi đó, sản phẩm được chọn đặt loại A, biết rằng sản phẩm được chọn của chi nhánh I, là xác suất có điều kiện P(M | N).

Ta có:  $ \mathrm{P}(N \mid M) = 0.65 $;  $ \mathrm{P}(M) = 0.75 $;  $ \mathrm{P}(N) = 0.54 $.

Khi đó,  $ \mathrm{P}(M \cap N) = \mathrm{P}(N \cap M) = \mathrm{P}(M) \cdot \mathrm{P}(N \mid M) = 0.75 \cdot 0.65 = 0.4875. $

 $  \text{Suy ra } P(M \mid N) = \frac{P(M \cap N)}{P(N)} = \frac{0.4875}{0.54} \approx 0.9.  $

Vậy xác suất sản phẩm được chọn đặt loại A, biết rằng sản phẩm được chọn của chi nhánh I, là khoảng 0,9.

### 9. Xét các biến cố:

A: "Lần thứ hai lấy được quả bóng màu đỏ".

B: "Lần thứ nhất lấy được quả bóng màu xanh".

Khi đó, xác suất để lần thứ hai lấy được quả bóng màu đỏ, biết rằng lần thứ nhất đã lấy được quả bóng màu xanh, là xác suất có điều kiện P(A | B).

Sơ đồ hình cây biểu thị cách tính xác suất có điều kiện P(A | B), được về như sau:

Vậy xác suất để làm thư hai lấy được quả bóng màu đỏ, biết rằng lần thứ nhất đã lấy được quả bóng màu xanh, là  $ \frac{7}{18} $.

### S2 CÔNG THỨC XÁC SUẤT TOÀN PHẦN. CÔNG THỨC BAYES

### 10. A. 11. C.

 $$ \begin{aligned}12.\ Theo\ gia\ thi\acute{t},\ ta\ co:\ P(B\mid A)=0,95;\ P(B\mid\overline{A})=0,8;\ P(A)=\frac{24}{50}=0,48;\end{aligned} $$ 

 $$ \mathrm{P}(\overline{A})=\frac{26}{50}=0,52.\mathrm{S u y r a} $$ 

 $$ \mathrm{P}(B)=\mathrm{P}(A).\mathrm{P}(B\mid A)+\mathrm{P}(\overline{A}).\mathrm{P}(B\mid\overline{A})=0.48.0,95+0.52.0,8=0.872. $$ 

 $$ \textcircled{D}\mathrm{d}p\mathrm{~s}\hat{\mathrm{o}}:\mathrm{a})\mathbf{D},\mathrm{b})\mathbf{S},\mathrm{c})\mathbf{S},\mathrm{d})\mathbf{D}. $$

## 13. Xét các biến cố:

A: “Khách hàng được chọn chắc chắn mua”;

B: “Khách hàng được chọn nói sẽ mua”.

Theo giả thiết, ta có:

 $$ \mathrm{P}(B)=\frac{550}{800}=\frac{11}{16};\mathrm{P}(\overline{B})=\frac{250}{800}=\frac{5}{16};\mathrm{P}(A\mid B)=0,6;\mathrm{P}(A\mid\overline{B})=0,01. $$ 

Theo công thức xác suất toàn phần, ta có:

 $$ \begin{aligned}\mathrm{P}(A)&=\mathrm{P}(B)\mathrm{~.~}\mathrm{P}(A\mid B)+\mathrm{P}(\overline{B})\mathrm{~.~}\mathrm{P}(A\mid\overline{B})\\&=\frac{11}{16}\mathrm{~.~}0,6+\frac{5}{16}\mathrm{~.~}0,01=\frac{133}{320}.\end{aligned} $$ 

Vậy xác suất chọn được khách hàng chắc chắn mua là  $ \frac{133}{320} $.

## 14. Xét biến cố M: "Thi nghiệm thứ nhất thành công".

Khi đó,  $ \mathrm{P}(A) = \mathrm{P}(M \cap C) $;  $ \mathrm{P}(B) = \mathrm{P}(\overline{M} \cap C) $.

Theo giá thiết, ta có: P(M) = 0.6; P(M) = 0.4; P(C | M) = 0.8; P(C | M) = 0.3.

Suy ra xác suất của biển có A là:

 $$ \mathrm{P}(A)=\mathrm{P}(M\cap C)=\mathrm{P}(M)\mathrm{~.~}\mathrm{P}(C\mid M)=0,6\mathrm{~.~}0,8=0,48; $$ 

Xác suất của biển có B là:

 $$ \mathrm{P}(B)=\mathrm{P}(\overline{M}\cap C)=\mathrm{P}(\overline{M}).\mathrm{P}(C\mid\overline{M})=0,4.0,3=0,12. $$ 

Theo công thức xác suất toàn phần, xác suất của biển cổ C là:

 $$ \mathrm{P}(C)=\mathrm{P}(M\cap C)+\mathrm{P}(\overline{M}\cap C)=0,48+0,12=0,6. $$ 

## 15. Xét các biến cố:

M: "Sản phẩm lấy ra lần thứ nhất không bị lỗi",

N: “Sản phẩm lấy ra lần thứ hai không bị lỗi”.

Khi đó,  $ \mathrm{P}(A) = \mathrm{P}(N|M) $;  $ \mathrm{P}(B) = \mathrm{P}(\overline{N} \mid M) $;  $ \mathrm{P}(C) = \mathrm{P}(N \mid \overline{M}) $;  $ \mathrm{P}(D) = \mathrm{P}(\overline{N} \mid \overline{M}) $;  $ \mathrm{P}(E) = \mathrm{P}(\overline{N}) $.

Sau khi lấy một sản phẩm không bị lỗi thi số sản phẩm còn lại 1 599, số sản phẩm lỗi là 35 nên xác suất của biến cố A là:

 $$ \mathrm{P}(A)=\mathrm{P}(N\mid M)=\frac{1\ 599-35}{1\ 599}=\frac{1\ 564}{1\ 599}; $$ 

Xác suất của biển cổ B là:  $ P(B) = P(\overline{N} \mid M) = \frac{35}{1599} $.

Sau khi lấy một sản phẩm bị lỗi thi số sản phẩm còn lại 1 599, số sản phẩm lỗi là 34 nên xác suất của biến cố C là:

 $$ \mathrm{P}(C)=\mathrm{P}(N\mid\overline{M})=\frac{1\ 599-34}{1\ 599}=\frac{1\ 565}{1\ 599}; $$ 

xác suất của biển cổ D là:

 $$ \mathrm{P}(D)=\mathrm{P}(\overline{N}\mid\overline{M})=\frac{34}{1\ 599}. $$ 

Theo công thức xác suất toàn phần, xác suất của biến cố E là:

 $$ \begin{aligned}\mathrm{P}(E)=\mathrm{P}(\overline{N})&=\mathrm{P}(M),\mathrm{P}(\overline{N}\mid M)+P(\overline{M}),\mathrm{P}(N\mid\overline{M})\\&=\frac{1\ 600-35}{1\ 600}\cdot\frac{35}{1\ 599}+\frac{35}{1\ 600}\cdot\frac{34}{1\ 599}=\frac{7}{320}.\end{aligned} $$ 

## 16. Xét các biến cố:

A: "Chọn được xạ thù hàng I",

B: "Viên đàn đó trùng mục tiêu".

Khi đó,  $ \mathrm{P}(A) = \frac{4}{10} = 0, 4; \quad \mathrm{P}(\overline{A}) = \frac{6}{10} = 0, 6; \quad \mathrm{P}(B \mid A) = 0, 75; \quad \mathrm{P}(B \mid \overline{A}) = 0, 6. $

Sơ đồ hình cây biểu thị tình huống đã cho là:

Theo công thức xác suất toàn phần, ta có:

 $$ \mathrm{P}(B)=\mathrm{P}(A).\mathrm{P}(B\mid A)+\mathrm{P}(\overline{A}).\mathrm{P}(B\mid\overline{A})=0,4.0,75+0,6.0,6=0,66. $$ 

Vậy xác suất đề viên đản đó trứng mục tiêu là 0,66.

### BÀI TẬP CUỐI CHƯỚNG VI

17. D. 18. B. 19. A.

20. Đáp số: a) Đ, b) Đ, c) S, d) S.

21. Xét các biến cố:

A: "Học sinh được chọn bị cân thi",

B: “Học sinh được chọn thuộc trường Hoà Bình”.

Theo giả thiết, ta có:

 $$ \mathrm{P}(B)=\frac{350}{800}=\frac{7}{16};\mathrm{P}(\overline{B})=\frac{450}{800}=\frac{9}{16};\mathrm{P}(A\mid B)=0,2;\mathrm{P}(A\mid\overline{B})=0,3. $$ 

Theo công thức xác suất toàn phần, ta có:

 $$ \mathrm{P}(A)=\mathrm{P}(B).\mathrm{P}(A\mid B)+\mathrm{P}(\overline{B}).\mathrm{P}(A\mid\overline{B}) $$ 

 $$ =\frac{7}{16}\cdot0,2+\frac{9}{16}\cdot0,3=\frac{41}{160}. $$ 

Vậy xác suất chọn được học sinh bị cận thị là  $ \frac{41}{160} $.

## 22. Xét các biến cố:

A: "Lấy được viên bi màu đỏ".

B: "Chọn được hộp bi thử nhất".

Theo giả thiết, ta có:

 $$ \mathrm{P}(B)=\mathrm{P}(\overline{B})=\frac{1}{2};\mathrm{P}(A\mid B)=\frac{6}{13};\mathrm{P}(A\mid\overline{B})=\frac{10}{21}. $$ 

Theo công thức xác suất toàn phần, ta có:

 $$ \mathrm{P}(A)=\mathrm{P}(B)\ ,\mathrm{P}(A\mid B)+\mathrm{P}(\overline{B})\ ,\mathrm{P}(A\mid\overline{B})=\frac{1}{2}\ ,\frac{6}{13}+\frac{1}{2}\ ,\frac{10}{21}=\frac{128}{273}. $$ 

Vậy xác suất để viên bi được lấy có màu đỏ là  $ \frac{128}{273} $.

## 23. a) Xét các biến cố:

A: “Người được chọn nhiễm bệnh”,

B: “Người được chọn xét nghiệm có kết quả dương tính”.

 $$ \mathrm{Khi~dô,~P}(A)=\frac{11}{80};\mathrm{P}(\overline{A})=\frac{69}{80};\mathrm{P}(B\mid A)=0,9;\mathrm{P}(B\mid\overline{A})=0,05. $$

Sơ đồ hình cây biểu thị tình huống đã cho là:

b) Theo công thức xác suất toàn phần, xác suất người X xét nghiệm có kết quả dương tính là:

 $$ \mathrm{P}(B)=\mathrm{P}(A).\mathrm{P}(B\mid A)+\mathrm{P}(\overline{A}).\mathrm{P}(B\mid\overline{A})=\frac{11}{80}.0,9+\frac{69}{80}.0,05=\frac{267}{1600}. $$ 

Theo công thức Bayes, ta có:

 $$ \mathrm{P}(A\mid B)=\frac{\mathrm{P}(A)\cdot\mathrm{P}(B\mid A)}{\mathrm{P}(B)}=\frac{\frac{11}{80}\cdot0,9}{\frac{267}{1\ 600}}=\frac{66}{89}. $$ 

Vây xác suất để X là người nhiễm bệnh, biết rằng X có kết quả xét nghiệm dương tính, là  $ \frac{66}{90} $.
