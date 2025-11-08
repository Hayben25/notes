## 8.1 Pressure of Gas

- Gas molecules in motion and exert a force on surface in contact with
- Vacuum doesn't pull, pressure pushes

## Atmospheric Pressure

- Force on any area due to atmosphere = weight of air column above it
- Pressure = force/area
- Atmospheric pressure = pressure from the column of air
- Can measure with a barometer
	- See Fig 8.2
- Standard Atmospheric Pressure (1 atm)
	-  The pressure that supports a column of Hg exactly 760 mm high at 0$\degree$C at sea level
	- 1 torr = 1 mm Hg $\implies$ 1 atm = 760 mm Hg =760 torr

## 8.2 The Gas Laws

- P-V Relationships: Boyle's Law
	- Used a manometer to measure pressure
	- Found that graph of V vs. $\frac{1}{P}$ is a straight line
	- PV=constant
- T-V Relationship: Charle's Law
	- See Fig. 8.9
	- Always extrapolate to -273.15$\degree$C to be a zero for any P, n
	- V $\propto$ T or $\frac{V}{T}$=const; V=const\*T
	- Identify absolute zero (T for V=0; unattainable)
- Volume - Amount Relationship: Avogadro's Law
	- At T, P const: V $\propto$ n (n$\uparrow\ \rightarrow$   V$\uparrow$)

## 8.3 Ideal Gas Equation

| Boyle's Law    | $V\propto\frac{1}{P}$ | n, T const |
| -------------- | --------------------- | ---------- |
| Charle's Law   | $V\propto T$          | n, P const |
| Avogadro's Law | $V\propto n$          | P, T const |
- $\implies V\propto nT/P$
- Proportionality constant is the gas constant R
- $V=R\frac{nT}{P}$ or $PV=nRT$  (Must have temperature in K)
- 2 assumption for ideal gas
	- Molecules to not attract or repel each other
	- Molecules don't have volume
- Real gases behave like ideal gases under reasonable conditions $\implies$ can use equation
- From experiment At 0$\degree$C, P = 1 atm, find 1 mol $\rightarrow$ V=22.414L
- Therefore, $$R=\frac{PV}{nT}=\frac{(1 atm)(22.414L)}{(1mol)(273.15K)}=0.082057\frac{L*atm}{K*mol}$$

## Standard Conditions

- Standard temperature and pressure (STP)
- $T=0\degree C$, $P=1\ atm$
- What is the standard molar volume? 22.414L
- What is P (in atm) exerted by 1.82 moles of $SF_6$ gas in a 5.43 L steel vessel at 69.5$\degree$C
	- $P=\frac{nRT}{V}$
		- $T=69.5+273=342.5\ K$
		- $n=1.82\ moles$
		- $R=0.0821 \frac{L*atm}{mol*K}$
		- $P=\frac{(1.82\ mol)(0.0821 \frac{L*atm}{mol*K})(342.5\ K)}{5.43\ L}=9.42\ atm$

## Density

- $\frac{n}{V}=\frac{P}{RT}$
- $n=\frac{m(mass)}{M(molar\ mass)}$
- $d=\frac{m}{V}=\frac{MP}{RT}$
- Ex. What is the density of $NH_3$ (g/L) at 752 mmHg & 55$\degree$C
	- $P(atm)=\frac{752\ mmHg}{760\ mmHg/atm}=0.989\ atm$
	- $T=55+273=328\ K$
	- $d=\frac{(17.03\ g/mol)(0.989\ atm)}{(0.0821 \frac{L*atm}{mol*K})(328\ K)}$

## 8.4 Dalton's Law of Partial Pressures

- Each gas behaves as if only gas present
- $P_T=P_1+P_2+P_3+\dots$
	- $P_i$ is the pressure each gas would have if present alone
- Partial Pressure - P of each gas in the mixture ($P_i$)
- A & B mixture
	- $P_T=P_A+P_B=\frac{n_ART}{V}+\frac{n_BRT}{V}=(n_A+n_B)\frac{RT}{V}=\frac{nRT}{V}$
		- $n=n_A+n_B$
	- $\frac{P_A}{P_T}=\frac{n_ART/V}{(n_A+n_B)RT/V}=\frac{n_A}{n_A+n_B}=X_A$
		- $X_A$ mole fraction is the fraction of the moles of a specific gas to the total moles (dimensionless $0\le X_A\le1$)
		- $P_A=X_AP_T$
		- $P_B=X_BP_T$
		- $X_A+X_B=1$
		- $P_i=X_iP_T$ is an ideal mixture
- Ex. A gas mixture contains 4.46 mol Ne, 0.74 mol Ar, 2.15 mol Xe
	- What are the partial pressures if $P_{tot}=2\ atm$
	- $X_{Ne}=\frac{n_{Ne}}{n_{tot}}=\frac{4.46}{4.46+0.74+2.15}=0.607$
		- $P_{Ne}=X_{Ne}*P_{tot}=(0.607)*(2\ atm)=1.21\ atm$
	- $X_{Ar}=0.1\rightarrow P_{Ar}=X_{Ar}*P_{tot}=(0.1)*(2\ atm)=0.2\ atm$
	- $X_{Xe}=0.293\rightarrow P_{Xe}=X_{Xe}*P_{tot}=(0.293)*(2\ atm)=0.586\ atm$
- How many liters of $CO_2$ gas at STP can be obtained by completely burning one mole of $C_3H_8$?
	- $C_3H_8(g)+5O_2(g)\rightarrow 4H_2O(\ell)+3CO_2(g)$
	- $(3\ mol\ CO_2)(22.414\ L)=67.242\ L$

## Collecting Gas Over Water

- Fig 8.13
- When $H_2O$ in tube level with $H_2O$ in beaker
	- $P_{tot}=P_{atm}$
	- $P_{tot}=P_{gas}+P_{H_2O}$
- Gas Laws predict behavior but why do they hold?
	- Must look at molecular level

## Kinetic Molecular Theory

- L. Boltzmann and J. C. Maxwell
- Determined (mathematically) that gas properties could be explained from motions of individual molecules
- Kinetic Molecular Theory Postulates
	1. Molecular volume is negligible, particles considered as points
	2. Molecules in constant **random** motion, they can gain or lose energy when they collide but total $E_K$ for all molecules stay the same (collisions are elastic)
	3. No attractive or repulsive forces in between collisions
	4. $\bar{E_K}\propto T$ (In $K$)
- $u : \bar{u^2}=frac{u_1^2+u_2^2+\dots+u_N^2}{N}=$mean square speed
- $\bar{E_K}=\frac{1}{2}m\bar{u^2}\implies \frac{1}{2}m\bar{u^2}\propto T$ (as stated in postulate 4)
	- or $\frac{1}{2}m\bar{u^2}=CT$

## Distribution of Molecular Speeds

- Depends on T
- Derived mathematically by Maxwell
- Fig 8.21
- From Kinetic Molecular Theory:
	- $PV=\frac{1}{3}nM\bar{u^2}=nRT$
	- $\rightarrow \bar{u^2}=\frac{3RT}{M}$, or $\sqrt{\bar{u^2}}=u_{rms}=\sqrt{\frac{3RT}{M}}$
		- $=1.92*10^3\ m/s$ for $H_2\ @\ 25\degree C$ ~2x bullet
	- Also get meaning of $T$: $\bar{E_K}=\frac{3}{2}(\frac{R}{N_A})T$

## 8.7 Graham's Laws of Diffusion and Effusion

- Diffusion - movement of one gas through another
	- Demonstrates random motion
		- Mean free path: average distance traveled between successive collisions
	- Because random motion $\rightarrow$ diffusion takes a long time
	- Since $u_{rms}$ light gas > $u_{rms}$ heavy gas; at same T lighter gasses diffuse faster
- Graham's Law of Diffusion
	- When T, P same
		- $\frac{rate_1}{rate_2}=\sqrt{\frac{M_1}{M_2}}$
	- Explained  by kintetic theory
		- $rate\propto u_{rms}=\sqrt{\frac{3RT}{M}}$
		- At same T
			- $\frac{rate_1}{rate_2}=\frac{(u_{rms})_1}{(u_{rms})_2}=\sqrt\frac{M_1}{M_2}=\frac{\ell/t_1}{\ell/t_2}=\frac{t_2}{t_1}$
- Effusion - process by which gas escapes a container through a tiny hole
	- Although process is different it has the same equation given by *Graham's Law of Diffusion*
	- $\frac{rate_1}{rate_2}=\sqrt\frac{M_1}{M_2}$
- Ex Compare effusion rates of He vs. $N_2$
	- $\frac{rate_{He}}{rate_{N_2}}=\sqrt\frac{28.02}{4.003}=2.65$ 