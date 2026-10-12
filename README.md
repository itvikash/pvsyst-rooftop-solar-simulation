# pvsyst-rooftop-solar-simulation
# ☀️ Grid-Connected Rooftop PV System Simulation (PVsyst)

> **Status: 🚧 In progress.** Project setup is done; the PVsyst simulation and results will be added soon.

Design and performance simulation of a **grid-connected rooftop solar PV system** using **PVsyst**. The project covers site selection, system sizing, shading analysis, loss modelling, and yield estimation, and studies how tilt, azimuth, and shading affect energy output.

---

## 📌 Objective
- Design a grid-connected rooftop PV system for a residential/commercial building
- Estimate annual energy yield, Performance Ratio (PR), and specific yield
- Analyse system losses (temperature, soiling, shading, wiring, mismatch, inverter)
- Compare design options (tilt, orientation, shading vs no shading)
- Evaluate basic economics (savings and payback period)

---

## 🧰 Tools & Technologies
- **PVsyst** (PV system design and simulation)
- **Meteonorm / NASA-SARA** (weather data)
- **Microsoft Excel / Python** (extra calculations and plots)
- **Manufacturer datasheets** (module and inverter parameters)

---

## 🗺️ Site Details
| Parameter | Value |
|---|---|
| Location | To be added |
| Latitude / Longitude | To be added |
| Weather data source | To be added |
| Roof type | To be added |
| Available roof area | To be added |
| Nearby obstacles (shading) | To be added |

---

## ⚙️ System Configuration
| Component | Specification |
|---|---|
| System type | Grid-connected, rooftop, no battery |
| PV module (make, model, Wp) | To be added |
| Number of modules | To be added |
| System size (kWp) | To be added |
| Inverter (make, model, kW) | To be added |
| String configuration | To be added |
| DC/AC ratio | To be added |
| Tilt / Azimuth | To be added |

---

## 🔬 Methodology
1. **Site and weather data:** set the location and import meteorological data
2. **Orientation:** define tilt and azimuth, and run an optimisation to find the best angles
3. **Near shading:** build a simple 3D scene of surrounding obstacles
4. **System design:** select modules and inverter, then check string sizing against inverter voltage and current limits
5. **Loss parameters:** set soiling, thermal, wiring, mismatch, and inverter losses with justification
6. **Simulation:** run the hourly simulation for a full year
7. **Analysis:** study the loss diagram, PR, specific yield, and sensitivity cases
8. **Economics:** estimate annual savings and payback period

---

## 📉 Loss Assumptions
| Loss type | Value | Justification |
|---|---|---|
| Soiling | To be added | Local dust conditions |
| Temperature (Uc/Uv) | To be added | Mounting type |
| Wiring (ohmic) | To be added | Cable length and size |
| Module mismatch | To be added | Default / chosen |
| Inverter efficiency | To be added | Datasheet |
| Shading | To be added | From near-shading scene |

---

## 📊 Results
| Metric | Value |
|---|---|
| Annual energy produced (kWh/year) | To be added |
| Specific yield (kWh/kWp/year) | To be added |
| Performance Ratio (PR) | To be added |
| Capacity Utilisation Factor (CUF) | To be added |

**Loss diagram:** `images/loss_diagram.png` *(to be added)*
**Monthly energy yield:** `images/monthly_yield.png` *(to be added)*

---

## 🔍 Sensitivity Analysis
| Case | Yield (kWh/kWp/yr) | PR (%) |
|---|---|---|
| Optimal tilt | To be added | To be added |
| Actual roof tilt | To be added | To be added |
| With shading | To be added | To be added |
| Without shading | To be added | To be added |

**Key findings:** *to be added after simulation.*

---

## 💰 Economic Estimate
| Item | Value |
|---|---|
| System cost | To be added |
| Electricity tariff | To be added |
| Annual savings | To be added |
| Simple payback period | To be added |

---

## 📁 Repository Structure
```
├── datasheets/         # Module and inverter datasheets
├── project-files/      # PVsyst project files
├── report/             # PDF simulation reports
├── images/             # Loss diagram, charts, screenshots
├── calculations/       # Hand calculations and Excel/Python files
└── README.md
```

---

## ✅ Progress Tracker
- [x] Create repository and README
- [ ] Finalise site and building details
- [ ] Shortlist module and inverter, add datasheets
- [ ] Hand calculation of system size and string sizing
- [ ] Set up PVsyst project
- [ ] Build near-shading scene
- [ ] Run simulation and export report
- [ ] Sensitivity analysis
- [ ] Economic analysis
- [ ] Final README update with results

---

## 📚 Learnings & Limitations
*To be updated after simulation. Will include key learnings about PV design and any simplifications made (for example, an idealised shading scene or assumed loss values).*

---

## 🚀 Future Work
- Compare multiple module and inverter combinations
- Add battery storage and self-consumption analysis
- Validate results against measured data from a real plant
- Extend to hotspot detection using thermal imaging

---

## 👤 Author
@itvikash
Electrical and Electronics Engineering 
