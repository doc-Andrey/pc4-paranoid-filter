# PC4-Paranoid Filter  
**Multi-mode Phase-Coupled Resonance (PC4) filter with physical gating**

This repository contains the reference dataset and experimental code for the **PC4-Paranoid Filter** — an adaptive, physics-constrained sensor fusion architecture designed for operation in unknown, adversarial, or non-Gaussian environments.

The PC4 approach differs fundamentally from Kalman-based estimators by:
- relying on **phase consensus** rather than distributional assumptions,
- incorporating a **physical innovation gate**,
- remaining stable under sensor drift, failure, and snap-back scenarios **without pre-tuning**.

---

## 📦 Contents

- `PC4_Paranoid_Filter_Dataset.zip`  
  Full experimental dataset including:
  - reference PC4 filter implementations,
  - stress-test scenarios (drift, antiphase, snap-back),
  - all figures used in the associated Zenodo publication.

---

## 📄 Related publications

**Preprint (Zenodo):**  
> Osipov, A. (2026). *Multi-mode Phase-Coupled Resonance (PC4) Filter: A Cellular Unit for Complex Systems Integrity*.  
> DOI: https://doi.org/10.5281/zenodo.18102301

**Dataset (Zenodo):**  
> Osipov, A. (2026). *PC4-Paranoid Filter: Adaptive Physics-Constrained Sensor Fusion Dataset*.  
> DOI: https://doi.org/10.5281/zenodo.18131659

---

## 🔬 Reproducibility

All experiments are fully reproducible using the code contained in the dataset.  
No parameter tuning is required to reproduce the reported results.

---

## 📜 License

This repository is released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

---

## 🧠 Conceptual note

PC4 is not a filter in the classical signal-processing sense.  
It is a **cellular decision unit** inspired by biological sensory consensus and physical feasibility constraints.

It is suitable for:
- autonomous vehicles,
- drones and aerospace systems,
- robotics,
- biomedical signal fusion,
- complex adaptive systems.

---

**Author:**  
Andrey Osipov, MD, PhD  
