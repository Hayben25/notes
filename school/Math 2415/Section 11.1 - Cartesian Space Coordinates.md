- 2d plane is broken into 4 quadrants $\mathrm{r}^2$
- 3d plane is broken into $x$, $y$, $z$ coordinates
	- Organized $(x,y,z)$
	- Called octants instead of quadrants
# Planes

- $x-y$ plane: $(x,y,0)$
	- $z = 0$
- $x-z$ plane: $(x,0,z)$
	- $y=0$
- $y - z$ plane: $(0,y,z)$
	- $x = 0$
- Any plane parallel to a plane is $?=C$ where $?$ is whichever variable is not on the plane (e.x the a plane parallel to the $x-y$ plane is $z=C$ where $z \ne 0$)
# Formulas

- Distance formula
	-  $\sqrt{\mathrm{(x_1-x_2)}^2 + \mathrm{(y_1-y_2)}^2 + \mathrm{(z_1-z_2)}^2}$
- Midpoint formula
	- $\frac{x_1+x_2}{2}+\frac{y_1+y_2}{2}+\frac{z_1+z_2}{2}$
- Sphere formula
	- $\mathrm{(x-a)}^2 + \mathrm{(y-b)}^2 + \mathrm{(z-c)}^2 = \mathrm{r}^2$
	- Center @ $(a,b,c)$
# Examples

- Give the equation of sphere that has $A$ and $B$ endpoints of a diameter
	- $A=(2,0,-1) B=(2,1,3)$
	- Center is the midpoint of line $\overline{AB}$
	- $\frac{x_1+x_2}{2}+\frac{y_1+y_2}{2}+\frac{z_1+z_2}{2}$ = $\frac{2+2}{2}\hat{i}+\frac{0+1}{2}\hat{j}+\frac{-1+3}{2}\hat{k}= 2\hat{i} + \frac{1}{2}\hat{j} + 1\hat{k}$ 
	- Radius is $\frac{1}{2}$ length of $\overline{AB}$
		- $length = \sqrt{\mathrm{(x_1-x_2)}^2 + \mathrm{(y_1-y_2)}^2 + \mathrm{(z_1-z_2)}^2}$ $\implies\frac{\sqrt{\mathrm{(x_1-x_2)}^2 + \mathrm{(y_1-y_2)}^2 + \mathrm{(z_1-z_2)}^2}}{2} = radius$
		- $\frac{\sqrt{\mathrm{(2-2)}^2 + \mathrm{(0-1)}^2 + \mathrm{(3+1)}^2}}{2} = \frac{\sqrt{17}}{2} = r$
	- Combine both
		- $\mathrm{(x-a)}^2 + \mathrm{(y-b)}^2 + \mathrm{(z-c)}^2 = \mathrm{r}^2\implies$$\mathrm{(x-2)}^2 + \mathrm{(y-\frac{1}{2})}^2 + \mathrm{(z-1)}^2 = \mathrm{(\frac{\sqrt{17}}{2})}^2 = \frac{17}{4}$
- Find the center and radius of $\mathrm{x}^2+\mathrm{y}^2+\mathrm{z}^2+4x-8y-2z+5=0$
	- $\mathrm{x}^2+4x+4+\mathrm{y}^2-8y+16+\mathrm{z}^2-2z+1=16$
	- $\mathrm{(x+2)}^2+\mathrm{(y-4)}^2+\mathrm{(z-1)}^2=16$
	- Center is $(-2,4,1)$ and the radius is $4$