## Electric Potential
- The electric force is conservative and this has an associated potential energy
- If a charged particle moves from an initial point to a final point in an electric field, apply the relationships between the change $\Delta{V}$ in the potential, the charge $q$, the change $\Delta{U}$ in the potential energy, and the work $W$ done by the electric force.
- If a charged particle moves between two points in the electric field of a charged object, the amount of work done by the electric force is path independent

### From mechanics
- $\Delta{U}=U_f-U_i$
- $E_i=E_f$
- $K_i+U_i=K_f+U_f$
- $\Delta{K}=-\Delta{U}=-q\Delta{V}$
- $E_i+W_{app}=E_f$
- $K_i+U_i+W_{app}=K_f+U_f$
- $\Delta{K}=-\Delta{U}+W_{app}$
- $\Delta{K}=-q\Delta{V}+W_{app}$    if $\Delta{K}=0$    $(K_i=K_f)$
- $W_{app}=q\Delta{V}$

### Equipotential Surfaces and the Electric Field
- Adjacent points that have the same electric potential from an **equipotential surface**, which can be either an imaginary surface or a real, physical surface.
- The electric potential difference between two points $i$ and $f$ is
	$V_f-V_i=-\int_i^f\vec{E}\cdot{d}\vec{s}$
- The electric potential at a particular point is
	$V=-\int_i^f\vec{E}\cdot{d}\vec{s}$

### Potential due to a Charged Particle
- Potential due to a charged particle
	$V=\frac{1}{4\pi\epsilon_0}\frac{q}{r}$
- Potential due to a group of Charged Particles
	$V=\sum_{i=1}^{n}V_i=\frac{1}{4\pi\epsilon_0}\sum_{i=1}^{n}\frac{q_i}{r_i}$
- Potential due to an Electric Dipole
	$V=\frac{1}{4\pi\epsilon_0}\frac{p\cos\theta}{r^2}$
#### Potential due to a Continuous Charge Distribution
- Line of charge
	$V=\frac{\lambda}{4\pi\epsilon_0}\ln[\frac{L+(L^2+d^2)^{\frac{1}{2}}}{d}]$
- Charged Disk
	$V=\int{dV}=\frac{\sigma}{2\epsilon_0}\int_0^R\frac{R'dR'}{\sqrt{z^2+R'^2}}=\frac{\sigma}{2\epsilon_0}(\sqrt{z^2+R^2}-z)$

### Calculating the Field from the Potential
- Work of an electric field
	$-q_0dV=q_0E(\cos\theta)ds$
		or
	$E\cos\theta=-\frac{dV}{ds}$

- To find electric field vector components, we can use the same procedure for $V(x,y,z)$
$$\begin{align}
f(x,y,z) \leftarrow function
\\
f(x,y,z) = 3xy + 4xz + 3yz
\end{align}$$
$$\begin{align}
\frac{d}{dx} \rightarrow \frac{\partial{f(x,y,z)}}{\partial{x}} = 3y + 4z + 0
\\
\frac{d}{dy} \rightarrow \frac{\partial{f(x,y,z)}}{\partial{y}} = 3x + 0 + 3z
\\
\frac{d}{dz} \rightarrow \frac{\partial{f(x,y,z)}}{\partial{z}} = 0 + 4x + 3y
\end{align}$$
#### Deriving an expression for the electric field at any point on a charged disk
$$\begin{align}
E_z=-\frac{\partial{V}}{\partial{z}}=-\frac{\sigma}{2\epsilon_0}\frac{d}{dz}(\sqrt{z^2+R62}-z)
\\
E_z=-\frac{\sigma}{2\epsilon_0}[\frac{1}{2}(z^2+R^2)^{-1/2}(2z)-1]
\\
E_z=\frac{\sigma}{2\epsilon_0}[1-\frac{1}{\sqrt{z^2+R^2}}]
\end{align}$$
##### Potential Energy of a two-particle system
#### $U=\frac{1}{4\pi\epsilon_0}\frac{q_1q_2}{r}$
