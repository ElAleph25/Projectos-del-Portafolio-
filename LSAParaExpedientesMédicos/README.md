
# Análisis semántico latente para expedientes médicos 
**Código:** [`LSA para expedientes médicos.ipynb`](https://github.com/ElAleph25/Projectos-del-Portafolio-/blob/main/LSAParaExpedientesM%C3%A9dicos/LSA%20para%20expedientes%20me%CC%81dicos.ipynb)

**Objetivo:** Realizar consultas relevantes de expedientes médicos similares.

**Descripción:**
Un problema en el sector salud, es que surja una enfermedad que provoque una epidemia, pandemia o endemia, que atente con la salud de una gran cantidad de personas en una población. Teniendo en cuenta los sintomas y características de dicha enfermedad, sería útil para los médicos y especialistas poder revisar, en sus bases de datos, los expedientes médicos de muchos pacientes y compararlos entre sí con base a las características la enfermedad. Hacer la comparación de muchos expedientes médicos similares, hace posible identificar a los pacientes con estos síntomas, para después, darles un seguimiento médico para priorizar su salud y prevenir el avance de la enfermedad. En este caso, nuestro DataSet contiene 13924 registros que son expedientes médicos. El conjunto completo de datos se encuentra en [`OHSUMED dataset`](https://www.mat.unical.it/OlexSuite/Datasets/SampleDataSets-about.htm).

El análisis semántico latente (LSA por sus siglas en inglés), es un método del "Procesamiento del Lenguaje Natural" que compara, en un corpus de textos, los documentos más similares. La metodología es, esencialmente: preprocesar y vectorizar textos, utilizar la descomposición singular de matrices
(SVD) y, finalmente, comparar los textos con la similitud del coseno. 

Es por esto que, LSA, puede ayudarnos a cumplir el propósito de comparar expedientes médicos. 

**Skills:** Preprocesamiento de texto (lemmatización y stemming), vectorizar textos (Bolsas de Palabras y TF-IDF), álgebra lineal (descomposición SVD). 

**Paquetería:** Python, Pandas, Numpy, Matplotlib, SciPy, Nltk.

**Resultados:** Al utilizar LSA que, en este caso, lo consideramos como un modelo de aprendizaje no supervisado, tenemos una forma de comparar muchos expedientes médicos. La comparación de estos textos, es con base a la similitud de frases o palabras. 
Esto puede ser de gran utilidad para los médicos que necesitan encontrar patrones, palabras y frases comúnes que cumplan un conjunto de pacientes. 
