# TelecomX LATAM - Análisis de Fidelización y Abandono de Clientes

## 🧠 Objetivo del Proyecto
Este proyecto tiene como objetivo analizar el comportamiento de los clientes de una empresa de telecomunicaciones en América Latina, enfocándose en la **fidelización y abandono**.  
Se busca identificar qué factores (contrato, método de pago, tipo de servicio de internet, soporte técnico, situación familiar, edad, entre otros) influyen en la permanencia o abandono del servicio.

## 📊 Metodología
Se emplea un **Análisis Exploratorio de Datos (EDA)** para comprender la distribución y relación entre las variables categóricas y numéricas con la variable objetivo (`Churn`).  
Se utilizan técnicas de visualización, incluyendo:  
- **Gráficos de barras y pastel** para distribución de categorías.  
- **Boxplots** y **violin plots** para comparar variables numéricas según fidelización.  
- **Heatmaps** para identificar combinaciones de factores de riesgo.  

## 🔧 Herramientas y Tecnologías
- **Python**: Lenguaje de programación principal.  
- **Pandas**: Manipulación y análisis de datos.  
- **Matplotlib y Seaborn**: Visualización de datos.  
- **Jupyter Notebook / Google Colab**: Entorno interactivo para ejecutar el análisis.  

## 📁 Estructura del Proyecto
- **Notebook principal (`TelecomX_Analisis.ipynb`)**: Contiene el análisis completo, gráficos y conclusiones.  
- **Conjunto de datos (`TelecomX_Data.json`)**: Datos utilizados para el análisis.  
- **Diccionario de datos (`TelecomX_diccionario.md`)**: Descripción de las variables presentes en el dataset.  

## 🔍 Conclusiones Principales
- Los **contratos mensuales** y el **pago por cheque electrónico** presentan mayor abandono.  
- La **Fibra Óptica** es el servicio de internet con mayor riesgo de abandono, especialmente sin soporte técnico.  
- La presencia de **pareja o dependientes** disminuye la probabilidad de abandono.  
- Los clientes que pagan **más al mes** pero con **menos tiempo en la empresa** tienen mayor riesgo de abandono.  
- La implementación de **soporte técnico** y estrategias de fidelización tempranas son clave para reducir la evasión.  

## 💡 Recomendaciones
1. Incentivar contratos más largos para nuevos clientes.  
2. Promocionar soporte técnico para clientes de alto riesgo.  
3. Crear planes especiales para clientes con Fibra Óptica y Cheque Electrónico.  
4. Monitorear y fidelizar a los clientes durante los primeros meses de servicio.  
5. Implementar estrategias de engagement familiar para clientes con pareja o dependientes.
