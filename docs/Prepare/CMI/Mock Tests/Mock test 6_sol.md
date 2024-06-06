---
layout: default
title: Mock test 11
nav_exclude: true
---


#  MT #11: Full-syllabus
## [Solutions]
#### Timings: 14:00-17:00 Hrs &nbsp;&nbsp;  Date: 9 July 2021
{: .fs-3 .text-grey-004 }

---

## Part A: Short-answer type questions


<ol>


<p>
<li>
\(ABCD\) is a unit square and \(P\) is the midpoint of segment \(OB\) in the figure below. What
is the length of \(AP\)?

<p style="text-align:center">
<img src="/assets/images/mt11_square.png"/>
</p>

</li>
</p>

<details open><summary>Sol.</summary>
<b>Ans.</b> \( \sqrt{\frac{5}{8}} \)<br>

\(OP=BD/4=\frac{1}{2\sqrt{2}}\).

\begin{align*}
AP^2 &= OP^2 + AO^2 \\
     &= 1/8+ 1/2 \\
     &= 5/8 \\
\end{align*}
</details>



<li>
Suppose \(2 \log x+\log y=x-y\). Then the equation of the tangent line to the graph of this equation at the point \((1,1)\) is:<br>
(a) \(x+2 y=3\)<br>
(b) \(x-2 y=3\)<br>
(c) \(2 x+y=3\)<br>
(d) \(2 x-y=3\)
</li>

<details open><summary>Sol.</summary>

\begin{align*}
\frac{2}{x} + \frac{1}{y}\cdot \frac{dy}{dx} &= 1 - \frac{dy}{dx} \\
\frac{dy}{dx} &= -\frac{1}{2}
\end{align*}

The equation of the line that passes through \( (1,1) \) with slope \(-1/2\) is \(x+2y=3\).

</details>

<li>
<p>
How many triples \(({A}, {B}, {C})\) are there of sets with union \({A} \cup {B} \cup {C}=\{1,2,3,4,5,6,7,8\}\) and \({A} \cap {B} \cap {C}=\varnothing ?\)
</p>

<details open><summary>Sol.</summary>
<p>
<b>Ans.</b> \(6^{8}\)<br>
There are six possibilities for each element corresponding to the six colored regions in the venn diagram below:

<p style="text-align:center">
<img src="/assets/images/mt11_venn3.png"/>
</p>


<br><i>Source: Putnam.</i>
</p>
</details>

</li>

<p>
<li>Find all integers \(x\) for which \( |x^3+2x| \) is prime.</li>
<details open><summary>Sol.</summary>
The expression \( x^3+2x \equiv 0 \pmod{3} \). So \(x^3+2x=\pm 3\), which
means \(x=+1 \text{ or } -1\).
</details>
</p>





<li>
<p>
Given that \(a_{1}=2, a_{2}=3, a_{n}=a_{n-1}+2 a_{n-2}\), what is \(a_{19}+a_{20}\)?
</p>
</li>

<details open><summary>Sol.</summary>
<p>
<b>Ans.</b> \(2^{18} \times 5\)<br>

\begin{align*}
a_{n} &=a_{n-1}+2 a_{n-2} \\
a_{n}+a_{n-1} &=2\left(a_{n-1}+a_{n-2}\right) \\
&=2^{n-2}\left(a_{1}+a_{2}\right)
\end{align*}

So \( a_{20}+a_{19}=2^{18} \times 5\).
</p>
</details>


<li>
<p>
A spirograph is a toy that has a cog and a rack. The cog and the rack have teeth that fit together. In the figure shown below,
the cog has 12 teeth and the rack has 30.</p>

<p style="text-align:center">
<img src="/assets/images/mt11_spiro.png"/>
</p>

<p>The cog has a hole near its circumference. If we put a pen in the hole and turn the cog around
the rack many times, we get a pattern. In the example shown above, we get a pattern with five pointed ends. Pointed ends are those
points in the pattern where the pen is closest to the rack.</p>

<p>Suppose the cog had 9 teeth and the rack had 20. How may pointed ends would the pattern have?</p>

</li>

<details open><summary>Sol.</summary>
<b>Ans.</b> 20.<br>
Label the teeth of the rack from \(0\ldots 19\). Without loss of generality, assume that the pen is closest to the rack in the starting position. So teeth number 0
has a pointed end. Now we get a pointed end after every rotation of the cog. So there will be pointed ends at teeth numbers \(0, 9, 18, \ldots, \pmod{20}\). Since 9 and 20
are relatively prime there will be 20 pointed ends.
</details>




<p>
<li>
\[ \lim_{x \rightarrow 0}\left(\frac{\sin x}{x}\right)^{\frac{1}{1-\cos x}} \]
</li>
<details open><summary>Sol.</summary>
We take logs and evaluate by L'Hopital's rule:<br>

\begin{align*}
\lim_{x \rightarrow 0} \log \left[\left(\frac{\sin x}{x}\right)^{\frac{1}{1-\cos x}}\right] & =\lim _{x \rightarrow 0} \frac{\log (\sin x)-\log x}{1-\cos x} \\
&=\lim _{x \rightarrow 0} \frac{\frac{\cos x}{\sin x}-\frac{1}{x}}{\sin x} \\
&=\lim _{x \rightarrow 0} \frac{x \cos x-\sin x}{x \sin ^{2} x} \\
&=\lim_{x \rightarrow 0} \frac{-x \sin x}{\sin ^{2} x+2 x \sin x \cos x} \\
&=\lim _{x \rightarrow 0} \frac{-x}{\sin x+2 x \cos x} \\
&=\lim _{x \rightarrow 0} \frac{-1}{\cos x+2 \cos x-2 x \sin x} \\
&=-\frac{1}{3}
\end{align*}

Therefore, the answer is \(e^{-1 / 3}\).
</details>
</p>



<p>
<li>
How many positive integers divide at least one of \(10^{30}\) and \(20^{30}\) ?<br>
</li>
</p>

<details open><summary>Sol.</summary>
<b>Ans.</b> 1891.<br>
A factor of \(10^{30}\) is also a factor of \(20^{30}=2^{60} 5^{30}\). There are \(61\times 31\) factors of \(20^{30}\).<br>
<b>Exercise</b>. What is the answer if the numbers were \(10^{40}\) and \(2^{30}\)?
</details>





<li>
<p>

Suppose that the set \(\{1,2, \cdots, 2022\}\) has been partitioned into disjoint pairs \(\left\{a_{i}, b_{i}\right\}(1 \leq i \leq 1011)\)
so that for all \(i,\left|a_{i}-b_{i}\right|\) equals 1 or 6 . What are the possible values of the last digits of the sum:<br>

\[ \left|a_{1}-b_{1}\right|+\left|a_{2}-b_{2}\right|+\cdots+\left|a_{1011}-b_{1011}\right| \]
</p>


<details open><summary>Sol.</summary>
Let \(S\) be the sum.

\[ S=\sum\left|a_{i}-b_{i}\right| \equiv \sum\left(a_{i}+b_{i}\right)=1+2+\cdots+2022\equiv 1 \pmod{2} \]

\[ S=\sum\left|a_{i}-b_{i}\right|=1 \cdot 1011 \equiv 1 \pmod{5} \]
So \(S \equiv 1(\bmod 10)\).
</details>



</li>


<li>
<p>
There is a highway on which a group of police officers are testing for drunk-driving.
They have breathalyzers that raises a false alarm in 5% of the cases in which the driver is sober. That is, even if the driver is not drunk there
is a 5% chance that the breathalyzer incorrectly shows him to be drunk.  However, the breathalyzer never fails to detect a truly drunk person.
We know for a fact that one in a every thousand drivers on the highway is driving drunk.
Suppose the police officers stop a driver at random to administer a breathalyzer test. It indicates that the driver is drunk.
The probability that he is truly drunk is around: <br>

(a) 2%<br>
(b) 10%<br>
(c) 20%<br>
(d) 95%


</p>
</li>

<details open><summary>Sol.</summary>

<b>Ans.</b> 2%.<br>

Let \(B\) denote the event that breathalyzer indicates that the driver is drunk.
Bayes's theorem tells us that

\[
p(\text { drunk } \mid B)=\frac{p(B \mid \text { drunk }) p(\text { drunk })}{p(B)}
\]

From the problem statement it follows that:

\begin{align*}
p(\text { drunk })&=0.001 \\
p(\text { sober })&=0.999 \\
p(B \mid \text { drunk })&=1.00\\
p(B \mid \text { sober })&=0.05
\end{align*}

As you can see from the formula, one needs \(p(B)\) for Bayes' theorem, which one can compute from the preceding values using the law of total probability:

\[p(B)=p(B \mid \text{drunk} ) p(\text{drunk})+p(B \mid \text{sober} ) p( \text{sober} )\]

which gives

\[ p(B)=(1.00 \times 0.001)+(0.05 \times 0.999)=0.05095 \]

Plugging these numbers into Bayes' theorem, one finds that

\[ p(\text { drunk } \mid B)=\frac{1.00 \times 0.001}{0.05095}=0.019627 \]



<br><i>It is common to overestimate the probability. This is a known bias called as base-rate fallacy. Source: Wikipedia.</i>

</details>




<!--

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

-->







</ol>



## Part B: Subjective questions


<p>
<b>B1. </b> Prove or disprove: There are two numbers \(x, y\) such that:

\begin{align*}
x+y&=1\\
x^{2}+y^{2}&=2\\
x^{3}+y^{3}&=3
\end{align*}

</p>

<details open><summary>Sol.</summary>
<p>
Suppose the equations are numbered (1), (2) and (3).<br>

From (1) and (2), \(1=(x+y)^{2}=x^{2}+2 x y+y^{2}=2+2 x y\), hence
\(x y=-1 / 2\).  <br>

From (1) and (3), \(1=(x+y)^{3}=x^{3}+3 x y(x+y)+y^{3}=3+3 x y\), hence
\(x y=-2 / 3\). A contradiction, hence numbers \(x\) and \(y\) do not exist.<br>

</p>
</details>


---

<p>
<b>B2.</b> In the figure shown below, \(ABCD\) is a square with side length of \(4\) cm. \(DQ=BP=1\) cm. Line segments \(AQ\)
and \(DP\) intersect at point \(X\). Find the area of the triangle \(PQX\).<br>

<p style="text-align:center">
<img src="/assets/images/mt11_square_tri.png"/>
</p>

</p>


<details open><summary>Sol.</summary>
Let \(\Delta T\) denote the area of triangle \(T\).
\(\Delta PQX = \Delta P Q D - \Delta Q D X\).<br>


<b>Lemma 1: </b> \(\Delta PQD = 3/2\).<br>
By the standard area of a triangle formula, \(\Delta P Q D=\frac{1}{2} \cdot 1 \cdot 3=\frac{3}{2}\;\;\;\square\).<br>

<b>Lemma 2: </b> \(\Delta QDX = 6/19\).<br>
Let \(\angle Q D X=\angle C D P=\theta\). Since triangle \(P C D\) is a right triangle with side lengths 3, 4 and 5. So we have \(\sin \theta=\frac{3}{5}\) and \(\cos \theta=\frac{4}{5}\).
Now by the sine area formula, \(\Delta QDA=2=\Delta Q D X+\Delta X D A=\frac{1}{2} \cdot D X \cdot(\sin \theta+4 \cos \theta)\), so solving for \(D X\) gives \(D X=\frac{20}{19}\).
Thus \(\Delta Q D X=\frac{1}{2} \cdot 1 \cdot \frac{20}{19} \cdot \frac{3}{5}=\frac{6}{19}.\;\;\;\square\)<br>

Hence, the answer is \(\frac{3}{2}-\frac{6}{19}=\frac{45}{38}\).

<br><i>Source: SMT.</i>
</details>


---

<p>
<b>B3.</b> (a) Suppose we have a polynomial \(p(x) = a_n x^n + a_{n-1}x^{n-1} + \cdots + a_0\) where \(a_i\)s are real numbers. If \( \sum \frac{a_i}{i+1} = 0 \), prove that \(p(x)\) has a real root between 0 and 1. \(\;\;\;\) [4 marks]<br>
(b) Evaluate the following integral:
\[ \int_{0}^{\pi} \frac{x \sin x}{1+\cos ^{2} x} d x \;\;\;\;\;\;\;\;  \text{[6 marks]} \]
</p>

<details open><summary>Sol.</summary>

(a) We have \( \sum \frac{a_i}{i+1} =  \int_0^1 p(x) = 0\). Hence, \(p(c)=0\) for some \(c \in (0,1)\).<br><br>

(b) Suppose we denote the integral by \(I\). Substituting \(x=\pi-u\), we get

\[ I=\int_{0}^{\pi} \frac{(\pi-u) \sin u}{1+\cos ^{2} u} d u \]

It follows that

\begin{align*}
2 I&=\int \frac{\pi \sin x}{1+\cos ^{2} x} d x \\
&=\pi \int_{-1}^{1} \frac{1}{1+u^{2}} d u \\
&=\pi\left|\tan ^{-1} u\right|_{-1}^{1} \\
&=\pi\left(\frac{\pi}{4}-\left(-\frac{\pi}{4}\right)\right) \\
&=\frac{\pi^{2}}{2}
\end{align*}



so

\[ \int_{0}^{\pi} \frac{x \sin x}{1+\cos ^{2} x} d x=I=\frac{\pi^{2}}{4} \]


</details>


---


<p>
<b>B4.</b> Determine all polynomials \(f(x)=a x^{2}+b x+c\) such that
\(f(a)=a, f(b)=b\) and \(f(c)=c\).
</p>



<details open><summary>Sol.</summary>
<p>
If \(a=0\), the graph of \(a x^{2}+b x+c\) is a straight line passing through the points \((0,0),(b, b)\) and
(c,c). Hence it must be the line \(y=x\) unless all of \(a, b\) and \(c\) are 0 . Thus we have so far two possible answers: \(f(x)=x\) and \(f(x)=0\).

If \(a \neq 0 .\), the graph of \(a x^{2}+b x+c\) is a parabola. It cannot pass through three distinct points
\((a, a),(b, b)\) and \((c, c)\) which are collinear. Hence we must have either \(a=b, a=c\), or \(b=c\).<br>

<i>Case I: </i>. Suppose \(f(x)=a x^{2}+a x+c\) with \(a \neq 0\). The condition \(f(c)=c\) gives
\(a c^{2}+a c+c=c\), where \(c^{2}=-c\), that is \(c=0\) or \(-1\). If \(c=0\), then \(f(a)=\) a yields
\(a^{3}+a^{2}=a\), hence \(a=1 / 2(-1 \pm \sqrt{5})\). If \(c=-1\), then \(f(a)=a\) yields \(a^{3}+a^{2}-1=a\), that
is \((a+1)\left(a^{2}-1\right)=0\), hence \(a=\pm 1\). So we have here two more solutions: \(f(x)=a\left(x^{2}+x\right)\) with
\(a=1 / 2(1\pm \sqrt{5})\) and \(f(x)=\pm\left(x^{2}+x\right)-1\)
<br><br>

<i>Case II: </i> Suppose \(f(x)=a x^{2}+b x+a\) with \(a \neq 0\). The condition \(f(a)=\) a gives
\(a^{y_{1}}+a b+a=a\), hence \(b=-a^{2}\). The condition \(f(b)=b\) gives \(a b^{2}+b^{2}+a=b\) which,
with our. previous conclusion, gives \(a^{5}+a^{4}+a^{2}+a=0\), that is \(a(a+1)^{2}\left(a^{2}-a+1\right)=0\). If \(a=-1\), then \(b=-1\) giving a solution already obtained in the first case. If \(a^{2}-a+1=0\), we obtain a complex solution: \(a=c=1 / 2(1 \pm \sqrt{(}-3)), b=1 / 2(-1 \pm \sqrt{1}-3))\) and \(f(x)=a x^{2}-a^{2} x+a\)
<br><br>

<i>Case III: </i> Suppose \(f(x)=a x^{2}+b x+b\) with \(a \neq 0\). The condition \(f(b)=b\) gives
\(a b^{2}+b^{2}+b=b\), that is \((a+1) b^{2}=0\), so \(a=-1\) or \(b=0 .\) If \(a=-1\), then \(f(a)=\) a yields
\(a^{3}+a b+b=a\), that is \(-1-b+b=-1\) which is true for all b. If \(b=0\), the condition \(f(a)=\) a gives \(a^{3}=a\), hence \(a=\pm 1\). So we have the final two solutions:
\(f(x)=-x^{2}+b x+b\) for any \(b\) and \(f(x)=\pm x^{2}\).
</p>
<br>Source: Vol 15 1979, Parabola.
</details>


---


<p>
<b>B5.</b> A special matrix is a square matrix whose entries are \(0\) or \(1\) such that, in each row, the \(1\)s appear as consecutive entries.
For example, the following is a \(4 \times 4\) special matrix.

\[
\left[\begin{array}{llll}
0 & 1 & 1 & 1 \\
0 & 1 & 1 & 0 \\
0 & 1 & 1 & 0 \\
1 & 1 & 1 & 1
\end{array}\right]
\]

Show that the determinant of any special matrix is either \(1,-1\) or \(0\).
</p>

<details open><summary>Sol.</summary>
Let us prove the statement by induction on \(n\), the number of rows in the special matrix \(M\).
If \(n=1\), then \(M=\left[\begin{array}{ll}0\end{array}\right]\) or \(M=[1]\), and so \(\operatorname{det}(M)\) is 0 or 1.
Now suppose that \(M\) is an \(n \times n\) special matrix and that the result is true for \((n-1) \times(n-1)\) special matrices.
If all entries in the first column of \(M\) are 0 , then \(\operatorname{det}(M)=0\).
<br>
Otherwise, consider all rows of \(M\) whose leftmost entry is 1 and, among these, consider a row with the minimal number of 1's.<br>
Subtract this row from all other rows whose leftmost entry is 1 to obtain the matrix \(M^{\prime}\).
Observe now that \(M^{\prime}\) is a special matrix with \(\operatorname{det}(M)=\operatorname{det}\left(M^{\prime}\right)\).<br>
Furthermore, the matrix \(M^{\prime}\) has only one 1 in its leftmost column.
So by expanding along the leftmost column, we see that \(\operatorname{det}\left(M^{\prime}\right)=\pm \operatorname{det}\left(M^{\prime \prime}\right)\), where \(M^{\prime \prime}\) is an \((n-1) \times(n-1)\) special matrix.
By the induction hypothesis, we have \(\operatorname{det}\left(M^{\prime \prime}\right)=0,1\) or \(-1\), from which it follows that \(\operatorname{det}(M)=\operatorname{det}\left(M^{\prime}\right)=0,1\) or \(-1 .\)
This completes the induction.
</details>

---

<p>
<b>B6.</b> Show that the number \(4^{2020}\) cannot be written as a sum of three cubes. In other words,
prove that there are no integers \(a_1,a_2\) and \(a_3\) such that
\[  a_1^3 + a_2^3 + a_3^3 = 4^{2020} \]
</p>

<details open><summary>Sol.</summary>
<p>
Observe that the cube of any integer is \(-1,0\) or \(1\) modulo \(9\),
which can be seen by calculating \(1^{3}, 2^{3}, 3^{3}, \ldots, 9^{3}\) modulo \(9\).
It follows that the sum of three perfect cubes is \(-3,-2,-1,0,1,2\) or \(3\) modulo \(9\).<br>

On the other hand, we have
\[ 4^{3\cdot 673} \times 4 \equiv 1^{673}\times 4 \equiv 4 (\mathrm{mod}\;\; 9) \]

</p>
</details>







<!--

<p>
<b>B7.</b>
Consider the quadratic function \(f(x)=x^{2}+b x+c\) defined on the set of real numbers. Given that the zeros of f are two distinct prime numbers \(p\) and \(q\), and \(f(p-q)=6 p q\), determine the primes \(p\) and \(q\), and the function \(f\).
</p>

<details open> <summary>Sol.</summary>
<p>
As \(p, q\) are the roots of \(x^{2}+b x+c=0\), we have \(p^{2}+b p+c=0\) and \(q^{2}+b q+c=0\). Hence by subtraction,

\[ p^{2}-q^{2}+b(p-q)=0, \quad \therefore p^{2}+b(p-q)=q^{2}\]

Combining this with the given fact that \(6 p q=f(p-q)=\) \(p^{2}+q^{2}-2 p q+b(p-q)+c\), we get

\[ 8 p q=2 q^{2}+c \]

giving \(c=2 q(4 p-q)\). Now, using the familiar equalities for sum and product of the roots of a quadratic equation, we get:
\[
c=p q, \quad \therefore 7 p q=2 q^{2}, \quad \therefore 7 p=2 q \text { . }
\]

Since \(p\) and \(q\) are prime numbers, the last equality can only be satisfied if \(p=2\) and \(q=7\). This gives \(c=14\). Hence \(f(x)=x^{2}-9 x+14\).
<br><i>Source: At right angles.</i>
</p>
</details>



-->


