# ONE-Challenge-3
Challenge Telecom X: análisis de evasión de clientes

# 📊 Proyecto: Análisis de Evasión de Clientes (Churn) en Telecom X

## 🎯 Propósito del Análisis

El objetivo de este proyecto es analizar el problema de la **evasión de clientes** (`Churn`) en la empresa de telecomunicaciones **Telecom X**. A través del **Análisis Exploratorio de Datos (EDA)**, se busca identificar los factores clave que influyen en la decisión de los clientes de cancelar sus servicios. Los `insights` obtenidos servirán como base para desarrollar **estrategias de retención** más efectivas y para la creación de futuros modelos predictivos.

## 📂 Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

* `TelecomX_Data.json`: Archivo de datos original, utilizado como fuente de información a través de una API.
* `README.md`: Este archivo, que proporciona una descripción general del proyecto, su propósito e instrucciones.
* `notebooks/`: Directorio que contiene el `notebook` de Jupyter con todo el código y el análisis.
    * `Challenge Telecom X 1.ipynb.ipynb`: El `notebook` principal que contiene los pasos de **Extracción, Transformación y Carga (ETL)**, el análisis exploratorio y el informe final.

## 📈 Gráficos e Insights Clave

A continuación, se presentan algunos de los gráficos e `insights` más relevantes obtenidos durante el análisis:

### **Distribución de Churn**
La evasión es un problema significativo, con una tasa del 25.4% de los clientes que han cancelado sus servicios.

<img width="609" height="471" alt="image" src="https://github.com/user-attachments/assets/71d8474e-12e4-454f-a614-6b45a65d8689" />


### **Evasión por Tipo de Contrato**
El **tipo de contrato** es el factor más influyente. Los clientes con contratos **"Month-to-month"** tienen una tasa de `churn` extremadamente alta, lo que indica un bajo nivel de compromiso.

<img width="704" height="623" alt="image" src="https://github.com/user-attachments/assets/13a45efb-f566-48f0-b873-0dd58f72674f" />


### **Impacto de la Permanencia**
Existe una correlación directa entre el tiempo de permanencia y el `churn`. Los clientes que evaden tienen una **permanencia mucho más corta** en la compañía, lo que sugiere que el riesgo de abandono es mayor en los primeros meses.

---
