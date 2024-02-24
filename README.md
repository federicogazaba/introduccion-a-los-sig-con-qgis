# Introduccion a los Sistemas de Informacion Geografica con Qgis

Versión 2.0

## Descripción

Básicamente este repositorio contiene el libro "Introducción a los Sistemas de Información Geográfica con Qgis" realizado con el software Lyx (editor LaTeX). Su licencia libre permite modificaciones y aportes, y con ese propósito se dispuso en este repositorio.

La estructura del libro va desde el nivel 0 al 6, en niveles de dificultad y complejidad creciente. Fue pensado para que se lo utilice como material de aprendizaje autónomo, pero también puede ser utilizado en cursos:

- Introducción. Permite al lector conocer acerca de los Sistemas de Información Geográfica y las Infraestructuras de Datos Espaciales, de forma que pueda comprender los conceptos básicos que hacen al trabajo con datos georreferenciados. Quienes tienen que alcanzar este nivel son aquellos que trabajen con datos territoriales, en especial los responsables del planeamiento y la toma de decisiones, ya que es imprescindible que conozcan la potencialidad de estos sistemas.

- Consulta. Este nivel deberán alcanzarlo quienes necesiten solamente explorar y consultar datos espaciales. La competencia principal en este nivel es poder examinar los atributos de datos y hacer consultas espaciales de forma visual que podrán incluir en informes gráficos con datos exportados a planillas de cálculo, con fuentes propias o externas.

- Edición. El trabajo cotidiano de carga y modificación de datos espaciales en un SIG son quienes deben completar este nivel. La elaboración de datos georreferenciados nuevos o la edición de datos preexistentes es la principal competencia a adquirir.

- Diseño. Los datos de un SIG pueden ser analizados desde una computadora, tanto para la toma de decisiones como para su publicación en línea, sin embargo a veces es necesario realizar salidas de impresión en planos de diversos tamaños. El nivel Diseñador tiene las competencias básicas para elaborar mapas temáticos para imprimir o visualizar en pantalla.

- Análisis. Es el último nivel que completa este curso y permite adquirir las herramientas para realizar análisis de datos de forma integral. Aquellos que necesiten profundizar en el uso de un SIG son los destinatarios de este nivel, donde podrán realizar geoprocesos vectoriales, filtros avanzados, consultas complejas de datos, etc.

- Anexos. En el anexo se encuentran algunas herramientas y configuraciones avanzadas que por sus características se decidió no incluir en ninguno de los capítulos anteriores.

## Cambios en la segunda versión

• Actualización de portada
• Actualización de lista de grupos
• Actualización de enlaces
• Capítulos 1 y 2: Revisión, renovación y actualización de gráficos. Reformulación de definiciones y conceptos. Actualización de enlaces. Agregado de simbología ráster. Agregado de herramientas y configuraciones.
• Capitulo 3: Actualización de gráficas y textos de procesos vectoriales. Agregado de procesos vectoriales básicos y nueva sección de edición de capas ráster.
• Capítulo 4: Actualización de gráficas y textos. Agregado de configuraciones y nuevos elementos de mapa.
• Capítulo 5: Actualización de gráficas y textos de procesos de análisis vectorial. Agregado de procesos vectoriales avanzados. Incorporación de nueva sección de análisis ráster.
• Capítulo 6: Actualización de gráficas y textos. Incorporación de nuevos complementos y configuraciones. Agregado de nueva sección de fuentes de datos abiertos.

## Data

Para hacer más accesible y global la utilización de este libro se toman los datos SIG de Natural Earth (http://www.naturalearthdata.com/downloads/) que es un repositorio de datos vectoriales y raster de dominio público. Con esto se logra que el manual pueda ser utilizado en cualquier parte del mundo sin problemas
de localización regional.

## Estructura del documento

El libro está confeccionado con el software Lyx (https://www.lyx.org/WebEs.Home), un procesador de documentos del tipo (WYSIWYM) que combina TeX/LaTeX con la facilidad de uso de una interfaz gráfica. Para abrir el documento es necesario descargar la carpeta /img (donde se encuentran todas las imágenes) y el archivo "introduccion-a-los-sig-con-qgis.lyx" en el mismo lugar. Una vez abierto se podrá exportar a los diferentes formatos que provee el programa como por ejemplo PDF (pdflatex). En particular, sobre una instalación de Lyx en Ubuntu conviene que la ruta de la carpeta raíz no contenga caracteres no convencionales para evitar errores en la exportación a PDF.

Se adjuntó un archivo en formato PDF de cada versión (la segunda versión en tres partes debido al tamaño que limita github de subida).

La carpeta /img y /img2 contienen las imágenes de cada versión del libro donde su prefijo va del 0 al 7 de acuerdo al capítulo al que pertenece. Es decir, para compilar el pdf de cada versión hará falta descargar el archivo lyx y la carpeta /img correspondiente.

## Licencia

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

Este trabajo está licenciado bajo
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
