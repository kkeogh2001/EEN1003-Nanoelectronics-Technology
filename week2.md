### Why the Schrödinger Equation?

- The Schrödinger Equation is **the foundation of quantum mechanics**, essential to model and predict electron behavior in nano-scale materials and devices.
- It allows calculation of probability distributions, energy levels, band structures, and tunneling effects—vital for nanoelectronic design.

### The Schrödinger Equation

- **Time-dependent Schrödinger Equation (1D):**
  $$
  i\hbar \frac{\partial}{\partial t} \Psi(x, t) = -\frac{\hbar^2}{2m} \frac{\partial^2}{\partial x^2} \Psi(x, t) + U(x)\Psi(x, t)
  $$
  where:  
  $$ m $$ = mass,  
  $$ U(x) $$ = potential energy.
- **Physical Meaning:** The wavefunction $$\Psi(x, t)$$ describes the quantum state—its squared modulus $$|\Psi(x, t)|^2$$ gives the probability of finding a particle at $$ x $$ and time $$ t $$.
- The **Hamiltonian operator** represents total energy:  
  $$ \hat{H} = -\frac{\hbar^2}{2m}\frac{\partial^2}{\partial x^2} + U(x) $$.

### Stationary States and the Time-Independent Schrödinger Equation (TISE)

- If $$ U(x) $$ does not depend on time:
  $$
  -\frac{\hbar^2}{2m} \frac{d^2}{dx^2} \psi(x) + U(x)\psi(x) = E\psi(x)
  $$
- **Stationary states** have time-independent probability distributions and fixed energy values.

### Quantum Confinement: Infinite and Finite Wells

- **Infinite Potential Well (1D Box):**
  - Only certain standing waves (energy states) fit in the box.
  - Allowed energies:
    $$
    E_n = \frac{n^2 \pi^2 \hbar^2}{2mL^2}
    $$
    where $$ n = 1, 2, 3,\ldots $$ and $$ L $$ is box width.
  - **Zero-point energy:** The lowest possible energy ($$ n=1 $$) is not zero.
- **Finite Potential Well:**
  - The wavefunction leaks (tunnels) into/through barriers.
  - Energy levels: Fewer and lower than infinite well; true bound states must have $$ E < V $$.

### The Heisenberg Uncertainty Principle

- It is **impossible to precisely know both position (x) and momentum (p):**
  $$
  \Delta x \Delta p \geq \frac{\hbar}{2}
  $$
- This sets fundamental quantum limits on measurement accuracy and predicts spread in energy and position.

### Quantum Tunneling

- Particles have a finite probability to tunnel through energy barriers, even if $$ E < V $$. Key for nanoelectronic processes like tunneling diodes.

### Quantum Wells and Device Applications

- **Quantum wells:** Thin (nm-scale) layers where electrons are confined, leading to discrete energy levels.
- Created using semiconductor heterostructures (e.g., GaAs/AlGaAs).
- Used in lasers, detectors, and high-speed transistors.

### Structure of Matter: Crystals and Lattices

- **Atoms:** Defined by atomic number ($$ Z $$), mass ($$ A $$), valence electrons determine chemical properties.
- **Solid states:**
  - *Crystalline*: Atoms have a long-range, regular (periodic) arrangement.
  - *Amorphous*: No long-range order.
- **Lattice:** The repeating geometric arrangement in a crystal.
  - *Unit cell*: The smallest repeating unit.
  - *Bravais lattice*: One of 14 symmetrical ways to fill space in 3D.
- **Symmetry:** Includes translation symmetry, rotation axes, mirror planes, and inversion centers.

### Important Crystal Lattice Types

- **Simple Cubic (SC):** Lattice point at each corner.
- **Body Centered Cubic (BCC):** Extra point at cube center.
- **Face Centered Cubic (FCC):** Extra points at each face center.
- Not all unit cells show the full symmetry: FCC primitive cell is a rhombohedron.

***

#### Key Points to Revise

- **Schrödinger equation**: Forms, meaning, and applications to wells.
- **Stationary state concept** and differences between infinite/finite wells.
- **Uncertainty principle**: Equation, physical meaning, implications.
- **Quantum tunneling** and why it’s crucial for nanoscale devices.
- **Crystalline structure**: Definitions, lattice/Bravais types, symmetry.
- **Typical exam focus**: Interpret wavefunctions, draw well diagrams, label energy levels, calculate quantized energies, explain tunneling, describe crystal structures.
