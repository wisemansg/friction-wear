# 🧪 SURFACE SCIENCE & TECHNOLOGY — TRIBOLOGY LAB PROJECT

**Student:** Wiseman Siriro  
**Student Code:** S333263  
**Supervisor:** Prof. Federico Simone Gobber  
**Institution:** Polytechnic University of Turin, Italy  
**Program:** MSc Materials Engineering for Industry 4.0  
**Research Topic:** Friction & Wear Testing (Tribology)

---

## 📚 Project Overview

The project involves experimental work focused on tribological testing methods and the influence of coatings and lubricants on friction, wear mechanisms, and surface performance.

The work integrates analysis of:
- Pin-on-Disc testing (PVD coatings)
- Disc-on-Disc testing
- Block-on-Ring testing (lubricated steel contact)
- FTIR oil analysis
- Hertzian contact mechanics evaluations
- Wear mechanism classification
- Image & debris inspection via microscopy & EDS

---

# ❓ QUESTION 1 — Tribological Testing & Wear Mechanisms

## 🔍 **How lab-scale tribology informs anti-wear surface design**

Tribological testing at the laboratory scale aids in the design of surface treatments for structural or wear-resistant purposes by enabling:

✔ Characterization of friction coefficient (CoF)  
✔ Analysis of wear rates & wear modes  
✔ Optimization of material and coating selection  
✔ Validation of performance under simulated conditions  
✔ Prediction of component lifespan & maintenance cycles

This allows materials engineers to match treatments to industrial requirements such as durability, oxidation resistance, and thermal stability.

---

## 🟠 Pin-on-Disc Method — Description

The pin-on-disc method characterizes frictional force, CoF and wear rate between a stationary pin and a rotating disc.

Key parameters controlled:

- Applied normal load
- Surface roughness
- Sliding velocity
- Disc rotation speed
- Material hardness & microstructure
- Data acquisition for CoF trends

ASTM G99 standards define typical dimensions:

| Parameter | Typical Range |
|---|---|
| Pin Ø | 2–10 mm |
| Disc Ø | 30–100 mm |
| Disc thickness | 2–10 mm |

Wear can be quantified via:
- LVDT measurement
- Mass loss
- Profile scanning
- Optical/microscopy inspection

---

## 🔵 Disc-on-Disc Method — Description

The disc-on-disc test evaluates friction and wear using two rotating discs in contact under controlled load, enabling the study of:

- Lubrication regimes
- Oxidation phenomena
- Conformal vs non-conformal contact
- Fretting conditions
- Mixed motion patterns

The geometry allows replication of industrial applications (e.g. gears, bearings, clutches).

---

## ⚙ Wear Mechanisms Reproducible in Lab

Tribometers can reproduce multiple wear modes, including:

- Adhesive wear
- Abrasive wear
- Fatigue wear
- Fretting wear
- Erosive wear
- Corrosive wear
- Micro-fracture wear
- Oxidative wear

---

# 🧪 QUESTION 2 — Case Study 1: PVD Coating Comparison (Pin-on-Disc)

### 📊 Materials Tested

PVD coatings evaluated under identical test conditions:

| Coating | Notes |
|---|---|
| **AlTiCrN** | Low CoF, high oxidation resistance |
| **AlTiN** | Balance between friction & wear |
| **TiN** | High hardness, higher CoF |

### 📈 Coefficient of Friction (CoF) Analysis

Experimental observations:

- Running-in phase: 0–10 m (asperity conformity)
- Stabilization: 10–100 m
- AlTiCrN shows lowest & most stable CoF
- TiN exhibits highest CoF and fluctuation

Implications:

✔ Lower CoF → lower wear → improved tool life  
✔ Higher CoF → higher thermal & mechanical stress  

**Conclusion:**  
AlTiCrN is most suitable for dry cutting of hardened steels based on friction performance alone.

---

# 🛢 QUESTION 3 — Case Study 2: Block-on-Ring with Lubricated Steel Contact

### ⚙ Test Configuration

| Parameter | Value |
|---|---|
| Geometry | Steel Block vs Steel Ring |
| Load | 100 kg & 200 kg |
| Speed | 100 rpm |
| Lubricants | Mineral Oil vs Synthetic Oil |

Objectives:

- Compare lubrication effects on CoF
- Evaluate wear & oil film performance
- Analyze debris chemistry (EDS + FTIR)

---

## 🔬 FTIR Oil Characterization

Findings:

- Mineral oil: fewer absorption peaks → simpler hydrocarbon chains
- Synthetic oil: more peaks → functional additives (esters, ZDDP, etc.)

---

## 📉 CoF Results Summary

Synthetic oil showed lower frictional response than mineral oil at both loads due to improved film strength and anti-wear additive chemistry.

---

## 🧮 Holm-Archard Wear Model

Wear volume \( V \) calculated:

V = K * (F_N / H) * d


Where:  
- \( K \) = wear coefficient  
- \( F_N \) = normal load  
- \( H \) = hardness  
- \( d \) = sliding distance  

Synthetic oil produced lower calculated wear volumes than mineral oil at both 100 kg & 200 kg loads.

---

## 🧱 Hertzian Contact Analysis

Initial pin-disc contact begins as point contact, evolving toward increased conformity and reduced pressure over time.

HertzWin simulations used to extract:

✔ von Mises stress distribution  
✔ subsurface shear stress peaks  
✔ equivalent stress localization  

---

# 🏁 Key Engineering Conclusions

- Coatings strongly influence dry sliding behavior
- Lubricants dramatically change wear & CoF profiles
- Oxidation & debris chemistry govern long-term wear
- Hertzian theory explains initial stress-driven wear
- AlTiCrN best performer for dry cutting among PVD coatings
- Synthetic oil superior to mineral oil in lubricated steel contact
