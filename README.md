# 📊 Telco Churn Analysis: De Datos a Estrategia de Retención

**Autor:** Ezequiel Brunet  
**Herramientas:** Python (Pandas, NumPy, Matplotlib, Seaborn)  

## 🎯 El Problema de Negocio
Retener a un cliente existente cuesta entre 5 y 7 veces menos que adquirir uno nuevo. En este proyecto analicé un dataset de +7.000 clientes de una empresa de telecomunicaciones para identificar los factores de riesgo que impulsan el abandono (churn) y proponer una estrategia de retención basada en datos, cuantificando su impacto económico.

## 💡 Hallazgos Clave
Tras la limpieza de datos y el análisis exploratorio (EDA), descubrí que el problema no es únicamente el precio, sino la percepción de soporte y el tipo de compromiso:

* **El impacto en el tipo de contrato:** El **43%** de los clientes con contrato mensual abandona el servicio, frente a un churn casi nulo en contratos anuales.
* **El primer año es clave:** La mayor fuga se concentra en los primeros **12 meses** de vida del cliente.
* **El problema oculto (Tech Support):** En usuarios de Fibra Óptica, no tener soporte técnico eleva el abandono al **50%**. Tenerlo lo reduce drásticamente al 23%.

## 🚀 Impacto y Recomendación Accionable
Los datos muestran que la combinación de **Fibra Óptica + Contrato Mensual + Sin Soporte Técnico** es el perfil de mayor riesgo. 

**Estrategia propuesta:** Ofrecer soporte técnico bonificado o con descuento a clientes de fibra óptica durante su primer año. 
* **Retorno estimado:** Esta acción focalizada tiene el potencial de retener a ~300 clientes en riesgo, salvando más de **$311,600 USD anuales** en ingresos perdidos.

## 📂 Estructura del Proyecto
* `Proyecto_Churn.ipynb`: Notebook principal con la limpieza de datos, EDA, validación de hipótesis y cálculo de impacto económico.
* `Archivo.csv`: Dataset original utilizado para el análisis.

---
*Puedes ver el código completo y las visualizaciones abriendo el archivo .ipynb en este repositorio.*
