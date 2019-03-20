¡Muy bien! :tada: En los resultados podés ver las celdas de memoria relevantes al ejercicio. Como la memoria es muy grande, sólo te mostramos las direcciones que nos importan: `EEEE` y `EEEF`.

Lo que ocurre en un proceso de **lectura** de memoria (también comocido como *read*, en inglés) es lo siguiente:

* Por el **bus de control** se le informa a la memoria que se quiere leer de ella.
* Por el **bus de direcciones** se le dice de qué dirección se quiere leer.
* Por el **bus de datos** viajan los bits que estaban en esa celda.

Y en un proceso de **escritura** (o *write*) es similar:

* Por el **bus de control** se le avisa a la memoria que se quiere escribir en ella.
* Por el **bus de direcciones** se le especifica en qué dirección se quiere escribir.
* Por el **bus de datos** viajan los bits que quieren escribirse en esa celda.