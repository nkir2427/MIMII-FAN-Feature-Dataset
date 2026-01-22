# MIMII FAN Feature Dataset

## Overview
This repository contains a numerical feature dataset derived from the **MIMII Fan audio dataset**. The original `.wav` waveform files were processed to extract numerical features for use in machine learning–based anomaly detection experiments.

The dataset was generated as part of an academic research study and is intended to support reproducibility and further research in audio-based anomaly detection.

---

## Dataset Description
- **Source dataset:** MIMII Fan Sound Dataset  (https://zenodo.org/records/3384388)
- **Original data format:** `.wav` audio files  
- **Derived data format:** Numerical feature representations  
- **Feature extraction:** MATLAB-based signal processing and feature extraction scripts  
- **Use case:** Machine learning and anomaly detection research  

The extracted features were used in experimental evaluations reported in an academic publication.

---

## Folder Structure
```text
data/
├── -6dB/          # Extracted numerical feature datasets under SNR -6dB
├──  0dB/          # Extracted numerical feature datasets under SNR 0dB
├──  6db           # Extracted numerical feature datasets under SNR 6dB
├── matlab/        # MATLAB scripts used for feature extraction
└── README.md
