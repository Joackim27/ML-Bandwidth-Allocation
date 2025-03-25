# AI-Based Bandwidth Allocation for Optimized Network Traffic

This repository demonstrates how to build a **Random Forest Regressor** to predict optimal `Resource_Allocation` (as a percentage) given various QoS metrics such as `Latency`, `Signal_Strength`, and `Allocated_Bandwidth`. The project also includes a **SHAP**-based interpretability module to understand how each feature influences the predicted resource allocation.

---

## Overview

With the exponential growth in network demands, **dynamic bandwidth allocation** is crucial. This project builds a machine learning model to **automate** resource allocation decisions by predicting the percentage of bandwidth or other resources to allocate under different network conditions.

**Key Features**:
- **Latency (ms)**  
- **Signal_Strength (dBm)**  
- **Allocated_Bandwidth (Mbps)**

**Target**:
- **Resource_Allocation** (a float percentage from 0–100)

---

## Dataset

1. **Source**:(https://www.kaggle.com/datasets/omarsobhy14/5g-quality-of-service)
2. **Columns**:
   - `Timestamp`
   - `User_ID`
   - `Latency` (ms)
   - `Signal_Strength` (dBm)
   - `Allocated_Bandwidth` (Mbps and Kbps)
   - `Resource_Allocation` (%)

## Methodology
- shown in workflow.io