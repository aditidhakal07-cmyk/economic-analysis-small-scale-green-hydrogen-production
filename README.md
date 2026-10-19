# Levelized Cost of Hydrogen (LCOH) – Techno-Economic & Sensitivity Analysis

## Project Overview

This repository presents a techno-economic assessment of a photovoltaic (PV)-integrated hydrogen energy system developed as part of a master's thesis focusing on renewable hydrogen integration into industrial coffee roasting.

The Excel-based model evaluates the **Levelized Cost of Hydrogen (LCOH)** for four system configurations, considering different hydrogen storage technologies, operating strategies, and economic assumptions.

Technical and operational input data are obtained from **MATLAB/Simulink simulations and energy system optimization results**, providing the basis for cost calculations and sensitivity analyses.

## Objectives

- Evaluate the LCOH across two hydrogen system configurations.
- Calculate annualized capital expenditures (CAPEX) and operating expenditures (OPEX).
- Assess the economic influence of hydrogen storage configurations and system utilization.
- Identify major LCOH cost drivers through One-at-a-Time (OAT) sensitivity analysis.
- Investigate the combined influence of electrolyzer CAPEX and hydrogen storage costs.

## System Configurations

The analysis considers two configurations:

| Case | System Configuration |
|---|---|
| Case 1 | Low-pressure hydrogen storage with demand-matching operation |
| Case 2 | High-pressure hydrogen storage with demand-matching operation |

The system incorporates a PV installation of approximately 60 kWp, hydrogen production through 10 kW PEM electrolysis, and hydrogen storage for industrial energy supply.

## Methodology

### 1. LCOH Calculation

The economic model considers:

- Annualized investment costs for PV, electrolyzer, compressor, and hydrogen storage.
- Operation and maintenance expenditures.
- Grid electricity costs.
- Electrolyzer stack replacement provisions.
- Revenue from surplus PV electricity exported to the grid.
- Annual hydrogen production and hydrogen supplied to the industrial process.

Both gross and net LCOH are evaluated, with net costs accounting for feed-in revenue.

### 2. One-at-a-Time (OAT) Sensitivity Analysis

Individual technical and economic parameters are varied while other parameters remain constant to evaluate their influence on LCOH.

Investigated parameters include electricity costs, component CAPEX, discount rate, component lifetimes, and specific energy consumption.

### 3. Two-Parameter Sensitivity Analysis

A bivariate sensitivity analysis investigates the combined influence of:

- Electrolyzer CAPEX
- Hydrogen storage costs

The results are organized into LCOH matrices suitable for heatmap visualization.


## Excel Workbook Structure

| Worksheet | Description |
|---|---|
| Introduction | Project overview and workbook navigation |
| Economic Assumptions | Technical and economic input parameters |
| Case Inputs | Operational data from simulation and optimization results |
| Annualized Costs | Annualized CAPEX and OPEX calculations |
| LCOH Calculations | Hydrogen cost calculations for four configurations |
| OAT-Sensitivity | Individual parameter sensitivity analysis |
| OAT Scenario Curves | LCOH variation across selected parameter ranges |
| Two-parameters sensitivity | Combined electrolyzer CAPEX and storage cost analysis |

## Tools and Technologies

- **Microsoft Excel:** Financial modelling, LCOH calculations, scenario evaluation, and sensitivity analysis.
- **MATLAB/Simulink:** Dynamic system modelling and technical performance assessment.
- **Mixed-integer Linear Programming (MILP) Optimization:** Operational and energy flow optimization.
- **MATLAB:** Data visualization and sensitivity plotting.

## Model Assumptions and Limitations

The economic assessment is based on defined technical and financial assumptions, including a 20-year project assessment period and a base discount rate of 6%.

Sensitivity analyses evaluate parameter changes around fixed system configurations. Operational optimization is not repeated for each sensitivity scenario.

The results are specific to the investigated industrial application and should not be interpreted as universally applicable hydrogen production costs.

## Project Context

This work forms part of a master's thesis investigating the integration of renewable hydrogen into industrial coffee roasting, combining dynamic simulation, energy system optimization, and techno-economic evaluation.

## Usage

The Excel workbook is provided for academic demonstration, technical review, and portfolio purposes.

The workbook contains model assumptions, calculation formulas, scenario results, and sensitivity analysis data. MATLAB plotting scripts may be used to visualize selected results.

## Author

**Aditi Dhakal**

Master's Thesis Project | Renewable Energy Systems | Hydrogen Technologies | Techno-Economic Analysis
