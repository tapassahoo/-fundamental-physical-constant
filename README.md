
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
\hat{p}&=i\big(\dfrac{m\omega\hbar}{2}\big)^{1/2}(\hat{a}^{\dagger}-\hat{a}),\\
\end{align*}
$$

where $\hat{a}^{\dagger}$ and $\hat{a}$ are commonly known as `raising` and `lowering` operators, respectively.


