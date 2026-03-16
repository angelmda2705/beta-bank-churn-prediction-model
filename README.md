# beta-bank-churn-prediction-model
Beta Bank ha observado que cada mes algunos de sus clientes abandonan el banco. Los analistas descubrieron que retener a los clientes actuales es significativamente más económico que adquirir nuevos clientes.  

El objetivo de este proyecto es desarrollar un **modelo de machine learning** capaz de predecir si un cliente abandonará el banco en el futuro cercano utilizando información histórica sobre su comportamiento.

---

## Objetivo

Construir un modelo de clasificación que permita identificar clientes con alto riesgo de abandono (**churn**).

Para aprobar el proyecto se requiere:

- Obtener un **F1-score mayor o igual a 0.59**
- Evaluar el modelo utilizando también la métrica **ROC-AUC**

Estas métricas permiten medir la capacidad del modelo para detectar correctamente a los clientes que podrían abandonar el banco.

---

## Datos utilizados

El conjunto de datos contiene información sobre el comportamiento de los clientes del banco, incluyendo variables relacionadas con su perfil y actividad financiera.

La variable objetivo es:

**Exited**
- 1 → el cliente abandonó el banco
- 0 → el cliente permanece en el banco

---

## Metodología

El proyecto se desarrolló siguiendo las siguientes etapas:

1. Exploración y análisis de los datos.
2. Preprocesamiento de los datos.
3. División del conjunto de datos en entrenamiento y prueba.
4. Entrenamiento de diferentes modelos de clasificación.
5. Ajuste del modelo para mejorar su rendimiento.
6. Evaluación del modelo utilizando **F1-score** y **ROC-AUC**.
7. Visualización del desempeño del modelo mediante la **curva ROC**.

---

## Modelos evaluados

Se entrenaron y evaluaron diferentes algoritmos de clasificación, incluyendo:

- Random Forest
- Logistic Regression

El modelo final fue seleccionado en función de su desempeño utilizando la métrica **F1-score**.

---

## Resultados

El modelo final logró:

- **F1-score superior a 0.59**, cumpliendo con el requisito del proyecto.
- Un buen desempeño en la métrica **ROC-AUC**, lo que indica que el modelo tiene una buena capacidad para distinguir entre clientes que abandonan el banco y aquellos que permanecen.

La curva ROC muestra que el modelo tiene un rendimiento significativamente mejor que una predicción aleatoria.

---

## Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## Autor

Angel Mendiola Del Angel  
Ingeniero Industrial | Científico de Datos
