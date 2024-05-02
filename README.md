The Cauchy-Schwarz Inequality

$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$

# Math 4 Intro To Pre Calc

## Find Key Features of a Hyperbola from General Form：
**我用a对应x，b对应y**

### $$± Ax^2 ± By^2 ± Cx ± Dy ± [ignorable-number] = 0$$
**中，要计算的有X, Y, a, b, c, r (半径)**

$$a=|\sqrt B|$$

$$b=|\sqrt A|$$

$$X=-(\frac{C/A}2)\qquad$$

$$Y=-(\frac{D/B}2)\qquad$$

$$a^2+b^2=c^2$$

$$r=\sqrt {A\times C}$$

***一般情况下不用算r。**


***计算X和Y的时候要带上正负。**
$$Center = (X，Y)$$
$$FocalLength = c$$
$$Asymptotes: y=\frac{b}{a}(x-X)+Y， and， y=\frac{-b}{a}(x-X)+Y$$
**例如: y=(±5/4)(x-3)+4，小写x是Variables，毕竟Asymptotes是一个equation**


#### 性质方程：看A和B哪一个是负的，因为必然有且仅有一个是负的，例如 -25x^2+49y^2，那么性质=(y-x)，反之则是(x-y)，只有这两种可能性。

如果性质是(x-y)：
$$Vertices: (X+a， Y)， and, (X-a， Y)$$
$$Co-Vertices: (X， Y-b)， and， (X， Y-b)$$
$$Foci: (X+c，Y) ，and， (X-c， Y)$$

如果性质是(y-x): 
$$vertices: (X， Y+b)，and， (X， Y-b)$$
$$Co-vertices: (X+a， Y)，and， (X-a， Y)$$
$$Foci: (X， Y+c)， and， (X，Y-c)$$

注意Vertices：X永远都是加减a，Y永远都是加减b，而不同的性质，只是把vertices 和co-vertices 的名字反过来了而已，方程没有变化
--------------------------------------------------------------------
## lim
$$\\lim_{x \\to \\infty} \frac{x^2}x\qquad$$

**lim to ∞的时候，忽略所有低次方的x，分子和分母都只用最高的一个。如果次方数量上大下小，代表DNE；如果次方数量下大上小，代表0；如果同等次方，那就是双方的系数相除。（Limits to Infinity (Type 1))**

证明的方法：例题：
$$\lim_{x\to\infty}\frac{2x^6+x^3-36}{8x^2+2x^5}$$

解题思路：
$$\lim_{x\to\infty}\frac{2x^{6}+x^{3}-36}{8x^{2}+2x^{5}}\times\frac{\frac{1}{x^{6}}}{\frac{1}{x^{6}}}$$

-------------------

$$\\lim_{x \\to \\infty} \frac{sin(x)}x=1\qquad$$
**这个是要背下来的常识，不过就这一个，因为cosine没有**

Limits Analytically--trig延后
Continuity - Find K看不懂
Intermediate Value Theorem看不懂
Types of Discontinuities (Graphically)在教科书PDF P.95
limit 练习题P。103
Continuity: 

$$f(x) = \\begin{cases} x^2 & \\text{if } x \\geq 0 \\\\-x^2 & \\text{if } x < 0 \\end{cases}$$

**这种情况是continue，而如果x在右边则可能是discontinue，需要计算两个function，如果值不一样才是discontinue**

**找tangent line的function**

example：

$$f(x)=\frac{x}{x+4},\quad(-5,5)$$

先找出一阶导数 $f'(x) = \frac{4}{(x+4)^2}$ ，再把x坐标点的-5带进x得到4，再用linear公式 $y-y_1=m(x-x_1)\implies y-5=4(x-(-5))\implies y=4x+25$ 

Calc AB:

对于
$$\lim_{x\to0}\frac{\sin(x)}{2x}$$
这种问题，可以使用洛必达（L'Hôpital）规则，这个规则适用于代入精确的x值之后，如 $\frac{\infty}{\infty}$ 或者 $\frac{0}{0}$ 的不定型极限，该极限会等于 $\lim_{x\to a}\frac{f(x)}{g(x)}=\lim_{x\to a}\frac{f^{\prime}(x)}{g^{\prime}(x)}$ ，所以 
$$\lim_{x\to0}\frac{\cos(x)}2=\frac{\cos(0)}2=\frac12$$

**Unit 5 Calc**
F'(x)=0 is Critical point
F''(x) changes sign (+-),is Point of Infaction
F'(x)=0, and F''(x) is +, there's a relative minimum; if F''(x) is -,there's a relative max
F''(x)>0 is concave up,F''(x)<0 is concave down. Always true.
Horizontal tangent line is F'(x)=0, Verticle tangent is F'(x)=DNE.

**Unit 6 Calc**
U-substitution, try your best to replace something that could be canceled out with the u'. It could be u=sin(2x), or u=2x depending on what you have. 
/int 1/x = ln x only works for one single x not x^2. 

**Unit 8 Volumes**
semi circle vol has an extra 1/2 inside
two different triangle volumes. 
