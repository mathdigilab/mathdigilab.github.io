---
layout: default
title: Mock test 10
nav_exclude: true
---


#  MT #10: Full-syllabus
## [Solutions]
#### Timings: 14:00-17:00 Hrs &nbsp;&nbsp;  Date: 18 June 2021
{: .fs-3 .text-grey-004 }

---



## Part A: Short-answer type questions

<ol>

<p>
<li>

There are three pastures of area 35 acres, 10 acres and 65 acres.  On a certain date the owner places 17, 7 and 23 cows  in the pastures, respectively.
The grass in the first pasture is exhausted after 7 weeks, and that in the second after 4 weeks.

For how long can the 23 cows be grazed in the third pasture?

<br>Assume that initially there is the same amount of grass/unit area and
that new grass grows at the same constant rate in all three pastures.

</li>
</p>

<details open><summary>Sol.</summary>
<b>Ans.</b> 13.<br>
Let us take as a unit of grass the amount initially available in each acre, i.e. the first pasture has 35 units, the second 10, the third 65. Suppose that grass grows at a rate of runits/week/acre, and each cow eats at a rate of c units/week.

Then in the first pasture, after 7 weeks \(35+7.35 r\) units of grass are eaten by 17 cows, so \[35+7.35r=7.17c\]
Similarly for the second pasture we have \[10+4.10r=4.7c\]

If the third pasture is exhausted after \(n\) weeks, \(65+nr=nc23\).<br>
Solving these equations simultaneously, we find \(n=13\).
</details>



<p>
<li> Find the shortest distance from the point \(A=(0,2)\) to the arc of the parabola \(y=x^2\) which is between \(x=0\) and \(x=1\).
</li>
</p>

<details open><summary>Sol.</summary>
If \(B\) is a point on the parabola, we have:
\begin{align*}
AP^2 &= x^2 + (2-y)^2 \\
 &= x^2 + (2-x^2)^2 \\
 &= x^4 - 3x^2 + 4 \\
 &= (x^2-3/2)^2 + 7/4 \\
\end{align*}

The minimum is attained when \(x=1\). Hence, the minimum value of \(AB\) is \(  \left( (1-3/2)^2 + (7/4) \right)^{1/2} = \sqrt{2} \).

</details>

<p>
<li>

We have an \(n\times n\) grid of points, where \(n\) is an even number. There is a black spot at the
center of the grid. In how many ways can we draw an axis-parallel rectangle with corners as the grid points such
that the spot is inside the rectangle? An example of a rectangle is shown for a grid of size \(n=6\):

<p style="text-align:center">
<img src="/assets/images/mt10_lattice.png"/>
</p>


</li>
</p>

<details open><summary>Sol.</summary>
The rectangle is determined by the bottom-left corner and top-right corner. There are \(n^2/4\) ways to pick each. So the
number of enclosing rectangles is \(n^4/16\).
</details>



<p>
<li> Let \(A\) be a \(3 \times 3\) matrix with entries from the set \(\{-1 , +1\}\). Also, it is given that the first row and the first column of \(A\) contains only \((+1)\). Find the maximum value of determinant of \(A\).</li>
</p>


<details open><summary>Sol.</summary>
Let's assume the matrix is
\[ \textbf{A}=\begin{bmatrix} +1 & +1 & +1 \\ +1 & (-1)^a & (-1)^b \\ +1 & (-1)^c & (-1)^d\end{bmatrix}\] and thus \[\det(\textbf A)=(-1)^{a+d}+(-1)^{b}+(-1)^{c}-(-1)^{b+c}-(-1)^{a}-(-1)^{d}\] <br>

From this we can see that \(\det(\textbf A)\) is always even because switching one of \((+1)\) with \((-1)\) will change the sum by \(2\). <br><br> Now observe that if we take \(\textbf{A} = \begin{bmatrix} +1 & +1 & +1 \\ +1 & -1 & +1 \\ +1 & -1 & -1\end{bmatrix}\) . Thus, \(\det(\textbf{A}) = 4\) . So, we need to check for the possibility of \(6\).<br><br>

When the determinant is \(6\), we want the following parities: \[ \begin{matrix}\textbf{even} &\textbf{odd} \\ a+d & b+c\\ b & a\\ c & d\end{matrix}\]

But now left side says that sum \((a + b + c + d)\) must be even, and the right part says that it must be odd. Contradiction! Thus, the maximum possible value of \(\det(\textbf{A})\) is \(\boxed{4}\).

</details>

<p>
<li>Evaluate : \(\displaystyle\int_0^{102} \sum_{k=1}^{100} \dfrac{\prod_{n=1}^{100}(x-n)}{x-k}\,\text{dx}\) </li>
</p>

<details open><summary>Sol.</summary>
Set \(f(x)~:=~\displaystyle\prod_{k=1}^{100} (x-k)\). Then \(f'(x) = f(x)\cdot \displaystyle\sum_{k=1}^{100} {1\over {x-k}}\) , which is exactly the function inside the integral.<br><br>
Hence the answer is \[f(102)-f(0) = \prod_{k=1}^{100} (102-k) - \prod_{k=1}^{100} (-k) = \prod_{k=2}^{101} k - \prod_{k=1}^{100} k = 101!-100! = \boxed{100\cdot 100!}\]
</details>

<p>
<li> Does there exist a real polynomial \(H(x)\) with integer coefficients such that \(H(13) = 21\) and \(H(50) = 122\)?</li>
</p>

<details open><summary>Sol.</summary>
Since \(H\) is an integer polynomial, so for any two integers \(a\) and \(b\) , we must have \(a - b | H(a) - H(b)\) . But here, \((50 - 13) = 37 \nmid 101 = 122 - 21 = H(50) - H(13)\). Thus, there is no such polynomial.
</details>


<li>
<p> Consider two functions \(f\) and \(g\) defined as :
\[ f(x) = \dfrac{1}{x+a} + \dfrac{1}{x+b} - \dfrac{1}{c_1}\quad~\&~\quad g(x) = \dfrac{1}{x+a} + \dfrac{1}{x+b} - \dfrac{1}{c_2} \]

where \(a, b, c_1, c_2\) are real constants.
Both \(f\) and \(g\) have the property that their roots are equal in magnitude, but opposite in sign, i.e. if \(\alpha\) is one root of \(f\) , then its other root is \((-\alpha)\) . Simlarly, if \(\beta\) is one root of \(g\) , then the other root of \(g\) is \((-\beta)\).<br><br>

Let \(P_1\) denote the product of roots of \(f\) , and let \(P_2\) denote the product of two roots of \(g\). Find the value of \(\big(P_1 + P_2\big)\) , when \(a = 12\) , \(b = 13\) , \(c_1 = 147\) and \(c_2 = 187\) .
</p>

<i>Note: Incorrect problem.</i>
</li>


<details open><summary>No Solution</summary>

For the given values of the constants, the functions \(f\) and \(g\)
do not satisfy the condition that the roots have the same magnitude. Marks
was awarded to everybody.


<!--

Consider the function \[ h(x) = \dfrac{1}{x+a} + \dfrac{1}{x+b} - \dfrac{1}{c} \] where \(c\) is any non-zero real constant.

\begin{align*}
h(x) = 0 &\implies c(2x + a + b) = (x+a)(x+b)\\
&\implies x^2 + (a+b-2c)x + (ab - bc -ca) = 0
\end{align*}

Now, if \(r\) and \((-r)\) are two roots of \(h\) , then : \[ r^2 + (a+b-2c)r + (ab - bc -ca) = 0 \quad\&\quad r^2 - (a+b-2c)r + (ab - bc -ca) = 0 \]

Adding these two, we get \(a+b-2c=0\) which implies \(c=\frac{1}{2}(a+b)\) . Now, the product of the roots of \(h\) will be : \[ P = ab - bc - ca = ab - \dfrac{(a+b)^2}{2} = -\dfrac{a^2 + b^2}{2}\] which depends only on \(a\) and \(b\).<br><br>

Thus, in our problem, \[P_1 + P_2 = -\dfrac{a^2 + b^2}{2} - \dfrac{a^2 + b^2}{2} = -(12^2 + 13^2) = \boxed{-313}\quad\square \]
-->


</details>

<li><p> Evaluate the following integral : \(\displaystyle\int_{0}^{2\pi} \frac{1}{3+\cos t}dt\)</p></li>

<details open><summary>Sol.</summary>

Firstly, observe that the integrand is symmetric around \(\pi\). Thus, \[\displaystyle  \int_{0}^{2\pi} \frac{1}{3+\cos t}dt = 2 \int_{0}^{\pi} \frac{1}{3+\cos t}dt\]
Let us substitute \( \cos t = \frac{1-\tan^2\frac{t}{2}}{1+\tan^2\frac{t}{2}}\) , and put \(z = \tan\frac{t}{2}\). Then, we get:

\[I := \int_{0}^{\pi} \frac{1}{3+\cos t}dt = \int_{0}^{\pi} \frac{1+\tan^2 \frac{t}{2}}{4+2\tan^2 \frac{t}{2}}dt \]

Observe that we can substitute \(\tan\frac{t}{2} = z\) directly, to get :  \[ I = \int_0^\infty \dfrac{2}{2(2 + z^2)} dz = \dfrac{1}{\sqrt{2}} \tan^{-1}\big(\frac{z}{\sqrt{2}}\big)\bigg\vert_0^\infty = \dfrac{\pi}{2\sqrt{2}} \]

Thus, \[\displaystyle\int_{0}^{2\pi} \frac{1}{3+\cos t}dt = 2I = \dfrac{\pi}{\sqrt{2}}\]

</details>


<li>
<p>
We have a circular table with 6 chairs. Alice, Bob and Charlie each pick a random chair to sit down
in. What is the probability that there are two empty chairs next to each person?
</p>
</li>

<details open><summary>Sol.</summary>
Suppose Alice sits first. Bob has two favourable positions out of five possible options to sit. Charlie has one favourable option out of four
remaining positions. Hence, the required probability is \(2/5\times 1/4=1/10\).
</details>


<!--
SMT 2014 Gen. Tie 1/10.
-->

<li>
<p>
Given a complex number \(z\) such that \( z^{13}=1\), find all possible values of \( z+z^{3}+z^{4}+z^{9}+z^{10}+z^{12} \).
</p>
</li>


<details open><summary>Sol.</summary>

<b>Ans.</b> \( 6, \frac{-1 \pm \sqrt{13}}{2} \)
<br>
If \(z=1\), then the expression is simply equal to 6 . Otherwise, let \(\omega=z+z^{3}+z^{4}+z^{9}+z^{10}+z^{12}\). We find that

\[\omega^{2}=z^{2}+z^{6}+z^{8}+z^{5}+z^{7}+z^{11}+2X\]
where \(X=\left(z^{4}+z^{5}+z^{10}+z^{11}+1+z^{7}+z^{12}+1+z^{2}+1+z+z^{3}+z^{6}+z^{8}+z^{9}\right)\).

Applying the identity \(z+z^{2}+z^{3}+\cdots+z^{12}=-1\), we arrive at \(\omega^{2}=-1-\omega+2(3-1)=3-\omega\), and the solutions to the quadratic are \(\omega=\frac{-1 \pm \sqrt{13}}{2}\).

<br><i>Source: SMT 2013.</i>
</details>


</ol>



## Part B: Subjective questions

---
<p>
<b>B1.</b> In how many ways can \(2^{100}\) be expressed as a sum of four squares of integers?
</p>

<details open><summary>Sol.</summary>
We solve for the general case of \(2^n\).

If \(n=1,2^{n}=2^{1}=2\) which is expressible in only one way as \(1^{2}+1^{2}+0^{2}+0^{2}\).
<br>
If \(n=2,2^{n}=2^{2}=4\) which is expressible in two ways as \(2^{2}+0+0+0\), or as \(1^{2}+1^{2}+1^{2}+1^{2}\)
<br>

If \(n \geqslant 3,2^{n}\) is divisible by 8.<br>

<b>Lemma</b>. Square of an odd number leaves a remainder of 1 on division by 8.<br>
<i>Proof.</i> \((2k+1)^{2}=8 \cdot \frac{k(k+1)}{2}+1\) where \(\frac{k(k+1)}{2}\) is an integer, as
\(k(k+1)\) is even. \(\;\;\;\square\)<br>

It follows that \(x_{1}{ }^{2}+x_{2}{ }^{2}+x_{3}{ }^{2}+x_{4}{ }^{2}\) cannot be
divisible by 8 if any of the \(x_{1}\) are odd numbers. Therefore, if \(n \geq 3\) and \(x_{1}^{2}+x_{2}^{2}+x_{3}^{2}+x_{4}^{2}=2^{n} \;\; (1)\)
every \(x_{1}\) is even, \(x_{1}=2 X_{1}\) say, and \(X_{1}^{2}+X_{2}^{2}+X_{3}^{2}+X_{4}^{2}=2^{n-2}\;\;(2)\)<br><br>

Every solution of (1) may be obtained by doubling \(X_1\)s in a solution of \((2)\), so that \((1)\) and \((2)\) have the same number of solutions.

<br>Hence, repeating the argument, the number of solutions of \(x_{1}^{2}+x_{2}^{2}+x_{3}^{2}+x_{4}^{2}=2^{n}\)
is the same as the number of solutions of \(x_{1}^{2}+x_{2}^{2}+x_{3}^{2}+x_{4}^{2}=2^{1}\)
if \(n\) is odd, hence one solution.  If \(n\) is even, we count the solutions to \(x_{1}^{2}+x_{2}^{2}+x_{3}^{2}+x_{4}^{2}=2^{2}\) and there are two solutions.

</details>


---

<p>
<b>B2.</b> Consider the following polynomial where \(a_1,\ldots,a_n\) are distinct integers.

\[ r(x) =  \left(x-a_{1}\right)^{2}\left(x-a_{2}\right)^{2}\left(x-a_{3}\right)^{2} \ldots \left(x-a_{n}\right)^{2}+1 \]

Prove that \(r(x)\) cannot be written as the product of two other polynomials with integral coefficients.

</p>

<details open><summary>Sol.</summary>
<br>
Suppose, on the contrary, there exist polynomials \(p(x), q(x)\) with integer coefficients such that

\[ p(x) q(x)=\left(x-a_{1}\right)^{2}\left(x-a_{2}\right)^{2} \cdot \ldots\left(x-a_{n}\right)^{2}+1 \;\;\; (1) \]

Since the right hand side is always positive \(p(x)\) can never vanish, and hence its sign never changes.
We may assume that \(p(x)\) and \(q(x)\) are positive for all real \(x_0\). Substituting \(x=a_k\) in (1) gives


\begin{align*}
p\left(a_{k}\right) q\left(a_{k}\right)&=1 \\
p\left(a_{k}\right)=q\left(a_{k}\right)&=1 \quad \text { for } k=1,2, \ldots n
\end{align*}


By the factor theorem:

\begin{align*}
p(x)&=1+F(x)\left(x-a_{1}\right) \ldots\left(x-a_{n}\right)\\
q(x)&=1+G(x)\left(x-a_{1}\right) \ldots\left(x-a_{n}\right)
\end{align*}


where \(F(x)\) and \(G(x)\) are polynomials. From (1) the degree of \(p(x)q(x)\) is \(2n\) so that \(F(x)\)
and \(G(x)\) both have degree 0, that is, they are constants.  Suppose \(F(x)=a\) and  and \(G(x)=b .\)
Substitution in \((1)\) now gives \(a b=1\) and \(a+b=0\), but there are no real numbers \(a\) and \(b\) satisfying these equations.

<br><i>Source: Parabola</i>.


</details>


---

<p>
<b>B3. </b>  (i) Suppose \(f: \mathbb{R} \rightarrow \mathbb{R}\) is a differentiable function. Suppose \(f'(x) > f(x)\) for all \(x \in \mathbb{R}\) , and \(f(x_0) = 0\) for some \(x_0 \in \mathbb{R}\). Prove that \(f(x) > 0\) for all \(x > x_0\). \(\;\;\;\) [5 marks]<br>
(ii) Show that the equation \(Ae^x = 1 + x + \frac{x^2}{2}\) , where \(A\) is a positive constant, has exactly one real root. \(\;\;\;\) [5 marks]
</p>


<details open><summary>Sol.</summary>
(i)  Let \(g(x) = e^{-x} f(x)\) . Then, \(g'(x) =e^{-x} (f'(x) — f(x)) > 0\) . As \(g\) is an increasing function, so we have \(g(x)= e^{-x} f(x) \geqslant 0\) for \(x >x_0\) , and the conclusion follows.
<br>
<br>
(ii) Let \(f : \mathbb{R} \to \mathbb{R}\) be defined by \(f(x) = Ae^x - 1 - x - \dfrac{x^2}{2}\).<br><br>

Now, \(f(x) \to -\infty\) as \(x \to -\infty\) , and \(f(x) \to +\infty\) as \(x \to +\infty\) . Hence, as \(f\) is continuous, it has at least one real root, say \(x_0\). Observe that : $$f'(x) = Ae^x - 1 - x > Ae^x - 1 - x - \frac{x^2}{2} = f(x)\qquad\forall~ x\in\mathbb{R}$$

Thus, by part (i), we deduce that \(f\) has only one real root, viz. \(x_0\).

<br><i>Source:</i> UC Berkeley Ph.D Entrance Exam, Spring 1987<br>
</details>


---

<p>
<b>B4.</b>
We have a unit square made out of black paper. There are \(n\) axis-aligned white squares contained inside the black unit square. Let \(S\) denote
the set of white squares. The squares in \(S\) are pairwise disjoint. Prove that there exists a horizontal line
that intersects the unit square and passes through at most \( \sqrt{n} \) squares in \(S\).
<br>
You may assume that \(n\) is a perfect square.  For example, the figure shows a unit square containing \(n=9\) white squares.
</p>

<p style="text-align:center">
<img src="/assets/images/mt10_squares.png"/>
</p>


<details open><summary>Sol.</summary>

Assume, for a contradiction, that every horizontal line cuts more than
\(\sqrt{n}\) white squares. Suppose \(l_i\) is the side length of the \(i\)th white square.
Then the following must be true:<br>

<b>Proposition.</b> \( \sum l_i > \sqrt{n} \)<br>
<i>Proof.</i>
Assume that the black square is a unit square in the coordinate plane with bottom-left
corner at the origin.<br>
Let \(S=y_1,y_2,\ldots,y_k\) be the sequence of \(y\)-coordinates of all the horizontal edges of white squares in increasing order. <br>

Partition the unit square into horizontal strips so that the \(i\)th strip
is between \(y_{i}\) and \(y_{i+1}\).<br>

Here is the key. Let us double count the lengths of vertical sides of the white squares. Each
strip is made of up some portion of the left and right edges of the squares
so they must add up to \(2\sum l_i\). <br>

A horizontal line in the middle of each strip will cut through more than \(\sqrt{n}\)
squares, by our assumption. So the total lengths across all strips must be more than \(2\sqrt{n}\).

<br>Hence, \( 2\sum l_i > 2\sqrt{n} \) \(\;\;\;\square\)

<br>

But since the areas of all the white squares is less than 1, we have \(\sum l_i^2< 1\).

From RMS-AM inequality,

\[ \sqrt{\frac{l_{1}^{2}+\cdots+l_{n}^{2}}{n}} \geq \frac{l_{1}+\cdots+l_{n}}{n} \]

This contradicts the proposition. Hence, there must be a horizontal line that
cuts at most \(\sqrt{n}\) squares.

</details>


---

<p>
<b>B5</b>. \(ABC\) is an equilateral triangle and \(P\) is point on the circumcircle of \(ABC\). \(P\) is
any point on the arc \(AC\). Prove that \(PB=PA+PC\).
</p>

<details open><summary>Sol 1.</summary>
Let the side length of the equilateral triangle \(ABC\) be \(s\).
From Ptolemy's theorem,
\begin{align*}
PA\cdot CB + PC\cdot AB &= PB\cdot AC \\
PA\cdot s + PC\cdot s &= PB\cdot s  \\
PA + PC  &=  PB
\end{align*}
</details>




<details open><summary>Sol 2.</summary>
<i>Alternate solution without using Ptolemy's theorem.</i>

<p style="text-align:center">
<img src="/assets/images/mt10_circumcircle_sol.png"/>
</p>

Construct \(PX\) equal to \(PC\). Since \( \angle CPX = \angle CAB =60^\circ\), \(PCX\)
is equilateral. \( \angle CXB = 120^\circ = \angle CPA\) and \( CX=CP \). Also,
\( \angle PAC = PBC \). Therefore, \( \Delta CPA = \Delta CXB \) and \(PA = XB\). Hence:
\[ PC + PA  = PX + XB = PB \].
</details>


---

<p>
<b>B6. </b>

Let \(x\) be any real number and \(N\) be any integer \(>1\).
Show that there exists a rational number \(p/q\), with \(p\) and \(q\) integers and \(0< q \leqslant N\), such that:  \[\left|x-\frac{p}{q}\right| < \frac{1}{Nq}\]
<br>
For example, if \(x=\pi\) and \(N=10\), we can take \(p/q=22/7\). Then \(|\pi-22 / 7|<1/70\).

</p>


<details open><summary>Sol.</summary>

For each of the \((N+1)\) integers \(q, 0 \leqslant q \leqslant N\), consider \(\{q x\}=q x-[q x]\). Here \([qx]\) is the largest integer not greater than \(qx\), so that \(\{qx\}\) is the fractional part of \(qx, 0 \leqslant\{qx\}<1\).

Take \(N\) boxes, labelled \(1,2, \ldots, N\), and put \(\{q x\}\) into the box labelled \(j\) if \(\frac{j-1}{N} \leqslant\{q x\}<\frac{j}{N}\).
By the pigeon-hole principle, there is a box containing at least two numbers \(\left\{q_{1} x\right\}\) and \(\left\{q_{2} x\right\}\) where
\(0 \leqslant q_{1}< q_{2} \leqslant N\).
Since they both lie in an interval of length \(\frac{1}{N}\) we have \(\left|\left\{q_{1} x\right\}-\left\{q_{2} x\right\}\right|< \frac{1}{N}\) i.e. \(\left|\left(q_{2} x-\left[q_{2} x\right]\right)-q_{1} x-\left[q_{1} x\right]\right| < \frac{1}{N}\)
Putting \(q=q_{2}-q_{1}\) and \(p=\left[q_{2} x\right]-\left[q_{1} x\right]\) this is \(|q x-p|< \frac{1}{N} ;\) hence \(\left.\right|x-\frac{p}{q} \mid<\frac{1}{Nq}\)

</details>

