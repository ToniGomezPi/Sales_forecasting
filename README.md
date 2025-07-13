# 🧠 M5 Demand Forecasting – Predicción de Demanda de Productos

Este proyecto utiliza el dataset de Kaggle "M5 Forecasting - Accuracy" para construir un modelo de predicción de demanda de productos minoristas.

## 🎯 Objetivo

Predecir las ventas futuras por producto y tienda a partir de datos históricos de ventas, precios y calendario.

## 📁 Estructura del Proyecto

```txt
m5-demand-prediction/
├── data/
│   ├── raw/           # Datos originales del dataset M5
│   └── processed/     # Datos listos para modelado
├── notebooks/         # Análisis exploratorio, features, modelos
├── models/            # Modelos entrenados (.pkl, .pt)
├── src/               # Scripts de limpieza, entrenamiento, predicción
├── README.md
└── requirements.txt
```

## ⚙️ Tecnologías

- Python 3.10+
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- PyTorch
- PySpark

## 🗂️ Dataset

- `calendar.csv`
- `sales_train_validation.csv`
- `sell_prices.csv`
- `sample_submission.csv`

Dataset original disponible en: https://www.kaggle.com/competitions/m5-forecasting-accuracy

## 📅 Progreso

- [x] Preparación de entorno
- [ ] Exploración inicial de datos
- [ ] Ingeniería de características
- [ ] Modelado con scikit-learn
- [ ] Modelado con PyTorch
- [ ] Inferencia y visualización de resultados
- [ ] Documentación final
