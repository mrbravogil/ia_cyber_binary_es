# De Flujos de Red a Alertas SIEM  
### *Detección de Intrusiones con Random Forest en CICIDS2017*



### Descripción

Este proyecto implementa un **sistema de detección de intrusiones basado en machine learning** utilizando un clasificador **Random Forest** entrenado sobre el dataset **CICIDS2017**.  
El objetivo es clasificar tráfico de red como **Benign** o **Attack**, simulando un escenario práctico orientado a entornos **SIEM**.


### Objetivo

- Construir un **clasificador binario reproducible**
- Distinguir tráfico malicioso de tráfico legítimo
- Evaluar el modelo con métricas adecuadas para datos desbalanceados



### Dataset

- **CICIDS2017** – Canadian Institute for Cybersecurity  
- Tráfico realista de red corporativa con ataques como:
  - DoS / DDoS  
  - PortScan  
  - Web Attacks  
  - Infiltration  
  - Botnet  



### Metodología

- Análisis exploratorio de datos (EDA)
- Preprocesamiento y selección de variables
- Entrenamiento de un modelo Random Forest
- Evaluación con Accuracy, Precision, Recall, F1-score y PR-AUC
- Análisis de *feature importance*
- Predicción mediante `predict` y `predict_proba`



### Resultados

- Pipeline binario reproducible (Attack vs Benign)
- Buen rendimiento en detección de ataques
- Reducción de complejidad manteniendo la eficacia del modelo
- Uso de probabilidades para ajuste de umbrales en escenarios SIEM


### Vías de desarrollo futuras

- Validación cruzada
- Evaluación por tipo de ataque
- Optimización de umbrales de decisión
- Pruebas con tráfico real


**Nota:** Este proyecto es una prueba de concepto.  
El rendimiento puede variar en escenarios reales debido a cambios en la distribución del tráfico y a nuevos patrones de ataque.
