# Seismic Hazard Analysis in the Neuquen Basin, Argentina

This repository contains a Jupyter Notebook that reproduces the seismic hazard analysis carried out in the Neuquén Basin region, Argentina. The study is based on the methodology and results presented in the research paper:

**Andrea Beatriz Rodriguez**, Centro Atómico Ezeiza, CNEA, Argentina

**María Laura Rosa**, Sismología, Facultad de Ciencias Astronómicas y Geofísicas, UNLP

## 📌 Objective

The goal of this project is to estimate the seismic hazard in the Neuquén Basin using a probabilistic approach. The analysis includes catalog compilation, homogenization, declustering, seismic source characterization, and the computation of ground motion exceedance maps using the software **R-CRISIS**.

## 📁 Files and Structure

- `seismic_hazard.ipynb`: Main notebook with catalog processing, zoning, recurrence analysis, and hazard calculation.
- `Catalogs/`: Contains raw and processed earthquake catalogs.
- `Imagenes/`: Figures and hazard maps used in the notebook and paper.
- `README.md`: Project description and documentation.
- `Seismic Hazard Analysis.docx`: Full research paper including methodology, figures, and results.

## 🔍 Summary

- A seismic catalog was built from public sources and homogenized to moment magnitude $M_W$.
- The region was divided into eight seismogenic zones based on geological and geophysical criteria.
- Magnitude–frequency relationships were calculated for each zone using the Gutenberg–Richter law.
- Seismic hazard maps were computed for a return period of 475 years, including:
  - **Peak Ground Acceleration (PGA)**
  - **Spectral Acceleration at T = 0.2s and T = 1s**
- Results show PGA values ranging from **0.14g in the north** to **0.02g in the southeast** of the Neuquén Basin.

## 🛠️ Tools and Libraries

* Python (NumPy, Pandas, Matplotlib, etc.)
* ZMAP (for magnitude completeness and recurrence analysis)
* R-CRISIS (for probabilistic seismic hazard computation)
* Microsoft Word (report writing)

## 📌 Key Concepts

* **Probabilistic Seismic Hazard Analysis (PSHA)**
* **Moment Magnitude Homogenization**
* **Declustering of seismic catalogs**
* **Gutenberg-Richter Relationship**
* **Seismogenic Zoning**
* **Ground Motion Prediction Equations (GMPEs)**

## 🔗 Data Sources

* INPRES 
* CSN (Chile)
* OVDAS
* CERESIS
* USGS
* ISC-GEM and ISC-EHB
* IRIS
* SARA Project
* Sielfeld et al. (2019)

## ▶️ How to Run

To reproduce the analysis:

1. Clone the repository: git clone https://github.com/andrerodriguez1/Seismic-Hazard-Analysis-in-the-Neuquen-Basin

2. Open the Jupyter Notebook: jupyter notebook seismic_hazard.ipynb

3. Run each cell in sequence.

## 📜 License

This repository is shared for academic and research purposes. If you use this code or data in your research, please cite the paper below.

## ✏️ Citation

Rodriguez, A. B., & Rosa, M. L. (2025). *Seismic Hazard Analysis in the Neuquén Basin region, Argentina.*

## 🤝 Acknowledgments

Thanks to the following institutions for providing seismic data:
INPRES, CSN, OVDAS, CERESIS, USGS, IRIS, ISC, and others.
Special thanks to the developers of R-CRISIS for making seismic hazard analysis accessible.

