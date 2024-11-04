# Clasificación de expedientes médicos

**Código:** [`LSA para expedientes médicos.ipynb`](https://github.com/ElAleph25/Projectos-del-Portafolio-/blob/main/LSAParaExpedientesM%C3%A9dicos/LSA%20para%20expedientes%20me%CC%81dicos.ipynb)

**Problema:** Realizar consultas relevantes de expedientes médicos similares. Para este fin, el dataset que se utilizará, tiene 13924 expedientes médicos, y estará preprocesado para tener resumenes textuales de enfermedades que están catalogadas en 23 categorías.
El conjunto completo de datos se encuentra en [`OHSUMED dataset`](https://www.mat.unical.it/OlexSuite/Datasets/SampleDataSets-about.htm).

**Solución:** Se usará un modelo del procesamiento del lenguaje natural para obtener las consultas más relevantes para documentos médicos similares de acuerdo a la similitud en sus palabras. 

El análisis semántico latente (LSA por sus siglas en inglés), es un método del álgebra lineal númerica que ayuda a comparar la similitud de de textos vectorizados con la métrica de la similitud del coseno.

**Skills:** Preprocesamiento de texto (lemmatización y stemming), vectorizar textos (Bolsas de Palabras y TF-IDF), álgebra lineal (descomposición SVD). 

**Paquetería:** Python, Pandas, Numpy, Matplotlib, SciPy, Nltk.
