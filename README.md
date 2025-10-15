# Threshold Photoelectron Spectrum of Cyclobutadiene

## 📘 Overview
This repository shows the year 1 poster projecrs **“Threshold Photoelectron Spectrum of Cyclobutadiene: Comparison with Time-Dependent Wave Packet Simulations”**, presented by **April Zeng, Jimmy Zheng, and Sherry Zhao** from the **Department of Chemistry, University College London (UCL)**.

The project reinvestigates the photoionization and vibronic coupling behavior of **cyclobutadiene (C₄H₄)** — a prototypical *antiaromatic* molecule — using **mass-selected threshold photoelectron spectroscopy (ms-TPEs)** and **time-dependent wave packet simulations**.

---

## 🔬 Background
Cyclobutadiene (CBD) is the smallest and most studied example of an **antiaromatic** molecule, characterized by 4π delocalized electrons that destabilize the ring structure. This unique instability gives rise to rich vibronic coupling and Jahn–Teller distortions observable in its electronic spectra.

---

## ⚗️ Methodology
- **Experimental technique:**  
  Mass-selected Photoelectron–Photoion Coincidence Spectroscopy (**PEPICO**) was used to record **ms-TPE spectra**, minimizing contamination from reactive intermediates.

- **Simulation approach:**  
  Time-dependent **wavepacket dynamics** were performed using a **vibronic coupling model Hamiltonian**, parametrized with **CASPT2** (Complete Active Space with Second-Order Perturbation Theory) calculations.

## 🧮 CASPT2 Calculation Explained

### 1️⃣ Complete Active Space (CAS)
- In a **complete active space (CAS)** calculation, we **choose an active space** that includes the most important part of electronic excitations (e.g., π → π*).
- Electrons within these orbitals are allowed to **redistribute in all possible ways**, leading to a **multireference wavefunction** — the **CASSCF (Complete Active Space Self-Consistent Field)**.

### 2️⃣ Role of CASSCF
- CASSCF accounts for **essential static electron correlation**, but it has a limitation:
  - It **cannot describe dynamic correlation**, which mainly arises from **short-range electron–electron interactions**.

### 3️⃣ Introducing PT2 (Second-Order Perturbation Theory)
- To overcome this limitation, **PT2** is applied:
  - First, a **reliable reference wavefunction** is obtained from CASSCF.
  - Then, the **remaining dynamic correlation** is recovered through **second-order perturbation theory**.
- The combination gives us **CASPT2 (Complete Active Space with Second-Order Perturbation Theory)** — a powerful balance of static and dynamic electron correlation.

---

## ⚗️ What CASPT2 Provides
CASPT2 yields highly accurate:
- **Ionization energies**
- **Potential energy surfaces**
- **Vibronic coupling models**

These outputs form the foundation for **time-dependent wavepacket simulations**, which allow us to explore how **vibrational modes influence changes in the electronic structure over time**.

---

## 🧠 Connection to Wavepacket Dynamics
By combining CASPT2 results with **wavepacket propagation models**, we can:
- Simulate how vibrational motions (like ν₄) evolve on the potential energy surface.
- Understand how these vibrations **couple to electronic states** and shape the **photoelectron spectrum**.

Finally, the **simulated spectra** are compared with the **experimental ms-TPE spectra** to validate the theoretical model.


---

## 📈 Results
- The **adiabatic ionization energy (IE)** of cyclobutadiene was determined to be **8.06 ± 0.02 eV**, in close agreement with simulations.
- The dominant vibrational contribution in the spectrum arises from the **ν₄ mode**, coupled to **ν₁** and **ν₅** vibrations due to **Jahn–Teller distortions**.
- Theoretical and experimental spectra show excellent consistency, validating the CASPT2-based vibronic coupling model.

---

## 🧠 Interpretation
- The **neutral** and **cationic** forms of CBD exhibit strong **pseudo-Jahn–Teller** and **Jahn–Teller** interactions, respectively.
- The **ν₄ vibration** mediates transitions between rectangular **D₂h** minima and a square **D₄h** transition state, defining the molecule’s dynamic behavior upon ionization.

---

## 📚 References
1. *IUPAC Gold Book: Antiaromaticity*. (2013).  
2. *J. Phys. Chem. Lett.* **2021**, 12, 6901–6906.  
3. Baer, T.; Tuckett, R. P. *Phys. Chem. Chem. Phys.* **2017**, 19, 9698–9723.  
4. Köppel, H.; Domcke, W.; Cederbaum, L. S. *Adv. Chem. Phys.* **1984**, 57, 59.  
5. Mukherjee, B. et al. *Int. Rev. Phys. Chem.* **2019**, 38, 287–341.  
6. Kohn, D. W.; Chen, P. *J. Am. Chem. Soc.* **1993**, 115, 2844–2848.

---

## 🙏 Acknowledgements
The authors gratefully thank **Prof. Worth Graham** for his inspiring discussion and guidance on the computational methods and analysis.

---

## 📄 File
- `MYA Poster 47.pdf` — full poster with figures, analysis, and methodology.

---

## 🧩 Citation
If you reference this work, please cite as:

>  Zhao, S; Zeng, A.;Zheng, J. (2023). *Threshold Photoelectron Spectrum of Cyclobutadiene: Comparison with Time-Dependent Wave Packet Simulations*. University College London.

---

## 🧪 Keywords
`Cyclobutadiene` · `Photoelectron Spectrum` · `Vibronic Coupling` · `Jahn–Teller Effect` · `CASPT2` · `Wavepacket Dynamics` · `Antiaromaticity`
