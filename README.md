# Introduccion a los Sistemas de Informacion Geografica con Qgis

Versión 1.0

## Descripción

Básicamente este repositorio contiene el libro "Introducción a los Sistemas de Información Geográfica con Qgis" realizado con el software Lyx (editor LaTeX). Su licencia libre permite modificaciones y aportes, y con ese propósito se dispuso en este repositorio.

La estructura del libro va desde el nivel 0 al 6, en niveles de dificultad y complejidad creciente. Fue pensado para que se lo utilice como material de aprendizaje autónomo, pero también puede ser utilizado en cursos:

- Introducción. Permite al lector conocer acerca de los Sistemas de Información Geográfica y las Infraestructuras de Datos Espaciales, de forma que pueda comprender los conceptos básicos que hacen al trabajo con datos georreferenciados. Quienes tienen que alcanzar este nivel son aquellos que trabajen con datos territoriales, en especial los responsables del planeamiento y la toma de decisiones, ya que es imprescindible que conozcan la potencialidad de estos sistemas.

- Consulta. Este nivel deberán alcanzarlo quienes necesiten solamente explorar y consultar datos espaciales. La competencia principal en este nivel es poder examinar los atributos de datos y hacer consultas espaciales de forma visual que podrán incluir en informes gráficos con datos exportados a planillas de cálculo, con fuentes propias o externas.

- Edición. El trabajo cotidiano de carga y modificación de datos espaciales en un SIG son quienes deben completar este nivel. La elaboración de datos georreferenciados nuevos o la edición de datos preexistentes es la principal competencia a adquirir.

- Diseño. Los datos de un SIG pueden ser analizados desde una computadora, tanto para la toma de decisiones como para su publicación en línea, sin embargo a veces es necesario realizar salidas de impresión en planos de diversos tamaños. El nivel Diseñador tiene las competencias básicas para elaborar mapas temáticos para imprimir o visualizar en pantalla.

- Análisis. Es el último nivel que completa este curso y permite adquirir las herramientas para realizar análisis de datos de forma integral. Aquellos que necesiten profundizar en el uso de un SIG son los destinatarios de este nivel, donde podrán realizar geoprocesos vectoriales, filtros avanzados, consultas complejas de datos, etc.

- Anexos. En el anexo se encuentran algunas herramientas y configuraciones avanzadas que por sus características se decidió no incluir en ninguno de los capítulos anteriores.

## Data

Para hacer más accesible y global la utilización de este libro se toman los datos SIG de Natural Earth (http://www.naturalearthdata.com/downloads/) que es un repositorio de datos vectoriales y raster de dominio público. Con esto se logra que el manual pueda ser utilizado en cualquier parte del mundo sin problemas
de localización regional.

## Estructura del documento

El libro está confeccionado con el software Lyx (https://www.lyx.org/WebEs.Home), un procesador de documentos del tipo (WYSIWYM) que combina TeX/LaTeX con la facilidad de uso de una interfaz gráfica. Para abrir el documento es necesario descargar la carpeta /img (donde se encuentran todas las imágenes) y el archivo "introduccion-a-los-sig-con-qgis.lyx" en el mismo lugar. Una vez abierto se podrá exportar a los diferentes formatos que provee el programa como por ejemplo PDF (pdflatex). En particular, sobre una instalación de Lyx en Ubuntu 20.04 conviene que la ruta de la carpeta raíz no contenga caracteres no convencionales para evitar errores en la exportación a PDF.

Se adjuntó un archivo en formato tex, exportado directamente de Lyx, para abrir desde algún editor LaTeX convencional.

La carpeta /img contiene las imágenes del libro donde su prefijo va del 0 al 6 de acuerdo al capítulo que pertenece. 

## Licencia

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

Este trabajo está licenciado bajo
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
