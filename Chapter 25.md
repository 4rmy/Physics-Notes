## 25-1 Capacitance
- A capacitor consists of two isolated conductors (the plates) with charges +q and -q, Its capacitance C is defined from $$q=CV$$ where V is the potential difference between the plates.
- When a circuit with a battery, an open switch, and an uncharged capacitor is completed by closing the switch, conduction electrons shift, leaving the capacitor plates with opposite charges.

## 25-2 Calculating the Capacitance
- We generally determine the capacitance of a particular capacitor configuration by (1) assuming a charge $q$ to have been placed on the plates, (2) finding the electric field $\vec{E}$ due to this charge, (e) evaluating the potential difference V between the plates, and (4) calculating $C$ from $q=CV$. Some results are the following:
	- A parallel-plate capacitor with flat parallel plates of area $A$ and spacing $d$ has capacitance $$C=\frac{\epsilon_0A}{d}$$
	- A cylindrical capacitor (two long coaxial cylinders) of length $L$ and radii $a$ and $b$ has capacitance $$C=2\pi\epsilon_0\frac{L}{\ln(\frac{b}{a})}$$
	- A spherical capacitor with concentric spherical plates of radii $a$ and $b$ has capacitance $$C=4\pi\epsilon_0\frac{ab}{b-a}$$
	- An isolated sphere of radius $R$ has capacitance $$C=4\pi\epsilon_0R$$
## 25-3 Capacitors in Parallel and in Series
- The equivalent capacitances $C_{eq}$ of combinations of individual capacitors connected in parallel and in series can be found from $$C_{eq}=\sum_{j=1}^nC_j \tag{$n$ capacitors in parallel}$$
	and
	$$
	\frac{1}{C_{eq}}=\sum_{j=1}^n\frac{1}{C_j} \tag{$n$ capacitors in series}
	$$
- For parallel capacitors in with the same charge and voltage, we can "replace" the capacitors with a single capacitor equivalent to the 3 capacitors, to simplify calculations.

$$\begin{align}
q_1=C_1V\\q_3=C_2V\\q_3=C_3V\\\\
q = q_1 + q_2 + q_3\\
q = C_1V + C_2V + C_3V\\
q = V(C_1 + C_2 + C_3)\\
\frac{q}{V} = C_1 + C_2 + C_3\\
\frac{q}{V} = C_{eq} = \sum_{j=1}^nC_j
\end{align}
$$

- series have the same charge $q$, parallels have the same $V$

## 25-4 Energy Stored in an Electric Field
- The electric potential energy $U$ of a charged capacitor $$ U = \frac{q^2}{2C} $$ and $$ U = \frac{1}{2}CV^2 $$ is equal to the work required to charge the capacitor. This energy can be associated with the capacitor's electric field $\vec{E}$
- The potential energy of a charged capacitor may be viewed as being stored in the electric field between its plates.
- Every electric field, in a capacitor or from any other source, has an associated stored energy. in vacuum, the __energy density__ $u$ (potential energy per unit volume) in a field of magnitude $E$ is $$ u=\frac{1}{2}\epsilon_0E^2$$
## 25-5 Capacitor with a Dielectric
- If the space between the plates of a capacitor is completely filled with a __dielectric material__, the capacitance $C$ in vacuum (or, effectively, in air) is multiplied by the material's __dielectric constant__ $\kappa$, which is a number greater than 1.
- In a region completely filled by a dielectric material of dielectric constants $\kappa$, all electrostatic equations containing the permittivity constants $\epsilon_0$ are to be modified by replacing $\epsilon_0$ with $\kappa\epsilon_0$
- 