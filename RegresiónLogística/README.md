# Análisis de sentimientos en la industria hotelera

**Código:** [`Regresión logística para clasificación de reseñas.ipynb`](https://github.com/ElAleph25/Projectos-del-Portafolio-/blob/main/An%C3%A1lisisSem%C3%A1nticoLatente/LSA%20para%20expedientes%20me%CC%81dicos.ipynb)

**Objetivo:** Se tratará el análisis de sentimientos en la industria hotelera.

**Descripción:** Se utilizará modelos de machine learning que permiten leer textos e interpretar las relaciones que existen entre las distintas palabras para hacer una mejor predicción. Los modelos del procesamiento del lenguaje natural han revolucionado la mayor parte de las industrias.

En este caso, se usará la regresión logistica con penalización Ridge para realizar una clasificación binaria según la autenticidad de comentarios a hoteles, utilizando un corpus de 1600 opiniones a hoteles de Chicago. 
Este corpus consiste en críticas falsas y autenticas de 20 hoteles de Chicago. Los datos fueron originalmente descritos en dos documentos de acuerdo con el sentimiento positivo o negativo de los mismos.

Este corpus contiene:

* 800 comentarios auténticos, de los cuáles 400 están clasificados como positivos y 400 como negativos
* 800 comentarios falsos, igualmente dividio en 400 comentarios positvas y 400 negativos.

**Skills:** Preprocesamiento de texto (lemmatización y stemming), vectorizar textos (Bolsas de Palabras y TF-IDF), álgebra lineal (descomposición SVD). 

**Paquetería:** Python, Pandas, Numpy, Matplotlib, SciPy, Nltk, Sklearn.

**Resultados:** Se obtiene un clasificador binario de reseñas positivas o negativas para un hotel. Este clasificador puede ser de gran utilidad para los clientes que buscan un buen lugar para pasar sus vacaciones, por ejemplo. 


