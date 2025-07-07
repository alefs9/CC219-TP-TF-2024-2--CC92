# Clasificador Automático de Tickets de Soporte

## 🎯 Objetivo del Proyecto

Este proyecto tiene como objetivo principal desarrollar e implementar un sistema de **clasificación automática de tickets de soporte al cliente** utilizando técnicas de **Procesamiento de Lenguaje Natural (NLP)** y **Machine Learning**.

El sistema busca identificar de manera eficiente si un ticket es **"Urgente"** o **"No Urgente"** basándose en el contenido de su descripción. Esto permite:

* Optimizar los tiempos de respuesta
* Mejorar la eficiencia operativa
* Aumentar la satisfacción del cliente

El enfoque está orientado a entornos de **retail y e-commerce**.


## 👥 Participantes

* **Alexandra Fong Saravia** - U202216001
* **Carlos Alejandro Molina Huatuco** - U20211G139
* **Ian Joaquin Sanchez Alva** - U202124676


## 📂 Descripción del Dataset

Se utilizó el **Customer Support Ticket Dataset** disponible en Kaggle, que contiene **8,469 registros** simulando tickets reales de soporte.

Este dataset incluye información relevante como:

* Tipo de ticket
* Canal de ingreso
* Descripción del problema
* Prioridad asignada


## 📊 Conclusiones

Luego de aplicar técnicas de **limpieza de datos** y **vectorización de texto** mediante **TF-IDF**, se evaluaron los siguientes modelos de machine learning:

* **Regresión Logística**
* **SVM (Lineal)**
* **Random Forest**
* **XGBoost**

### 🏆 Resultados

Todos los modelos alcanzaron un rendimiento excepcional, superando el **98% de exactitud**.

El modelo **XGBoost** se destacó como la **mejor solución**:

* **Recall (clase "Urgente")**: 0.992
* **F1-Score**: 0.992

Su **alta capacidad para minimizar falsos negativos** —crítico en contextos de soporte urgente— lo posiciona como el modelo más **fiable y robusto para producción**.



