>I apologise for the poor formatting at the start

---

This is energy balance
pressure energy + kinetic energy + potential energy 1st form
$$\dot{m}(\frac{v^2}{2}+gh)+P\dot{V} = constant$$
$$\frac{\rho v^2}{2}+\rho gh+P = constant$$
2nd form:
$$\frac P \rho + \frac {v^2}2 + gh1 = constant$$

3rd form:

$$\frac P {\rho g} +\frac {v^2}{2g} + h1 = constant$$
the third form is the **head form**

---

With frictional losses included, the energy term goes in the RHS and pump energy rate
$$P_1V_1+\frac{\dot m v_1^2}{2}+\dot mgh_1 = P_2V_2 + \frac{\dot mv_2^2}{2}+\dot mgh_2 + frictionalLosses$$
$$\frac {P_1} {\rho g}+\frac{v_1^2}{2 g}+h_1 + pumpHead= \frac {P_2} {\rho g} + \frac {v_2^2}{2 g}+h_2 + \frac{frictionalLosses}{\dot m g}$$

>[!problem]
>$P_2=P_1$, $v_1 = 2m/s$, $v_2 = 1m/s$ $V = 10^{-2}m^3s^{-1}$, $\rho = 800kg{m}^{-3}$, during the journey the losses are 1000 metres head, height difference is 500 metres. Pump head
>
$$\frac{P_1}{\rho g}+\frac {v_1^2}{2g}+h_1+pump = \frac {P_2}{\rho g} + \frac {v_2^2}{2g}+h_2+fric$$
$$\frac{2^2}{20}+0+pump = \frac{1^2}{20}+500+1000$$
$$pump = 1500+0.05-0.2$$
pump head is 1499.85 metres

---
>[!problem]
>During a trip to the beach. $P_{atm}$ = 1atm, a car runs out of gas,It becomes necessary to siphon gas out of the tank of a good samaritan. The siphon is a small diameter hose and to start the siphon it becomes necessary to insert one end in the full gasoline tank, fill the hose with gasoline via suction and then place the other end in the gasoline can below the level of the gasoline tank. The difference in pressure between point 1 and point 2 causes the liquid to flow from higher to lower elevation. Point 2 is located 0.75 meter below point 1. Point 3 is located 2m above point 1. So the liquid flows from point 1 to 3 finally to 2. Frictional losses are to be disregarded. Diameter of hose is 4mm.
>
>Determine:
>* Time to take to move 4 litres into the can
>* Pressure at point 3. Assume gasoline density to be $750kgm^{-3}$
>![[Pasted image 20240716110730.png]]

## Solution

Bernoulli equation in *head* form
$$\frac{P_1}{\rho g} + \frac{v_1^2}{2g}+h_1+pump = \frac{P_2}{\rho g} + \frac{v_2^2}{2g}+h_2+fric$$
Take the tank as point 0, the pressure at 0 and 2 are the same, thus:
$$\frac{P_0}{\rho g} + \frac{v_0^2}{2g}+h_0= \frac{P_2}{\rho g} + \frac{v_2^2}{2g}+h_2$$
=>$$h_0= \frac{v_2^2}{2g}+h_2$$
since v_0 is approximately 0m/s
> the rest of part 1 is really easy


the *pump* and *fric* terms are 0, $P_2 = 1atm$, $h_1-h_2 = 0.75$, $v_1=v_2$:
$$\frac{P_1}{750*9.81}= {\frac{101325}{750*9.81}-0.75}$$
=> $$P_1 = 95806pa$$
Thus pressure at point 3 is:
=> $$\frac{P_1}{\rho g}+h_1-h_3 = \frac{P_3}{\rho g}$$=> $$\frac{95806}{750*9.81}-2 = \frac{P_3}{750*9.81}$$
=> $$P_3 = 81091pa$$



> Remarks on solution - most braindead method of getting the answer I pity all who read this and try to make sense of it

