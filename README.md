# UNICIENCIAS_G-03_Mineria_Datos

## Segmentación de Pacientes para Predicción de Diabetes Tipo 2

Proyecto académico del grupo **G-03** enfocado en la aplicación del proceso KDD, análisis exploratorio de datos, reducción de dimensionalidad y aprendizaje no supervisado sobre el dataset **Pima Indians Diabetes Dataset**.

El objetivo principal es analizar patrones clínicos asociados con diabetes tipo 2 y segmentar pacientes mediante técnicas exploratorias como **PCA** y **k-Means**, usando principalmente **Orange Data Mining** y un notebook en Python como soporte reproducible de los gráficos.

---

### Integrante

- Daniel Mauricio Castro Yaruro

---

### Dataset

Se utilizó el dataset **Pima Indians Diabetes Dataset**, disponible en Kaggle y referenciado originalmente por el National Institute of Diabetes and Digestive and Kidney Diseases.

El dataset contiene información clínica de pacientes mujeres de origen Pima e incluye las siguientes variables:

| Variable | Descripción |
|---|---|
| `Pregnancies` | Número de embarazos |
| `Glucose` | Concentración de glucosa |
| `BloodPressure` | Presión arterial diastólica |
| `SkinThickness` | Espesor del pliegue cutáneo |
| `Insulin` | Nivel de insulina |
| `BMI` | Índice de masa corporal |
| `DiabetesPedigreeFunction` | Historial familiar de diabetes |
| `Age` | Edad |
| `Outcome` | Diagnóstico: 1 = diabético, 0 = no diabético |

---

### Estructura del repositorio

```text
.
├── notebooks/
│   └── G03_FaseB_EDA_PCA_KMeans_Notebook.ipynb
│
├── orange_files/
│   ├── FaseA/
│   │   └── diabetes.ows
│   │
│   └── FaseB/
│       └── diabetes_faseB_template.ows
│
├── README.md
└── LICENSE
