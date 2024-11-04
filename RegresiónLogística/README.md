# Análisis de sentimientos en la industria hotelera

**Código:** [`Regresión logística para clasificación de reseñas.ipynb`](https://github.com/ElAleph25/Projectos-del-Portafolio-/blob/main/Regresi%C3%B3nLog%C3%ADstica/Regresio%CC%81n%20logi%CC%81stica%20para%20clasificacio%CC%81n%20de%20resen%CC%83as.ipynb)

**Problema:** Obtener un clasificador binario de reseñas positivas o negativas para un hotel, que es conocido como un "análisis de sentimientos".

**Solución:** Se utilizará modelos de machine learning que permiten leer textos e interpretar las relaciones que existen entre las distintas palabras para hacer una mejor predicción. Los modelos del procesamiento del lenguaje natural han revolucionado la mayor parte de las industrias.

En este caso, se usará la regresión logistica con penalización Ridge para realizar una clasificación binaria según la autenticidad de comentarios a hoteles, utilizando un corpus de 1600 opiniones a hoteles de Chicago. 
Este corpus consiste en críticas falsas y autenticas de 20 hoteles de Chicago. Los datos fueron originalmente descritos en dos documentos de acuerdo con el sentimiento positivo o negativo de los mismos.

Este corpus contiene:

* 800 comentarios auténticos, de los cuáles 400 están clasificados como positivos y 400 como negativos
* 800 comentarios falsos, igualmente dividio en 400 comentarios positvas y 400 negativos.

**Skills:** Preprocesamiento de texto (lemmatización y stemming), vectorizar textos (Bolsas de Palabras y TF-IDF), álgebra lineal (descomposición SVD). 

**Paquetería:** Python, Pandas, Numpy, Matplotlib, SciPy, Nltk, Sklearn.

