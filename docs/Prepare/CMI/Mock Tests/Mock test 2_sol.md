---
layout: default
title: Mock test 6
nav_exclude: true
---


#  Mock test #6: Solutions
#### Full syllabus test
#### Timings: 17:00-20:00 Hrs &nbsp;&nbsp;  Date: 1 April 2021
{: .fs-3 .text-grey-004 }

---

## Part A: Short-answer type questions

<ol>

<li>Find a non-constant polynomial that divides all the polynomials in the set:
\[ \mathcal{P} =  \{ P_k: P_k(x) = x^{3k+2}+x+1, k\in \mathbb{N} \}  \]
</li>

<details open><summary>Sol.</summary>

Let \(\omega\) be the complex cube root of unity. Both \(\omega\) and \(\omega^2\) are the roots of every polynomial in \(\mathcal{P}\). Therefore, \((x-\omega)(x-\omega^2)=x^2+x+1\)
must divide every \(P_k\).


</details>



<li>Let \(\alpha_1,\ldots,\alpha_n\) denote the \(n\) roots of unity. Let \(\alpha_1=1\). What is the value of the following product?

\[ \prod_{i=2}^n (1-\alpha_i) \]

</li>


<details open><summary>Sol.</summary>
\(\alpha_2,\ldots,\alpha_n\) are the roots of the polynomial \( x^{n-1}+x^{n-2}+\ldots+1 \).<br>

\(1-\alpha_2,\ldots,1-\alpha_n\) are the roots of the polynomial \( (1-x)^{n-1}+(1-x)^{n-2}+\ldots+1 \).

It follows from Vieta's formula that \(n\) is the value of the given product.
</details>


<li>We have a regular hexagon whose area is 1 sq.unit. A triangle is formed by joining the midpoints of alternate sides as shown below. What is the
area of the triangle?


<p style="text-align:center">
<img src="/assets/images/hex_triangle.png"/>
</p>


</li>

<details open><summary>Sol.</summary>
<b>Ans.</b> 3/8.
</details>

<li>Let \( \displaystyle f(x) = \frac{x^2e^{x^2}}{1-x^2} \). Find the \(6\)th derivative of \(f\) evaluated at 0, that is, \(f^6(0)\). </li>


<details open><summary>Sol.</summary>




The Taylor series is given by
\[
f(x)=x^{2}\left(1+\frac{x^{2}}{1 !}+\frac{x^{4}}{2 !}+\cdots\right)\left(1+x^{2}+x^{4}+\cdots\right)
\]

\(f^{(n)}(0)=a_{n} n !\), where \(a_{n}\) is the \(n\)th Taylor series coefficient.

The coefficient of \(x^{6}\) is \(\frac{1}{2 !}+\frac{1}{1 !}+1=\frac{5}{2}\), so \(f^{(6)}(0)=6! \cdot \frac{5}{2}=1800\).



</details>


<li>The number of real valued solutions to the equation \(e^x=\sin x\) is:
<ol>
<li>0</li>
<li>1</li>
<li>2</li>
<li>4</li>
<li>none of the above.</li>
</ol>
</li>


<details open><summary>Sol.</summary>
(e) There are infinite solutions. For every \(n\in\mathbb{N}\), there is a solution in the interval \([-2n\pi,-2(n+1)\pi]\).
</details>




<li>
Find a line \(l\) that intersects the four lines given below. The lines are in \(\mathbb{R}^3\). Express
the equation of \(l\) in the parameterized form as given for \(l_i\)s.
<br>

\begin{align*}
l_1: &\; (1,0,0) + t(0,0,1) \\
l_2: &\; (0,1,0) + t(1,0,0) \\
l_3: &\; (0,0,1) + t(0,1,0) \\
l_4: &\; (0,0,0) + t(6,6,-1)
\end{align*}


</li>


<details open><summary>Sol.</summary>
The equation of a line that passes through points \( (x_1,y_1,z_1) \) and \((x_2,y_2,z_3)\) is:

\[ \frac{x-x_1}{x_1-x_2}  = \frac{y-y_1}{y_1-y_2} = \frac{z-z_1}{z_1-z_2} \]


Without loss of generality, assume that \(l\) passes through \( (1,0,a) \) and \( (b,1,0) \) of \(l_1\) and \(l_2\). So the
equation of \(l\) is:<br>

\[ \frac{x-1}{1-b}  = \frac{y-0}{0-1} = \frac{z-a}{a-0} \]


We have the equation in two variables \(a\) and \(b\). Since \(l\) intersects
\(l_3\), it passes through \(x=0\) and \(z=1\).  <br>

\begin{align*}
\frac{0-1}{1-b} &= \frac{1-a}{a-0}  \\
\implies & \boxed{b(1-a) = 1}
\end{align*}

Since \(l\) also passes through \(l_4:x=y=-6z\) we get:

\begin{align*}
\frac{x-1}{1-b} &= \frac{x-a}{a-0} \\
\frac{-6z-0}{0-1} &= \frac{z-a}{a} \\
x=-6z \implies &  \boxed{6a = 6ab-1}
\end{align*}

Using the two boxed equations, we get a quadratic in \(a\). Solving for \(a\)
gives \(a=-1/2\) and \(b=2/3\)  or \(a=1/3\) and \(b=3/2\).<br>


Hence the possible lines are \( (1,0,-1 / 2)+t(-1/3,1,1/2) \)
and \( (1,0,1/3)+t(1/2,1,-1/3) \).<br>


<br><i>Comment: This was a hard problem for Part A. Nobody solved it</i>

</details>



<li>
Suppose \(a_i\) and \(b_i\) are real numbers such that \(\sum_1^\infty a_i^2\) and \(\sum_1^\infty b_i^2\) converge. Which of these statements is true?

<ol>
<li>The sequence \(\sum_1^\infty |a_i-b_i| \) converges. </li>
<li>The sequence \(\sum_1^\infty |a_i-b_i|^{3/2} \) converges. </li>
<li>The sequence \(\sum_1^\infty (a_i-b_i)^2 \) converges. </li>
<li>The sequence \(\sum_1^\infty (a_i-b_i)^3 \) converges. </li>
</ol>
</li>

<details open><summary>Sol.</summary>
<b>Ans.</b> (c) and (d)

\[ 0 \leq (a_i-b_i)^2 = 2a_i^2 + 2b_i^2-(a_i+b_i)^2 \leq 2a_i^2 + 2b_i^2 \]


Since \(\sum a_i^2 \) and \(\sum b_i^2\) are absolutely convergent, \(\sum 2a_i^2+2b_i^2 \)
is also convergent.
<br>
For sufficiently large \(i\), \(|a_i-b_i|<1\) so \( |a_i-b_i|^3 \leq |a_i-b_i|^2 \). Since \( (a_i-b_i)^3 \)
is absolutely convergent it is convergent.

</details>



<li>
<p>
Let \(\phi(n)\) denote the number of positive integers less than \(n\) that are relatively prime to \(n\).
In other words, \(\phi(n)\) counts all \(m\) such that
\(\operatorname{gcd}(m, n)=1\).


</p>


<p>
The number \(n=220358\) is a product of three primes \(p\), \(q\) and \(r\).
We also know that \(\phi(n) = 109480.\)
</p>

<p>
Find the values of \(p\), \(q\) and \(r\).
</p>

</li>


<details open><summary>Sol.</summary>
See <a href="/docs/number_theory/gcd/#totient-function">A3, 2016</a>.
</details>


<li>
<p>Calculate the determinant of the matrix given below:

\begin{bmatrix}
1 & 2 & 3 & 4 & 5 & 6\\
2 & 2 & 3 & 4 & 5 & 6\\
3 & 3 & 3 & 4 & 5 & 6\\
4 & 4 & 4 & 4 & 5 & 6\\
5 & 5 & 5 & 5 & 5 & 6\\
6 & 6 & 6 & 6 & 6 & 6\\
\end{bmatrix}
</p>

</li>

<details open><summary>Sol.</summary>

Apply: \(C_1 \leftarrow C_1-C_2\). Then set \(C_{i} \leftarrow C_1+C_i\) for \(i\in\{2,\ldots,6\}\). We get:

\begin{bmatrix}
-1 & 0 & 0 & 0 & 0 & 0\\
0 & 2 & 3 & 4 & 5 & 6\\
0 & 3 & 3 & 4 & 5 & 6\\
0 & 4 & 4 & 4 & 5 & 6\\
0 & 5 & 5 & 5 & 5 & 6\\
0 & 6 & 6 & 6 & 6 & 6
\end{bmatrix}

Recursively applying a similar operation on the minor of element -1 we get:

\begin{bmatrix}
-1 & 0 & 0 & 0 & 0 & 0\\
0 & -1 & 0 & 0 & 0 & 0\\
0 & 0 & -1 & 0 & 0 & 0\\
0 & 0 & 0 & -1 & 0 & 0\\
0 & 0 & 0 & 0 & -1 & 0\\
0 & 0 & 0 & 0 & 0 & 6
\end{bmatrix}

Hence the determinant is -6.

<br><i>Problem source: <a href="https://math.stackexchange.com/questions/2013663/if-a-ij-maxi-j-calculate-the-determinant-of-a">Math Stack Exchange.</a></i>

</details>

<li>
<p>
Suppose \( S=\{1,2,3,4,5,6,7\} \).  Find the number of pairs \( (A,B) \)
that can be formed such that \(A \subseteq S\) and \(B\subset A\).
</p>
</li>


<details open><summary>Sol.</summary>
Set \(A\) can have 1 to 7 elements. Set \(B\) can have \(2^n-1\) elements
if \(A\) has \(n\) elements.

\begin{align*}
\sum_{n=1}^{7}\binom{7}{n} \left(2^{n}-1\right) &=\sum_{n=0}^{7} \binom{7}{n} \left(2^{n}-1\right) \\
&= (2+1)^{7}-(1+1)^{7} \\
&=\:3^7-2^7 \\
&= 2059
\end{align*}



</details>


</ol>





---

## Part B: Subjective questions

**Submission files:** Each question in this part must be answered on a page of its own. Name the files as B1.jpg, B2.jpg, etc. In case you have multiple files
for the same question, say B4, name the corresponding files as B4-1.jpg, B4-2.jpg, etc.
{: .fs-3 }


**Clearly explain your entire reasoning.** No credit will be given without reasoning. Partial solutions may get partial credit.

---

<p>
<b>B1.</b> Let \( f(x)=a_{0}+a_{1} x+a_{2} x^{2}+a_{3} x^{3}\) be a polynomial with integer coefficients
such that \(a_{0}\) and \(a_{3}\) are odd numbers.

<ol>
<li>Suppose \(p\) has a rational root \(\frac{p}{q}\), where \(\text{gcd}(p,q)=1\). Prove that both \(p\) and \(q\) must be odd.</li>
<li>Suppose \(a_0,a_3\) and \(a_0+a_1+a_2+a_3\) are all odd. Prove that \(f\) has no rational roots.</li>
</ol>

</p>


<details open><summary>Sol.</summary>
(a)

\begin{align*}
a_{0}+a_{1} \frac{p}{q} +a_{2} \left(\frac{p}{q}\right)^{2}+a_{3} {\left(\frac{p}{q}\right)}^{3} &= 0 \\
a_{0}q^3+a_{1}pq^2 +a_{2}p^2q+a_{3}p^3 &= 0 \\
\implies  p|a_0 \text{ and } q|a_3 &
\end{align*}

An even number cannot divide an odd number. Since \(a_0\) and \(a_3\) are odd, \(p\) and \(q\) must be odd.<br>  <br>

(b)  Since \(f(1)\) is given to be odd, \(a_1+a_2\) must be odd (<b>C1</b>).<br>

Let us suppose that \(p/q\) is a rational root of \(f\).
 Hence, \( a_{0}q^3+a_{1}pq^2 +a_{2}p^2q+a_{3}p^3 = 0 \). From, part (a) both \(p\) and \(q\) must be odd. Taking \(\pmod{2}\)
of the above equation, we see that \( a_1+a_2 \) must be even, which contradicts (<b>C1</b>).


</details>



---

<p>
<b>B2. </b> By induction or otherwise, show that:

\[ \binom{n}{2} ! >\; 2^{n^2} \]

for all \(n\geq 6\).
</p>


<details open><summary>Sol.</summary>
<i>Base case</i>. Claim: \(\binom{6}{2}! > 2^{32} \)

\begin{align*}
\binom{6}{2}! =  15! & = 1\times2\times3\times4\times5\times6\times7\times8\times9\times10\times11\times12\times13\times14\times15 \\
                 & > 1\times2\times2\times4\times4\times4\times4\times8\times8\times8\times8\times8\times8\times8\times8 \\
                 & > 1\times2^2\times4^4\times8^8 \\
                 & > 1\times2^2\times2^8\times2^{24} \\
                 & > 2^{34}
\end{align*}

<i>Hypothesis.</i> \( \binom{n}{2} ! >\; 2^{n^2} \) for a fixed \(n\geq 6\)<br>

<i>Inductive step.</i> <br>

\begin{align*}
\binom{n+1}{2}  &=  \binom{n}{2} + \binom{n}{1}   \\
                &=  \binom{n}{2} + n   \\
\binom{n+1}{2}! &=  \binom{n}{2}! \prod_{i=1}^{n} \left(\binom{n}{2}+i\right)! \\
                &>  \binom{n}{2}!\;\; 2^{3n} \;\;\text{ since }\binom{n}{2}>15>2^3 \text{for } n\geq 6 \\
                &>  2^{n^2}2^{2n+1} \;\;\text{ by hypothesis} \\
                &>  2^{(n+1)^2}
\end{align*}






</details>

---

<p>
<b>B3.</b> We are given two positive integers \(a>2\) and \(n\) such that the following \(n+1\) numbers
are all composite numbers:

\[ a,a+1,a+2,\ldots,a+n \]

Prove that there exists an integer \(t>1\) such that the following consecutive numbers are all composite:

\[ a^t,a^t+1,a^t+2,\ldots,a^t+n \]

</p>

<details open><summary>Sol.</summary>

<b>Lemma 1. </b> \(a^{k(p-1)+1} \equiv a \pmod{p} \)  for a prime \(p\) and any integer \(k\).<br>

<i>Proof.</i> If \(p\nmid a\), then \(a^{k(p-1)}\equiv 1 \pmod{p}\) by Fermat's little theorem. If \(p\mid a\), both LHS and RHS in
the lemma are \(0 \pmod{p}\). \(\;\;\;\square\)<br><br>


Let \(p_i\) denote a prime that divides \(a+i\).<br>

<b>Claim. </b> \(p_i | a^t+i\), where \(t=\prod_{i=1}^{n} (p_i-1)+1\).<br>

<i>Proof.</i> By Lemma 1, \(a^t \equiv a \pmod{p}\). So \(a^t+i \equiv a+i \equiv 0 \pmod{p_i}\).  \(\;\;\;\square\)<br><br>



Hence, for the above choice of \(t\), the numbers \( a^t,a^t+1,a^t+2,\ldots,a^t+n \) are all composite.

</details>

---

<p>
<b>B4.</b> Consider the trapezoid \(ABCD\) in which \(|AD|=|BC|\). Prove that the centroid of the triangle \(ABD\) lies on the line \(CF\). Here,
point \(F\) is the projection of \(D\) on \(AB\).


</p>

<details open><summary>Sol.</summary>

Let \(M\) be the midpoint of side \(AB\). Consider the trapezoid \(CDFM\). Since \(CD:FM=2:1\) the diagonals divide
each other in the same ratio, from points \(C\) and \(D\). Hence, the centroid of \(ABD\) coincides with the intersection
of the diagonals. Hence, the centroid lies on \(CF\).


<p style="text-align:center">
<img src="/assets/images/iso_trapezoid_sol.png"/>
</p>

<br>
<i>Problem source: Sharygin geometry olympiad</i>.

</details>

---

<p>
<b>B5. </b> Let \(\pi\) denote a permutation of numbers from \(1\) to \(12\). We denote
the number at the \(i\)th position by \(\pi(i)\).
For example, if the permutation is \([1,12,11,2,3,4,5,6,7,8,9,10]\), then \(\pi(1) = 1\), \(\pi(2)=12\), \(\pi(3)=11\), etc.

Count the number of permutations \(\pi\) that satisfy the following condition:

\[ \pi(i) < \pi(i+1) \;\;\text{for } i \in \{1,2,4,5,7,8,9,11\} \]

<i>Write your answer as a single number (without any factorials or binomials).</i>


</p>

<details open><summary>Sol.</summary>

Partition the permutation into four segments of lengths 3, 3, 4 and 2 as shown. The condition is to ensure
that elements within each segment are sorted in increasing order. The elements in the first segment can
be picked in \( \binom{12}{3} \) ways. The next segments can be filled in \( \binom{9}{3} \), \( \binom{6}{4}\) and \( \binom{2}{2} \) ways, respectively.


<p style="text-align:center">
<img src="/assets/images/permutation_segment.png"/>
</p>

The total number of permutations satisfying the condition is:
\[ \binom{12}{3}\binom{9}{3}\binom{6}{4}\binom{2}{2} = 277200 \]

</details>


---


<p>
<b>B6. </b> We have a function \(f:\mathbb{R}\rightarrow\mathbb{R}\) that is twice differentiable and satisfies the following equation:

\[  \int_{x-y}^{x+y} f(t) dt  = 2yf(x)  \]

Prove that \(f(x)=ax+b\) for some \(a,b\in\mathbb{R}\).
</p>


<br>
<i>Problem source: AoPS forum ISI/CMI 2019 prep.</i>

<details open><summary>Sol.</summary>

Let \(F\) be the anti-derivative of \(f\). We have

\[ F(x+y)-F(x-y)=2 y f(x) \]

Keeping \(x\) fixed, differentiate the above equation with respect to \(y\):

\[ f(x+y)+f(x-y)=2 f(x) \]

Differentiate again w.r.t \(y\):

\begin{align*}
f^\prime(x+y)-f^\prime(x-y) &= 0  \\
f^\prime(x+y)&=f^\prime(x-y) \;\;\;\; \forall y \\
f^\prime(x)&=a \;\;\;\text{ for some constant }a \\
f(x)&=ax+b
\end{align*}





</details>



