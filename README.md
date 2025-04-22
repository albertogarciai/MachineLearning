# 🧠 Proyecto de Evaluación - Machine Learning

Este repositorio contiene dos mini-proyectos de aprendizaje supervisado aplicando técnicas de Machine Learning con Python. Cada ejercicio incluye un pipeline completo: exploración de datos, preprocesamiento, modelado, evaluación y visualización.

---

## 📁 Estructura del proyecto

---

## Ejercicio 1: Regresión – Video Game Sales

- **Dataset:** [Video Game Sales](https://www.kaggle.com/datasets/anandshaw2001/video-game-sales)
- **Archivo:** `regresion_videojuegos.py`
- **Objetivo:** Predecir la variable `Global_Sales` a partir de características como el `Genre`, `Platform` y `Year`.

### Pasos:
- Eliminación de valores nulos
- Encoding de variables categóricas (`Platform`, `Genre`)
- Escalado de variables
- Entrenamiento con Regresión Lineal
- Métricas: `MSE` y `R²`
- Visualización de ventas reales vs. predichas

---

## Ejercicio 2: Clasificación – Enfermedad Cardíaca

- **Dataset:** [Heart Disease - UCI](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data)
- **Archivo:** `clasificacion_corazon.py`
- **Objetivo:** Clasificar si un paciente padece una enfermedad cardíaca (binaria).

### Pasos:
- Conversión de la columna `num` en variable binaria `target`
- Limpieza y selección de variables relevantes
- Codificación de variables categóricas (si las hay)
- Escalado de datos
- Modelo: `RandomForestClassifier`
- Métricas: `accuracy`, `precision`, `recall`, `f1-score`
- Visualización: matriz de confusión

---

## 💻 Requisitos

- Python 3.8+
- Librerías necesarias:

```bash
pip install pandas matplotlib seaborn scikit-learn

python regresion_videojuegos.py
python clasificacion_corazon.py
