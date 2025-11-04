# Circuits

## Problem 1
- The electrons are going from left to right because electrons move from - to + or towards higher potential. That direction is left to right because v$_b$ is negative.

| Device | Current (mA) | Voltage (V) | Sign Convention |
| ------ | ------------ | ----------- | --------------- |
| A      | 1.5          | 15          | Passive         |
| B      | 1.5          | 5           | Active          |
| C      | 0.5          | 10          | Passive         |
| D      | 2            | 20          | Active          |
| E      | 2            | 10          | Passive         |

| Device | Power (W) | Absorbs/Delivers |
| ------ | --------- | ---------------- |
| A      | 22.5      | Absorbed         |
| B      | 7.5       | Delivered        |
| C      | 5         | Absorbed         |
| D      | 40        | Delivered        |
| E      | 20        | Absorbed         |
- Power is conserved because Power absorbed = Power Delivered because $22.5\ W+5\ W+20\ W=7.5\ W+40\ W=47.5\ W$

## Problem 2

```tikz
\usepackage{circuitikz}
\begin{document}
\begin{circuitikz}[american]

\draw (0,0)
to[vsource=$v_A$, i>_=$i_A$] (0,4)
to[R=$R_1$, v=$v_1$] (3,4)
to[vsource=$v_B$] (3,3) to[short, i>_=$i_B$](3,2) to[,R=$R_3$, v=$v_3$](3,0) -- (0,0);
\draw (3,4)
to[R=$R_2$, v=$v_2$] (6,4) -- (6,0)
to[short, -*, i>_=$i_C$](3,0);

\end{circuitikz}
\end{document}
```

| Resistor | Current | Voltage | Ohm's Law     |
| -------- | ------- | ------- | ------------- |
| $R_1$    | $i_A$   | $v_1$   | $v_1=i_A*R_1$ |
| $R_2$    | $i_C$   | $v_2$   | $v_2=i_C*R_2$ |
| $R_3$    | $i_B$   | $v_3$   | $v_3=i_B*R_3$ |
- $\ell 1:v_1+v_3+v_A+v_B=0$, $\ell 2:v_3+v_B-v_2=0$
	- $\ell 1:i_A*R_1+i_B*R_3+v_A+v_B=0$
	- $\ell 2:i_B*R_3+v_B-i_C*R_2=0$
- $i_A=i_B+i_C$
- $i_A*R_1+i_B*R_3+v_A+v_B=i_B*R_3+v_B-i_C*R_2$
	- $i_A*R_1+v_A=-i_C*R_2$ 
	- Using the KCL equation from part c
		- $i_B*R_1+i_C*R_1+v_A=-i_C*R_2$
		- $i_B=\frac{-i_C*R_2-i_C*R_1-v_A}{R_1}$
	- Plugging the new $i_B$ into $\ell 2$
		- $(\frac{-i_C*R_2-i_C*R_1-v_A}{R_1})*R_3+v_B-i_C*R_2=0$
		- $\frac{-i_C*R_2*R_3}{R_1}-i_C*R_3-\frac{v_A*R_3}{R_1}-i_C*R_2=-v_B$
		- $i_C(-\frac{R_2*R_3}{R_1}-R_3-R_2)=\frac{v_A*R_3}{R_1}-v_B$
		- $i_C=\frac{v_B-\frac{v_A*R_3}{R_1}}{\frac{R_2*R_3}{R_1}+R_3+R_2}$
		- $i_C=\frac{2.5\ V-\frac{4\ V*(8.2*10^3\ \Omega)}{6.2*10^3\ \Omega}}{\frac{(4.7*10^3\ \Omega)(8.2*10^3\ \Omega)}{6.2*10^3\ \Omega}+8.2*10^3\ \Omega+4.7*10^3\ \Omega}=-1.4597*10^{-4}\ A$
	- Plugging the number we found for $i_C$ into the equation for $i_B$
		- $i_B=\frac{-(-1.4597*10^{-4}\ A)*(4.2*10^3\ \Omega)-(-1.4597*10^{-4}\ A)*(6.2*10^3\ \Omega)-4\ V}{6.2*10^3\ \Omega}=-3.885\ A$