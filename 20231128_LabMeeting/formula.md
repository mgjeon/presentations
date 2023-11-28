If $\mathbf{B}$ is **NOT** divergence-free,

$$
\frac{1}{8\pi} \int_V \mathbf{B}^2 \rm{d}V - \frac{1}{8\pi} \int_V \mathbf{B}_\text{p}^2 \rm{d}V 
\neq
\frac{1}{8\pi} \int_V (\mathbf{B} - \mathbf{B}_\text{p})^2 \rm{d} V 
$$

i.e.,


$$
E_\text{free} \neq E_\text{J}
$$

<!---------------------------------------------------------------------------------------------------------------------->

## Magnetic energy - Thomson's theorem

- Total magnetic energy $E$ in a volume $V$ (cgs-Gaussian units)

$$
E = \frac{1}{8\pi} \int_{V} B^2 \rm{d}V
$$

- $\mathbf{B} = \mathbf{B}_\text{p} + \mathbf{B}_\text{J}$

$$
E = E_\text{p} + E_\text{J} + \frac{1}{4\pi} \int_{\partial V} (\phi \cdot \mathbf{B}_\text{J}) \cdot \rm{d}\mathbf{S} - \frac{1}{4\pi}\int_{V} \phi (\nabla \cdot \mathbf{B}_\text{J}) \rm{d}V
$$

where

$$
E_\text{p} = \frac{1}{8\pi} \int_{V} B_\text{p}^2 \rm{d}V 
\quad \quad
E_\text{J} = \frac{1}{8\pi} \int_{V} B_\text{J}^2 \rm{d}V
$$

- $\partial V$ : boundary of $V$
- $\rm{d} \mathbf{S} = \mathbf{\hat{n}} \rm{d}S$
    - $\mathbf{\hat{n}}$ : external normal to $\partial V$


::: footer
@valori2013
:::

<!---------------------------------------------------------------------------------------------------------------------->

## Magnetic energy - Thomson's theorem

- Total magnetic energy $E$ in a volume $V$ (cgs-Gaussian units)
$$
E = E_\text{p} + E_\text{J} + \frac{1}{4\pi} \int_{\partial V} (\phi \cdot \mathbf{B}_\text{J}) \cdot \rm{d}\mathbf{S} - \frac{1}{4\pi}\int_{V} \phi (\nabla \cdot \mathbf{B}_\text{J}) \rm{d}V
$$

- Two conditions are classically considered:
    1. $\nabla \cdot \mathbf{B}_\text{J} = 0$ 

    1. $(\mathbf{\hat{n}} \cdot \mathbf{B}_\text{J})|_{\partial V} = 0$
        - The potential field $\mathbf{B}_p$ is computed from the same distribution of normal field of $\mathbf{B}$ on the boundary of $V$.
            - $(\mathbf{\hat{n}} \cdot \mathbf{B})|_{\partial V} = (\mathbf{\hat{n}} \cdot \mathbf{B}_\text{p})|_{\partial V}$
            - $\mathbf{\hat{n}} \cdot (\mathbf{B} - \mathbf{B}_\text{p})|_{\partial V} = 0$ 


- If these two conditions hold, then

$$
E = E_\text{p} + E_\text{J}
$$
