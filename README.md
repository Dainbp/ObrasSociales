# OSOnto
## Introducción
Recientemente se ha obtenido acceso a grandes volúmenes de *datos públicos* relacionados con las prestadoras de servicios de salud, las obras sociales, los hospitales públicos y las farmacias de todo el país.

La publicación de *datos abiertos* por parte del Estado, significa un avance en términos de acceso a la información y transformación social. Sin embargo, esto suscita una problemática asociada aún no tratada: la transformación de los datos en información.

Todos los datos mencionados anteriormente se encuentran publicados en formatos no legibles y difícilmente tratables por sistemas automatizados o autónomos. También sucede que los datos provienen de diversas fuentes con estándares distintos, definiciones ambiguas y sin criterios de normalización.

El primer paso para lograr esta transformación consiste en `*sanitizar*', estandarizar y desambiguar los datos para poder utilizarlos.

Luego, es necesario agregarles valor a estos datos para poder extraer *información* (o incluso **conocimiento**) a partir de su análisis y las relaciones que se pueden lograr y obtener de todo el volumen disponible.

Por ello se pretende modelar en una *ontología* la información de cobertura y convenios de obras sociales estatales, en distintas regiones, tanto en farmacias como en clínicas y centros médicos. Así como también de los profesionales de la salud se desea conocer sus datos de contacto y si existe su especialidad.

Finalmente, se espera lograr la implementación de un sistema de consulta que permita aprovechar la información estructurada por la ontología lograda respondiendo consultas sobre servicios médicos.

## ¿Que puedo encontrar en el repositorio?
Se encuentran disponibles: 
* los filtros automáticos para ser aplicados utilizando OpenRefine dentro del directorio *filtros_openrefine*.
* la definición de la ontología en formato owl en el archivo *Obras_Sociales.owl*.
* individuos y datos crudos y procesados para analizar las diferencias en el directorio *datos*.

Actualmente la DB realizada en GraphDB no se encuentra disponible.

## Licencia
La licencia de la ontología y la implementación lograda es GNU-GPLv3, el PDF con el informe está licenciada bajo la Licencia Creative Commons Atribución-SinDerivadas 4.0 Internacional. Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nd/4.0/.
