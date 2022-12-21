Esta práctica consiste en entregar un script R markdown con el Análisis Descriptivo y Exploratorio del dataset principal utilizado en la sesión "Introducción a R".

El conjunto de datos que se encuentra en https://archive.ics.uci.edu/ml/machine-learning-databases/00320/student.zip

Este dataset consta de:

2 archivos CSV con los datos: student-mat.csv, student-por.csv
Un script student-merge.R que mostraba cómo obtener los estudiantes que aparecen en ambos CSV
Un "diccionario" que describe los campos: student.txt.
La descripción de los datos (diccionario) se encuentra en: https://archive.ics.uci.edu/ml/datasets/Student+Performance

Para facilitaros la realización de la práctica, deciros que el análisis debería idealmente contar con estas 5 fases

1. Introducción con el objetivo del análisis:

En esta práctica pretende llegar sólo hasta el Exploratorio
Pero se debe ir pensando en una finalidad posterior (Modelo predictivo, Clasificación, ....) Aunque esta finalidad última no se incluya en la práctica, se debe plantear la "hipótesis" en la introducción. Con este dataset se podría tratar de predecir el valor de la nota final G3, o clasificar a los alumnos como aprobados o suspendidos en base a que esa nota sea mayor o menor que 5, pero se puede pensar otro objetivo si así se quiere).
Se recomienda leer este estudio "Using data mining to predict secondary school student performance" http://hdl.handle.net/1822/8024. Se puede bajar el paper en PDF: https://repositorium.sdum.uminho.pt/bitstream/1822/8024/1/student.pdf.
Este paper aplica algunos modelos y los compara.
2. Carga de los datos

Pueden utilizarse los comandos vistos en la sesión "Introducción a R"  (ej. librería {downloader}, read.csv,etc.). Apartado “# 12. R: Leyendo y escribiendo datos” del script ("Introduccion_R.Rmd").
3. Análisis descriptivo

Pueden utilizarse los comandos que en el script de la sesión están en el apartado “Summarizing”.
4. Análisis exploratorio (puede ser apoyado en algún método NO supervisado)

Pueden utilizarse los comandos de los apartados “Gráficos exploratorios” y "Clustering" del script.
5. Conclusiones: ¿Pensamos que este dataset puede servir para la finalidad/modelo que habíamos planteado en la Introducción? ¿Tenemos ya alguna conclusión preliminar sobre qué variables pueden resultar más últimes para dicha finalidad/modelo (predictivo, clasificación, ...)?

El informe será entregado en formato Rmarkdown (http://rmarkdown.rstudio.com/) en el que se incluirá el código R y las explicaciones convenientes, así como los gráficos.

El informe PPT, PDF, Word o HTML que se genere a partir del Rmarkdown, no podrá superar las 8 páginas de extensión con un máximo de 6 figuras.

La entrega consistirá en adjuntar el archivo R Markdown al moodle. Se recomienda subir también el informe (PPT, PDF, Word o HTML) por si hay algún problema en la ejecución del script.
