
### List of components of the system and associated reference units.

| Component       | Reference       | Symbol          |
| --------------- | --------------- | --------------- |
| Oscillation     | Cycle           | Cy              |
| Time            | Second          | s               |
| Space           | Meter           | m               |
| Mass            | Kilogram        | kg              |
| Charge          | Coulomb         | C               |
| Temperature     | Kelvin          | K               |

### List of the measured constants of nature from the NIST standard and associated reference units. 

| Constant        | Label           | Value           | Measure Reference   |
| --------------- | --------------- | --------------- | ------------------ |
| Speed of Light  | c               | 2.99792458 $\times$ 10$^8$ | $\text{m.s}^{-1}$ | 
| Planck's Constant| h              | 6.62606957 $\times$ 10$^{-34}$ | $\text{J.s} = \text{kg.m}^2.\text{s}^{-1}$|
| Boltzmann Constant | k$_{\text{B}}$ | 1.3806503 $\times$ 10$^{-23}$ | $\text{J.K}^{-1} = \text{kg.m}^2.\text{s}^{-2}.\text{K}^{-1}$ |
| Molar Gas Constant | R | 8.3145   | $\text{J.K}^{-1}.\text{mol}^{-1}$|
| Faraday Constant.  | F | 96484.56 | $\text{C.mol}^{-1}$|

### Determination of Dimensions

- [X] **Gas Constant R**
From the ideal gas law $PV = nRT$ we get:

$$
\begin{align*}
R&=\dfrac{PV}{nT} \\
&=\dfrac{\dfrac{\text{force}}{\text{area}}\times \text{volume}}{\text{amount} \times \text{temperature}} \\
&=\dfrac{\dfrac{\text{force}}{(\cancel{\text{length}}\times \cancel{\text{length}})} \times (\cancel{\text{length}}\times\cancel{\text{length}}\times\text{length})}{\text{amount} \times \text{temperature}} \\
&=\dfrac{\text{force} \times \text{length}}{\text{amount} \times \text{temperature}}
\end{align*}
$$

Since $\text{force} \times \text{length} = \text{work}$:

$$R=\dfrac{\text{work}}{\text{amount} \times \text{temperature}}.$$

Therefore, the unit of the universal gas constant is $\text{J.K}^{-1}.\text{mole}^{-1}.$

Again,

$$\text{force}=\dfrac{\text{mass}\times\text{length}}{(\text{time})^2}.$$

Therefore,
$$R=\dfrac{\text{mass} \times (\text{length})^2}{\text{amount} \times \text{temperature}\times(\text{time})^2}$$.

Then, the unit becoms kg⋅m$^2$⋅s$^{−2}$⋅K$^{−1}$⋅mol$^{−1}$.

- [X] **Some Quantities Associated with Simple Harmonic Oscillator**

The position and momentum operators for a simple harmonic oscillator can be expressed as

$$
\begin{align*}
\hat{x}&=\big(\dfrac{\hbar}{2m\omega}\big)^{1/2}(\hat{a}^{\dagger}+\hat{a}),\\
\hat{p}&=i\big(\dfrac{m\omega\hbar}{2}\big)^{1/2}(\hat{a}^{\dagger}-\hat{a}),
\end{align*}
$$

where $\hat{a}^{\dagger} \ \text{and} \ \hat{a}$ are commonly known as `raising` and `lowering` operators, respectively. Above equalities manifest that the unit of the position and momentum operators must be same as the prefactors associted with their definitions.

In SI unit,

$$
\begin{align*}
\bigg(\dfrac{\hbar}{2m\omega}\bigg)^{1/2}&=\bigg(\dfrac{\text{J.s}}{\text{kg.s}^{-1}}\bigg)^{1/2}\\
&=\bigg(\dfrac{\text{work}\times \text{s}}{\text{kg.s}^{-1}}\bigg)^{1/2}\\
&=\bigg(\dfrac{\text{force}\times\text{length}\times \text{s}}{\text{kg.s}^{-1}}\bigg)^{1/2}\\
&=\bigg(\dfrac{\text{mass}\times\text{acceleration}\times\text{length}\times \text{s}}{\text{kg.s}^{-1}}\bigg)^{1/2}\\
&=\bigg(\dfrac{\text{kg}.\text{m.s}^{-2}.\text{m.s}}{\text{kg.s}^{-1}}\bigg)^{1/2}\\
&=\bigg(\dfrac{\cancel{\text{kg}}.\text{m}^2.\cancel{\text{s}^{-2}}.\cancel{\text{s}}}{\cancel{\text{kg}}.\cancel{\text{s}^{-1}}}\bigg)^{1/2}\\
&=\sqrt{m^2}
&=m.
\end{align*}
$$

Similarly,

\begin{align*}
\bigg(i\big(\dfrac{m\omega\hbar}{2}\big)^{1/2}&=\bigg(\dfrac{\text{J.s}}{\text{kg.s}^{-1}}\bigg)^{1/2}\\
&=\bigg(\dfrac{\text{work}\times \text{s}}{\text{kg.s}^{-1}}\bigg)^{1/2}\\
&=\bigg(\dfrac{\text{force}\times\text{length}\times \text{s}}{\text{kg.s}^{-1}}\bigg)^{1/2}\\
&=\bigg(\dfrac{\text{mass}\times\text{acceleration}\times\text{length}\times \text{s}}{\text{kg.s}^{-1}}\bigg)^{1/2}\\
&=\bigg(\dfrac{\text{kg}.\text{m.s}^{-2}.\text{m.s}}{\text{kg.s}^{-1}}\bigg)^{1/2}\\
&=\bigg(\dfrac{\cancel{\text{kg}}.\text{m}^2.\cancel{\text{s}^{-2}}.\cancel{\text{s}}}{\cancel{\text{kg}}.\cancel{\text{s}^{-1}}}\bigg)^{1/2}\\
&=\sqrt{m^2}
&=m.
\end{align*}
$$




