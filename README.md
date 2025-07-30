# Seismic Hazard Analysis in the Neuquen Basin, Argentina

This repository contains a Jupyter Notebook that reproduces the seismic hazard analysis carried out in the Neuquén Basin region, Argentina. The study is based on the methodology and results presented in the research paper:

**Andrea Beatriz Rodriguez**, **María Laura Rosa**
Centro Atómico Ezeiza, CNEA, Argentina
Sismología, Facultad de Ciencias Astronómicas y Geofísicas, UNLP

## 📌 Objective

The goal of this project is to estimate the seismic hazard in the Neuquén Basin using a probabilistic approach. The analysis includes catalog compilation, homogenization, declustering, seismic source characterization, and the computation of ground motion exceedance maps using the software **R-CRISIS**.

## 🔍 Summary

* A seismic catalog was built from public sources and homogenized to moment magnitude $M_W$.
* The region was divided into eight seismogenic zones based on geological and geophysical criteria.
* Magnitude–frequency relationships were calculated for each zone using the Gutenberg–Richter law.
* Seismic hazard maps were computed for a return period of 475 years, including:

  * Peak Ground Acceleration (PGA)
  * Spectral Acceleration at T = 0.2s and T = 1s
* Results show PGA values ranging from 0.14g in the north to 0.02g in the southeast.

## 📊 Files

* `seismic_hazard.ipynb`: Notebook containing the step-by-step implementation of data processing and seismic hazard modeling.
* `Seismic Hazard Analysis.docx`: Full paper including methodology, maps, results, and references.

## 🛠️ Tools and Libraries

* Python (NumPy, Pandas, Matplotlib, etc.)
* ZMAP (for magnitude completeness and recurrence analysis)
* R-CRISIS (for probabilistic seismic hazard computation)

## 📌 Key Concepts

* **Probabilistic Seismic Hazard Analysis (PSHA)**
* **Moment magnitude homogenization**
* **Declustering of seismic catalogs**
* **Gutenberg-Richter recurrence models**
* **Seismogenic zoning**
* **Ground Motion Prediction Equations (GMPEs)**

## 🔗 Data Sources

* INPRES
* CSN (Chile)
* OVDAS
* CERESIS
* USGS
* ISC-GEM
* SARA Project
* Sielfeld et al. (2019)

## 📜 License

This repository is shared for academic and research purposes. Please cite the original paper if using this work in your research.

## ✏️ Citation

Rodriguez, A. B., & Rosa, M. L. (2025). *Seismic Hazard Analysis in the Neuquén Basin region, Argentina.*

## 🤝 Acknowledgments

Thanks to the institutions that provided access to seismic data and to the developers of the R-CRISIS software.

