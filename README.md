# TelecomX-Alura-1
Se realizara el Challenge de analisis de datos TelecomX

# Analisis de Evasion de Clientes (Churn) - Telecom X

Este proyecto forma parte del challenge de **Alura Latam** enfocado en Ciencia de Datos. El objetivo principal es analizar e identificar los patrones que llevan a los clientes de una empresa de telecomunicaciones a cancelar sus servicios.

## Objetivo del Proyecto
Identificar factores criticos de abandono y proponer estrategias basadas en datos para mejorar la retencion de clientes, la cual presenta una tasa actual del **26.5%**.

## Herramientas y Tecnologias
* **Lenguaje**: Python 3.x
* **Librerias**: Pandas, Matplotlib, Seaborn
* **Entorno**: Google Colab
* **Hardware de Procesamiento**: AMD Ryzen 7 8700F / 16GB RAM DDR5

## Principales Hallazgos
* **Contratos**: Los clientes con planes "Mes a Mes" representan el mayor volumen de fugas.
* **Metodos de Pago**: El uso de "Electronic Check" esta fuertemente vinculado a la evasion.
* **Factor Precio**: Existe una sensibilidad alta cuando los cargos mensuales superan los 70-80 USD.
* **Periodo Critico**: La mayor probabilidad de abandono ocurre durante el primer mes de servicio.

## Estructura del Repositorio
* `Analisis_Churn_TelecomX.ipynb`: Notebook con todo el proceso de limpieza (ETL), analisis exploratorio (EDA) y conclusiones.
* `Customer-Churn.json`: Dataset original utilizado para el analisis.
