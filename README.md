# Euler-Cromer Method and Oscillator Dynamics

⚡ Computational Physics project focused on comparing Euler and Euler-Cromer numerical integration methods for oscillatory systems. The project investigates energy conservation, numerical stability, and damping effects in simple harmonic and damped oscillators through simulations and theoretical analysis.

---

## Topics Covered

- Euler Method
- Euler-Cromer Method
- Simple Harmonic Motion (SHM)
- Energy Conservation
- Numerical Stability
- Damped Oscillators
- Underdamped, Critically Damped, and Overdamped Motion
- Scientific Visualization

---

## Problems Simulated

### 1. Euler vs Euler-Cromer for SHM

The simple harmonic oscillator:

$$
\ddot{x} = -x
$$

is solved using both Euler and Euler-Cromer methods for different time steps.

The project compares:

- Position evolution
- Numerical accuracy
- Energy conservation
- Long-term stability

---

### 2. Energy Analysis of Euler-Cromer

The total energy is:

$$
E = \frac{1}{2}(v^2+x^2)
$$

The change in energy at each step is analyzed theoretically and verified numerically to understand why Euler-Cromer remains stable while standard Euler diverges.

---

### 3. Damped Harmonic Oscillator

The damped oscillator studied is:

$$
\ddot{x}+2b\dot{x}+\omega_0^2x=0
$$

Three damping regimes are investigated:

- Underdamped Motion
- Critically Damped Motion
- Overdamped Motion

The numerical solutions are compared with analytical predictions.

---

## Technologies Used

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Features

- Euler and Euler-Cromer implementation
- Energy conservation analysis
- Numerical vs analytical comparison
- Damping regime visualization
- Oscillator trajectory plotting
- Stability investigation

---

## Key Observations

- Standard Euler causes energy to grow continuously, leading to unstable solutions.
- Euler-Cromer keeps energy bounded and produces physically realistic oscillations.
- The average energy drift in Euler-Cromer remains close to zero over long times.
- Damping reduces oscillation amplitude and eventually brings the system to equilibrium.
- Different damping coefficients produce distinct motion characteristics.

---

## Conclusion

This project demonstrates the advantages of the Euler-Cromer method for simulating oscillatory systems. Through energy analysis and damping simulations, it highlights the importance of choosing stable numerical integration schemes in Computational Physics.

---

## How to Run

Clone the repository:

```bash
git clone <repository-link>
```

Install dependencies:

```bash
pip install numpy matplotlib jupyter
```

Run the notebook:

```bash
jupyter notebook
```

---
