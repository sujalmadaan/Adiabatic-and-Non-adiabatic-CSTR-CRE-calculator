# Adiabatic-and-Non-adiabatic-CSTR-CRE-calculator
# ⚗️ CSTR Analysis – Adiabatic & Non-Adiabatic 

This project provides an interactive analysis and simulation of a **Continuous Stirred Tank Reactor (CSTR)** under both **adiabatic** and **non-adiabatic** conditions. It allows users to compute and visualize:

- ✅ Steady-state conversion
- 🌡️ Reactor temperature profiles
- 🧪 Reactor volume requirements
- ⚡ Reaction rates
- 🔁 Multiple steady states & stability
- 🔥 Thermal runaway behavior

> 📌 Explore it live: [https://cll-122-project.vercel.app/](https://cll-122-project.vercel.app/)

---

## 🚀 Features

- Dual-mode simulation: **Adiabatic** and **Non-Adiabatic** CSTRs
- Calculates:
  - Conversion (X)
  - Reactor Temperature (T)
  - Volume (V)
  - Rate of Reaction (r<sub>A</sub>)
- Identifies **multiple steady states** (if present)
- Performs **stability analysis** (stable/unstable)
- Visualizes:
  - Heat generation vs removal
  - Conversion vs temperature
  - Volume vs conversion
- Deployed as a **web app** using [Vercel](https://vercel.com)



## 🧪 How It Works

- **Material balance**:  
  \[
  F_{A0}(X) = V r_A
  \]
- **Energy balance** (non-adiabatic):  
  \[
  Q_{gen} = Q_{rem} \Rightarrow (-\Delta H) r_A V = UA(T - T_c)
  \]
- Solves numerically for steady-state intersections
- Stability determined from the **intersection** of energy balance and mole balance curves

---


