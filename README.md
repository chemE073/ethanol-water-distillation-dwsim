# Ethanol-Water Distillation Simulation (DWSIM)

A process simulation and parametric study of a continuous ethanol-water 
distillation column, built using DWSIM 9.0.5 (open-source chemical 
process simulator).

## 🎯 Objective
To simulate an ethanol-water distillation column and study how reflux 
ratio, boil-up ratio, and number of stages affect ethanol purity and 
energy consumption — and identify the most energy-efficient operating 
conditions.

## 🛠️ Tools Used
- **Software:** DWSIM 9.0.5
- **Thermodynamic Model:** NRTL
- **Column Solver:** Wang-Henke (Bubble Point)

## 📊 Key Findings
- Achieved **80 mol% ethanol purity** in the distillate
- Identified an optimal operating point (Reflux=3, Boil-up=1) saving 
  **54% energy** compared to default settings
- At industrial boil-up ratio (0.4), achieved **79% energy reduction** 
  while maintaining near-identical purity (79.6%)

## 📁 Contents
- `simulation.dwxmz` — DWSIM simulation file
- `Report.docx` — Full project report with theory, methodology, and results

## 📈 Parametric Study
Four independent analyses were performed:
1. Effect of Reflux Ratio (1–10)
2. Effect of Boil-up Ratio (0–9)
3. Effect of Number of Stages (5–15)
4. Effect of Stages at Optimal Boil-up Ratio

See the full report for detailed results, graphs, and conclusions.

## 👤 Author
ASHISH — Chemical Engineering, Final Year


## 👤 Author
[Your Name] — Chemical Engineering, Final Year
