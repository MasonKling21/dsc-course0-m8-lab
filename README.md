# Aviation Safety Analysis

An exploratory data analysis of aviation accident data, focused on understanding what factors contribute to fatal and serious injuries across different aircraft types.

## Overview

The lab covers two main phases: data cleaning and exploratory analysis. The cleaned dataset was used to compute a **Fatal/Serious Rate (FSR)** — the fraction of people onboard who were killed or seriously injured — as the primary metric throughout.

## Data Cleaning

- Handled missing values and standardized column formats
- Derived key columns: `Total.Onboard`, `Fatal.Serious.Count`, and `Fatal.Serious.Rate`
- Split the data into **small planes** (<20 onboard) and **large planes** (≥20 onboard) for separate analysis

## Analysis

**Aircraft Make**
- Filtered to makes with at least 10 incidents to ensure reliable averages
- Compared mean FSR across makes for both small and large planes
- For small planes, focused on the 10 safest makes by mean FSR
- Visualized using bar charts and violin plots

**Weather & Engine Type**
- Compared FSR across weather conditions (VMC vs IMC)
- Compared FSR across engine types (reciprocating, turbofan, etc.)
- IMC conditions and certain engine types showed notably higher injury rates