---
layout: default
title: Mock test 12
nav_exclude: true
---


#  MT #12: Full-syllabus
## [Solutions]
#### Timings: 14:00-17:00 Hrs &nbsp;&nbsp;  Date: 23 July 2021
{: .fs-3 .text-grey-004 }

---

## Part A: Short-answer type questions


<ol>

<li>
<p>
Find a value \(k\) such that \(f(x)=x^{2}+kx-17, f(4)=f^{\prime}(4)\).
</p>
</li>

<details open><summary>Sol.</summary>
<b>Ans.</b>\({3}\)<br>
We have that \(f(4)=4 k-1\) and \(f^{\prime}(4)=2(4)+k=k+8\).
Setting these equal to each other, we see that \(k=3\).
</details>


<li>
<p>
Suppose we have a number \(x\) such that:
\begin{align*}
x & \equiv 1 \pmod{2}\\
x & \equiv 2 \pmod{3}\\
x & \equiv 3 \pmod{5}
\end{align*}
List all the possible values of \(x \pmod{30}\).


</p>
</li>

<details open><summary>Ans.</summary>
\(x=23\). From Chinese Remainder Theorem.
</details>



<li>
<p>
\(AEBCD\) is a pentagon such that \(ABCD\) is a rectangle and  \(AEB\) is an isosceles triangle. A circle
passes through \(A,B,C\) and \(D\). This circle has radius 1. Find the value of \(|AD|\) for which
the rectangle and triangle have the same area.
</p>
</li>


<details open><summary>Sol.</summary>
<b>Ans.</b> 2/5 units.<br>
The height of \({E}\) above \({AB}\) is \(1-{AD} / 2\). Hence \((1-AD/2)=2AD\).
</details>





<li>
<p>
If \(a=(\sqrt{3}+\sqrt{2})^{-3}\) and \(b=(\sqrt{3}-\sqrt{2})^{-3}\). Find the value of:
 \[\frac{1}{(a+1)}+\frac{1}{(b+1)}\].
</p>
</li>

<details open><summary>Sol.</summary>
\begin{align*}
ab &=(\sqrt{3}+\sqrt{2})(\sqrt{3}-\sqrt{2})=1 \\
(b+1)+(a+1) &=a b+a+b+1 \\
&=(a+1)(b+1) \\
\Rightarrow & \frac{1}{a+1}+\frac{1}{b+1}=1
\end{align*}
</details>

<li>
<p>
Find the value of \(n\) that maximizes\(\left|\sqrt{n^{2}+4 n+5}-\sqrt{n^{2}+2 n+5}\right|\).
</p>
</li>

<details open><summary>Sol.</summary>
<b>Ans.</b> \( -3 \).<br>

Notice that

\[ \left|\sqrt{n^{2}+4 n+5}-\sqrt{n^{2}+2 n+5}\right|=\left|\sqrt{(n+2)^{2}+(0-1)^{2}}-\sqrt{(n+1)^{2}+(0-2)^{2}}\right| \]

If we let \({P}\) be the point \((n, 0), A\) be the point \((-2,1)\) and \(B\) be the point \((-1,2)\) on the \(x y\) coordinate plane, then the expression above represents the absolute difference between \(P A\) and \(P B\).
By triangle inequality, \(A B \geq P A-P B\) and \(A B \geq P B-P A\), so \(A B=\sqrt{2}\) is the maximum value.
The triangle inequality tells us that this bound is tight when \(A, B, P\) are collinear. The points are collinear when \(n=-3\).

<br><i>Source: SMT 2019.</i>
</details>


<li>
<p>Numbers from 1 to 9999 are written on a paper. How many times is the digit 2 written?</p>
</li>

<details open><summary>Sol.</summary>
<b>Ans.</b>\(4000\).<br>
Imagine writing the numbers as \(0000,0001,\ldots,9999\). There are \(10,000\) numbers and \(40,000\) digits. Each
digit appears the same number of times. So the digit \(2\) appears \(4000\) times. The leading zeroes
do not affect the count of \(2\)s.
</details>






<li>
<p>
Suppose \(f: \mathbb{R} \rightarrow \mathbb{R}\) is an odd and differentiable function. Then for every \(x_{0} \in \mathbb{R}, f^{\prime}\left(-x_{0}\right)\) is equal to:<br>
(a) \(f^{\prime}\left(x_{0}\right)\)<br>
(b) \(-f^{\prime}\left(x_{0}\right)\)<br>
(c) 0<br>
(d) -1<br>
(e) None of these. <br>
</p>
</li>

<details open><summary>Sol.</summary>
<b>Ans.</b> (a). \(f(x) = -f(-x) \implies f^{\prime}(x) = f^{\prime}(-x)\).
</details>



<li>
How many ways are there to choose positive integers \(x\) and \(y\) such that the least common multiple of \(x\) and \(y\) is 144 ?
</li>

<details open><summary>Sol.</summary>
 Note that \(144=2^{4} 3^{2}\). First, consider the powers of \(2\).
 Numbers \(x\) and \(y\) must be divisible by 1 of \(2^{0},2^{1},2^{2},2^3\) and \(2^{4}\). However, we cannot have both \(x\) and \(y\) be divisible by only \(2^{0}, 2^{1},2^2\), or \(2^{3}\) and not \(2^{4}\).
 Hence, there are \(5 \cdot 5-4 \cdot 4=9\) ways of distributing the powers of 2. Similarly, there are 5 ways of distributing the powers of 3.
 Hence, the number of ways to choose positive integers \(x\) and \(y\) is \(9 \cdot 5=45\).
</details>


<li>
Consider tangent circles \(\gamma_{1}\) and \(\gamma_{2}\) with centers \(O_{1}, O_{2}\) and radii \(R, r\) with \(r < R \), respectively.
Let \(\overline{A B}\) be a common external tangent of length 16. The area of \(A B O_{1} O_{2}\) is 160. Find the ordered pair \((r, R)\).
</li>


<details open><summary>Sol.</summary>
<b>Ans.</b> \((4,16)\).<br>
By the area of a trapezoid, \(160=\frac{16 \times(r+R)}{2}\).
So, \(r+R=20\). Also, Pythagorean Theorem gives us \((R-r)^{2}+16^{2}=(R+r)^{2}\).
So, \(R-r=12\).
</details>


<li>
<p>
Let \(a, b \in \mathbb{C}\) such that \(a+b=a^{2}+b^{2}=\frac{2 \sqrt{3}}{3} i\). Compute \(|\operatorname{Re}(a)|\).
</p>
</li>

<details open><summary>Sol.</summary>
<b>Ans.</b> \(\frac{1}{\sqrt{2}}\)<br>
From \(a+b=2 \frac{\sqrt{3}}{3} i\) we can let \(a=\frac{\sqrt{3}}{3} i+x\) and \(b=\frac{\sqrt{3}}{3} i-x .\) Then \(a^{2}+b^{2}=2\left(\left(\frac{\sqrt{3}}{3} i\right)^{2}+x^{2}\right)=\)
\(2\left(x^{2}-\frac{1}{3}\right)=\frac{2 \sqrt{3}}{3} i\). So \(x^{2}=\frac{1+\sqrt{3} i}{3}=\frac{2}{3} e^{i \pi / 3}, x=\pm \frac{\sqrt{2}}{\sqrt{3}} \cdot \frac{\sqrt{3}+i}{2}\). Since \(|\operatorname{Re}(a)|=|\operatorname{Re}(x)|\), the answer is
\(\frac{\sqrt{2}}{\sqrt{3}} \cdot \frac{\sqrt{3}}{2}=\frac{1}{\sqrt{2}}\)
</details>


<!--

<li>
\[\lim_{n \rightarrow \infty} \frac{1 \cdot 1 !+2 \cdot 2 !+\cdots+n \cdot n !}{(n+1) !} \;\;\;\;\text{is}\]
(a) 1 <br>
(b) does not exist.<br>
(c) 2 <br>
(d) \(\frac{1}{2}\)<br>
</li>


<details open><summary>Sol.</summary>
(a) Observe that \(1 \cdot 1 !+2 \cdot 2 !+\cdots+n \cdot n !=(2-1) \cdot 1 !+(3-1) \cdot 2 !+\cdots+((n+1)-1) \cdot n !=\)
\((2 !-1 !)+(3 !-2 !)+\cdots+(n+1) !-n !=(n+1) !-1 .\)
Therefore \(\lim_{n \rightarrow \infty} \frac{1 \cdot 1 !+2 \cdot 2 !+\cdots+n \cdot n !}{(n+1) !}=\lim_{n \rightarrow \infty} \frac{(n+1) !-1}{(n+1) !}=1\).
</details>

-->


</ol>



## Part B: Subjective questions



<p>
<b>B1.</b>
Consider the quadratic function \(f(x)=x^{2}+b x+c\) defined on the set of real numbers. Given that the zeros of \(f\) are two distinct prime numbers \(p\) and \(q\), and \(f(p-q)=6 p q\), determine the primes \(p\) and \(q\), and the function \(f\).
</p>

<details open> <summary>Sol.</summary>
<p>
As \(p, q\) are the roots of \(x^{2}+b x+c=0\), we have \(p^{2}+b p+c=0\) and \(q^{2}+b q+c=0\). Hence by subtraction,

\[ p^{2}-q^{2}+b(p-q)=0, \quad \therefore p^{2}+b(p-q)=q^{2}\]

Combining this with the given fact that \(6 p q=f(p-q)=\) \(p^{2}+q^{2}-2 p q+b(p-q)+c\), we get

\[ 8 p q=2 q^{2}+c \]

giving \(c=2 q(4 p-q)\). Now, using the familiar equalities for sum and product of the roots of a quadratic equation, we get:

\[ c=p q, \quad \therefore 7 p q=2 q^{2}, \quad \therefore 7 p=2 q.  \]

Since \(p\) and \(q\) are prime numbers, the last equality can only be satisfied if \(p=2\) and \(q=7\). This gives \(c=14\). Hence \(f(x)=x^{2}-9 x+14\).
<br><i>Source: At right angles.</i>
</p>
</details>


<p>
<b>B2.</b> \(AB\) is a diameter of a circle of radius \(10\).
\(C\) is a point on the circle such that the length of arc \(B C=\frac{5 \pi}{3}\).
The bisector of \(\angle A C B\) cuts the circle at \(D\). Find the length of \(CD\).

<p style="text-align:center">
<img src="/assets/images/mt12_circle.png"/>
</p>

</p>

<details><summary>Sol.</summary>
Let \(O\) be the center of the circle. \(\angle BOC = \frac{5 \pi}{3} \cdot \frac{1}{10}=\frac{\pi}{6} .\) Since \(C D\) bisects \(\angle A C B, D\) is the mid-point of the arc \(A D B\). Therefore \(O D \perp A B\).
Hence \(\angle C O D=\frac{\pi}{6}+\frac{\pi}{2}=\frac{2 \pi}{3}\) and consequently \(C D=\)
\(2 \cdot 10 \cdot \sin \frac{\pi}{3}=10 \sqrt{3}\)
</details>



<p>
<b>B3.</b> Determine the number of positive integers \(n\) less than \(1000000\) for which the sum
\[
\frac{1}{2 \times\lfloor\sqrt{1}\rfloor+1}+\frac{1}{2 \times\lfloor\sqrt{2}\rfloor+1}+\frac{1}{2 \times\lfloor\sqrt{3}\rfloor+1}+\cdots+\frac{1}{2 \times\lfloor\sqrt{n}\rfloor+1}
\]

is an integer.<br>
<i>Notation.</i> \(\lfloor x\rfloor\) denotes the largest integer that is less than or equal to \(x\).<br><br>
</p>

<details open><summary>Sol.</summary>
Observe that each term of the sequence is of the form \(\frac{1}{2 m+1}\) for some positive integer \(m\) and that the terms form a non-increasing sequence. The terms equal to \(\frac{1}{2 m+1}\) are

\[
\frac{1}{2\left\lfloor\sqrt{m^{2}}\right\rfloor+1}, \frac{1}{2\left\lfloor\sqrt{m^{2}+1}\right\rfloor+1}, \frac{1}{2\left\lfloor\sqrt{m^{2}+2}\right\rfloor+1}, \ldots, \frac{1}{2\left\lfloor\sqrt{(m+1)^{2}-1}\right\rfloor+1}
\]

In particular, there are \((m+1)^{2}-m^{2}=2 m+1\) terms equal to \(\frac{1}{2 m+1}\). So the first 3 terms are equal to \(\frac{1}{3}\), the next 5 terms are equal to \(\frac{1}{5}\), the next 7 terms are equal to \(\frac{1}{7}\), and so on. It follows that the sum of the series is an integer if and only if

\[n=3+5+7+\cdots+(2 m+1)=(m+1)^{2}-1\]

for some positive integer \(m\).

Since \(100^{2}-1\) is less than one \(10000\) while \(101^{2}-1\) is more than \(10000\),
we deduce that the answer is \(100-1=99\).
<br><i>Source: 2017 Australian Olympiad.</i>
</details>

<p>
<b>B4.</b> We say that a function \(f: \mathbb{R} \rightarrow \mathbb{R}\) is flippy if \(f(f(x))=-x\) for all \(x \in \mathbb{R}\)<br>

(a) Prove or disprove: \(f\) is always injective.\(\;\;\;\) [2 marks]<br>
(b) Give an example of a flippy function.\(\;\;\;\) [3 marks]<br>
(c) Prove that there is no flippy function that is continuous. \(\;\;\;\) [5 marks]

</p>

<details open><summary>Sol.</summary>

<br>
(a) The equation \(f(a)=f(b)\) implies that \(f(f(a))=f(f(b))\), from which it follows that \(a=b\). Therefore, \(f\) is injective.<br>

(b) We define a flippy function \(f: \mathbb{R} \rightarrow \mathbb{R}\) by

\[
f(x)=\left\{\begin{array}{ll}
0, & \text { if } x=0 \\
x+1, & \text { if } x>0 \text { and }\lceil x\rceil \text { is odd } \\
-x+1, & \text { if } x>0 \text { and }\lceil x\rceil \text { is even } \\
x-1, & \text { if } x<0 \text { and }\lfloor x\rfloor \text { is odd }
\end{array}\right.
\]


(c) In order to obtain a contradiction, suppose that \(f: \mathbb{R} \rightarrow \mathbb{R}\) is a flippy function that is continuous. We start with the following two observations.<br>

<br><b>Lemma</b> \(f\) is an odd function.<br>
<i>Proof. </i> Substituting \(f(a)\) for \(x\) in the functional equation yields \(f(f(f(a)))=-f(a)\). However, the functional equation also implies that \(f(f(f(a)))=f(-a)\). Equating these two expressions yields the fact that \(f(-a)=-f(a)\) for all \(a \in \mathbb{R}\). So \(f\) is an odd function and \(f(0)=0\;\;\;\square\).<br>

<i>Case I: </i> If \(f(1)>0\), then the assumption that \(f\) is continuous and injective implies that \(f(a)>0\) for all \(a>0\).<br>

Otherwise, the existence of \(a>0\) for which \(f(a)<0\), combined with the intermediate value theorem, would imply the existence of \(b>0\) for which \(f(b)=0\). This contradicts the fact that \(f\) is injective. So if \(f(1)>0\), we deduce that \(f(f(1))>0\), which contradicts the fact that \(f(f(1))=-1\). <br>

<i>Case II:</i> Similarly, if \(f(1)<0\), then the fact that \(f\) is continuous and injective implies that \(f(a)<0\) for all \(a>0\) and that \(f(a)>0\) for all \(a<0\). So we again deduce that \(f(f(1))>0\), which contradicts the fact that \(f(f(1))=-1\).
Hence, there is no continuous function \(f: \mathbb{R} \rightarrow \mathbb{R}\) such that \(f(f(x))=-x\) for all \(x \in \mathbb{R}\).<br>

</details>

<p><b>B5 (a).</b> Suppose \(p\) and \(q\) are relatively prime numbers. Compute the limit:
\[ \lim_{k\rightarrow \infty} \sqrt{k^{2} q^{2}+2 p k}-\sqrt{k^{2} q^{2}} \]
</p>


<details open><summary>Sol.</summary>
\begin{align*}
\lim_{k \rightarrow \infty} a_{k} &=\lim_{k \rightarrow \infty} \sqrt{k^{2} q^{2}+2 p k}-\sqrt{k^{2} q^{2}} \\
&=\lim_{k \rightarrow \infty} \frac{\left(k^{2} q^{2}+2 p k\right)-\left(k^{2} q^{2}\right)}{\sqrt{k^{2} q^{2}+2 p k}+\sqrt{k^{2} q^{2}}} \\
&=\lim_{k \rightarrow \infty} \frac{2 p k}{\sqrt{k^{2} q^{2}+2 p k}+k q} \\
&=\lim_{k \rightarrow \infty} \frac{2 p}{\sqrt{q^{2}+\frac{2 p}{k}}+q} \\
&=\frac{p}{q}
\end{align*}
</details>





<p>
<b>B5 (b).</b> Show that :
\(\displaystyle\lim_{x\rightarrow\infty}\dfrac{1}{x} \int_{0}^{x} \frac{1}{3+\cos t}dt = \frac{1}{2\sqrt{2}}\)
</p>

<details open><summary>Sol.</summary>
Define : \(f(t)=\frac{1}{3+\cos t}\) . Observe that \(f\) is periodic with period = \(2\pi\).

Therefore, for any \(x \in \mathbb{R}\), if \(N = \left\lfloor\frac{x}{2\pi}\right\rfloor\), then we have : \(\int_0^x f(t)\,dt = N \int_0^{2\pi}f(t)\,dt + \int_0^{x- 2\pi N}f(t)\,dt := A +B\)
Observe that : \[ |B| = \left|\int_0^{x- 2\pi N}f(t)\,dt \right| \leq \int_0^{2\pi}|f(t)|\,dt\,\]
Thus, \[ \lim_{x\to\infty}  \frac{1}{x} \int_0^x f(t)\,dt = \frac{1}{2\pi}\left(\lim_{x\to\infty} \frac{2\pi}{x} \left\lfloor \frac{x}{2\pi} \right\rfloor \right)\int_0^{2\pi}f(t)\,dt =\frac{1}{2\pi} \int_0^{2\pi}f(t)\,dt\,\]

Hence, we obtain : \[ \lim_{x\to\infty}  \frac{1}{x} \int_0^x \dfrac{1}{3+\cos t}\,dt = \frac{1}{2\pi}\int_0^{2\pi}\dfrac{1}{3+\cos t}\,dt =\frac{1}{2\sqrt{2}}\quad\blacksquare\]

</details>


<p>
<b>B6.</b> A nonnegative integer \(k\) is <i>special</i> when all pairs of 1s in the binary
representation of \(k\) are separated by at least two zeroes.
For example, \(9=1001_{2}\) is special, but \(10=1010_{2}\) is not special.
How many special numbers are less than \(2^{15}\)?
</p>


<details open><summary>Sol.</summary>
<i>Notation</i>. Let \(a_{n}\) denote the number of sparse numbers with no more than \(n\) binary digits.
For numbers with less than \(n\) binary digits, append leading zeroes so all numbers have \(n\) binary digits.
We have that \(a_{0}=1\), \(a_{1}=2\), and \(a_{2}=3\) since for these lengths, either zero digits are 1 or one digit is 1.
We claim that the recurrence \(a_n=a_{n-1}+a_{n-3}\) holds for \(n \geq 3 .\) We split this analysis into two cases; numbers where the \(n\) th binary digit is 0 or 1 .<br>
<i>Case I: </i> When the \(n\) th binary digit is zero, we can remove that zero to get a valid number with \(n-1\) binary digits. <br>
<i>Case II:</i> When the \(n\) th binary digit is one, it is known that the \((n-1) \mathrm{th}\) and ( \(n-2\) )th digits are both zero, so we can truncate those to get a valid number with \(n-3\) binary digits.
Therefore, the recurrence holds. With the given initial conditions, \(a_{15}=406\).
</details>



