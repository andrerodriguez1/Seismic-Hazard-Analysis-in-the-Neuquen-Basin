# Análisis de Peligrosidad Sísmica en la Cuenca Neuquina, Argentina

Este repositorio contiene un cuaderno Jupyter que reproduce el análisis de peligrosidad sísmica realizado en la región de la Cuenca Neuquina, Argentina. El estudio se basa en la metodología y resultados presentados en el artículo científico:

**Andrea Beatriz Rodriguez**, Centro Atómico Ezeiza, CNEA, Argentina  

**María Laura Rosa**, Sismología, Facultad de Ciencias Astronómicas y Geofísicas, UNLP

---

## 📌 Objetivo

El objetivo de este proyecto es estimar la peligrosidad sísmica en la Cuenca Neuquina utilizando un enfoque probabilístico. El análisis incluye la compilación del catálogo sísmico, su homogeneización, declustering, caracterización de fuentes sísmicas y el cálculo de mapas de aceleración excedida mediante el software **R-CRISIS**.

---

## 📁 Archivos y estructura

- `seismic_hazard.ipynb`: Cuaderno principal con procesamiento del catálogo, zonificación, curvas de recurrencia y cálculo de peligrosidad.
- `Catalogs/`: Contiene los catálogos sísmicos crudos y procesados.
- `Images/`: Figuras y mapas utilizados en el cuaderno y en el artículo.
- `README.md`: Descripción general del proyecto (versión en inglés).
- `Seismic Hazard Analysis.docx`: Artículo completo con metodología, figuras y resultados.

---

## 🔍 Resumen

- Se construyó un catálogo sísmico con datos públicos y se homogeneizó a magnitud de momento $M_W$.
- Se dividió la región en ocho zonas sismogénicas basadas en criterios geológicos y geofísicos.
- Se calcularon relaciones magnitud–frecuencia para cada zona utilizando la ley de Gutenberg–Richter.
- Se generaron mapas de peligrosidad sísmica para un período de retorno de 475 años, incluyendo:
  - **Aceleración Pico del Terreno (PGA)**
  - **Aceleración Espectral para T = 0.2s y T = 1s**
- Los resultados muestran valores de PGA que van desde **0.14g en el norte** hasta **0.02g en el sureste** de la Cuenca.

---

## 📷 Resultados

Se generaron mapas de peligrosidad sísmica para un período de retorno de 475 años (equivalente a una probabilidad de excedencia del 10% en 50 años). A continuación se muestra una imagen representativa:


<img width="1642" height="2048" alt="PGA" src="https://github.com/user-attachments/assets/395690d9-098e-4ae4-b663-1175ff0c1a8a" />
