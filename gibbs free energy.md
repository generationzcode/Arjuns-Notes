#thermo 
$$\frac{d}{dt}(U^t+PV-TS) = \sum{m_i(H_i-TS_i)}+\dot{w_s}$$
This gives maximum possible work that can be extracted from a process
$$\frac {dU^t}{dt}+P_e\frac{dV}{dt}+T\frac{dS^t}{dt} = \sum{mH_i} - \sum{mTS_i} + \dot{w_s}-TS^t_{gen}$$
Gibbs energy requires isothermal conditions

$$B=H-T_oS$$ T_o is the ambient temperature, matter of notation use 300K
>[!note]
>$$S^t_{gen}>=0$$


$$G=U+PV-TS$$
or
$$G=H-TS$$

or
$$\frac{dG^t}{dt} = \sum{m_iG_i} +W_s-TS^t_{gen}$$
>B,X and G are just different ways of looking at systems, you can use anything even U and S to evaluate stuff

$$dU = TdS-PdV$$
$$dH = TdS+VdP$$
$$dG=VdP-SdT$$
thus
$$dH = \frac{\delta H}{\delta T}_PdT + \frac{\delta H}{\delta P}_TdP$$
=> $$(\frac{\delta H}{\delta P})_T = T(\frac{\delta S}{\delta P})_T+V$$
=> $$\frac{\delta G}{\delta P}_T = V$$
=>$$\frac{\delta}{\delta T}.(\frac{\delta G}{\delta P})_T = (\frac{\delta V}{\delta T})_P$$
=> $$\frac{\delta G}{\delta T}_P = -S$$
=>$$\frac{\delta}{\delta P}.(\frac{\delta G}{\delta T})_P = -(\frac{\delta S}{\delta T})_T$$
=> $$\frac{\delta V}{\delta T}_P = -\frac{\delta S}{\delta T}_T$$
=> $$dH = C_pdT+[V+T(\frac{\delta S}{\delta T})_T]dP$$
=> $$dH = C_pdT+[V-T(\frac{\delta V}{\delta T})_P]dP$$
=> $$dS = \frac{\delta S}{\delta T}_P+{\frac{\delta S}{\delta P}}_TdP$$
=> $$dS = \frac{C_p}{T}dT-\frac{\delta V}{\delta T}_TdP$$
## Ideal Gas
PV = RT
$$\frac{\delta V}{\delta T}_P = \frac{R}{P}$$
$$dH = C_PdT +[V-\frac{\delta V}{\delta T}T]dP$$
$$dH = C_pdT$$
___
$$dS = \frac{C_p}{T}dT-\frac{R}{P}dP$$
integrating,$$S_2-S_1 = C_pln\frac{T_2}{T_1} - R ln\frac{P_2}{P_1}$$
$$C_pln\frac{T_2}{T_1} = R\ ln\frac{P_2}{P_1}$$
## Liquids
$$dH = C_pdT+[V-T\alpha V]dP$$
Alpha is the coefficient of thermal expansion (volumetric)
> [!problem]
> water from 30 to 50 degrees celsius, 1 to 100 bar
> to get enthalpy change, we take the above equation at constant pressure to 50 degrees celsius then at constant temp from 1 to 100 bar

