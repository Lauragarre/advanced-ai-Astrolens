# AstroLens: Explorador Inteligente del Universo con Visión Artificial

**Objetivo:** Clasificar imágenes astronómicas (galaxias, estrellas, nebulosas) con Deep Learning usando el dataset **Galaxy10 DECaLS** y establecer una base para ampliar con detección y clustering.

## 🚀 Quickstart (Colab recomendado)
1. Abre este repo en Google Colab y ejecuta el notebook `notebooks/01_EDA_preprocessing_and_CNN.ipynb`.
2. El dataset **Galaxy10 DECaLS** se descargará automáticamente vía `astroNN` la primera vez que ejecutes el notebook.
3. Revisa la sección de _Resultados preliminares_ al final del notebook (accuracy y ejemplos de predicción).

## 📦 Estructura
```
AstroLens/
├─ notebooks/
│  └─ 01_EDA_preprocessing_and_CNN.ipynb
├─ data/           # (opcional) materiales locales
├─ models/         # modelos guardados
├─ technical_report.md
├─ requirements.txt
└─ README.md
```

## 🧰 Dependencias principales
- TensorFlow (Keras)
- astroNN (para descargar Galaxy10 DECaLS fácilmente)
- numpy, pandas, matplotlib, scikit-learn

Instalación local (opcional):
```bash
pip install -r requirements.txt
```

## 🧪 Próximos pasos (para la versión de presentación)
- Extraer _embeddings_ de la CNN y aplicar **KMeans** para clustering.
- Probar **YOLO/DETR** para detección (opcional).
- Generar descripciones con un **LLM** (opcional).
- Añadir una demo con **Streamlit** (opcional).
# advanced-ai-Astrolens
