Hayden Cianessi - hcianess@cougarnet.uh.edu

1. The problem we have is that we want to find the dimensions of a pool with a rectangular pool with a semicircle on top that will give the largest area, limited by the fact that the outer perimeter must be at most 150 *ft* in length.
2. We are given that the pool is comprised of a rectangle of height $h$ and width of $2r$. The semicircle on top has a radius of $r$.
3. We can use the theory that the circumference of a circle is $P=2\pi r$ and that the perimeter of a rectangle is $P=2h+4r$ since $2h+4r$ is the sum of the side lengths of the rectangle. We can edit the theories, as we should only solve for half of the perimeter of the circle, as it is a semicircle, making the equation for the perimeter $P=\pi r$. We also need to change the equation for the perimeter of the rectangle, as the outer perimeter does not include one of the $2r$ side lengths, making the equation for this problem combined with that of the semicircle $P_{outer}=\pi r+2h+2r$. The area can be found with the equation for the area of the rectangle, $A=2rh$ can find the maximum area by either taking the derivative or making a table. 
4. We are assuming that all side lengths don't vary with their given values, all angles in the rectangle are 90 degrees  and that the semicircle is half of a perfect circle.
5. 
	- $P_{outer}=150=\pi r+2h+2r \implies h = 75-r-\frac{\pi r}{2}$
	- Since $h = 75-r-\frac{\pi r}{2}$, then 
		- $A = 2rh = 2r(75-r-\frac{\pi r}{2})=150r-2r^2-\pi r^2$ 
	- To find the maximum of $A$, solve for when $\frac{dA}{dr}=0$
		- $\frac{dA}{dr}=-2\pi r +150 -4r = 0 \implies r = \frac{150}{2\pi+4}ft\approx 14.59ft$
	- Plugging the value found for r into the equation for $h$ we find that
		- $h=75-\frac{150}{\pi +4}-\frac{150\pi}{2(\pi+4)}=37.5$
6. To verify we can make a table of $A(r)$
	- $A(5)=621.46$
	- $A(10)=985.84$
	- $A(20)=943.36$
	- $A(25)=536.5$ 
	- Since $A$ increases as $r$ approaches 14.59 and decreases as it increases past $r=14.59$, it can be  assumed that there is a maximum between $r=10$ and $r=20$ meaning that our answer from 5 of $r\approx14.49$ holds true.
	[[engi1100]]
