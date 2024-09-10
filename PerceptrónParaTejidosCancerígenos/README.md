# Predicción de tejidos cancerígenos
**Código:** [`Perceptrón para tejidos cancerígenos.ipynb`](https://github.com/ElAleph25/Projectos-del-Portafolio-/blob/main/Perceptr%C3%B3nParaTejidosCancer%C3%ADgenos/Perceptro%CC%81n%20para%20tejidos%20canceri%CC%81genos.ipynb)

**Objetivo:** Se tratará la predicción de tejidos cancerígenos utilizando imágenes. 

**Descripción:** Utilizaremos un modelo matemático conocido como Perceptrón lineal, el cual podrá predecir, a pesar de que la base de datos a usar no contiene datos estructurados sino imágenes, qué tejidos de esófago tienen cáncer. Este tipo de técnicas son muy valiosas en medicina.

Este modelo realizará una clasificación binaria de un subconjunto de imágenes provenientes del [Data Challenge by Mauna Kea](https://challengedata.ens.fr/participants/challenges/11/).
El conjuntode datos está formado por 1,469 imágenes de tejido sano (Clase 0)  y 3,594 imágenes de displasia/cáncer (Clase 1).

Las imágenes originales fueron escaladas de 519x521 pixeles a 260x260 para reducir el tiempo y la memoria requeridos para el procesamiento. El conjunto de imágenes utilizadas están disponibles en el archivo comprimido [CarpetaImagenes.zip](https://drive.google.com/file/d/1Abi4hjl5djn8X75YCcMXL5htq7iqf7VY/view?usp=sharing), fuera de este repositorio.

**Skills:** Preprocesamiento de imágenes (vectorización de imágenes), visualización de imágenes, álgebra lineal. 

**Paquetería:** Python, Pandas, Numpy, Matplotlib, Seaborn, Sklearn, Skimage.

**Resultados:** Se obtiene un clasificador binario de tejidos cancerígenos. Este clasificador puede ser de gran utilidad para los especialistas que traten estas enfermedades, ya que reduce el tiempo de revisión y el gran costo que tiene realizar estas pruebas. 


