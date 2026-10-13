# CIC-IDS2017 — Exploratory Data Analysis

## Overview
This project performs Exploratory Data Analysis (EDA) on the cleaned Tuesday Working Hours subset of the CIC-IDS2017 network intrusion detection dataset.

## Objectives
- Analyze network traffic using descriptive statistics.
- Visualize traffic class distribution and numerical feature patterns.
- Investigate flow duration and packet-length characteristics.
- Examine correlations between numerical features.
- Identify at least five insights that could influence machine-learning models or security decisions.

## Dataset
- **Dataset:** CIC-IDS2017
- **File:** Tuesday Working Hours
- **Records:** 421,626
- **Columns:** 79
- **Traffic classes:** BENIGN, FTP-Patator, SSH-Patator

The original dataset is available from the https://www.unb.ca/cic/datasets/ids-2017.html .

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Analysis Performed
- Descriptive statistical analysis
- Traffic class distribution
- Flow duration analysis
- Forward packet-length analysis
- Correlation analysis

## Key Findings
The dataset contains a substantial imbalance between benign and attack traffic. Additional findings on flow duration, packet lengths, extreme values, and feature correlations are documented in the notebook and should be interpreted using the observed results.

## Future Work
The analysis will support further investigation into network traffic patterns and machine-learning-based intrusion detection.
