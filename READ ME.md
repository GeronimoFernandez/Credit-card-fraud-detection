# Credit Card Fraud Detection

## 🎯 Resultados Clave
- **ROC-AUC: 0.996** - Excelente capacidad discriminativa
- **Recall: 82%** - 8 de cada 10 fraudes detectados
- **Precisión: 63%** - 6 de cada 10 alertas son fraudes reales
- **Validación Cruzada: 0.9948 (±0.0014)**

## 📊 Modelos Evaluados
| Modelo | ROC-AUC | Recall | Precisión | F1-Score |
|--------|---------|--------|-----------|----------|
| Logistic Regression | 0.913 | 0.76 | 0.04 | 0.07 |
| Random Forest | 0.939 | 0.77 | 0.12 | 0.21 |
| XGBoost (umbral 0.5) | 0.996 | 0.97 | 0.19 | 0.32 |
| **XGBoost (umbral 0.9)** | **0.996** | **0.82** | **0.63** | **0.71** |

## 🛠️ Tecnologías
- Python 3.12
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn

## 📁 Estructura del Proyecto
Credit_Card_Fraud_Detection/
├── data/ # Datos raw y procesados
├── notebooks/ # Jupyter notebooks
├── images/ # Visualizaciones
├── reports/ # PDF final
├── README.md
└── requirements.txt


## 👤 Autor
**Geronimo Fernandez** - Data Scientist

## 📄 Licencia
MIT