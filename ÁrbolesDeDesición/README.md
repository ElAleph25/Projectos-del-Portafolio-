# Cálculo del Churn o tasa de abandono
**Código:** [`Clasificador de clientes Telecom.ipynb`](https://github.com/ElAleph25/Projectos-del-Portafolio-/blob/main/%C3%81rbolesDeDesici%C3%B3n/Clasificador%20de%20clientes%20Telecom.ipynb)

**Objetivo:** Se tratará el tema del cálculo de la tasa de abandono en una compañía telefónica.

**Descripción:** Se realizará un análisis para la retención de clientes de una empresa de telecomunicaciones, utilizando árboles de decisión y bosques aleatorios para entender las características más relevantes para la retención de clientes de una empresa de telecomunicaciones.

El conjunto de datos se tomó de [Kaggle](https://www.kaggle.com/datasets/mnassrib/telecom-churn-datasets?datasetId=255093&sortBy=voteCount&select=churn-bigml-80.csv). Éste cuenta con 3,333 renglones y 20 columnas.

El conjunto de datos disponible aquí, incluye los registros tanto el conjunto de entrenamiento (churn-bigml80.csv), como del conjunto de evaluación (churn-bigml20.csv).
Cabe además señalar que para facilitar la interpretación tanto del análisis exploratorio como del modelo, los nombres de las columnas del conjunto de datos se tradujo al español. 

**Skills:** Preprocesamiento de los datos (One Hot Encoding).

**Paquetería:** Python, Pandas, Numpy, Matplotlib, SciPy, Graphviz.

**Resultados:** Obtenemos un clasificador de retención de clientes cuya característica más importante de no abandono son los cargos al día. 
Por lo tanto, los árboles de decisión funcionan muy bien en general en las industrias dedicadas al servicio. 

