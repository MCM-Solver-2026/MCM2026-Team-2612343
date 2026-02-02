# Supplementary Materials for MCM 2026 Problem A

Welcome to the official data repository for **Team #2612343**. 
This repository contains the processed datasets and source code supporting our submission for the 2026 Mathematical Contest in Modeling (MCM), Problem A.

## 📂 Repository Structure

The data is organized into two main directories. **Please unzip the files before use.**

### 1. Data for Problem 1 (TTE Prediction Model)
- **Directory**: [`Problem_1_Data/`](./Problem_1_Data)
- **File**: `MCM2026_master_modeling_table.zip` (Compressed)
- **Description**: This ZIP archive contains the **Master Modeling Table** (CSV format). 
    - *Note*: Due to file size limits (>25MB), the dataset is compressed. Please unzip it to access the 36,000-sample synthesized dataset.

### 2. Data for Problem 2 (Scenario & Sensitivity Analysis)
- **Directory**: [`Problem_2_Data/`](./Problem_2_Data)
- **File**: `data2.zip` (Compressed Archive)
- **Description**: This ZIP archive contains **5 distinct CSV datasets** used for sensitivity analysis. 
- **Contents of `data2.zip`**:
    - `Battery_Behavior_by_Capacity.csv`: Discharge curves under different battery capacities.
    - `Battery_Behavior_by_Aging_Level.csv`: Impact of SOH (State of Health) on discharge rates.
    - `Power_Consumption_Profile_by_Scenario.csv`: Breakdown of power draw (CPU, Screen, Network) for different user activities.
    - `SOC_Depletion_by_Scenario.csv`: SOC trajectories over time for various usage scenarios.
    - `SOC_Depletion_by_Temperature.csv`: Battery performance data under varying ambient temperatures.

## 🔗 Data Provenance (Source Attribution)

All datasets in this repository were derived and processed from the following open-source scientific repositories:

1.  **Device Power Consumption**:
    - **Source**: *AndroWatts Dataset* (Zenodo)
    - **DOI**: [10.5281/zenodo.14314943](https://doi.org/10.5281/zenodo.14314943)
    - **License**: CC BY 4.0

2.  **Battery Aging & Degradation**:
    - **Source**: *Battery Degradation Datasets* (Mendeley Data)
    - **DOI**: [10.17632/v8k6bsr6tf.1](https://doi.org/10.17632/v8k6bsr6tf.1)
    - **License**: CC BY 4.0

---
*Note: This repository is intended for academic and competition review purposes only.*
