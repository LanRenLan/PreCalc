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


### 性质方程：看A和B哪一个是负的，因为必然有且仅有一个是负的，例如 -25x^2+49y^2，那么性质=(y-x)，反之则是(x-y)，只有这两种可能性。

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

$$\\lim_{x \\to \\infty} \frac{sin(x)}x=1\qquad$$
**这个是要背下来的常识，不过就这一个，因为cosine没有**

Limits Analytically--trig延后
Continuity - Find K看不懂
Intermediate Value Theorem看不懂
Types of Discontinoities (Graphically)在教科书PDF P.95
limit 练习题P。103
Continuity: 

$$f(x) = \\begin{cases} x^2 & \\text{if } x \\geq 0 \\\\-x^2 & \\text{if } x < 0 \\end{cases}$$

**这种情况是continue，而如果x在右边则可能是discontinue，需要计算两个function，如果值不一样才是discontinue**

**找tangent line的function**

example：

$$f(x)=\frac{x}{x+4},\quad(-5,5)$$

先找出一阶导数 f'(x) = \frac{4}{(x+4)^2} ，再把x坐标点的-5带进x得到4，再用linear公式y - y1 = m(x - x1)代y - 5 = 4(x - (-5))，y=4x+25
