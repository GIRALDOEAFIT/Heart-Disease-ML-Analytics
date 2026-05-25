# Predicción de Enfermedad Cardíaca mediante Machine Learning

Proyecto final de Analítica de Negocios – Universidad EAFIT.

Este proyecto aplica técnicas de Machine Learning para analizar variables clínicas y predecir enfermedad cardíaca utilizando el UCI Heart Disease Dataset.

---

# Objetivos del proyecto

- Clasificar pacientes con y sin enfermedad cardíaca.
- Identificar variables clínicas relevantes.
- Evaluar modelos de pronóstico utilizando redes neuronales.
- Analizar limitaciones y consideraciones éticas del uso de IA en salud.

---

# Dataset utilizado

## UCI Heart Disease Dataset – versión combinada

Características principales:

- 920 registros clínicos.
- 15 variables.
- Clasificación binaria.
- Datos provenientes de:
  - Cleveland Clinic
  - Hungary Institute of Cardiology
  - V.A Medical Center
  - University Hospital Zurich

Archivo utilizado:

heart_disease_combined.csv

---

# Modelos implementados

## 1. Random Forest Classifier

Modelo principal de clasificación para detectar presencia de enfermedad cardíaca.

### Resultados principales

| Métrica | Resultado |
|---|---|
| Accuracy | 0.8424 |
| F1 Score | 0.8612 |
| Recall | 0.8824 |
| AUC | 0.9201 |

---

## 2. MLPRegressor

Modelo de redes neuronales utilizado para pronóstico de variables clínicas.

### Resultados finales

| Variable objetivo | MAE | RMSE | R² |
|---|---|---|---|
| chol | 43.4284 | 55.3219 | -0.1298 |
| thalach | 18.6394 | 23.7781 | 0.1779 |

---

# Principales hallazgos

- Random Forest fue el modelo más sólido del proyecto.
- El dataset funciona mejor para clasificación que para pronóstico.
- La selección de la variable objetivo impacta directamente el desempeño del modelo.
- Las variables clínicas sí permiten identificar patrones de riesgo cardiovascular.

---

# Video de presentación

El video explicativo y demostración del proyecto puede visualizarse en el siguiente enlace:

[Ver presentación en YouTube](https://youtu.be/CdZ5CP8PfAg)

---

# Archivos del repositorio

| Archivo | Descripción |
|---|---|
| Proyecto_Final_Heart_Disease_Colab_Portafolio.ipynb | Notebook principal |
| heart_disease_combined.csv | Dataset |
| diapositivas.pdf | Presentación final |

---

# Tecnologías utilizadas

- Python
- Google Colab
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- GitHub

---

# Integrantes

- Samuel David Giraldo Gil
- Jacobo Hinestroza Escobar

---

# Universidad EAFIT

Analítica de Negocios – 2026
