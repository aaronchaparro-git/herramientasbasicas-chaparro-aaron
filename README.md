# Análisis de E-commerce — Dataset Olist (Brasil)

**Autor:** Aaron Chaparro  
**Curso:** Herramientas Básicas para el Análisis de Datos — UTN  
**Cohorte:** 2026  
**Docente:** Virginia March  

---

## Objetivo

Realizar un análisis end-to-end del e-commerce brasileño utilizando el 
Brazilian E-commerce Public Dataset de Olist, disponible públicamente en 
[Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).

La pregunta central del análisis es: **¿Cuáles son los factores que influyen 
en los tiempos de entrega y la satisfacción del cliente en el e-commerce de Olist?**

---

## Dataset

- **Fuente:** [Brazilian E-commerce Public Dataset — Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- **Período:** 2016–2018
- **Archivos utilizados:** olist_orders_dataset.csv, olist_order_items_dataset.csv, olist_customers_dataset.csv

---

## Pasos realizados

1. **Inspección** — diagnóstico estructural de los datasets: dimensiones, tipos de datos, nulos y duplicados
2. **Limpieza** — conversión de fechas, tratamiento de nulos, normalización de variables geográficas y creación de métrica de tiempo de entrega
3. **Exploración (EDA)** — análisis de volumen temporal, tiempos de entrega, distribución geográfica y precios
4. **Dashboard** — visualización ejecutiva en Power BI con KPIs y panel de filtros

---

## Archivos del repositorio

| Archivo | Descripción |
|---|---|
| [notebook](aaron_herramientas_basicas.ipynb%20-%20Colab.html) | Análisis completo en Python (Colab) |
| [PBI.png](PBI.png) | Captura del dashboard en Power BI |
| [olist_dashboard.csv](olist_dashboard.csv) | Dataset limpio exportado desde Python |

---

## Principales hallazgos

- El volumen de pedidos creció casi **9 veces** entre enero 2017 y enero 2018
- Se detectó un pico de demanda en **noviembre 2017** asociado al Black Friday
- El tiempo promedio de entrega es de **12.1 días**, con casos extremos de hasta 209 días
- **São Paulo** concentra la mayor parte de los pedidos del país

---

## Herramientas utilizadas

Python · pandas · matplotlib · seaborn · Power BI · GitHub

---

## Fuentes

- Olist. (2018). *Brazilian E-Commerce Public Dataset by Olist*. Kaggle. https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce
