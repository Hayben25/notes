## Thermochemistry

- Study of heat (thermal energy) changes in chemical reactions
- Subbranch of thermodynamics
- Only first law (Hooray)
- Universe = System + surroundings
	- System - specific part of universe of interest
	- Surroundings - the rest of the universe
- E.x. Combustion of $H_2(g)$
	- $2H_2(g)+O_2(g)\rightarrow 2H_2O(l)+energy$
	- Reaction is the system
	- Everything else is the surroundings
	- Energy released - exothermic
- E.x. At high T's:
	- $energy + 2HgO(s)\rightarrow 2Hg(l) + O_2(g)$
	- Energy gained from surroundings
	- Endothermic reaction

## Forms of Energy Transfer

- Heat - Thermal energy ($q$) \[$T_1>T_2\implies$ heat flows $T_1\rightarrow T_2$]
- Work - energy transferred when an object is moved by a force
	- E.x. Moving a piston when a gas expands
		- Pressure volume work
		- $W=-P\Delta V=-P(V_f-V_i)$
## 1$^{st}$ Law of Thermodynamics

- $\Delta U=q+w$
	- $\Delta U$ is internal energy, also called $\Delta E$
	- $\implies$ principle of conservation of energy
		- Energy is not created or destroyed, it is transferred to and from the surroundings
	- $q>0$ (+)  $\rightarrow$ head absorbed
	- $q<0$ (-)  $\rightarrow$ head released
	- $w>0$ (+)  $\rightarrow$ work done on the system
	- $w<0$ (-)  $\rightarrow$ work done by the system ($w=-P(V_f-V_i)<0$)
- Energy Units
	- $1\ J(Joule)=1\ kg*m^2/s^2$
	- $101.3\ J = 1\ L*atm$
	- $1\ cal=4.184\ J$ modern definition
		- Chemical reactions use kJ, kcal
	- Nutritional Calorie $(C)=1\ kcal$

## State Functions

- Changes depend **only** on state of the system, **not** on how it got there
- State functions: U, P, T, V
- $q$ and $w$ **in general** are not state functions = forms of energy transfer $\implies$ depend on the path
- Frequently carry out experiments in an open vessel (constant P)
	- Therefore new function
		- Enthalpy: $\Delta H=q_P$

## 7.1 Enthalpy

- $H\in U+PV$ - state function
- $\Delta H =\Delta U+P\Delta V=q+w+P\Delta V=q-P\Delta V+P\Delta V=q$
- $\Delta H$ refers to the transfer of heat
- For many reactions $\Delta H\approx\Delta U$ (but not always)

## Some types of $\Delta H$

- Heat of Combustion ($\Delta H_{comb}$)- 1 mol of substance combines with $O_2$
- Heat of Formation ($\Delta H_f$) - 1 mol of compound produced from its elements
	- $K(s)+ \frac{1}{2}Br_2(l)\rightarrow KBr(s)\ \Delta H=\Delta H_f$
- Heat of Fusion ($\Delta H_{fus}$) - 1 mol of substance melted
	- $H_2O(s)\rightarrow H_2O(l)$
- Heat of Vaporization ($\Delta H_{vap}$) - 1 mol of substance vaporized
	- $H_2O(l)\rightarrow H_2O(g)$

- How to measure heat changes?

## 7.2 Calorimetry

- Heat Capacity ($C$) - Amount of heat required for sample $\Delta T=1K$ $C=\frac{q}{\Delta T}$ (extensive)
- Specific Heat ($s$) - Amount of heat needed to change T of 1 g by 1K $s=\frac{C}{m}$ (intensive)
- Looking at both equations we find $q=ms\Delta T$ and $q=C\Delta T$
- $H_2O$: $s=4.184\ J/(g*K)$ 
	- Heat capacity of 60 g of $H_2O$
		- $C=60\ g*4.184=251\ J/K$
	- Molar heat capacity: $J/(mol*K)$
		- $H_2O=75.40\ J/(mol*K)$
- Ex. $486\ g\ H_2O$ is heated from $8.50\degree C\rightarrow 74.6\degree C$. What is the heat absorbed?
	- $q=ms\Delta T=(486\ g)*(4.184\ J/(g*K))*(66.1K)=134*10^3\ J=134\ kJ$
	- How measure?
- Constant V Calorimetry
	- Use bomb calorimeter (see Fig 7.6)
	- $q_{sample}=-q_{calorimeter}=-(q_{bomb}+q_{water})$ Therefore,
		- $q_{sample}=-(calorimeter\ heat\ capacity)*(\Delta T)$
- What is the heat capacity of the calorimeter used if $0.8650\ g$ of graphite releases $393.5\ kJ/mol$ & $\Delta T=2.613K$
	- $q=C\Delta T$ $C=\frac{q}{\Delta T}$ $q_{calorimeter}=-q_{sample}$
	- Calorimeter heat capacity$=\frac{q_{calorimeter}}{\Delta T}\frac{-q_{sample}}{\Delta T}=\frac{-(-395.5\ kJ/mol)(\frac{0.8650}{12.01}mol\ C)}{2.613\ K}=10.85\ kJ/K$
	- Not measuring $\Delta H$:
		- $\Delta U =q+w=q-P\Delta V=q_v$
		- but typically $\Delta H\approx\Delta U\implies$ small correction
	- Constant P calorimery - simpler, see Fig. 7.5
		- For other than combustion reactions
			- $P_{const}\rightarrow \Delta H$
- Ex. Drop a hot alloy into $H_2O$
	- $q_{alloy}=-q_{H_2O}$
		- $T_{final}$ is the same
	- $q=m\ s\ \Delta T=m\ s(T_{final}-T_{initial})$
- $\Delta H$ Calculations
	- Frequently cannot measure $\Delta H_{rxn}$ directly
	- Use the fact that H is a State Function
	- $A+B\overrightarrow{_{\Delta H_{rxn}}}C+D$
	- Hess's Law - when reactants $\rightarrow$ products, $\Delta H$ is the same whether reaction takes one step or many steps
	- Ex. $(graphite)+2H_2(g)\rightarrow CH_4(g)$ doesn't happen as written
		- How get $\Delta H$?
		- Use reactions for which know $\Delta H$
			1. $C(graphite)+O_2(g)\rightarrow CO_2(g)$
				- $\Delta H^0$$_{rxn}=-393.5\ kJ$
			2.  $2H_2(g)+O_2(g)\rightarrow 2H_2O(\ell)$
				- $\Delta H^0$$_{rxn}=-571.6\ kJ$
			3. $CH_4(g)+2O_2(g)\rightarrow CO_2(g)+2H_2O(\ell)$
				- $\Delta H^0$$_{rxn}=-890.2\ kJ$
		- $(1)+(2)-(3)$
		- $\Delta H_{rxn}=\Delta H_1 +\Delta H_2-\Delta H_3=-74.9\ kJ$
	- Know $\Delta H$ varies with conditions
		- Standard $\Delta H$ of Formation and Standard $\Delta H$ of Reaction
			- Gas: 1 atm & ideal behavior
			- Aqueous solution: 1M
			- Pure substance: most stable form at 1 atm and T of interest (for us $T=25\degree C$)
			- $\Delta H^0$$_{rxn}$ ≡ the standard heat of reaction $\implies$ reactants and products in standard states
		- Recall: formation reaction: 1 mol of compound form its elements
			- $C(graphite)+2H_2(g)\rightarrow CH_4(g)\ \Delta H^0$$_{rxn}$
			- Therefore, standard heat of formation for $CH_4=-74.9\ kJ/mol$
		- $\Delta H^0$$_f$'s have been tabulated $\implies$ can use to calculate $\Delta^0$$_{rxn}$
		- Note:
		1. $\Delta H^0$$_f=0$ for element in its standard state
			- $\implies \Delta H^0$$_f$(graphite)=0, $\Delta H^0$$_f$(diamond)$\ne 0$
			- $\Delta H^0$$_f$($O_2(g)$)=0, $\Delta H^0$$_f$($O_3(g)$)$\ne 0$
		2. $\Delta H^0$$_f\lt 0$ for most compouds
			- $\implies$ most cases compounds are more stable than elements
		3. $\Delta H^0$$_f=\sum n\Delta H^0$$_f(products)-\sum m\Delta H^0$$_f(reactants)$
			- Ex. $C (graphite)+O_2(g)\rightarrow CO_2(g)$
				- $\Delta H^0$$_f=(1)\Delta H^0$$_f(CO_2(g)-(1)\Delta H^0$$_f(C(graphite))-(1)$
	- Examples
		- Calculate $\Delta H^0$$_fC_2H_2$
			1. $C(graphite)+O_2\rightarrow CO_2(g)$     $\Delta H^0$$_{rxn}=-393.5\ kJ$
			2. $H_2(g)+\frac{1}{2}O_2(g)\rightarrow H_2O(l)$      $\Delta H^0$$_{rxn}=-285.8\ kJ$
			3. $2C_2H_2(g)+5O_2(g)\rightarrow 4CO_2(g)+2H_2O(l)$     $\Delta H^0$$_{rxn}=-2598.8\ kJ$
			- $2C (graphite)+H_2(g)\rightarrow C_2H_2(g)$
			- $2(eqn\ 1)+(eqn\ 2)-\frac{1}{2}(eqn\ 3)$
				- $\Delta H^0$$_{rxn}=2\Delta H_1 + \Delta H_2-\frac{1}{2}\Delta H_3=2(-393.5)-285.8+\frac{1}{2}(-2598.8)=226.6\ kJ/mol$
		- Ex. $B_5H_9$ explodes when exposed to $O_2$ according to $2B_5H_9(l)+12O_2(g)\rightarrow 5B_2O_3(s)+9H_2O(l)$
			- (In 1950's considered for rocket fuel but no good because $B_2O_3$'s abrasiveness destroyed the nozzles)
			- What is the kJ/g released in this reaction?
			- $\Delta H^0$$_{rxn}=[(5)\Delta H^0$$_f(B_2O_3)+(9)\Delta H^0$$_f(H_2O)]-[(2)\Delta H^0$$_f(B_5H_9)+(12)\Delta H^0$$_f(O_2)]$
				- $=[5*(-1263.6\ kJ/mol)+9*(-285.8\ kJ/mol)]-[2*(-73.2\ kJ/mol)]=-9036.6\ kJ$
			- $\frac{\Delta H}{gm}=\frac{-9036.6\ kJ}{2\ mol\ B_5H_9}*\frac{1}{63.12\ g/mol\ B_5H_9}=-71.58\frac{kJ}{g\ B_5H_9}$
	- Bond Energies and Thermochemistry 
		- For calculation - use H = state function
			- Gas phase
				- Break all atoms in reactants $\Delta H_1$$^0=\sum BE(rectants)$
				- Rebuild products $\Delta H_2$$^0=-\sum BE(products)$
			- $\Delta H_{rxn}$$^0=\Delta H_1$$^0+\Delta H_2$$^0$
			- Only for Diatomic or less molecules
			- For polyatomics it gives an approximate result
		- Liquid or solid must use $\Delta H_{vap}$, $\Delta H_{sub}$