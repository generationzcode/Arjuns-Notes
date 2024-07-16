#thermo 
![[Pasted image 20240703111509.png]]
$$\frac{dU^t}{dt} = \sum M_i (H_i + \frac{V_i^2}{2}+gh_i)+Q+W_s-P_e\frac{dV}{dt}$$

Q is the rate of energy supplied on the left side
W is the work inputted
the summation head is for gases entering and leaving, If the system doesn't have such components, it equals 0
The work done is done against the external pressure
> [!notation] Notation
> Work done by the gas is negative, on it is positive, a t superscript on a variable means total, absence of a t means specific

## Turbine
Turbine converts high pressure, high temperature steam to low pressure and temperature steam, uses the energy for something else
$$0=m(H_1-H_2)+w_s$$
where H1 is the enthalpy of gas entering the turbine and H2 is the enthalpy of the gas leaving the turbine. W_s is the work done by the shaft on the gas, in this gase, work is done **on** the shaft thus w_s is negative

## Compressor
HIgh pressure, temperature from low pressure,temperature is compressor
Same eqn as turbine
w_s here will be positive since shaft is doing work on the gas

## Pipeline
Imagine one
$$U_2+P_2V_2+\frac{v_2^2}{2}+gh_2 = U_1+P_1V_1+\frac{v_1^2}{2}+gh_1$$
Usually U_1 and U_2 are the same
V is specific volume
## LPG cylinder
We are filling a cylinder slowly with LPG,thus:
$$\frac{dU^T}{dt} = n_1H_1$$
$$\frac{d(nU)}{dt} = \frac{dn}{dt}H_1$$
$$ndU = dn(H_1-U)$$
$$\frac{dU}{H_1-U} = \frac{dn}{n}$$
$$\int^{T_f}_{T_1}\frac{dT}{\gamma T_1-T} = \int_0^{n_f}\frac{dn}{n}$$
> [!notes] notes on the jump from H-U to Ti-T
> $$H = Href + C_p(T-T_ref)$$
> $$H_ref = U_ref+RT_ref$$
> $$U = U_ref+C_v(T-T_ref)$$
> $$H_1-U = C_p(T_1)-C_v(T))$$

## Unsteady state reservoir
* Imagine a reservoir of gas with initial temperature 300K and 300bar pressure
* Flow of gas is perfectly steady state outward
* As materials leave, they take enthalpy with them
$$H = C_vT+RT$$
$$dU^t = Hdm$$
$$nC_vdT+C_vTdm = -(C_vT+RT)dm$$
$$\frac{CvdT}{RT} = \frac{dm}{m}$$
$$\int^T_{T1}\frac{C_vdT}{RT} = \int^{\frac{m}{2}}_{m}dm$$

