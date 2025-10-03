# Demand Prediction – Sika Colombia

Repositorio de tesis de Maestría en Ciencia de Datos:  
**Forecasting de demanda a nivel SKU en Sika Colombia (2019–2026)**  
usando modelos estadísticos (SARIMA) y de Machine Learning (LSTM).

---

## Objetivos
- Elevar el *forecast accuracy* de ~70% a >80%.  
- Comparar modelos SARIMA vs LSTM en distintos patrones de demanda.  
- Medir mejoras reales mediante *Forecast Value Added (FVA)*.  

---

## Estructura del repositorio
- `data/` → datos crudos y procesados (no sensibles).  
- `notebooks/` → notebooks de exploración, modelado y comparación.  
- `src/` → funciones y módulos reutilizables (SARIMA, LSTM, métricas).  
- `scripts/` → entrenamiento y evaluación automatizada.  
- `results/` → gráficos y métricas.  
- `docs/` → artículos, referencias y extended abstract.  
- `presentations/` → presentaciones de la tesis.  

---

## Uso
```bash
pip install -r requirements.txt
jupyter notebook notebooks/01_exploracion.ipynb
