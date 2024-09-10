
# Clasificación de expedientes médicos
**Código:** [`LSA para expedientes médicos.ipynb`](https://github.com/ElAleph25/Projectos-del-Portafolio-/blob/main/LSAParaExpedientesM%C3%A9dicos/LSA%20para%20expedientes%20me%CC%81dicos.ipynb)

**Objetivo:** Realizar consultas relevantes de expedientes médicos similares.

**Descripción:** Se usará un modelo del procesamiento del lenguaje natural para obtener las consultas más relevantes para documentos médicos similares de acuerdo a la similitud en sus palabras. 

El análisis semántico latente (LSA por sus siglas en inglés), es un método del álgebra lineal númerica que ayuda a comparar la similitud dde de textos vectorizados con la métrica de la similitud del coseno.

El DataSet que se utilizará estará preprocesado para tener resumenes textuales de enfermedades que están catalogadas en 23 categorías.
El conjunto completo de datos se encuentra en [`OHSUMED dataset`](https://www.mat.unical.it/OlexSuite/Datasets/SampleDataSets-about.htm).

**Skills:** Preprocesamiento de texto (lemmatización y stemming), vectorizar textos (Bolsas de Palabras y TF-IDF), álgebra lineal (descomposición SVD). 

**Paquetería:** Python, Pandas, Numpy, Matplotlib, SciPy, Nltk.

**Resultados:** Al utilizar LSA que, en este caso, lo consideramos como un modelo de aprendizaje no supervisado, tenemos una forma de comparar muchos expedientes médicos. La comparación de estos textos, es con base a la similitud de frases o palabras. 
Esto puede ser de gran utilidad para los médicos que necesitan encontrar patrones, palabras y frases comúnes que cumplan un conjunto de pacientes. 
