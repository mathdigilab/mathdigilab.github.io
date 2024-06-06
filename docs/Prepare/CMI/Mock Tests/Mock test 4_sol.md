---
layout: default
title: Mock test 9
nav_exclude: true
---


#  MT #9: Full-syllabus
## [Solutions]
#### Timings: 14:00-17:00 Hrs &nbsp;&nbsp;  Date: 4 June 2021
{: .fs-3 .text-grey-004 }

---

## Part A: Short-answer type questions

<ol>

<li>

<p>
Let \(n\) be a positive integer. Line segments can be drawn parallel to edges of a given
rectangle. What is the minimum number of line segments that are required so as to divide
the rectangle into exactly \(n\) subrectangles? The subrectangles need not be of the same dimension.
</p>

<p>
For example, in order to get 5 subrectangles we need 3 line segments.

<p style="text-align:center">
<img src="/assets/images/mt9_subrectangles.png"/>
</p>


</p>

</li>


<details open><summary>Sol.</summary>
If we have \(x\) horizontal lines and \(y\) vertical lines can we get \( (x+1)(y+1) \) subrectangles. For a
fixed \(t=x+y\), the number of subrectangles is maximized if \(x=y\) or \(x=y\pm 1\).<br>

Let \(p=\lfloor \sqrt{n} \rfloor\). Let \(f(n)\) denote the minimum number
of required to get \(n\) subrectangles. <br>


\[
 f(n)  =
  \begin{cases}
   2(p-1) & \text{if } n=p^2 \\
   2p-1 & \text{if } p^2 < n \leq p(p+1) \\
   2p & \text{if }  p(p+1) < n < (p+1)^2 \\
  \end{cases}
\]


</details>




<p>
<li>
The polynomial \( f(x)=a x^{2018}+b x^{2017}+c x^{2016} \)  has real coefficients less than 2020  and
\[ f\left(\frac{1+\sqrt{3} i}{2}\right)=2015+2019 \sqrt{3} i \]

Write the value of \(f(1)\).
</li>
</p>


<details open><summary>Sol.</summary>

<b>Ans.</b> 6053<br>

\[ f\left( e^{i\pi/3} \right) = e^{i2016\pi/3}( ae^{i2\pi/3} + be^{i\pi/3} + c  ) = 2015 + i2019\sqrt{3}    \]


\begin{align*}
-\frac{a}{2} + \frac{b}{2} + c &= 2015 \\
\frac{\sqrt{3}a}{2} + \frac{ \sqrt{3}b}{2} &= 2019\sqrt{3}
\end{align*}

\begin{align*}
-a + b + 2c &= 4030\\
a + b &= 4038
\end{align*}

Since the coefficients are less than \(2020\), \(a=2019,b=2019 \) and \(c=2015\)
is a solution.  \(f(1) = a+b+c = 6053 \).


<br><i>Source: Mathforces. Tricky polynomial.</i>
</details>



<p>
<li>
Let \(X\) be a set and \(A, B, C\) be its subsets. Which of the following is necessarily true?<br>

(a) \(A-(A-B)=B\)<br>
(b) \(A-(B \cup C)=(A-B) \cup(A-C)\)<br>
(c) \(A-(B \cap C)=(A-B) \cap(A-C)\)<br>
(d) \(B-(A-B)=B\)<br>

</li>



</p>



<details open><summary>Sol.</summary>
<b>Ans.</b>(d)<br>

Note that \(A-B=A \cap B^{\prime}\). So \((A-B)^{\prime}=\left(A \cap B^{\prime}\right)^{\prime}=A^{\prime} \cup B\).<br>
Hence \(B-(A-B)=B \cap(A-B)^{\prime}=B \cap\left(A^{\prime} \cup B\right)=\left(B \cap A^{\prime}\right) \cup B=B\).

<br>
<i>From Madhava competion.</i>
</details>



<!-- SAQ 3 -->
<p>
<li> Find the number of functions \(f:\{1,\ldots, 5\} \to \{1,\ldots, 5\}\) such that \(f(f(x))=x\) .</li>
</p>

<details open><summary>Sol.</summary>

<b>Ans.</b> 26.<br>

If for all \(n\) , we have \(f(n)=n\) , then obviously there is \(1\) way.<br><br>
If only \(3\) of the \(5\) numbers satisfy \(f(n)=n\) then there are \(\binom{5}{2}=10\) ways.<br><br>
If only \(1\) of the \(5\) numbers satisfies \(f(n)=n\) then there are \(\binom{5}{4}\times 3=15\) ways.<br><br>
Thus our answer is \(15+10+1=\boxed{26}\) .

</details>



<p>
<li>
The number of roots of \(g(x)=5 x^{4}-4 x+1=0\) in \([0,1]\) is<br>

(a) 0<br>
(b) 1<br>
(c) 2<br>
(d) 3<br>

</li>


<details open><summary>Sol.</summary>
\(g(0)>0\) and \(g(1)>0\) while \(g(1 / 2)<0\).
Hence, \(g(x)=0\) has at least two roots.
Note that \(g^{\prime}(x)<0\) if \(x^{3}<1 / 5\) and \(g^{\prime}(x)>0\) if \(x^{3}>1 / 5\).
Hence, the function is decreasing in \((-\infty, \sqrt[3]{1 / 5})\) and increasing on \((\sqrt[3]{1 / 5}, \infty)\).
At \(\sqrt[3]{1 / 5}\) the function has absolute minimum.
</details>


</p>







<!-- SAQ 6 -->
<p>
<li> Evaluate : \(\lim\limits_{n\to\infty} \displaystyle\int_{0}^{1} \left(1 + \frac{x}{n}\right)^n dx\) </li>
</p>


<details open><summary>Sol.</summary>
Consider \(u=1+\frac{x}{n}~\implies~du = \frac{1}{n} dx~\implies~ n⋅du=dx\).<br>
So, the given limit becomes:

\[ \lim\limits_{n\to\infty} \int_{0}^{1} \left(1 + \frac{x}{n}\right)^n dx = \lim\limits_{n\to\infty} \int_{1}^{1+\frac{1}{n}} n u^n du = \lim\limits_{n\to\infty} \bigg[\frac{n}{n+1}\left(1 + \frac{1}{n}\right)^{n+1} - \frac{n}{n+1}\bigg] = e - 1\]
</details>


<!-- SAQ 7 -->
<p>
<li> Consider a square \(ABCD\), whose length of a side is \(7\) units. Now, draw an equilateral triangle \(ABM\) so that the vertex \(M\) lies inside the square. The diagonal \(AC\) meets the triangle at the point \(K\). Find out the value of \(| CK - KM |\) .</li>
</p>


<details open><summary>Sol.</summary>

<p style="text-align:center">
<img src="/assets/images/mt9_triangle_sol.png"/>
</p>


Observe that in \(\Delta AKB\) , \(\angle AKB = 75^\circ\) , \(\angle KAB = 45^\circ\) , \(\angle ABK = 60^\circ\) . Thus, by sine rule, we have :
\[ \dfrac{BK}{\sin 45^\circ} ~=~ \dfrac{AK}{\sin 60^\circ} ~=~ \dfrac{7}{\sin 75^\circ} \]

which implies that \[ BK ~=~ \sin 45^\circ \cdot \dfrac{7}{\sin 75^\circ}~~~~\quad\text{and}\quad~~~~ AK ~=~ \sin 60^\circ \cdot \dfrac{7}{\sin 75^\circ}\].

Now, \(CK = AC - AK = 7\sqrt{2} - AK\) , and \(KM = BM - BK\) . Thus, we have:

\begin{align*}
|CK - KM| &~=~ 7\sqrt{2} - 7 - \dfrac{7}{\sin 75^\circ} \bigg[\dfrac{\sqrt{3}}{2} - \dfrac{1}{\sqrt{2}}\bigg]\\
&~=~ 7\big(\sqrt{2} - 1\big) - \dfrac{14\sqrt{2}}{\sqrt{3}+1}\cdot \dfrac{\sqrt{6} - 2}{2\sqrt{2}}\\
&~=~ \dfrac{7}{\sqrt{3}+1}\Big[\sqrt{6} + \sqrt{2} - \sqrt{3} - 1 - \sqrt{6} + 2 \Big]\\
&~=~\dfrac{7}{\sqrt{3}+1}\Big(\sqrt{2}+1-\sqrt{3}\Big)
\end{align*}





</details>



<!-- SAQ 8 -->
<p>
<li> \(2021\) players numbered \(1, 2, \cdots , 2021\) took part in a table tennis tournament. Each player played exactly one game against each of the \(2020\) other players, and no match ended in a draw. Let \(W_k\) and \(L_k\) denote the number of matches won and lost respectively by the \(k\)-th player, for \(k = 1, 2, \cdots , 2021\). Find out which among the following options is correct :

<ol>
<li> \(~~~~\displaystyle\sum_{k=1}^{2021} W^2_k = (2020)^2 - \displaystyle\sum_{k=1}^{2021} L^2_k\)</li>
<li> \(~~~~\displaystyle\sum_{k=1}^{2021} W^2_k = \binom{2021}{2} + \displaystyle\sum_{k=1}^{2021} L^2_k\)</li>
<li> \(~~~~\displaystyle\sum_{k=1}^{2021} W^2_k = (2020)^2 + \displaystyle\sum_{k=1}^{2021} L^2_k\)</li>
<li> \(~~~~\displaystyle\sum_{k=1}^{2021} W^2_k = \displaystyle\sum_{k=1}^{2021} L^2_k\)</li>
<li> \(~~~~\displaystyle\sum_{k=1}^{2021} W^2_k = 2021 + \displaystyle\sum_{k=1}^{2021} L^2_k\)</li>
</ol>
</li>
</p>


<details open><summary>Sol.</summary>
<b>Ans.</b> (d)<br>

Observe that each player played exactly \(2020\) matches, and each resulted in etiher a win or loss for the player. Thus, for every \(k\), we have \(W_k + L_k = 20\) . Now,

\begin{align*}
\displaystyle\sum_{k=1}^{2021} W^2_k - \displaystyle\sum_{k=1}^{2021} L^2_k &= \displaystyle\sum_{k=1}^{2021} \big[W^2_k - L^2_k\big]\\
&= \displaystyle\sum_{k=1}^{2021} \big(W_k + L_k\big)\big(W_k - L_k\big)\\
&= 2020 \cdot \displaystyle\sum_{k=1}^{2021} \big(W_k - L_k\big)\\
&= 2020 \cdot \left[\displaystyle\sum_{k=1}^{2021} W_k - \displaystyle\sum_{k=1}^{2021} L_k \right]\\
&= 2020 * 0\\
&= \boxed{0}
\end{align*}


</details>


<!-- SAQ 9 -->
<p>
<li> Let \(\Lambda\) be the set of all \(n \in \mathbb{N}\) such that both the numbers \((n+3)\), and \((n^2 + 3n +3)\) are perfect cubes. Find the cardinality of the set \(\Lambda\).
</li>
</p>


<details open><summary>Sol.</summary>
Let \(~n+3 = a^3\) , and \(~n^2 + 3n +3 = b^3\) . Then : $$(ab)^3 = a^3b^3 = (n+3)(n^2+3n+3) = n^3 + 6n^2 + 12n + 9 = (n + 2)^3 + 1$$ which is not a perfect cube for any natural \(n\). This gives rise to a contradiction as the LHS is a perfect cube. So, \(\Lambda\) is the null set.<br><br>

Therefore, there exists no such minimal element in \(\Lambda\), as it is empty.
</details>


<!-- SAQ 10 -->

<p>
<li> Consider \(ABCDE\) to be a convex pentagon such that \(AB = AE = CD = 1\), \(\angle ABC = \angle DEA = 90^\circ\) , and \(BC + DE = 1\). Find
the area of the pentagon.</li>
</p>

<details open><summary>Sol.</summary>

<p>
Rotate triangle \(ABC\) by \(\angle CAE\) to get the triangle \(AEC'\).
Since the three sides of \(\triangle AC'D\) are equal to the three sides
of \(\triangle ACD\), they are congruent, hence of equal area.
So the area of pentagon \(ABCDE\) is twice the area of \(\triangle AC'D\) which is \(\frac{1}{2}\) unit, so the pentagon's area is \(1\) unit, a constant.
</p>

<p style="text-align:center">
<img src="/assets/images/mt9_pentagon_sol.png"/>
</p>


</details>



</ol>



## Part B: Subjective questions


<p>
<b>B1.</b> Find all real \(x\) for which the equation holds:

\[ 4^{x}+9^{x}+36^{x}+\sqrt{\frac{1}{2}-2 x^{2}}=1 \]

</p>



<details open><summary>Sol.</summary>
To start with, note that we must have \(\frac{1}{2}-2 x^{2} \geq 0\), and therefore \(x^{2} \leq \frac{1}{4}\), i.e., \(-\frac{1}{2} \leq x \leq \frac{1}{2}\).<br>

<i>Case 1: </i> Now if \(x \geq 0\), then \(a^{x} \geq 1\) for any \(a>1\), hence \(4^{x}+9^{x}+36^{x}+\sqrt{\frac{1}{2}-2 x^{2}}>1\). So the given equation has no solution with \(0 \leq x\).<br>


<i>Case 2: </i> Next, note that \(4^{-1 / 2}+9^{-1 / 2}+36^{-1 / 2}=\frac{1}{2}+\frac{1}{3}+\frac{1}{6}=1\), and that \(\sqrt{\frac{1}{2}-2 x^{2}}=0\) when \(x=-\frac{1}{2}\). This
means that \(x=-\frac{1}{2}\) solves the given equation.<br>

<i>Case 3: </i>  Finally, suppose that \(-\frac{1}{2}< x < 0\). Then \(4^{x}+9^{x}+36^{x} > \frac{1}{2}+\frac{1}{3}+\frac{1}{6}\), i.e., \(4^{x}+9^{x}+36^{x}>1\), and therefore \(4^{x}+9^{x}+36^{x}+\sqrt{\frac{1}{2}-2 x^{2}}>1\). So the given equation has no solution with \(-\frac{1}{2}< x < 0\).
It follows that the only solution to the given equation is \(x=-\frac{1}{2}\).<br><br>

<i>Source: At right angles. Solution due to Praneetha Kalbhavi.</i>
</details>



---


<p>
<b>B2.</b> Consider a set of \(n\) islands \(X_1, \ldots , X_n\) arranged in
a circle. Assume \(n\geq 2\). There are two bridges between each pair of neighboring islands. For example,
the situation for \(n=5\) is shown below:<br>
</p>

<p style="text-align:center">
<img src="/assets/images/mt9_cycle.png"/>
</p>


<p>
(a) Suppose we start from island \(X_1\) and cross the \(2n\) bridges
exactly once. Show that we will return to \(X_1\) at the end of the journey. \(\;\;\) [2 marks]<br>


(b) Stating from the island \(X_1\), how many ways one can cross the \(2n\) bridges so
that each bridge is crossed exactly once? \(\;\;\) [8 marks]


</p>


<details open><summary>Sol.</summary>
(a) Every city has even number of bridges. The number of times we entry a
city must equal the number of times we leave it. The journey starts with
leaving \(X_1\), so it must end with entering it.<br>

(b) Let \( A \curvearrowright B \) denote a clockwise path from city \(A\) to \(B\). Similarly, \( \curvearrowleft \) denotes an
anti-clockwise path. We partition that paths into three types:<br>

(i) Paths that start with \(X_1 \curvearrowright X_i \curvearrowleft X_1 \) for \(1 < i \leq n\). There are \(2^n\) such paths for each \(i\).<br>
(ii) Paths that start with \(X_1 \curvearrowleft X_i \curvearrowright X_1 \) for \(1 < i \leq n\). There are \(2^n\) such paths for each \(i\).<br>
(iii) Paths of the type: \(X_1 \curvearrowleft X_1 \curvearrowright X_1 \), \(X_1 \curvearrowright X_1 \curvearrowleft X_1 \) , \(X_1 \curvearrowright X_1 \curvearrowright X_1\) and
\(X_1 \curvearrowleft X_1 \curvearrowleft X_1 \). There are \(2^n\) paths of each type.<br>


Adding up (i)-(iii), we get \( (n+1)2^{n+1} \) paths.


</details>


---

<p>
<b>B3.</b> Consider the sequence of natural numbers \(a_1,a_2,\ldots,a_n\) defined
as follows:<br>

<ul>
<li>\(a_1=2\).</li>
<li>For each positive number \(n\), \(a_{n+1} = a_n + \) product of the prime factors of \(a_n\).</li>
</ul>

The first eight numbers of the sequence are: \( 2, 4, 6, 12, 18, 24, 30 \text{ and } 60 \).
<br>

(a) Does the number 210 appear in the sequence? \(\;\;\) [1 mark]<br>
(b) Prove that the product of the first 2021 primes appears in the sequence. \(\;\;\) [9 marks]

</p>

<details open><summary>Sol.</summary>
(a) The sequence continues as:  \( 2, 4, 6, 12, 18, 24, 30, 60, 90, 120, 150, 180, 210 \).<br>
(b) We prove by induction. Let the primes be \(p_{1}< p_{2}< p_{3} < \cdots\). Now suppose that \(p_{1} p_{2} \cdots p_{k}\) is a term of the sequence for some \(k \geq 3\). Then the next terms of the sequence are

\[ 2 p_{1} p_{2} \cdots p_{k}, \quad 3 p_{1} p_{2} \cdots p_{k}, \quad 4 p_{1} p_{2} \cdots p_{k}, \quad 5 p_{1} p_{2} \cdots p_{k}, \quad \ldots \]

We keep adding \(p_{1} p_{2} \cdots p_{k}\) until we get a term of the sequence
that is divisible by a prime larger than \(p_{k}\).
Since the smallest positive integer not divisible by \(p_{1}, p_{2}, \ldots, p_{k}\) is \(p_{k+1}\), this term will be \(p_{1} p_{2} \cdots p_{k} p_{k+1}\).
So we have shown that if the product of the \(k\) smallest primes is a term of the sequence, then so is the product of the \(k+1\) smallest primes. <br>

<i>Problem source: Simon Marais 2019 competition</i>
</details>


---

<p>
<b>B4.</b> \(A B C\) is an acute triangle with \(B C=4\) and \(A C=5\).
Let \(D\) be the midpoint of \(BC\). \(BE\) is the altitude  to \(AC\).
\(CF\) is the angle bisector of \(\angle B C A\). If \(A D, B E\), and \(C F\) meet at a single point,
compute the length of \(BE\).
</p>


<p style="text-align:center">
<img src="/assets/images/mt9_triangle.png"/>
</p>


<details open><summary>Sol.</summary>
By the Angle Bisector Theorem, \(\frac{AF}{BF}=\frac{5}{4}\).
Then by Ceva's theorem:

\[ \frac{BD}{DC}\frac{CE}{AE}\frac{AF}{BF} = 1 \implies  \frac{C E}{A E}=\frac{4}{5}\]

so \(C E=\frac{20}{9}\).
By the Pythagorean theorem, \(BE^2 = BC^2-CE^2\):

\[BE=\frac{8 \sqrt{14}}{9}\]

<br><i>Source: SMT 2019.</i>
</details>


---

<p>
<b>B5.</b> Consider a real polynomial of the form \(p(x) = ax^4 + bx^2+c \).
We are given that \(0\leq p(x)\leq 1\) for all \(0 \leq x \leq 1\).
<ol>
<li>Show that the above condition implies that \(a\leq 4\). \(\;\;\) [7 marks]</li>
<li>Find a real polynomial with \(a=4\) that satisfies the given condition. \(\;\;\) [3 marks]</li>
</ol>

</p>


<details open><summary>Sol.</summary>


<p>
(a) Now \( p(0), p(1 / \sqrt{2}), p(1) \in [0,1]\),  so

\begin{align*}
0 \leq c  &\leq 1 \\
0 \leq a/ 4+b/2+c  &\leq 1 \\
0 \leq a+b+c  &\leq 1
\end{align*}


\begin{align*}
-2 \leq -2 c  &\leq 0 \\
0 \leq a+2b+4c &\leq 4 \\
-2 \leq -2 a-2b-2c &\leq 0
\end{align*}

Adding:\( -4 \leq -a \leq 4\).

<br>So the maximum value of \(a\) is at most 4 .

<br>

(b)This can be achieved by \(4\left(x^{2}-1 / 2\right)^{2}=4 x^{4}-4 x^{2}+1\).


</p>

</details>

---

<p> <b>B6.</b> Let \(\{a_k\}_{k \in \mathbb{N} }\) be a strictly increasing sequence of positive integers. Define the sequence \(\{s_n\}_{n \in \mathbb{N}}\) as

\[ s_n=\sum_{k=1}^{n}\frac{1}{[a_k,a_{k+1}]}\]

where \([a_k,a_{k+1}]\) is the least common multiple (i.e. LCM) of \(a_k\) and \(a_{k+1}\).<br>


<ol>
<li> Show that the sequence \(\{s_n\}_{n \in \mathbb{N}}\) is bounded above. \(\;\;\)[8 marks]</li>
<li> Prove that \(\{s_n\}_{n \in \mathbb{N}}\) converges.\(\;\;\)[2 marks]</li>
</ol>
</p>


<details open><summary>Sol.</summary>
<p>
(a) We have \(s_n = s_{n-1} + \dfrac{1}{[a_n,a_{n+1}]}\),
which means that \(s_n>0\), and \(\{s_n\}\) is a strictly increasing sequence.<br><br>

Denote the GCD of \(x\) and \(y\) by \((x,y)\). Now, from the well known result \([x,y]\cdot (x,y) = xy\) , and since \((x,y) | x-y \) , we have \((x,y)\leq |x-y|\) . <br><br>

Hence, we get:
\begin{align*}
s_n = \displaystyle\sum_{k=1}^{n} \dfrac{1}{[a_k,a_{k+1}]}&=\sum_{k=1}^{n} \frac{(a_k,a_{k+1})}{a_k \cdot a_{k+1}} \\
       & \leqslant \sum_{k=1}^{n} \frac{a_{k+1}-a_k}{a_k \cdot a_{k+1}} \\
       & = \sum_{k=1}^{n} \frac{1}{a_k}-\frac{1}{a_{k+1}}\\
       & =\frac{1}{a_1}-\frac{1}{a_{n+1}} \\
       & <\frac{1}{a_1}
\end{align*}


So, \(\{s_n\}\) is bounded above.<br><br>

<br>

(b) Now, since \(\{s_n\}\) is bounded above, and strictly increasing, thus by Monotone Convergence Theorem, \(\{s_n\}\) converges.<br><br>
</p>

</details>



