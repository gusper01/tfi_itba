## ITBA Especialización en Ciencia de Datos - Trabajo Final Integrador
## Análisis de Texto de Regulaciones Financieras utilizando NLP y ML  

Este repositorio contiene los datasets, las notebooks con el código, los archivos de datos que componen el trabajo Final Integrador cuyo objetivo es realizar una investigación utilizando técnicas de procesamiento de lenguaje natural (NLP) y aprendizaje automático (ML) para analizar un grupo de regulaciones, comunicaciones y publicaciones del BCRA que tratan o contienen referencias sobre medios de pago, tecnología y ciberseguridad. El propósito es evaluar la posibilidad de incorporar estas herramientas para automatizar la identificación de gaps regulatorios y/o la revisión de las regulaciones y publicaciones. 
Se toman un grupo de las regulaciones y comunicaciones que el Banco Central de la República Argentina [(BCRA)](https://www.bcra.gob.ar/) publica en su sitio web y que es de libre acceso. Se realizó una selección de un grupo de regulaciones y publicaciones que se refieren a temas de tecnología y ciberseguridad. 

# Metodología
Este proyecto sigue un marco de trabajo compuesto en fases, que abarcan desde el conocimiento del problema hasta las etapas de tratamiento de los datos, modelado, prueba y evaluación de resultados.

* Selección de Documentos: Seleccionar textos ordenados, guías de supervisión y comunicaciones relevantes para el análisis.
*Preprocesamiento: Realizar la extracción y limpieza de texto, creación del corpus y aplicar técnicas de tokenización, stemming y lematización.
*Procesamiento de Datos: Cuantificar palabras, crear visualizaciones de frecuencias, utilizar estadística TF-IDF y generar una matriz de términos y documentos.
* Análisis de Datos y Validación: Realizar el análisis de texto y validar las hipótesis planteadas.

# Contenido
| Carpeta              | Contenido |
| -------------------- | --------- |
| [Datasets](./Datasets) | Datasets generados con Python y Pandas |
| [Datos](./Datos) | Archivos Originales descargados desde el sitio del BCRA |
| [Notebooks](./Notebooks) | Notebooks Colab con el codigo fuente del webscraping, las pruebas de Librerias de NLP y el análisis  |
| [Fuentes](./Fuentes) | Archivos necesarios para realizar las pruebas con los modelos de [(Stanza)](https://stanfordnlp.github.io/stanza/models.html) |

¡Gracias por tu interés en este proyecto!
