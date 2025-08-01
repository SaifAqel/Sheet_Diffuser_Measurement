# 🌬️ Sheet Diffuser Efficiency Measurement

This project investigates the **performance and efficiency** of a sheet diffuser connected to a pipeline downstream of a radial fan. Using pressure and velocity measurements at various gap sizes, the diffuser's behavior was analyzed, and the optimal distance for maximum efficiency was determined. The project includes lab data, calculations, visual analysis, and error quantification.

---

## 📁 Project Contents

- `Sheet_Diffuser_Lab_Report.pdf`  
  Full lab report including:
  - Measurement setup and theoretical background
  - Diffuser efficiency formula and velocity calculations
  - Symmetry, pressure distribution, and error analysis
  - Conclusion with optimal configuration findings

- `Sheet_Diffuser_Efficiency_Analysis_Presentation.pptx`  
  Summary presentation with diagrams, results, and efficiency vs. gap size visualizations.

- `Sheet_Diffuser_Measurement_Data.xlsx`  
  Raw and processed measurement data:
  - Gap size, volume flow rate, velocity, and efficiency
  - Calibration and pressure distribution
  - Error and uncertainty values

---

## 🎯 Measurement Objective

To evaluate how **sheet distance (x)** affects:
- **Diffuser efficiency (η)**
- **Velocity symmetry**
- **Radial pressure distribution**

And to identify the **optimal gap size** that maximizes diffuser efficiency.

---

## ⚙️ Measurement Setup

- Location: Theodore von Kármán Wind Tunnel Lab, BME  
- Equipment:
  - Digital manometer (EBM-001)
  - Betz manometer (ARA_BETZ-01)
  - Pitot tube with angular rotation stand
- Controlled parameters:
  - Gap size `x`: 8 mm to 25 mm
  - Ambient temperature and pressure

---

## 📊 Key Results

| Parameter              | Value                        |
|------------------------|------------------------------|
| **Optimal gap size**   | 18 mm                        |
| **Max efficiency (η)** | 79.5% ± 0.051                |
| **Symmetry deviation** | ≤ ±0.018 (velocity error)    |
| **Efficiency error**   | ~15% relative at worst case  |
| **Flow pattern**       | Symmetric, mild separation   |

---

## 🧮 Key Formulas

- Efficiency:  
  `η = (p₂ - p₁)real / (ρ/2 · (v₁² - v₂²))`

- Velocity:  
  `v = qV / A` where `qV` is calculated from suction orifice pressure

- Density of air:  
  `ρ = p₀ / (R · T)`

- Error propagation:  
  Full error propagation of all input variables (pressure, diameter, gap)

---

## 📌 Authors

- **Saif-Aldain Aqel** – QTY3S6  
- **Heydarov Firuddin** – IG6JX7  
- **Horváth Kornél Ádám** – OFI50V  
- **Instructor**: Márton Koren  
- **Date**: 2023.04.18

---

## 🔗 References

1. Lajos, Tamás. *Az Áramlástan Alapjai*, BME Kiadó, 2005  
2. BME Department of Fluid Mechanics – [www.ara.bme.hu](http://www.ara.bme.hu)  
3. SKF & manometer calibration documentation

---
