
# 3D Left Ventricle Visualization and Shape Analysis using PCA

This repository contains MATLAB-based code and results from my research internship at **IIT BHU (May–July 2025)**. The goal was to model and analyze the 3D shape of the human heart's left ventricle (LV) using **Principal Component Analysis (PCA)**.

## 🔬 Project Overview

Traditional metrics like mass and volume often miss early cardiac shape changes. This project focuses on:
- Visualizing the end-diastole and end-systole phases
- Generating STL files for simulation and 3D printing
- Analyzing shape variability using PCA

## 🧰 Tools & Dataset

- **Data Source**: [Cardiac Atlas Project (CAP)](https://github.com/CardiacAtlasProject/PCATool)
- **Software**: MATLAB Online + PCATool
- **Dataset**: MESA study cardiac MRI
- **Key Files**:
  - `PCA_ED.mat` – End-diastole PCA model
  - `PCA_ES.mat` – End-systole PCA model
  - `SurfaceFaces.mat` – 3D triangle mesh

## 📂 Folder Description

- `data/`: Raw PCA and mesh data files
- `scripts/`: MATLAB code to visualize and export STL models
- `results/`: Exported STL files for 3D visualization/printing
- `report/`: Internship report PDF

## 📊 Output

- 3D LV model at End-Diastole and End-Systole
- STL files for CAD/3D printing applications

## 📘 Report

See full technical documentation in [Internship_Report.pdf](./report/Internship_Report.pdf)

## ✨ Learnings

- PCA application in biomedical shape modeling
- MATLAB 3D plotting, STL generation
- Medical imaging data handling

## 📄 License

This project is shared under the MIT License. See [LICENSE](./LICENSE) for details.
