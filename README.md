# ITBA Especialización en Ciencia de Datos - TFI
## Análisis de Texto de Regulaciones Financieras utilizando NLP y ML  

![Badge en Desarollo](https://img.shields.io/badge/STATUS-EN%20DESAROLLO-green)

Este repositorio contiene los datasets, las notebooks con el código y los archivos de datos que componen el trabajo Final Integrador cuyo objetivo es: Utilizar técnicas de procesamiento de lenguaje natural (NLP) y aprendizaje automático (ML) para analizar un grupo de regulaciones, comunicaciones y publicaciones del BCRA que tratan o contienen referencias sobre medios de pago, tecnología y ciberseguridad. El propósito es evaluar la posibilidad de incorporar estas herramientas para automatizar la identificación de gaps regulatorios y/o la revisión de las regulaciones y publicaciones. 
Se toman un grupo de las regulaciones y comunicaciones que el Banco Central de la República Argentina [(BCRA)](https://www.bcra.gob.ar/) publica en su sitio web y que es de libre acceso. Se realizó una selección de un grupo de regulaciones y publicaciones que se refieren a temas de tecnología y ciberseguridad. 

## Metodología
Este proyecto sigue un marco de trabajo compuesto en fases, que abarcan desde el conocimiento del problema hasta las etapas de tratamiento de los datos, modelado, prueba y evaluación de resultados.

* Selección de Documentos: Seleccionar textos ordenados, guías de supervisión y comunicaciones relevantes para el análisis.
*Preprocesamiento: Realizar la extracción y limpieza de texto, creación del corpus y aplicar técnicas de tokenización, stemming y lematización.
*Procesamiento de Datos: Cuantificar palabras, crear visualizaciones de frecuencias, utilizar estadística TF-IDF y generar una matriz de términos y documentos.
* Análisis de Datos y Validación: Realizar el análisis de texto y validar las hipótesis planteadas.

## Contenido
| Carpeta              | Contenido |
| -------------------- | --------- |
| [Datasets](./Datasets) | Datasets generados con Python y Pandas |
| [Datos](./Datos) | Archivos Originales descargados desde el sitio del BCRA |
| [Notebooks](./Notebooks) | Notebooks Colab con el código fuente del webscraping, las pruebas de Librerias de NLP y el análisis  |
| [Fuentes](./Fuentes) | Archivos necesarios para realizar las pruebas con los modelos de [(Stanza)](https://stanfordnlp.github.io/stanza/models.html) |

## Algunas Referencias 📌
* [Spacy](https://spacy.io/)
* [Nltk](https://www.nltk.org/)
* [Google_Colaboratory](https://colab.research.google.com/notebooks/welcome.ipynb?hl=es)
* [Craig Lewis & Steven Young, 2019, “Fad or future? Automated analysis of financial text and its implications for corporate reporting](https://www.tandfonline.com/doi/epdf/10.1080/00014788.2019.1611730?needAccess=true&role=button)
* [Computational Data Sciences and the Regulation of Banking and Financial Services](https://www.researchgate.net/publication/315511636_Computational_Data_Sciences_and_the_Regulation_of_Banking_and_Financial_Services)

## Autor ✒️
**Gustavo Pereyra** 2022 - [gusper01](https://github.com/gusper01)😊

¡Gracias por tu interés en este proyecto!
