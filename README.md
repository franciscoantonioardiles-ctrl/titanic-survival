# 🚢 Titanic Survival Prediction

<a href="https://franciscoantonioardiles-ctrl.github.io/titanic-survival/" target="_blank">
  <img src="https://img.shields.io/badge/🚀%20Ver%20Dashboard%20Interactivo-58a6ff?style=for-the-badge"/>
</a>

## Autor
**Francisco Ardiles Miranda**  
Analista de Datos Profesional Junior · Certificado Google  
[GitHub](https://github.com/franciscoantonioardiles-ctrl)

## Descripcion
Prediccion de supervivencia de pasajeros del Titanic usando **Machine Learning y Deep Learning** con 5-Fold Cross-Validation. Primer proyecto de la serie de Data Science en Kaggle.

## Resultados
| Modelo | AUC | F1-Score |
|---|---|---|
| Red Neuronal 5-Fold CV | **0.884** | 0.795 |
| Random Forest baseline | 0.87 | — |
| Baseline (solo mujeres) | 0.765 | — |

## Hallazgos Clave
- **Sex** es la variable mas importante: mujeres tuvieron 3x mas probabilidad de sobrevivir
- **1a Clase** tuvo tasa de supervivencia del doble que 3a Clase
- **Feature Engineering** aporta +11 puntos de AUC sobre el baseline
- Bug corregido: `RobustScaler` en Fare evita val_loss explosivo en entrenamiento

## Contenido
| Archivo | Descripcion |
|---|---|
| `titanic_notebook.ipynb` | Pipeline completo mejorado con celdas markdown |
| `titanic_report.pdf` | Reporte con 6 graficos y analisis completo |
| `index.html` | Dashboard interactivo |

## Stack Tecnologico
Python · pandas · scikit-learn · TensorFlow/Keras · matplotlib · seaborn
