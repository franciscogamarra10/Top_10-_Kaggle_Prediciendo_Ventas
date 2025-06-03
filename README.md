# 🔮 Kaggle Challenge: Predicción de Ventas por Tienda 🛒  
## 🏆 SMAPE: **0.43318** — ¡Top 10% en la competencia oficial!

---
## 🎯 Objetivo de la Competencia

En esta competencia de Kaggle, el objetivo es construir un modelo de series temporales para **predecir las ventas unitarias de miles de productos** vendidos en diversas tiendas de *Corporación Favorita*, un importante minorista de comestibles con sede en Ecuador.

Los participantes deben generar pronósticos diarios por tienda y categoría de producto, utilizando variables como fechas, promociones, feriados, y atributos del producto.
### 🧠 Estrategia General

Este notebook implementa un enfoque de predicción de ventas en múltiples etapas:

1. 📊 **Análisis exploratorio** de estacionalidad y lags
2. 🛠️ **Ingeniería de características**: Fourier, fechas, promociones (vía pipeline)
3. 🚫 Primer modelo **sin lags** (no autoregresivo) para entender la importancia de features
4. 🔁 Modelo **autoregresivo** usando lags seleccionados
5. 🚀 Propuestas de mejoras: stacking, nuevas features
