# CH_7

[TOC]

## 7.1 Entropy

### Clausius Inequality

$$
\oint{\frac{\mathrm{\delta} Q}{T}}\leq 0
$$

This inequality is valid for **all cycles**

And this property is named as **entropy**, which designated S and defined as

$$
\mathrm{d}S=\Big(\frac{\mathrm{\delta}Q}{T}\Big)_{int\;rev}
$$

The entropy of a system during a process can be determined by integrating between the initial and the final states

$$
\Delta S = S_2-S_1 = \int_1^2{\Big(\frac{\mathrm{\delta}Q}{T}\Big)_{int\;rev}}
$$

### Special Case: Internally Reversible Isothermal Heat Transfer Processes

$$
\Delta S = \int_1^2{\Big(\frac{\mathrm{\delta}Q}{T}\Big)_{int\;rev}} = \int_1^2{\Big(\frac{\mathrm{\delta}Q}{T_0}\Big)_{int\;rev}} = \frac{1}{T_0}\int_1^2{(\delta Q)_{int\; rev}}\\[2ex]
\Delta S = \frac{Q}{T_0}
$$

where $T_0$ is the constant temperature of the system and $Q$ is the heat transfer fo the internally reversible process

## 7.2 The Increase of Entropy Principle

$$
\oint{\frac{\mathrm{\delta}Q}{T}}\leq 0\\[2ex]
$$

or

$$
\int_1^2{\frac{\mathrm{\delta}Q}{T}}+\int_1^2{\Big(\frac{\mathrm{\delta}Q}{T}\Big)_{int\;rev}}\leq 0\\[2ex]
$$

while the second integral in the previous relation is recognized as the entropy change

$$
\int_1^2{\frac{\mathrm{\delta}Q}{T}}+S_1-S_2\leq 0\\[2ex]
S_2-S_1\geq \int_1^2{\frac{\mathrm{\delta}Q}{T}}\\[2ex]
$$

which can also be arranged as in differential form as

$$
\mathrm{d}S\geq\frac{\delta Q}{T}
$$

some entropy is generated or created during an irreversible process, which is due entirely to the presence of irreversibilities.

The entropy generated during a process is called **entropy generation** and is denoted by $S_{gen}$

$$
\Delta S_{sys}=S_2-S_1=\int_1^2{\frac{\mathrm{\delta Q}}{T}}+s_{gen}
$$

for an isolated system, the heat transfer is zero and the former equation reduces to

$$
\Delta S_{isolated}\geq 0
$$

The equation can be expressed as **the entropy of an isolated system during a process always increases or, in the limiting case of a reversible process, remains constant**. In other words, it _never_ decreases. This is known as the **increase of entropy principle**

$$
S_{gen} = \Delta S_{total}=\Delta S_{sys}+\Delta S_{surr}\geq 0
$$

Since the entropy change of a system can be negative during a process, but entropy generation cannot. The increase of entropy can be summarized as follows:

$$
S_{gen}
\begin{cases}
    > 0\;\text{Irreversible Process}\\[2ex]
    = 0\;\text{Reversible Process}\\[2ex]
    < 0\;\text{Impossible Process}\\[2ex]
\end{cases}
$$

## 7.3 Entropy Change of Pure Substances

<div align = center><img src = "./assets/Ch_7_figure_1.png"></div>

The value of entropy at a specified state is determined just like any other property. Similarly, in the saturated mixture region, it's determined from

$$
s=s_f+xs_{fg}
$$

The entropy change of a specified mass m during a process is simply

$$
\Delta S = m\Delta s = m(s_1-s_1)
$$

## 7.4 Isentropic Processes

$$
\Delta s = 0\quad\text{or}\quad s_1=s_2
$$

It should be recognized that ***a reversible adiabatic process*** is necessarily ***isentropic*** ($s_2=s_1$), but an ***isentropic process*** **is not necessarily** a ***reversible adiabatic process***.

## 7.5 Property Diagrams Involving Entropy

$$
\delta Q_{int\; rev}= T \mathrm{d}S\\[2ex]
Q_{int\; rev}= \int_1^2{T\mathrm{d}S}\\[2ex]
$$

<div align = center><img src = "./assets/Ch_7_figure_2.png"></div>

## 7.6 What is Entropy

### Boltzmann Relation

$$
S = k \ln W
$$

### Gibbs's Formulation

$$
S = -k\sum{p_i \log p_i} \qquad p_i = \frac{1}{W}<<1
$$

### Third Law of Thermodynamics

> **the entropy of a pure crystalline substance at absolute zero temperature is zero**

## 7.7 The T ds Relations

$$
\delta Q_{int\;rev}-\delta W_{int\; rev,out}=\mathrm{d}U
$$

And

$$
\delta Q_{int\;rev}=T\mathrm{d}S\\[2ex]
\delta W_{int\; rev,out}=P\mathrm{d}V\\[2ex]
$$

Therefore,

$$
T\mathrm{d}s = \mathrm{d}u+P\mathrm{d}v\\[2ex]
\mathrm{d}s = \frac{1}{T}(\mathrm{d}u+P\mathrm{d}v)
$$

the second equation is obtained by h

$$
\mathrm{d}h = \mathrm{d}u+P\mathrm{d}V+v\mathrm{d}P=T\mathrm{d}s+v\mathrm{d}P\\[2ex]
\mathrm{d}s = \frac{1}{T}(\mathrm{d}h-v\mathrm{d}P)
$$

## 7.8 Entropy Change of Liquids and Solids

since liquids and solids can be approximated as **incompressible** substances

$$
\mathrm{d}s = \frac{\mathrm{d}u}{T}=\frac{c\mathrm{d}T}{T}\\[2ex]
s_2-s_1 = \int_1^2{c(T)\frac{\mathrm{d}T}{T}}\approxeq c_{avg}\ln{\frac{T_2}{T_1}}
$$

when the progress is isentropic, the entropy change equals to 0

## 7.9 The Entropy Change of Ideal Gases

$$
\mathrm{d}s =c_v \frac{\mathrm{d}T}{T}+R\frac{\mathrm{d}v}{v}\\[2ex]
s_2-s_1 = \int_1^2{c_v(T)\frac{\mathrm{d}T}{T}+R\ln{\frac{v_2}{v_1}}}= \int_1^2{c_p(T)\frac{\mathrm{d}T}{T}-R\ln{\frac{P_2}{P_1}}}
$$

### Variable Specific Heats

choose absolute zero as the reference temperature and define a function $s^o$ as

$$
s^o = \int_0^T{c_p(T)\frac{\mathrm{d}T}{T}}\\[2ex]
s_2-s_1 = s_2^o-s_1^o-R\ln {\frac{P_2}{P_1}}
$$

### Constant Specific Heat 

during the **isentropic progress**, the change of the entropy equals to 0, therefore,

$$
\ln\frac{T_2}{T_1}=-\frac{R}{c_v}\ln\Big(\frac{v_w}{v_q}\Big)\\[2ex]
\ln\frac{T_2}{T_1}=\ln\Big(\frac{v_1}{v_2}\Big)^{R/c_v}\\[2ex]
\Big(\frac{T_2}{T_1}\Big)=\Big(\frac{v_1}{v_2}\Big)^{R/c_v} = \Big(\frac{v_1}{v_2}\Big)^{k-1}
$$

where $R =c_p-c_v$, $k=c_p/c_v$ and $R/c_v=k-1$

similarly, the another equation comes to

$$
\Big(\frac{T_2}{T_1}\Big)=\Big(\frac{P_2}{P_1}\Big)^{(k-1)/k}
$$

combing the two equation

$$
\Big(\frac{P_2}{P_1}\Big)=\Big(\frac{v_1}{v_2}\Big)^{k}
$$

### Relative Pressure and Relative Specific Volume

similarly, from the equation we can get

$$
\frac{P_2}{P_1} = \exp{\frac{s_2^o-s_1^o}{R}}=\frac{\exp{s_2^o}/R}{\exp{s_1^o/R}}\\[2ex]
$$

define $\exp{s^o/R}$ as the relative pressure $P_r$

$$
\Big(\frac{P_2}{P_1}\Big)_{s=const}=\frac{P_{r2}}{P_{r1}}\qquad \Big(\frac{v_2}{v_1}\Big)_{s=const}=\frac{v_{r2}}{v_{r1}}
$$
