# Clasificación de reseñas positivas y negativas de un hotel

**Código:** [`ClasificadorReseñasRegresiónLogística.ipynb`](https://github.com/ElAleph25/Projectos-del-Portafolio-/blob/main/ClasificadorRese%C3%B1asHoteles/ClasificadorResen%CC%83asRegresio%CC%81nLogi%CC%81stica.ipynb)

**Objetivo:** En un Corpus de reseñas de hoteles de Chicago, clasificar cuáles son las reseñas positivas y cuales no. 

**Descripción:** Se utilizará regresión logistica con penalización Ridge para realizar una clasificación binaria según la autenticidad de comentarios a hoteles, utilizando un corpus de 1600 opiniones a hoteles de Chicago. 
Este corpus consiste en críticas falsas y autenticas de 20 hoteles de Chicago. Los datos fueron originalmente descritos en dos documentos de acuerdo con el sentimiento positivo o negativo de los mismos.

Este corpus contiene:

* 800 comentarios auténticos, de los cuáles 400 están clasificados como positivos y 400 como negativos
* 800 comentarios falsos, igualmente dividio en 400 comentarios positvas y 400 negativos.

**Skills:** Preprocesamiento de texto (lemmatización y stemming), vectorizar textos (Bolsas de Palabras y TF-IDF), álgebra lineal (descomposición SVD). 

**Paquetería:** Python, Pandas, Numpy, Matplotlib, SciPy, Nltk, Sklearn.

**Resultados:** Se obtiene un clasificador binario de reseñas positivas o negativas para un hotel. Este clasificador puede ser de gran utilidad para los clientes que buscan un buen lugar para pasar sus vacaciones, por ejemplo. 

