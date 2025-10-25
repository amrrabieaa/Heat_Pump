# 🔥 Heat Pump Simulation with TESPy

This repository contains a **Thermodynamic Heat Pump Model** built using the [TESPy](https://tespy.readthedocs.io/en/main/) library (Thermal Engineering Systems in Python).  
It allows users to simulate both **design** and **off-design** operating conditions of a heat pump based on measured heat source and sink data.

---

## 📘 Overview

This project enables:
- Simulation of the **vapor compression heat pump cycle** (compressor, condenser, expansion valve, evaporator)
- Integration of **measured source/sink data** from Excel
- Calculation of **key performance indicators**, including:
  - COP (Coefficient of Performance)
  - Compressor power
  - Condenser and evaporator heat duties
- **Parametric off-design analysis** across multiple temperature and load conditions

---

## ⚙️ Features

✅ Modular class-based design (`HeatPumpModel`)  
✅ Built entirely with TESPy and pandas  
✅ Reads real-world data for water temperatures and heat load  
✅ Supports off-design and parametric simulations  
✅ Outputs COP, power, and heat flows for each case  

---

## 🧱 Model Structure

The heat pump thermodynamic cycle is defined as:

