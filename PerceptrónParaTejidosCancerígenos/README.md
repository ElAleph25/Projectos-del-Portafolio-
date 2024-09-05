# Perceptrón para la clasificación de tejidos sanos y cancerígenos en el esófago 
**Código:** [`Perceptrón para tejidos cancerígenos.ipynb`](https://github.com/ElAleph25/Projectos-del-Portafolio-/blob/main/Perceptr%C3%B3nParaTejidosCancer%C3%ADgenos/Perceptro%CC%81n%20para%20tejidos%20canceri%CC%81genos.ipynb)

**Objetivo:** En una muestra de 5063 imágenes de tejido esofágico, clasificar los que sí tienen cáncer y los que no. 

**Descripción:** En México, el consumo de tabaco y alcohol, es muy común en adultos. El abuso de estas sustancias, comúnmente lleva a la adicción y, por consiguiente, a padecer algún tipo de enfermedad crónica en el sistema respiratorio o gástrico. Uno muy común es el cancer de esófago. 
Diagnosticar este tipo de enfermedades, regularmente se realizan a través de una biopsia mediante un videoendoscopio. Lo ideal sería que, exista una maquina que pueda, automáticamente, diagnosticar si los tejidos del esófago observados por el videoendoscopio tienen cáncer o no, ya que hacerlos visualmente con la ayuda de un especialista, resulta ser altamente costoso y tardado.

El algoritmo del Perceptrón lineal nos puede ayudar a realizar la clasificación del tejido sano y cancerígeno en automático. Este algoritmo se usará para realizar una clasificación binaria de un subconjunto de imágenes provenientes del [Data Challenge by Mauna Kea](https://challengedata.ens.fr/participants/challenges/11/).

Para este clasificador se utilizaron solamente las imágenes de tejido sano y las imágenes de tejido con displasia/cáncer.
El conjuntode datos está formado por 1,469 imágenes de tejido sano (Clase 0)  y 3,594 imágenes de displasia/cáncer (Clase 1).

Las imágenes originales fueron escaladas de 519x521 pixeles a 260x260 para reducir el tiempo y la memoria requeridos para el procesamiento. El conjunto de imágenes utilizadas están disponibles en el archivo comprimido [CarpetaImagenes.zip](https://drive.google.com/file/d/1Abi4hjl5djn8X75YCcMXL5htq7iqf7VY/view?usp=sharing), fuera de este repositorio.

**Skills:** Preprocesamiento de imágenes (vectorización de imágenes), visualización de imágenes, álgebra lineal. 

**Paquetería:** Python, Pandas, Numpy, Matplotlib, Seaborn, Sklearn, Skimage.

**Resultados:** Se obtiene un clasificador binario de tejidos cancerígenos. Este clasificador puede ser de gran utilidad para los especialistas que tratan estas enfermedades, ya que reduce el tiempo de revisión y el gran costo que tiene realizar estas pruebas. 


