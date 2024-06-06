---
layout: default
title: Mock Test #1 solutions
has_children: false
nav_exclude: true
parent: CMI
permalink: docs/math-exams/cmi/mt-1-sol
color_scheme: light

---


#  MT #1: Full-syllabus
## [Solutions]
#### Timings: 10:30-13:30 Hrs &nbsp;&nbsp;  Date: 28 Feb 2021
{: .fs-3 .text-grey-004 }

---

<button class="btn js-toggle-dark-mode">◑</button>
<script>
const toggleDarkMode = document.querySelector('.js-toggle-dark-mode');
jtd.addEvent(toggleDarkMode, 'click', function(){
  if (jtd.getTheme() === 'light') {
    jtd.setTheme('dark');
    toggleDarkMode.textContent = '◑';
  } else {
    jtd.setTheme('light');
    toggleDarkMode.textContent = '◐';
  }
});
</script>

## Part A: Short-answer type questions

**Submission file:** Write answers to all the ten questions on a single sheet of paper. Email a picture of your answer sheet. Name the file as PartA.jpg.
{: .fs-3 }

**For this part, answers must be written without any explanation.**



<ol>


<li>
<p>
There are 8 marbles of different colors and 8 different bags of matching colors. In how many ways can we put one marble in each bag such
that exactly 5 marbles go to the bag of the matching color?
</p>
<details open><summary>Sol.</summary>
The number of ways of putting 5 balls in correct bags is \( {}^8C_5 \). There are two ways to derange the remaining
three balls.<br>
\[ {}^8C_5 \times 2 = 112 \]
</details>
</li>



<li>
<p>
Suppose \(f(x)\) is a continous function satisfying two relations:<br>

(a) \( f(x)-f\left(\frac{x}{4}\right)=\frac{3x}{4} \)<br>
(b) \( f(0) = 3 \)<br>

Find \(f(x)\).
</p>

<details open><summary>Sol.</summary>
<b>Ans.</b> \( f(x) = x+3 \).<br>

For any \(x \in \mathbb{R}\) we have:

\begin{align*}
f(x)-f\left(\frac{x}{4}\right) =\frac{3 x}{4} \\
f\left(\frac{x}{4}\right)-f\left(\frac{x}{4^{2}}\right)&=\frac{3 x}{4^{2}} \\
\vdots \\
f\left(\frac{x}{4^{n-1}}\right)-f\left(\frac{x}{4^{n}}\right)&=\frac{3 x}{4^{n}}
\end{align*}

Telescoping, we get:<br>

\begin{aligned}
f(x)-f\left(\frac{x}{4^{n}}\right) &=\frac{3 x}{4}\left\{1+\frac{1}{4}+\cdots+\frac{1}{4^{n-1}}\right\} \\
&=x\left(1-\frac{1}{4^{n}}\right)
\end{aligned}

Since \(f\) is continuous,
\[  \lim_{n \rightarrow \infty} f\left(\frac{x}{4^{n}}\right)=f(0) \]

Therefore \(f(x)-f(0)=x\).  Hence \( f(x)=x+3 \;\;\; \forall x \in R \).


</details>


</li>



<li>
<p>
Let \( z_{1}, z_{2}, z_{3}\) be complex numbers such that
\[ \left|z_{1}\right|=\left|z_{2}\right|=\left|z_{3}\right|=1 \]
and
\[ \frac{z_{1}^{2}}{z_{2} z_{3}}+\frac{z_{2}^{2}}{z_{1} z_{3}}+\frac{z_{3}^{2}}{z_{1} z_{2}}+1=0 \]
Find the value of \( \left|z_{1}^3+z_{2}^3+z_{3}^3\right| \).

</p>

<details open><summary>Sol.</summary>

\begin{align*}
\frac{z_{1}^{3}}{z_1 z_{2} z_{3}}+\frac{z_{3}^{2}}{z_{1}z_2z_{3}}+\frac{z_{3}^{3}}{z_1z_2z_3}&=-1  \\
z_{1}^3+z_{2}^3+z_{3}^3  &= -z_1z_2z_3  \\
\left|z_{1}^3+z_{2}^3+z_{3}^3\right|  = \left|z_1 z_2 z_3\right| &=  \left|z_1\right|\left|z_2\right|\left|z_3\right|=1
\end{align*}





</details>


</li>

<p>
<li>

There are \(n\) stones arranged in a circular pattern. At time \(t=0\) s, two grasshoppers are resting on a common stone. Grasshopper A starts to hop
in clockwise direction in intervals of 3 stones. Grasshopper B jumps every 7 stones at each time step in anti-clockwise manner. The figure below
shows the first jump. What is the earliest time step when both the grasshoppers land on the same stone again? Find this number when \(n=300\) and when \(n=301\).

<p style="text-align:center">
<img src="/assets/images/mt3_grasshopper.png"/>
</p>

</li>
</p>


<details open><summary>Sol.</summary>
Let the stones be labelled  \(0\ldots n-1\) in clockwise direction, with stone 0 being the initial starting point.
After \(t\) seconds the first grasshopper will be at stone no. \(3t\) and the second at \(-7t\) modulo \(n\) so:

\begin{align*}
3t &\equiv -7t \pmod{n} \\
10t &\equiv 0 \pmod{n}
\end{align*}

The value of \(t=30\)s if \(n=300\) and \(301\)s when \(n=301\).

</details>






<li>
<p>
 Four six-faced dice are rolled simultaneously. What is the probability that the highest-valued die shows 4? Write the answer as a reduced fraction.
</p>

<details open><summary>Sol.</summary>
The number of ways in which four is the highest face among the rolled dice = \(4^4 - 3^4\) = 175.
(We exclude the number of rolls that have the highest face as three or less).  The total number of outcomes is \(6^4\) = \(1296\).  <br>

Required probability = \(\frac{175}{1296}\).
</details>






</li>


<p>
<li>
Find the equation of the plane in \(R^3\) that passes through the following points: \( (2,0,0), (1,3,1) \) and \( (5,1,1) \).
</li>
<details open><summary>Sol.</summary>

Assume that the equation of the plane is \(ax+by+cz=1\). Since the plane passes through three points the equation must statisfy:

\begin{align*}
2a + 0 + 0 = 1 \\
a + 3b + c = 1 \\
5a + b + c = 1 \\
\end{align*}

We get \( a=1/2, b = 1\) and \(c=-5/2\), so the answer is \(x+2y-5z=2\).


</details>
</p>


<p>
<li>
\(ABC\) is a triangle with \( \angle A = 30^{\circ} \), \( \angle B = 60^{\circ} \) and \(AB=10\). Find the
length of the shortest trisector of \( \angle C \).
</li>
<details open><summary>Sol.</summary>
\begin{align*}
CD&=\sin 60^{\circ} \cdot BC\\
&=\sin 60^{\circ} \cdot \cos 60^{\circ} \cdot A B \\
&=\frac{\sqrt{3}}{2} \cdot \frac{1}{2} \cdot 10 \\
&=5 \frac{\sqrt{3}}{2}
\end{align*}
</details>
</p>




<p>
<li>
A non-zero polynomial \(p(x) = a_nx^n + a^{n-1}x^{n-1} + \ldots + a_0 \) is said to be a palindrome if \( a_i = a_{n-i} \) for \(i=0,\ldots,n\). It can
be proved that a polynomial is a palindrome if and only if \( p(x) = x^n p( \frac{1}{x} ) \). Which of these statements are true?

<ol>
<li>If \(p(x)\) and \(q(x)\) are palindromes then \( p(x)+q(x) \) is also a palindrome. </li>
<li>If \(p(x)\) and \(q(x)\) are palindromes then \( p(x)q(x) \) is also a palindrome. </li>
<li>Suppose \(p(x)\) is a palindrome that can be factored as \( r(x)s(x) \) where both \(r(x)\) and \( s(x) \) are polynomials with integer coefficients.  Then both \( r(x) \) and \( s(x) \) are palindromes. </li>
<li>Suppose \(p(x)\) is a palindrome that can be factored as \( r(x)s(x) \) where both \(r(x)\) and \( s(x) \) are polynomials with integer coefficients.  Then exactly one of \( r(x) \) or \( s(x) \) is a palindrome. </li>
</ol>

<details open><summary>Sol.</summary>
Only (b) is correct.<br>

Counterexample for (a): \( (x+1)+(x^2+2x+1)=x^2+3x+2  \).<br>
Counterexample for (c) and (d): \( 3x^2+10x+3=(3x+1)(x+3) \).

<br>
<br>
<i>Thanks to Devansh Kamra for pointing out a mistake in the earlier solution.</i>
</details>



</li>
</p>


<p>
<li>
The value of \( {}^{50}C_0 {}^{50}C_{1} + {}^{50}C_1 {}^{50}C_{2} +  \ldots + {}^{50}C_{49} {}^{50}C_{50} \) is:
<ol>
<li>\( {}^{100}C_{49}  \)</li>
<li>\( {}^{100}C_{50}  \)</li>
<li>\( {}^{100}C_{48}  \)</li>
<li>\( ({}^{50}C_{25})^2 \)</li>
</ol>
</li>


</p>

<details open><summary>Sol.</summary>
The given expression is the co-efficient of the term \(x^{49}\) in \( (1+x)^{50}\cdot (1+x)^{50} = (1+x)^{100} \).
</details>


<li>
<p>
Find all possible pairs of integers \((m, n)\) which satisfy \(m^{2}+2 m-35=2^{n}\).

<details open><summary>Sol.</summary>
Factoring, we have \( (m+7)(m-5)=2^{n}\). Notice that \(m+7\) and \(m-5\) are 12 apart,
and also observe that the only powers of 2 which differ by 12 are 4 and \(16,\) so \(n=2+4=6\).
There are two cases:<br>
(a) \(m+7=16\) and \(m-5=4\), which gives us \(m=9\).<br>

(b) \(m+7=-4\) and \(m-5=-16\), which gives us \(m=-11\).

The answer is therefore (9,6) and (-11,6). <br>
<i>Problem source:</i> SMT.
</details>

</p>
</li>




</ol>


## Part B: Subjective questions

**Submission files:** Each question in this part must be answered on a page of its own. Name the files as B1.jpg, B2.jpg, etc. In case you have multiple files
for the same question, say B4, name the corresponding files as B4-1.jpg, B4-2.jpg, etc.
{: .fs-3 }


**Clearly explain your entire reasoning.** No credit will be given without reasoning. Partial solutions may get partial credit.


<p>
<b>B1. </b> We have two circles touching each other as shown below. The radius of the smaller circle is \(r\). \(CM\) is the
diameter of the inner circle. \(AB\) is a tangent to the inner circle with \(M\) as its midpoint. Suppose \( |MA|=|MB|=a\) cm. Find the radius of the larger circle in terms of \(a\) and \(r\).

<p style="text-align:center">
<img src="/assets/images/mt_3_B1.png"/>
</p>

</p>

<details open><summary>Sol.</summary>

Let the radius of the larger circle be \(R\).  Now \(CM=2r\)  and \( MD=2(R-r) \). From Ptolemy's theorem, we have:

\begin{align*}
& CM \cdot MD=AM \cdot MB \\
\quad 2 r \cdot 2(R-r) &=a^{2} \\
\quad R &=\frac{a^{2}+4 r^{2}}{4 r}
\end{align*}


</details>

<p>
<b>B2 (a)</b> [4 marks] Find all positive integer solutions to the equation:
\[ 86x + 10y = 500 \]
</p>

<br>

<p>
<b>B2 (b)</b> [6 marks] Let us suppose \(a,b,c\) are positive integers.
Suppose the equation \( ax+by = c \) has \(m\) positive solutions.
How many positive solutions does the following equation have?
\[ ax+by = c+ab \]
</p>

<details open><summary>Sol.</summary>
<p>
<b>(a) Ans.</b> \( (5,7) \). <br>
<b>(b) Ans.</b> \(m+1\) solutions.

<br>
Let \( (x_0,y_0) \) be a particular solution to the first equation \( ax+by = c\). Let the GCD of \(a\) and \(b\) be \(g\). Without
loss of generality, we may assume that \( (x_0,y_0) \) is such that \( (x_0 + kb/g,y_0-ka/g) \) is a solution for \( k \in \{0,\ldots,m-1\} \).


<br>
This means that \( (x_0+b+kb/g,y_0-ka/g) \) is a solution to the second equation for \(k\in \{-g,\ldots,0,1,\ldots,m-1\}\).
Hence, there are \(m+g\) solutions.
</p>

<br>
<p>
<i>The earlier solution assumed that \(a\) and \(b\) are relatively prime. Thanks to Snehansu for the correction.</i>
</p>

</details>



<p>
<b>B3.</b> In the figure shown below, ABCD is a square with side length 1 unit. M is the midpoint of the side BC.
What is the area of the shaded portion?

<p style="text-align:center">
<img src="/assets/images/mt3_shaded_quad.png"/>
</p>

</p>


<details open><summary>Sol.</summary>

<p>

<p style="text-align:center">
<img src="/assets/images/mt3_shaded_quad_sol.png"/>
</p>


Triangles \(IAB\) and \(IMN\) are similar. The triangles have altitudes \(x\) and \(h\),
respectively. Hence, we have:

\[ \frac{AB}{MN} = \frac{x}{h} \]

\(AB=1\) and \(MN=1/2\), so \(x=2h\). Since \(x+h=1/2\), we have \(h=1/6\).

The area of the triangle \(IMN\) is \(1/2\times h \times MN=1/24\)  sq. units.  The area of the shaded portion is therefore \(1/12\) sq. units.

</p>

</details>






<p>
<b>B4 (a)</b>\[ \int_{0}^{1} x(1-x)^{2021} \,  dx \]
<br>
<b>B4 (b)</b>\[ \int_{0}^{\pi / 2} \frac{d x}{1+(\tan x)^{2021}} \]
</p>

<details open><summary>Sol.</summary>
<b>(a)</b> Substitute \(1-x=u\). We get \[ \int_{0}^{1} (1-u)u^{2021} \,  du = \frac{1}{2022} - \frac{1}{2023} \]
<b>(b)</b> Let \(f(x)\) denote the function in the integral. For any \(k\) we have:

\( f(\pi / 2-x)=1 /\left(1+\cot^{k} x\right)=\tan ^{k} x /\left(1+\tan ^{k} x\right)=1-f(x) \)


\begin{align*}
\int_{0}^{\pi / 2} \mathrm{f}(\mathrm{x}) \mathrm{dx}&=\int_{0}^{\pi / 4} \mathrm{f}(\mathrm{x}) \mathrm{d} \mathrm{x}+\int_{\pi / 4}^{\pi / 2} \mathrm{f}(\mathrm{x}) \mathrm{d} \mathrm{x} \\
&=\int_{0}^{\pi / 4} \mathrm{f}(\mathrm{x}) \mathrm{d} \mathrm{x}+\int_{0}^{\pi / 4} \mathrm{f}(\pi / 2-\mathrm{x}) \mathrm{d} \mathrm{x}\\
&=\int_{0}^{\pi / 4} \mathrm{f}(\mathrm{x}) \mathrm{d} \mathrm{x}+\int_{0}^{\pi / 4}(1-\mathrm{f}(\mathrm{x})) \mathrm{d} \mathrm{x} \\
&=\int_{0}^{\pi/4} \mathrm{d}\mathrm{x} \\
&=\pi/4
\end{align*}

<i>Probem source:</i> Putnam 1980.


</details>


<p>
<b>B5.</b> We are given a number \(P\). We want to pick \(n\) positive integers \(x_1,\ldots,x_n\) such that two conditions are met:<br>

<i>Condition 1:</i> The product of the \(x_i\)s must be \(P\). That is, \( x_1\times x_2\times\ldots x_n = P\).<br>
<i>Condition 2:</i> The GCD of \(x_1,\ldots,x_n\) is maximized.


<br><br>

(a) Let us denote the GCD by \(g\).  If the prime factorization of \( P=p_{1}^{k_{1}} \ldots p_{\ell}^{k_{\ell}}\), what is the value of \(g\)?<br>

(b) Write the value of \(g\) for \(n=5\) and \(P=2^5 \cdot 3^6\cdot 5^{10} \cdot 7^3\).
</p>




<details open>
<summary>Sol.</summary>


<p>
(a) Let \(g\) be the GCD  of \(x_{1}, \ldots, x_{n}\). Since \(x_{i}\) is a multiple of \(g\), \(P\) must be a multiple of \(g^{n}\).
But if \(P\) is a multiple of \(g^{n}\) we can make the GCD \(g\) by the following assignment:

\[ x_{1}=\cdots=x_{n-1}=g, x_{n}=g \times \frac{P}{g^{n}}\]

Thus, the answer is the maximum \(g\) such that \(g^{n}\) divides \(P\).

Let \( P=p_{1}^{k_{1}} \ldots p_{\ell}^{k_{\ell}}\) be the prime factorization of \(P\).
Then, \(g\) must be of the form \( g=p_{1}{ }^{k_{1}^{\prime}} \ldots p_{\ell}{ }^{k_{\ell}^{\prime}}\)
and \(g^{n}\) divides \(P\) when \(n k_{i}^{\prime} \leq k_{i}\) for each \(i\).
In order to maximize \(g\) we should choose \( k_{i}^{\prime}=\lfloor \frac{k_{i}}{n} \rfloor \).
Thus, the answer is \(p_{1}^{\left\lfloor\frac{k_{1}}{n}\right\rfloor} \ldots p_{\ell}^{\left\lfloor\frac{k_{\ell}}{n}\right\rfloor}\).

<br> <br>

(b) Applying the above formula: \(g = 2^13^15^2=150\).

<br> <br>

<i>Problem source</i>: Caddi 2018 Beginners <a href="https://img.atcoder.jp/caddi2018/editorial.pdf">[pdf]</a>.
</p>


</details>





<p>
<b>B6.</b> We have a square grid where \( (0,0) \) is the origin and \( (6,6) \) is the top-right corner. We want to move from
the origin to \( (6,6) \) using only right steps and upward steps. It is a well known fact that there are \( {}^{12}C_6 \) ways of doing this. Consider the
following addtional constraint: We are not allowed to step on the eight shaded coordinates shown in the figure below. How many ways are there to go from \( (0,0) \) to \( (6,6) \) obeying these constraints?
</p>


<p style="text-align:center">
<img src="/assets/images/mt3_lattice.png"/>
</p>


<details open><summary>Sol.</summary>
There are three sets of paths. We list each one along with its cardinality.
<ol>
<li> Paths that go below the blocks: There are 7 of them.</li>
<li> One path goes above the blocks.</li>
<li> Paths that go in-between the two blocks: These have to pass through \( (2,3) \) and \( (3,3) \). There are \( {}^5C_2\times {}^6C_{3} = 200 \).</li>
</ol>
There are \( 208 \) paths in all.
</details>



<!--
B6. Stanford General. Answer: 208.
https://faculty.math.illinois.edu/~hildebr/putnam/training19/integrals1.pdf

-->






