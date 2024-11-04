# Predicción de tejidos cancerígenos

**Código:** [`Perceptrón para tejidos cancerígenos.ipynb`](https://github.com/ElAleph25/Projectos-del-Portafolio-/blob/main/Perceptr%C3%B3nLineal/Perceptro%CC%81n%20para%20tejidos%20canceri%CC%81genos.ipynb)

**Problema:** Construir un clasificador binario de tejidos cancerígenos de esófago. Para ello, se utilizará el conjunto de datos formado por 1,469 imágenes de tejido sano (Clase 0) y 3,594 imágenes de displasia/cáncer (Clase 1). Este subconjunto de imágenes provienen del [Data Challenge by Mauna Kea](https://challengedata.ens.fr/participants/challenges/11/).

Las imágenes originales fueron escaladas de 519x521 pixeles a 260x260 para reducir el tiempo y la memoria requeridos para el procesamiento. El conjunto de imágenes utilizadas están disponibles en el archivo comprimido [CarpetaImagenes.zip](https://drive.google.com/file/d/1Abi4hjl5djn8X75YCcMXL5htq7iqf7VY/view?usp=sharing), fuera de este repositorio.

**Solución:** Utilizaremos un modelo matemático conocido como Perceptrón lineal, el cual podrá predecir, a pesar de que la base de datos a usar no contiene datos estructurados sino imágenes, qué tejidos de esófago tienen cáncer. Este tipo de técnicas son muy valiosas en medicina.

**Skills:** Preprocesamiento de imágenes (vectorización de imágenes), visualización de imágenes, álgebra lineal. 

**Paquetería:** Python, Pandas, Numpy, Matplotlib, Seaborn, Sklearn, Skimage.



