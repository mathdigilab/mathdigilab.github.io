---
layout: default
title: Mock test 8 Solutions
nav_exclude: true
---


#  MT #8: Full-syllabus
## [Solutions]
#### Timings: 17:00-20:00 Hrs &nbsp;&nbsp;  Date: 20 May 2021
{: .fs-3 .text-grey-004 }

---


## Part A: Short-answer type questions

<ol>

<li>
<p>
Find all possible triplets \( (x,y,z) \) satisfying the equations:

\begin{align*}
(x+1)(y+1)&=24 \\
(y+1)(z+1)&=8 \\
(z+1)(x+1)&=48
\end{align*}
</p>
</li>


<details open><summary>Sol.</summary>
<b>Ans. </b> \( (11,1,3) \) and \( (-13,-3,-5) \).


\begin{align*}
(x+1)^2(y+1)^2(z+1)^2 &=  2^{10}3^2 \\
(x+1)(y+1)(z+1) &=  \pm 2^{5}3 = \pm 96 \\
(z+1) &=  \frac{\pm 96}{(x+1)(y+1)}  \\
z = 3 \text{ or } -5
\end{align*}

Similarly, we find the values of \(x\) and \(y\).


</details>





<li>
<p>
There is a glass cylinder with radius \(R\). An ant is \(d\) cm from the mouth of the cylinder. It is
on the <i>outer surface</i> of the cylinder. There is a honey drop on the <i>inner surface</i> of cylinder
that is also \(d\) cm from the mouth of the cylinder and diametrically opposite to the ant. What is the shortest distance the ant has to travel
to get to the honey drop?
</p>

<p style="text-align:center">
<img src="/assets/images/mt8_ant_honey.png"/>
</p>



</li>


<details open><summary>Sol.</summary>

<b>Ans.</b> \(2\sqrt{d^2 + \left( \frac{\pi r}{2} \right)^2} \). <br>

<p style="text-align:center">
<img src="/assets/images/mt8_ant_honey_sol.png"/>
</p>

<i>Source: A. Zee (2013), Einstein Gravity in a Nutshell.</i>

</details>





<li>
<p>

In the triangle \(ABC\) given below, \(BC=8\) cm and \(AD=6\) cm. \(AD\) is the altitude of the triangle. Points
\(E\) and \(G\) are midpoints of segments \(BD\) and \(AC\), respectively. What is the length of \(EG\)?


<p style="text-align:center">
<img src="/assets/images/mt8_triangle.png"/>
</p>

</p>
</li>


<!--
RMO 2.19 Geometry
-->


<details open><summary>Sol.</summary>
Let \(GF\) be perpendicular to \(BC\). Since \(ADC\) is similar to \(GFC\), \(F\) is the midpoint of \(DC\) and \(GF=AD/2 = 3\) cm. \(EF=BC/2=4\) cm.
\begin{align*}
EG^2 &= GF^2 + EF^2 \\
&= 3^2 + 4^2 \\
EG &= 5\text{ cm }
\end{align*}

</details>


<p>
<li>
Let \(A\) be a non-empty subset of real numbers and \(f: A \rightarrow A\) be a function such that \(f(f(x))=x\) for all
\(x \in A\).  Then \(f(x)\) is<br>

<ol>
<li>a bijection.</li>
<li>one-one but not onto.</li>
<li>onto but not one-one.</li>
<li>neither one-one nor onto.</li>
<li>Not confined exclusively to one of the above four options.</li>
</ol>

</li>
</p>


<details open><summary>Sol.</summary>
<b>Ans.</b> (a). \(f\) is a bijection.<br>

<b>Lemma.</b> \(f(x)\) is one-to-one, that is, \(f(a)=f(b) \implies a = b\). <br>
<i>Proof.</i>  Suppose \(f(a) = f(b)\), then:

\[f(f(a)) = f( f(b) ) \implies a = b \;\;\;\;\;\square\]

<b>Lemma.</b> \(f(x)\) is onto.<br>
<i>Proof.</i> For any \(a\in A\), \(f(a)\in A\) is the pre-image of \(a\).\(\;\;\;\square\) <br>


</details>




<li> Which of the following functions are bijections?

<ol>
<li> \(f: \mathbb{R} \rightarrow \mathbb{R} \)  defined as \( f(x):=x+\tan^{-1}x \).</li>
<li> \(f: \mathbb{R} \rightarrow \mathbb{R} \)  defined as \( f(x):=x-\tan^{-1}x \).</li>
<li> \(f:\,  \mathbb{R}^+ \rightarrow \mathbb{R} \)  defined as \( f(x):=\lim_{n\rightarrow \infty} \frac{1}{n} \log_{e} (1+e^{nx}) \).</li>
</ol>



</li>


<details open><summary>Sol.</summary>
The last function is \(f(x) = x\) so it is a bijection. In the first two equations \(f^\prime(x) > 0\) so both are increasing functions. The range
of both functions is \(\mathbb{R}\).  Hence, all three functions are bijections.
</details>




<li>
<p>
A cone with height \(h\) is inscribed in a larger cone with height \(H\).
The vertex of the inner cone is at the center of the base of the larger cone.
For what value of \(h\) is the volume of the inner cone maximized?
</p>


<p style="text-align:center">
<img src="/assets/images/mt8_cone.png"/>
</p>

</li>


<details open><summary>Sol.</summary>

<b>Ans.</b> \(H/3\).<br>

Let \(R\) be the radius of the base of the larger cone and \(r\) that of the smaller cone.

\[ \frac{H-h}{r}=\frac{H}{R} \Rightarrow r=\frac{R}{H}(H-h) \]


Hence the volume of the inscribed cone is

\[ V=\pi r^{2} h=\frac{\pi R^{2}}{H^{2}}(H-h)^{2} h \]

\begin{align*}
0 &=\frac{d V}{d h} \\
&=\frac{\pi R^{2}}{H^{2}}\left(-2(H-h) h+(H-h)^{2}\right) \\
&=\frac{\pi R^{2}}{H^{2}}(H-h)(-2 h+H-h) \\
&=\frac{\pi R^{2}}{H^{2}}(H-h)(H-3 h) \\
& \Rightarrow h=H / 3, H
\end{align*}

At \(h=H\), the volume is zero. So \(h=H/3\) gives that maximum volume.

</details>


<li>
<p>An ATM machine dispenses one note at a time. We can collect either a Rs. 100, Rs. 200 or Rs. 500 note in one operation.
We can collect a certain sum in multiple ways. For example, there are three different ways to collect
a sum of Rs. 300: 100+200, 200+100 or 100+100+100. What is the minimum sum that we can collect in at least 30 different ways?
</p>
</li>

<!--
smt2018 discrete
-->


<details open><summary>Sol.</summary>
<b>Ans.</b> Rs. 800 <br><br>

Let \(f(x)\) denote the number of ways to take \(100x\) rupees. We can express \(f(x)\) recursively
in terms of smaller amounts. If the first note that is drawn is \(Rs. 100\), then there are \(f(x-1)\) ways to collect the rest. In general,

\[ f(x) = f(x-1) + f(x-2) + f(x-5) \]

\begin{align*}
f(1) &= 1 \\
f(2) &= 2 \\
f(3) &= 3 \\
f(4) &= f(3) + f(2) = 5 \\
f(5) &= f(4) + f(3) + 1 = 9 \\
f(6) &= f(5) + f(4) + f(1) = 15 \\
f(7) &= f(6) + f(5) + f(2) = 26 \\
f(8) &= f(7) + f(6) + f(3) > 30
\end{align*}




</details>


<p>
<li>

Let \(f\) be a twice differentiable function on \(\mathbb{R}\).
Also \(f^{\prime \prime}(x)>0\) for all \(x \in \mathbb{R}\).

Which of the following statements is true?

<ol>
<li> \(f(x)=0\) has exactly two solutions on \(\mathbb{R}\).</li>
<li> \(f(x)=0\) has a positive solution if   \(f(0)=0\) and \(f^{\prime}(0)=0\).</li>
<li> \(f(x)=0\) has no positive solution if  \(f(0)=0\) and \(f^{\prime}(0)>0\).</li>
<li> \(f(x)=0\) has no positive solution if  \(f(0)=0\) and \(f^{\prime}(0)<0\).</li>

</ol>





</li>
</p>

<details open><summary>Sol.</summary>
<b>Ans.</b> (c)<br>
\(f^{\prime \prime}(x)>0 \Rightarrow f^{\prime}(x)\) is increasing. Also \(f^{\prime}(0)>0 \Rightarrow f^{\prime}(x)>0\) if \(x>0 . \Rightarrow f(x)=0\) has
no positive solution.
</details>




<p>
<li>
Let \(\alpha_{1}, \alpha_{2}, \cdots, \alpha_{n}\) be the roots of the equation \(x^{n}-kx+1=0\) where \(n\geq 3\).
Find the value of \(\sum_{i=1}^{n} \alpha_{i}^{n}\) in terms of \(k\) and \(n\).
</li>
</p>

<!--
Madhava 2011 Part 2. \sum \alpha_i = 0. So the required sum is n.
-->


<details open><summary>Sol.</summary>
<b>Ans.</b> \(-n\)<br>

By Vieta's formula: \( \sum \alpha_i = 0\).

\begin{align*}
\sum (\alpha_i^n - k\alpha_i + 1) &= 0 \\
\sum (\alpha_i^n) + 0 + n  &= 0 \\
\sum (\alpha_i^n)  &= -n
\end{align*}

</details>


<p>
<li>
Let \(a,b,c\) be positive real numbers satisfying:
\[ a+b+c = 10 \text{ and } ab+bc+ca=25 \]

What is the maximum possible value of \(\text{min}(ab,bc,ac)\).

</li>
</p>



<details open><summary>Sol.</summary>
<b>Ans.</b> 25/9.<br>

Without loss of generality, assume \(a\leq b\leq c\). So now we have to maximize the value of \(ab\).


<b>Lemma.</b> At the optimal point, \(\frac{10}{3} \leq c \leq \frac{20}{3} \). <br>

<i>Proof.</i>

Then \(a+b+c=10\) implies \(c\geq \frac{10}{3}\). <br><br>

\begin{align*}
ab + bc + ca &= 25 \\
ab + c(10-c)  &= 25 \\
ab &= 25 - c(10-c)
\end{align*}

AM-GM inequality implies that \( \left( \frac{a+b}{2} \right)^2 \geq ab \). Substituting in the equation above:

\begin{align*}
\left( \frac{a+b}{2} \right)^2 &\geq 25 - c(10-c) \\
\left( \frac{10-c}{2} \right)^2 &\geq 25 - c(10-c) \\
c(10-c) &\geq 25 - \left( \frac{10-c}{2} \right)^2 \\
c(10-c) &\geq  \left( \frac{c}{2}  \right) \left( \frac{20-c}{2} \right)  \\
40 - 4c &\geq 20 - c \\
c &\leq \frac{20}{3}      \;\;\;\;\;\;\; \square
\end{align*}


We can express \(ab\) in terms of \(c\):

\begin{align*}
ab  = f(c) =  25 - c(10-c)
\end{align*}

Notice that \(f(c)\) is convex in the domain \( [10/3,20/3] \). It attains maximas at \(c=10/3\) and \(c=20/3\).
We can pick \(a=b=5/3\) and \(c=20/3\) and get the maximum.

</details>




</ol>






## Part B: Subjective questions


<p>
<b>B1. </b> The sides of a triangle are in arithmetic progression (A.P.) . The altitudes
of the triangle are also in A.P. Prove that the triangle must be equilateral.
</p>

<!--
Iberoamerican pdf 3rd  1988, A1
-->

<details open><summary>Sol.</summary>



Let the sides be \(a, a+d, a+2d\) with \(d>=0\). Then the altitudes are \({2\Delta} / {a} \geq {2\Delta} /({a}+{d}) \geq {2\Delta} /({a}+2 {~d})\),
where \({\Delta}\) is the area of the triangle.

Since the altitudes are in A.P.:

\begin{align*}
2\Delta/a+2\Delta/(a+2d) &= 4\Delta /(a+d) \\
1/a+1/(a+2d) &= 2 /(a+d) \\
(a+d)(a+2d) + a(a+d) &= 2a(a+2d) \\
(a+d)(a+2d) + a(a+d) &= 2a(a+2d) \\
(d-a)(a+2d) + a(a+d) &= 0 \\
2d^2 & = 0 \text{ which implies } d=0 \;\;\;\;\square
\end{align*}



</details>

---

<p>
<b>B2.</b> A plane is partitioned into regions by three sets of parallel lines. There is no point that is
common to three distinct lines. The number of lines in the first, second and third sets are \(x,y\) and \(z\), respectively.

<ol>
<li>Find the number of regions formed by the lines in terms of \(x, y\) and \(z\). [5 marks]</li>
<li>What is the minimum value of \(x+y+z\) for which it is possible to get at least 200 regions? [5 marks]</li>
</ol>

</p>

<!--
University of Toronto. pg. 173.
-->

<details open><summary>Sol.</summary>
<ol>
<li>
Assume that no point is common to three distinct lines. The \(x+y\) lines of the first two families partition the plane into \((x+1)(y+1)\) regions. Let \(\lambda\) be one of the lines of the third family. It is cut into \(x+y+1\) parts by the lines in the first two families, so the number of regions is increased by \(x+y+1\). Since this happens \(z\) times, the number of regions that the plane is partitioned into by the three families of lines is

\[ n=(x+1)(y+1)+z(x+y+1)=(x+y+z)+(x y+y z+z x)+1 \]
</li>


<li>Let \(u=x+y+z\) and \(v=x y+y z+z x\). By Cauchy-Schwarz Inequality, \(v \leq x^{2}+y^{2}+z^{2}\),
so that \(u^{2}=x^{2}+y^{2}+z^{2}+2 v \geq 3 v\). Therefore, \(n \leq u+\frac{1}{3} u^{2}+1\).
For \(u=23\), RHS is 200. If we choose \((x, y, z)=(8,8,7)\), then \(n=200\). So 23 lines are necessary and sufficient.
</li>

</ol>

</details>




---

<p>
<b>B3.</b> (a) Find two continous functions \(f: \mathbb{R}\rightarrow\mathbb{R}\) and \(g: \mathbb{R}\rightarrow\mathbb{R}\) such that:

<ul>
<li>\(f(x)\) is differentiable everywhere but \(g(x)\) is not.</li>
<li>\(f(x)\times g(x)\) is differentiable everywhere.</li> &nbsp;&nbsp;[3 marks]
</ul>

<br>


(b) Suppose \(f: \mathbb{R} \rightarrow \mathbb{R}\)
is a differentiable map satisfying \(f(0)=0\) and \(f(1)=1\).
For all real \(x\),  we have \(\left|f^{\prime}(x)\right| \leq 2\). <br>

What is the maximum possible value of \(\int_{0}^{1} f(x) d x\),
over all such possible functions \(f\)? &nbsp;&nbsp; [7 marks]

</p>


<details open><summary>Sol.</summary>

(a) \(f(x) = x^2\) and \(g(x)=|x|\). <br>

(b)

\begin{align*}
\int_0^t f^\prime(x)\, dx \leq \int_0^t 2\, dx &\Rightarrow f(t) \leq 2t  \\
\int_t^1 f^\prime(x)\, dx \geq \int_t^1 -2\, dx &\Rightarrow f(t) \leq -2t+3
\end{align*}

<p style="text-align:center">
<img src="/assets/images/mt8_integral_sol.png"/>
</p>

The maximum area is then given by:
\[ \int_0^{0.75} 2x dx + \int_{0.75}^1 (-2x+3) dx = 0.875 \]


</details>


---


<p>
<b>B4.</b> Let \(m\) be a positive integer, such that
\[ \frac{m+1}{m}=\frac{p+1}{p} \cdot \frac{q+1}{q} \]

where \(p\) and \(q\) are positive integers exceeding \(m\).

<ol>
<li> Prove that \((p-m)(q-m)=m(m+1)\). &nbsp; [2 marks] </li>
<li> Suppose \(\Phi(m)\) and \(\Phi(m+1)\) denote the number of
positive divisors of \(m\) and \(m+1\), respectively. Count the number of
positive integer pairs \( (p,q) \) that satisfy the above equation and
express this number in terms of \(\Phi(m)\) and \(\Phi(m+1)\). &nbsp; [6 marks]</li>
<li>Using the result in the previous part, find the number of ways in
which \(\frac{27}{26}\) can be expressed as a product of two rational numbers \(\frac{p+1}{p}\) and \(\frac{q+1}{q}\). &nbsp;[2 marks]</li>
</ol>
</p>

<details open><summary>Sol.</summary>

(i) We have \((m+1) p q=m(p+1)(q+1)\), which reduces to \((p-m)(q-m)=m(m+1)\). <br><br>


(ii) Suppose \(p=m+u\) and \(q=m+v\), where \(u v=m(m+1)\). So every representation of
\((m+1) / m\) corresponds to a factorization of \(m(m+1)\).  On the other hand, observe that, if \(u v=m(m+1)\), then

\begin{align*}
\frac{m+u+1}{m+u} \cdot & \frac{m+v+1}{m+v}=\frac{m^{2}+m(u+v+2)+u v+(u+v)+}{m^{2}+m(u+v)+u v} \\
&=\frac{m^{2}+(m+1)(u+v)+m(m+1)+2 m+1}{m^{2}+m(u+v)+m(m+1)} \\
&=\frac{(m+1)^{2}+(m+1)(u+v)+m(m+1)}{m^{2}+m(u+v)+m(m+1)} \\
&=\frac{(m+1)[(m+1)+(u+v)+m]}{m[m+(u+v)+m+1]}=\frac{m+1}{m}
\end{align*}


Since \(m(m+1)\) is not square, \(u\) and \(v\) are always distinct. Hence, there is a one-one correspondence between representations and unordered pairs \((u, v)\) of complementary factors of \(m(m+1)\).

Since \(m\) and \(m+1\) are coprime, the number of factors of \(m(m+1)\) is equal to \(\Phi(m) \Phi(m+1)\), and so the number of representations is equal to \(\frac{1}{2} \Phi(m) \Phi(m+1)\).<br><br>

(iii) \( \frac{\Phi(26)\cdot\Phi(27)}{2} = \frac{4\cdot 4}{2} = 8 \).


<br><br><i>Source: University of Toronto Competition.</i>
</details>




---

<p>
<b>B5.</b>. We have natural numbers \(a,b\) and \(c\) such that:

\[ a+b = \frac{ab}{c} \;\text{ and } \text{gcd}(a,b,c)=1 \]


Prove that \(a+b\) is a perfect square.


<!--
https://www.cut-the-knot.org/arithmetic/ShortEquationInReciprocals.shtml#solution
-->
</p>






<details open><summary>Sol.</summary>
(Solution due to Eugene Lee) From \(a+b=\frac{a b}{c}\), the primes factors of \(c\) are either in \(a\) or in \(b\) but not in both since \(\operatorname{gcd}(a, b, c)=1\).
<br>
We can factor \(c=c_{1} c_{2}\) such that  \(a=u c_{1}, b=v c_{2}\), with \(\operatorname{gcd}(u, c)=\operatorname{gcd}(v, c)=1\). Thus
\(u c_{1}+v c_{2}=u v .\) So \(u\) divides \(v c_{2}\), hence \(v .\) Similarly \(v\) divides \(u c_{1}\), hence \(u\). Therefore \(u=v\), and \(a+b=u^{2}\).
</details>




---

<p>

<b>B6.</b> Prove that any real number \(\alpha\geq \frac{3\sqrt{3}}{2}\) can be expressed in the form:

\[ \alpha=\sum_{n=0}^{\infty} \frac{a_{n+1}}{a_{n}^{3}} \]

where \(a_{0}, a_{1}, a_{2}, \ldots\) is an increasing sequence of
real numbers with \(a_{0}=1\).

</p>

<!--
https://www.simonmarais.org/2020.html
-->

<details open><summary>Sol.</summary>

<p>
We show that there is a solution where \(a_n\)s are in a geometric progression.
Let \(r>1\) be a real number, and consider the sequence \(a_{n}=r^{n}\) for all \(n>0\). For this sequence we have

\[
\sum_{n=0}^{\infty} \frac{r^{n+1}}{\left(r^{n}\right)^{3}}=\sum_{n=0}^{\infty} r^{1-2 n}=\frac{r}{1-r^{-2}}=\frac{r^{3}}{r^{2}-1} .
\]

Let \(f:(1, \infty) \rightarrow \mathbb{R}\) be the function defined by \(f(x)=\frac{x^{3}}{x^{2}-1}\). Then

\[ f^{\prime}(x)=\frac{x^{2}\left(x^{2}-3\right)}{\left(x^{2}-1\right)^{2}} \]

from which it follows that \(f\) is decreasing on \((1, \sqrt{3}]\) and increasing on \([\sqrt{3}, \infty)\). Since \(f(\sqrt{3})=\frac{3 \sqrt{3}}{2}\), it follows
that every number greater than \(\alpha\) can be expressed in the given form.
</p>

<i>From Simon Marais 2020 competition.</i>


</details>

