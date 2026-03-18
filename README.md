# 📊 Predicción de Ventas | Proyecto de Data Science
 
 <img src="https://img.shields.io/badge/Python-555555?style=flat&logo=python&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Jupyter-555555?style=flat&logo=jupyter&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Pandas-555555?style=flat&logo=pandas&logoColor=white"/> 
  <img src="https://img.shields.io/badge/NumPy-555555?style=flat&logo=numpy&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Matplotlib-555555?style=flat"/> 
  <img src="https://img.shields.io/badge/Seaborn-555555?style=flat"/> 
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-555555?style=flat"/>  
  <img src="https://img.shields.io/badge/Statsmodels-Statistical-555555?style=flat"/>  
  <img src="https://img.shields.io/badge/Estado-Completado-555555?style=flat"/>
</p>

**Análisis y Predicción de Ventas en el Rubro Farmacéutico**  
👩‍💻 *Rubis Becerra*


## 🎯 Objetivo

Analizar los factores que explican las ventas (*Sales*) y desarrollar un modelo predictivo aplicable en escenarios reales de negocio.


## 🔍 Principales Insights

- 📉 Distribución de ventas altamente sesgada con presencia de outliers  
- 🌍 Diferencias significativas por país (Alemania lidera en volumen y variabilidad)  
- 🔗 Fuerte correlación: **Sales vs Quantity (r = 0.75)**  
- 🔗 Baja correlación: **Sales vs Price (r = 0.12)**  

👉 Las ventas están impulsadas principalmente por el **volumen**, no por el precio


## 🤖 Enfoque de Modelado

Se evaluaron dos modelos:

- Modelo 1 → Incluye *Quantity*  
- Modelo 2 → Excluye *Quantity*  

### 🧠 Decisión clave

Dado que:

> **Sales = Price × Quantity**

Se selecciona el modelo **sin Quantity** para evitar relaciones mecánicas y asegurar aplicabilidad en predicción ex-ante.


## ⚙️ Modelo Utilizado

- Tipo: Aprendizaje supervisado  
- Problema: Regresión  
- Algoritmo: **Regresión Lineal Múltiple (OLS)**  


## 🧪 Feature Engineering

- One-Hot Encoding (`drop_first=True`)  
- Selección de variables para evitar multicolinealidad y overfitting  
- Filtrado de ventas positivas  
- Transformación logarítmica para tratar asimetría  


## 📈 Performance del Modelo

| Métrica | Train | Test  |
|---------|-------|-------|
| RMSE    | 1.622 | 1.560 |
| MAE     | 1.276 | 1.209 |

✔️ Sin overfitting  
✔️ Buena capacidad de generalización  


## 💡 Impacto de Negocio

- Permite estimar ventas futuras en escenarios reales  
- Identifica los principales drivers del ingreso  
- Facilita la toma de decisiones comerciales  
- Detecta oportunidades de mejora por región  

👉 Modelo diseñado para uso práctico (predicción ex-ante)


## 📬 Contacto

### 💼 Abierta a oportunidades laborales como Analista de Datos, BI Analyst, Reporting Analyst o Power BI Developer.

🔗 LinkedIn: *www.linkedin.com/in/rubis-becerra*



