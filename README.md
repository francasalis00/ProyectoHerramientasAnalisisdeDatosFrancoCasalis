# 📊 Análisis de Ventas Online Retail

**Autor:** Franco Casalis  
**Curso:** Herramientas para el análisis de datos  
 

---

## 🎯 Objetivo

El objetivo de este proyecto es analizar un dataset de ventas online para comprender el comportamiento de los ingresos, identificar patrones de venta y determinar qué productos y países tienen mayor impacto en los resultados.

---

## 📦 Dataset

Se utilizó el dataset *Online Retail*, que contiene información sobre transacciones reales de una tienda online, incluyendo productos, cantidades, precios, fechas y países.

Fuente:  
https://archive.ics.uci.edu/dataset/352/online+retail

---

## 🛠️ Proceso realizado

El análisis se desarrolló en Python utilizando la librería pandas. En primer lugar, se realizó la carga y exploración inicial del dataset. Luego se llevó a cabo la limpieza de datos, eliminando valores nulos relevantes, registros duplicados y valores negativos en las variables de cantidad y precio.

Posteriormente, se creó la variable *revenue* para calcular los ingresos a partir de la cantidad y el precio unitario. A partir de estos datos se realizó un análisis exploratorio (EDA), generando visualizaciones para entender la evolución de las ventas en el tiempo, el comportamiento por país y los productos más relevantes.

Finalmente, se desarrolló un dashboard en Power BI para presentar los principales resultados de forma visual e interactiva.

---

## 📊 Estructura del repositorio

- `/data/`: dataset utilizado en el análisis o enlace a la fuente  
- `/notebook/`: notebook con el análisis exploratorio en Python  
- `/dashboard/`: archivo de Power BI (.pbix) y visualización en imagen  

---

## 🔗 Archivos

- Notebook:  
https://github.com/francasalis00/ProyectoHerramientasAnalisisdeDatosFrancoCasalis
/blob/main/notebooks/herramientasbasicas_FrancoCasalis.ipynb  

- Dataset fuente:  
https://archive.ics.uci.edu/dataset/352/online+retail  

- Dashboard (Power BI):  
https://github.com/francasalis00/ProyectoHerramientasAnalisisdeDatosFrancoCasalis
/blob/main/dashboard/dashboard_ventas.pbix  

- Vista previa del dashboard:  
![Dashboard](<img width="746" height="432" alt="Captura de pantalla 2026-04-21 193851" src="https://github.com/user-attachments/assets/dfd6daad-38d8-42ae-b275-a434c92d9a65" />
)

---

## 💡 Conclusiones

El análisis muestra que las ventas presentan variaciones a lo largo del tiempo, con picos en determinados períodos. Además, se observa que el Reino Unido concentra la mayor parte de los ingresos, mientras que un grupo reducido de productos genera la mayor proporción de ventas.

---

## 📚 Referencias

- Online Retail Dataset: https://archive.ics.uci.edu/dataset/352/online+retail  
- Documentación pandas: https://pandas.pydata.org/  


 
