# Третье домашнее задание

## Первая задача

#### 1.
Выпишу задачу максимизации прибыли.
$$
\begin{cases}
    \pi = 2py-px \rightarrow max \\
    y = \sqrt{x}
\end{cases}
$$

#### 2.

FOC: $\frac{d\pi}{dy}=2p-2py=0$ \
y = 1

#### 3.
$y = \frac{2p}{2p}=1$

#### 4.
$$
\begin{cases}
    100lny + w \rightarrow max \\
    y = \sqrt{x}
\end{cases}
$$

$w = \bar{w} - 2y_1 - y_2^2$

$
\begin{cases}
    100ln(y_1 + y_2) + \bar w  - 2y_1 - y_2^2\rightarrow max \\
    y_2 = \sqrt{x}
\end{cases}
$

$
\begin{cases}
    \frac{100}{y_1+y_1} - 2 = 0 \\
    \frac{100}{y_1+y_1} - 2y = 0
\end{cases}
$

$
\begin{cases}
    y_1 = 49 \\
    y_2 = 1
\end{cases}
$

## Вторая задача


#### 1. 
$y_1 = ln(x_1) + ln(x_2)$

Функцию издержек TC(y) можно найти, подставив в производственную функцию $x_1^*, x_2^*$. \
Решу задачу минимизации расходов. 

$
\begin{cases}
    p_1x_1 + p_2x_2 \rightarrow min \\
    y \leq ln(x_1) + ln(x_2)
\end{cases}
$

Функция вогнута, поэтому можно приравнять y к $ln(x_1) + ln(x_2)$. 

$
\begin{cases}
    p_1x_1 + p_2x_2 \rightarrow min \\
    y = ln(x_1) + ln(x_2)
\end{cases}
$

$\zeta = p_1x_1 + p_2x_2 - \alpha(ln(x_1) + ln(x_2) - y)$

$
\begin{cases}
    p_1 - \frac{a}{x_1} = 0 \\
    p_2 - \frac{a}{x_2} = 0 \\
    ln(x_1) + ln(x_2) = y
\end{cases}
$


$x_1^* = \sqrt{\frac{p_2 e^y}{p_1}}, x_2^* = \sqrt{\frac{p_1 e^y}{p_2}}, a = \sqrt{p_1p_2e^y}$

$TC=p_1x_1 + p_2x_2=2e^{y/2}\sqrt{p_1p_2}$

#### 2.
Задача максимизации прибыли.

$
\begin{cases}
    \pi = qy - TC = qy - p_1x_1 - p_2x_2 \rightarrow max \\
    y = ln(x_1) + ln(x_2)
\end{cases}
$

$\zeta = qy - x_1p_1 - x_2p_2 - a(y - \ln x_1 - \ln x_2)$

$
\begin{cases}   
\frac{d\zeta}{dx_1} = \frac{a}{x_1} - p_1 = 0 \\
\frac{d\zeta}{dx_2} = \frac{a}{x_2} - p_2 = 0 \\
\frac{d\zeta}{dy} = q - a = 0\\
\frac{d\zeta}{da} = ln(x_1) + ln(x_2) - y = 0
\end{cases}
$

$x_1^* = q/p_1, x_2^* = q/p_2, a = q, y^* = log(q/p_1) + log(q/p_2)$


$\pi=q(ln\frac{q}{p_1} + ln\frac{q}{p_2}) - 2q$

#### 3.

$\epsilon_{x_1, p_1}=\frac{dx_1}{dp_1}\frac{p_1}{x_1} = -\frac{q}{p_1^2}\frac{p_1}{q/p_1}=-1$ \
$\epsilon_{x_2, p_2}=\frac{dx_2}{dp_2}\frac{p_2}{x_2} = -\frac{q}{p_2^2}\frac{p_2}{q/p_2}=-1$ \
$\epsilon_{y, q}=\frac{dy}{dq}\frac{q}{y} = \frac{2}{q}\frac{q}{log(q/p_1) + log(q/p_2)}=\frac{2}{log(q/p_1) + log(q/p_2)}$

#### 4. 

$y_1 = \sqrt{x_1} + \sqrt{x_2}$

Функцию издержек TC(y) можно найти, подставив в производственную функцию $x_1^*, x_2^*$. \
Решу задачу минимизации расходов. 

$
\begin{cases}
    p_1x_1 + p_2x_2 \rightarrow min \\
    y \leq \sqrt{x_1} + \sqrt{x_2}
\end{cases}
$

Функция вогнута, поэтому можно приравнять y к $\sqrt{x_1} + \sqrt{x_2}$. 

$
\begin{cases}
    p_1x_1 + p_2x_2 \rightarrow min \\
    y = \sqrt{x_1} + \sqrt{x_2}
\end{cases}
$

$\zeta = p_1x_1 + p_2x_2 - \alpha(\sqrt{x_1} + \sqrt{x_2} - y)$

$
\begin{cases}
    p_1 - \frac{a}{2\sqrt{x_1}} = 0 \\
    p_2 - \frac{a}{2\sqrt{x_2}} = 0 \\
    \sqrt{x_1} + \sqrt{x_2} = y
\end{cases}
$


$ x_1 = \frac{{p_2}^2 y^2}{{(p_1 + p_2)}^2} ,  x_2 = \frac{{p_2}^2 y^2}{{(p_1 + p_2)}^2} - 2y\sqrt{\frac{{p_2}^2 y^2}{{(p_1 + p_2)}^2}} + y^2, a = \frac{2p_1 p_2 y}{p_1 + p_2} $

$TC = p_1\frac{{p_2}^2 y^2}{{(p_1 + p_2)}^2} + p_2(\frac{{p_2}^2 y^2}{{(p_1 + p_2)}^2} - 2y\sqrt{\frac{{p_2}^2 y^2}{{(p_1 + p_2)}^2}} + y^2) = \frac{p_1 p_2 y^2}{p_1 + p_2}$
#### 5.

Задача максимизации прибыли.

$
\begin{cases}
    \pi = qy - TC = qy - p_1x_1 - p_2x_2 \rightarrow max \\
    y = \sqrt{x_1} + \sqrt{x_2}
\end{cases}
$

$\zeta = qy - x_1p_1 - x_2p_2 - a(y - \sqrt{x_1} - \sqrt{x_2})$

$
\begin{cases}   
a/(2 sqrt(x)) - p = 0, 
a/(2 sqrt(z)) - t = 0 \\
q - a = 0 \\
sqrt(x) - y + sqrt(z) = 0
\end{cases}
$

$x_1 = \frac{q^2}{4{p_1}^2}, x_2 = \frac{q^2}{4{p_2}^2}, y = \frac{1}{2} (\sqrt{\frac{q^2}{{p_1}^2}} + \sqrt{\frac{q^2}{{p_2}^2}}), a = q$


$\pi = q\frac{1}{2} \left( \sqrt{\frac{q^2}{{p_1}^2}} + \sqrt{\frac{q^2}{{p_2}^2}} \right) - p_1\frac{q^2}{4{p_1}^2} - p_2\frac{q^2}{4{p_2}^2} = \frac{q^2 (p_1 + p_1)}{4 p_1 p_2}$

#### 6.

$\epsilon_{x_1, p_1}=\frac{dx_1}{dp_1}\frac{p_1}{x_1} = -\frac{q^2}{2p_1^3}\frac{p_1}{\frac{q^2}{4{p_1}^2}}=-2$ \
$\epsilon_{x_2, p_2}=\frac{dx_2}{dp_2}\frac{p_2}{x_2} = -\frac{q^2}{2p_2^3}\frac{p_2}{\frac{q^2}{4{p_2}^2}}=-2$ \
$\epsilon_{y, q}=\frac{dy}{dq}\frac{q}{y} = \frac{p_1+p_2}{2p_1p_2}\frac{q}{\frac{1}{2} (\sqrt{\frac{q^2}{{p_1}^2}} + \sqrt{\frac{q^2}{{p_2}^2}})}=1$


#### 7.

$2e^{y_1/2}\sqrt{p_1p_2}=\frac{p_1 p_2 y_2^2}{p_1 + p_2}$

$ y_2 =  \sqrt{2} \sqrt{p_1 + p_2} \left( e^{\sqrt{p_1 p_2}} \right)^{\frac{y_1}{4}} / \sqrt{p_1} \sqrt{p_2}$

## Задача 3


#### 1.

$
\begin{cases}   
q1y1 + q2y2 + q3y3 - px \rightarrow max \\
 st. y1^2 + y2^2 + 2y3^2 = x 
\end{cases}
$

$L = q1y1 + q2y2 + q3y3 - p*x - a(x - 2y1^2 - y2^2 - y3^2)$

$
\begin{cases}   
-x + 2 y1^2 + y2^2 + y3^2=0, \\
-a - p = 0, \\
q1 + 4 a y1 = 0, \\
q2 + 2 a y2 = 0 , \\
q3 + 2 a y3 = 0
\end{cases}
$

$x = (q1^2 + 2 (q2^2 + q3^2))/(8 p^2), y1 = q1/(4 p), y2 = q2/(2 p), y3 = q3/(2 p)$

$TC_1 = px = (q1^2 + 2 (q2^2 + q3^2))/(8 p) $


#### 2.
Эластичность
$E_{x,p}= -(q1^2 + 2 (q2^2 + q3^2))/(4 p^3) * p / ((q1^2 + 2 (q2^2 + q3^2))/(8 p^2)) = -2$ \
$E_{y1, q1} = E_{y2, q2} = E_{y3, q3} = (1/(4 p))*q1/(q1/(4 p)) = 1$


#### 3.

$
\begin{cases}   
q1y1 + q2y2 + q3y3 - px \rightarrow max \\
 st. y1^2 + y2^2 + 2y3^2 = x 
\end{cases}
$

$L = q1y1 + q2y2 + q3y3 - p*x - a(x - y1^2 - y2^2 - 2y3^2)$

$
\begin{cases}   
-x + y1^2 + y2^2 + 2 y3^2=0, \\
-a - p = 0, \\
q1 + 2 a y1 = 0, \\
q2 + 2 a y2 = 0 , \\
q3 + 4 a y3 = 0
\end{cases}
$

$x = (2 q1^2 + 2 q2^2 + q3^2)/(8 p^2), y1 = q1/(2 p), y2 = q2/(2 p), y3 = q3/(4 p), a = -p$

$p = q2/(2 y2) and q1 = (q2 y1)/y2 and q3 = (2 q2 y3)/y2 and a = -q2/(2 y2) and x = y1^2 + y2^2 + 2 y3^2 and y2!=0$

$TC_2 = px = (2 q1^2 + 2 q2^2 + q3^2)/(8 p)$


#### 4.
Эластичность
$E_{x,p}= -(2 q1^2 + 2 q2^2 + q3^2)/(4 p^3) * p / ((2 q1^2 + 2 q2^2 + q3^2)/(8 p^2)) = -2$ \
$E_{y1, q1} = E_{y2, q2} = E_{y3, q3} = (1/(4 p))*q1/(q1/(4 p)) = 1$

#### 5.
$L=TC_1 + TC_2 - a * (3y1 + 2y2 +  3y3 - y) = (q1^2 + 2 (q2^2 + q3^2))/(8 p) + (2 q1^2 + 2 q2^2 + q3^2)/(8 p) - a * (3y1 + 2y2 +  3y3 - y) = (3 q3^2 + 4 q2^2 + 3 q1^2)/(8 p) - a * (3y1 + 2y2 +  3y3 - y)$


$ MC_1 = MC_2 $



## Task 4
$y=\sqrt{x_1}+\ln x_2, p_y = 1, p_{x_1}=q_1, p_{x_2}=q_2$

#### 1.
$\epsilon_{x_1} = \frac{dy}{dx_1} \frac{x_1}{y} = \frac{1}{2\sqrt{x_1}}\frac{x_1}{\sqrt{x_1}+\ln x_2} =  \frac{\sqrt{x_1}}{2(\sqrt{x_1} + \log{x_2})}$

$\epsilon_{x_2} = \frac{dy}{dx_2} \frac{x_2}{y} = \frac{1}{x_2}\frac{x_2}{\sqrt{x_1}+\ln x_2} =  \frac{1}{\sqrt{x_1}+\ln x_2}$

#### 2.
$q_1 \rightarrow q_1 + \tau_1, y \rightarrow \bar y$

$
\begin{cases}
    y=\sqrt{x_1}+\ln x_2 \\
    \tau = \tau_1x_1, \tau_1 = \tau/x_1 \\
    \pi= y-(q_1 + \tau_1)x_1 - q_2x_2 \rightarrow max
\end{cases}
$

$\zeta=y-(q_1+\tau_1)x_1-q_2x_2-a(y-\sqrt{x_1}-\ln{x_2})$

$
\begin{cases}
\frac{a}{2\sqrt{x_1}} - q_1 - \tau_1 = 0 \\
-p + \frac{a}{x_2} = 0 \\
 1 - a = 0 \\
\sqrt{x_1} - y + \log(x_2) = 0
\end{cases}
$



$ x_1 = \frac{1}{4(q_1 + \tau_1)^2}, \ x_2 = \frac{1}{q_2}, \ y = \frac{2q_1 \log\left(\frac{1}{q_2}\right) + 2\tau_1 \log\left(\frac{1}{q_2}\right) + 1}{2(q_1 + \tau_1)}, \ a = 1 $

$\tau_1 = \frac{-8q_{1} \tau + \sqrt{1 - 16q_{1} \tau} + 1}{8 \tau}$


#### 3.
$
\begin{cases}
    y=\sqrt{x_1}+\ln x_2 \\
    \tau = \tau_2x_2, \tau_2 = \tau/x_2 \\
    \pi= y-q_1x_1 - (q_2+ \tau_2)x_2 \rightarrow max
\end{cases}
$

$\zeta=y-q_1x_1-(q_2 + \tau_2)x_2-a(y-\sqrt{x_1}-\ln{x_2})$

$
\begin{cases}
\frac{a}{2\sqrt{x_1}} - q_1 = 0 \\
\frac{a - (q_2 + \tau_2)x_2}{x_2} = 0 \\
1 - a = 0 \\
\sqrt{x_1} - y + \log{(x_2)} = 0
\end{cases}
$

$ x_1 = \frac{1}{4q_1^2},  x_2 = \frac{1}{q_2 + \tau_2}, y = \frac{2q_1 \log{\frac{1}{q_2 + \tau_2}} + 1}{2q_1}, a = 1$

$\tau_2 = -\frac{q_2 \tau}{\tau - 1}$

#### 4.

$
\begin{cases}
    y=\sqrt{x_1}+\ln x_2 \\
    \tau = \tau_3y, \tau_3 = \tau/y \\
    \pi= (1+\tau_3)y-q_1x_1 - q_2x_2 \rightarrow max
\end{cases}
$

$\zeta=(1+\tau_3)y-q_1x_1-q_2x_2-a(y-\sqrt{x_1}-\ln{x_2})$

$
\begin{cases}
a/(2 sqrt(x)) - q = 0\\
-p + a/z = 0 \\
1 - a + t = 0 \\
sqrt(x) - y + log(z) = 0
\end{cases}
$

$x_1 = \frac{(\tau_3 + 1)^2}{4q_1^2}, x_2 = \frac{\tau_3 + 1}{q_2}, y = \log{\left(\frac{\tau_3 + 1}{q_2}\right)} + \frac{1}{2} \sqrt{\frac{(\tau_3 + 1)^2}{q_1^2}}, a = \tau_3 + 1$

$\tau_3 (\log{\left(\frac{\tau_3 + 1}{q_2}\right)} + \frac{1}{2} \sqrt{\frac{(\tau_3 + 1)^2}{q_1^2}})=\tau$



## Task 5


#### 1 and 2.
<img src="https://i.ibb.co/PwXG3Fn/Screenshot-20240317-190157-Samsung-Notes.jpg" alt="my-photo" border="0" height=300px></a> 

#### 3.
Больше технологическое множество $y_1 + y_2 \leq 1$, так как ему доступны все точки из второго множества и доступны точки с большим $y_1$, при фиксированном $y_2$.
#### 4.
$A+B = \{a + b \ | \ a \in A, \ b \in b\}.$

Рассмотрим разные комбинации из точек на границе, согласно формуле сумм множеств. Получается такой график.

Расммотрим граничные случаи.

(1/2, 0) + (1, 0) = (3/2, 0) \
(0, 1) + (0, 1) = (0, 2) \
(1, 0) + (0, 1) = (1, 1)

<img src="https://i.ibb.co/PrJwyqB/image.png" alt="my-photo" border="0" height=300px></a> 


## Task 6

#### 1.
$U(x,y)=2\sqrt{x}+y$

$L = 2\sqrt{x} + y - a(px + qy - w)$

$
\begin{cases}
-a p + 1/ \sqrt{x} = 0\\
1 - a q = 0 \\
w - p x - q y = 0 
\end{cases}
$

$a = 1/q, x^* = q^2/p^2=1, y^* = (p w - q^2)/(p q)=9, U(x,y)=2*1+9=11$

Краевой случай:
$y = 0, x = w/p=10, U(x, y)=2\sqrt{10}\approx6.32$

$x=0, y=10, U(x,y) = 10$

Оптимальное решение - $x^*=1, y^*=9$

#### 2.
p = 1, q = 2

$x^* = q^2/p^2=4, y^* = (p w - q^2)/(p q)=3, U(x,y)=2*2+3 = 7$ \
$y = 0, x = w/p=10, U(x, y)=2\sqrt{10}\approx6.32$

Спрос на x возрастет в 4 раза и станет 4, y станет 3.

#### 3.

$V = 2*\sqrt{q^2/p^2} + (p w - q^2)/(p q) = q/p + w/q$

$E=\frac{q (-q + p u)}{p}=$

Получу хиксианский спрос, подставив в маршалианский спрос функцию расходов.

$x^* = q^2/p^2, y*=(p \frac{q (-q + p u)}{p} - q^2)/(p q) = (p u - 2 q)/p$


<img src="https://i.ibb.co/SR0mMXL/2024-03-21-173901.png" alt="my-photo" border="0"></a> 
