ENGI 1100
Hayden Cianessi

## Problem 1
1. $\Sigma x_i=50+55+40+50+52+47+60+50+55+47+52+50+46+51+49=754\%$
2. Mean $=\frac{\Sigma x_i}{n}$;$n=15\implies$ Mean $=\frac{754\ \%}{15}\approx 50.27\%$ 
3. $\Sigma x_i=50^2+55^2+40^2+50^2+52^2+47^2+60^2+50^2+55^2+47^2+52^2+50^2+46^2+51^2+49^2=38194\%^2$
4. Standard Deviation $=\sqrt{\frac{n(\Sigma x_i^2)-(\Sigma x_i)^2}{n(n-1)}}=\sqrt{\frac{15(38194)-(754)^2}{15(14)}}\approx 4.57$
5. 

| Frequency | Range |
| --------- | ----- |
| 1         | 44    |
| 1         | 44-46 |
| 3         | 47-49 |
| 7         | 50-52 |
| 2         | 53-55 |
| 1         | 55    |

5. 
![[Pasted image 20251021183444.png]]
## Problem 2
1. $\Sigma X_i=20+25+30+35+40+45+50+55+60+65+70=495$
2. $\Sigma Y_i=1092+981+1382+1434+1927+2594+2195+3191+2531+3247+3906=24530$
3. $\Sigma X_iX_i=20^2+25^2+30^2+35^2+40^2+45^2+50^2+55^2+60^2+65^2+70^2=25025$
4. $\Sigma Y_iY_i=1092^2+981^2+1382^2+1434^2+1927^2+2594^2+2195^2+3191^2+2531^2+3247^2+3906^2=63769582$
5. $\Sigma X_iY_i$
$=1092*20+981*25+1382*30+1434*35+1927*40+2594*45+2195*50+3191*55+2531*60$
$+3247*65+3906*70$
$=1253415$
6. $m=[\frac{n(\Sigma x_iy_i)-(\Sigma x_i)(\Sigma y_i)}{n(\Sigma x_i^2)-(\Sigma x_i)^2}]$ and $b=[\frac{\Sigma y_i-m(\Sigma x_i)}{n}]$
	- $m=[\frac{12(1253415)-(495)(24530)}{12(25025)-(495)^2}]\approx 52.44$
	- $b=[\frac{24530-52.44(495)}{12}]=-118.983$
7. $r=\frac{n(\Sigma x_iy_i)-(\Sigma x_i)(\Sigma y_i)}{\sqrt{n(\Sigma x_i^2)-(\Sigma x_i)^2}\sqrt{n(\Sigma y_i^2)-(\Sigma y_i)^2}}=\frac{12*1253415-495*24530}{\sqrt{12*25025-495^2}\sqrt{12*63769582-24530^2}}=0.964$
8. 
![[Pasted image 20251021221612.png]]
9. Trial 1 because taking finding $\frac{\Sigma Y_i}{\Sigma X_i}$ for both trials gives $\bar{v_2}\approx 49.55$ and $\bar{v_1}\approx 61.66$ meaning that $\bar{v_1}> \bar{v_2}$.