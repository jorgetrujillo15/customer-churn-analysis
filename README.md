📊 Predicción y Segmentación de Cancelación de Clientes – Gimnasio

--------------------------------------------------------------

📌 Descripción del Proyecto

Este proyecto analiza el comportamiento de los clientes de un gimnasio con el objetivo de:

* Predecir la cancelación (churn)

* Identificar patrones asociados al abandono

* Segmentar clientes según su comportamiento

* Proponer recomendaciones estratégicas basadas en datos

Se combinan técnicas de análisis exploratorio (EDA), modelado predictivo y clustering para entender los factores que influyen en la retención.

--------------------------------------------------------------

🎯 Objetivos

* Identificar las variables más relacionadas con la cancelación

* Construir modelos predictivos de churn

* Segmentar clientes en grupos con características similares

* Traducir los hallazgos en acciones de negocio

--------------------------------------------------------------

🗂 Dataset

El dataset incluye información sobre:

* Datos demográficos (edad, género)

* Información contractual (duración del contrato, tipo de pago)

* Métricas de uso (frecuencia de asistencia, visitas)

* Antigüedad del cliente (lifetime)

* Variable objetivo: Churn (1 = Canceló, 0 = Activo)

--------------------------------------------------------------

🔎 Metodología

1️⃣ Análisis Exploratorio (EDA)

* Análisis de distribuciones

* Matriz de correlación

* Comparación entre clientes activos y cancelados

* Identificación de variables clave

2️⃣ Modelado Predictivo

* Regresión Logística

* Random Forest

* Evaluación mediante:

    * Accuracy

    * Precision

    * Recall

    * ROC-AUC

3️⃣ Segmentación de Clientes

* Estandarización de variables

* K-Means Clustering

* Perfilamiento de clústeres

* Visualización con boxplots

--------------------------------------------------------------

📈 Principales Hallazgos

* La baja frecuencia reciente de asistencia es el principal indicador de cancelación.

* Los contratos de corta duración están asociados a mayor churn.

* Los contratos largos reducen significativamente la probabilidad de cancelación.

* Las variables de comportamiento son más determinantes que las demográficas.

El análisis de clústeres permitió identificar:

* Un segmento estable con alta asistencia y baja cancelación.

* Un segmento de alto riesgo con baja frecuencia y contratos cortos.

* Clientes en transición con señales tempranas de desconexión.

--------------------------------------------------------------

💡 Recomendaciones de Negocio

* Implementar alertas tempranas ante disminución en la frecuencia de asistencia.

* Incentivar contratos de mayor duración.

* Diseñar campañas de retención dirigidas a clientes de baja actividad.

* Priorizar métricas de comportamiento en la estrategia de seguimiento.

--------------------------------------------------------------

🛠 Tecnologías Utilizadas

* Python

* Pandas

* NumPy

* Matplotlib / Seaborn

* Scikit-learn