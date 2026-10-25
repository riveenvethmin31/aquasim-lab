# AQUASIM LAB — Industrial Wastewater Treatment & Nickel Recovery Simulator

An interactive chemical engineering application and process digital twin built to simulate industrial wastewater treatment and heavy metal ($\text{Ni}^{2+}$) recovery via chemical hydroxide precipitation.

## 🔬 Scientific & Engineering Highlights
- **Experimental Validation:** Benchmark comparison against peer-reviewed experimental literature (*Baltpurvins et al., Water Research, 1997*), achieving an $R^2 = 0.984$ correlation.
- **Thermodynamic Speciation Engine:** Models $\text{Ni}^{2+}$ precipitation kinetics, temperature-dependent $K_{sp}$ equilibrium, and speciation ($\text{Ni(OH)}_2$, soluble hydroxo-complexes).
- **Interactive 3D Digital Twin:** 3D WebGL plant visualization using Three.js featuring Equalization Tanks, Chemical Dosing Skids, Rapid Mixers, Precipitation Reactors, and Clarifiers.
- **Mass Balance & Process Telemetry:** Computes real-time mass balances, stoichiometric reagent consumption ($\text{NaOH}, \text{Ca(OH)}_2, \text{Na}_2\text{CO}_3$), wet sludge cake generation, and operating costs ($\$/\text{h}$).

## 🛠️ Tech Stack
- **Frontend & UI:** HTML5, Tailwind CSS, Lucide Icons
- **3D Graphics Engine:** Three.js (WebGL, OrbitControls)
- **Analytics Charts:** Chart.js
- **Computation Engine:** JavaScript Process Simulation Engine
