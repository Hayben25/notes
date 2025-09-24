- In chapter 12: $\overrightarrow{f(t)}=x(t)\hat{i}+y(t)\hat{j}+z(t)\hat{k}$
	- Scalar input and vector output
- In chapter 13: $f(x,y)$ or $f(x,y,z)$
	- Vector input (or point) input and scalar output

## Domain and Range

- Domain - the set of all input values which make sense
	- No more union for domain :(
	- Set builder notation :{{
- Range - the set of all output values which make sense or are possible
- Domain Rules:
	- $\frac{1}{u}\implies u\ne 0$
	- $^{2k}\sqrt{u}\implies u \ge 0$
	- $log_b(u)\implies u \gt 0$

## Example

1. $f(x,y)=\sqrt{xy}$
	- $\sqrt{xy}\implies xy \ge 0$
	- $dom(f)=${$(x,y):xy\ge 0$}
	- $range(f)=${$[0,infinity]$}
	- For range, $f(x,y)=1: f(x,1)=\sqrt{1\cdot x}=\sqrt{x};$ gives $[0,infinity]$
		- QI and QIII as well as x and y axis
	- Formal way: Let $M\epsilon [0,infinity)$
		- $f(1,M^2)=\sqrt{1\cdot M^2}=M$
2. $f(x,y)=\frac{1}{\sqrt{x-y}}$ 
	- $\sqrt{x-y}\implies x-y \ge 0 \implies x \ge y$
	- $\frac{1}{\sqrt{x-y}}\implies \sqrt{x-y} \ne 0 \implies x-y \ne 0 \implies x \ne y$
	- Thus $D=\{(x,y): x\gt y\}$
		- $R=(0,infinity)$ 
	- Fix $y=0: f(x,0)=\frac{1}{\sqrt{x-0}}=\frac{1}{\sqrt{x}}$ gives $(0,infinity)$
3. $f(x,y)=\sqrt{9-x^2}-\sqrt{4-y^2}$
	- $\sqrt{9-x^2}\implies 9-x^2\ge 0 \implies 9 \ge x^2 \implies 3 \ge |x| \implies -3\le x \le 3$
	- $\sqrt{4-y^2}\implies 4-y^2\ge 0 \implies 4 \ge y^2 \implies 2 \ge |y| \implies -2\le y \le 2$
	- $D=\{(x,y)|-3\le x \le 3, -2\le y \le 2\}$
		- $R=[-2,3]$
	- Prove by plugging in for $f(3, 0)$ and $f(0,2)$
4. $f(x,y,z)=\frac{\sqrt{z}}{x^2-y^2}$
	- $\sqrt{z}\implies z \ge 0$
	- $\frac{1}{x^2-y^2}\implies x^2-y^2 \ne 0 \implies |x| \ne |y|$
	- $D=\{(x,y,z)| |x|\ne |y|, z\ge 0\}$
	- $R=(-infinity,infinity)$
	- Set $y=0,x=1,z=a^2$, $f(1,0,a^2)=\frac{\sqrt{a^2}}{1^2-0^2}=|a|$ $\epsilon[0.infinity)$
	- $x=0,y=1,z=a^2$, $f(0,1,a^2)=\frac{\sqrt{a^2}}{0^2-1^2}=-|a|$ $\epsilon[0,infinity)$
5. $f(x,y)=\frac{5}{ln(xy-1)}$
	- $ln(xy-1)\implies xy-1 \gt 0 \implies xy>1$
	- $\frac{1}{ln(xy-1)}\implies ln(xy-1)\ne 0 \implies xy-1 \ne 1 \implies xy \ne 2$
	- $Dom(f)=\{(x,y)|xy\gt 1, xy\ne 2\}$
	- $Range(f)=(-infinity,0)U(0,infinity)$
	- Choose $a\ne 0$ set $y=1, x=e^{5/a}+1$
		- $f(e^{5/a}+1,1)=\frac{5}{ln(e^{5/a}+1-1)}=a$ 