# 🩺 Heart Rate Variability (HRV) Analysis using NIFEA DB

A Python implementation analyzing autonomic dysfunction using the NIFEA database (Non-Invasive Fetal ECG Arrhythmia Database).

## 🔍 Project Overview

This project utilizes PhysioNet's [NIFEA DB 1.0.0](https://physionet.org/content/nifeadb/1.0.0/) to compare HRV patterns between normal and arrhythmic fetal ECG recordings.

### 🎯 Key Features:
- **Dataset:** [NIFEA DB](https://physionet.org/content/nifeadb/1.0.0/) (Non-Invasive Fetal ECG Arrhythmia Database)
  - 12-lead abdominal ECG recordings
  - 58 subjects (normal and arrhythmic cases)
  - Sampling frequency: 1kHz
  - Includes expert annotations
- **Processing Pipeline:**
  - RR interval correction (artifact removal)
  - HRV feature extraction
- **Analysis Focus:**
  - Time-domain: SDNN, RMSSD
  - Frequency-domain: LF/HF power ratios