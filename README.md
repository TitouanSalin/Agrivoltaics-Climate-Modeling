# Agrivoltaics in a Climate Model

**Research project — Laboratoire de Météorologie Dynamique (LMD) · Institut Polytechnique de Paris · 2025**

> Modeling the impact of agrivoltaic systems on crop productivity, resource efficiency, and resilience to dry conditions using the ORCHIDEE land-surface model.

## Overview

Agrivoltaics combines agricultural production and photovoltaic energy generation by installing solar panels above crops. Beyond reducing competition for land between agriculture and solar energy, photovoltaic panels modify local environmental conditions — including solar radiation and wind speed — and can therefore affect crop growth, water availability, and nutrient use.

This project investigates these interactions using **ORCHIDEE**, a dynamic vegetation and land-surface model. An agrivoltaic module representing the local effects of photovoltaic panels was coupled with ORCHIDEE to simulate crop–climate interactions over the **Iberian Peninsula from 1991 to 2020**.

The study compares conventional agriculture with agrivoltaic configurations across different nitrogen-input levels and evaluates their effects on:

- crop productivity and seasonal stability;
- nitrogen-use efficiency;
- water stress and water-use efficiency;
- N₂O emissions;
- crop resilience under extreme dry conditions.

## Methodology

The agrivoltaic modeling framework combines a representation of photovoltaic panels with the **ORCHIDEE** vegetation model.

The photovoltaic module modifies the local climatic conditions experienced by crops, particularly **solar radiation and wind speed**, before these variables are provided to ORCHIDEE. The resulting simulations provide diagnostics of vegetation growth, resource use, and ecosystem behavior.

Experiments cover **12 configurations**, including conventional agriculture and agrivoltaic systems with nitrogen-input rates ranging from 0% to 100% of the reference rate. Both **C3 and C4 crops** are evaluated over thirty years of climate conditions across the Iberian Peninsula.

The analysis additionally isolates particularly dry years to investigate whether agrivoltaic systems improve crop resilience under water-limited conditions.

## Key Results

The simulations indicate that agrivoltaic systems substantially modify crop–environment interactions, with particularly strong benefits for **C3 crops** under the conditions studied.

For C3 crops:

- **Agrivoltaics maintains the production level of conventional agriculture with approximately 50% lower nitrogen inputs.**
- Crop production becomes substantially more stable across seasons and years.
- Photovoltaic panels strongly reduce simulated **water stress** and improve water-use efficiency.
- **N₂O emissions are reduced** relative to conventional agriculture at equivalent nitrogen-input levels.
- During identified dry years, agrivoltaic configurations maintain substantially more stable crop production than conventional agriculture.

The effects are generally weaker for C4 crops, highlighting the importance of crop physiology and climatic conditions when assessing the benefits of agrivoltaic systems.

## Research Report

### [Agrivoltaics in a Climate Model](report/Agrivoltaics_in_a_Climate_Model.pdf)

**Inès Bichon · Victor Lemoine · Titouan Salin · Timothée Ruiz — 2025**

The full research report presents the modeling framework, experimental setup, results, and discussion of the study. It includes analyses of agricultural productivity, nitrogen and water resource efficiency, greenhouse-gas emissions, and crop behavior under extreme dry conditions.

## Code Availability

The simulations and analyses were conducted using research code developed and maintained within the **Laboratoire de Météorologie Dynamique (LMD)**.

**The source code belongs to LMD and is not distributed in this repository.** This repository contains the research report describing the methodology, experiments, and results of the project.

## Authors

**Inès Bichon · Victor Lemoine · Titouan Salin · Timothée Ruiz**

Research project conducted with the **Laboratoire de Météorologie Dynamique (LMD)** at **Institut Polytechnique de Paris**.
