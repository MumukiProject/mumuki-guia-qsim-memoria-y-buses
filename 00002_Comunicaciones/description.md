¿Y cómo se llega a la memoria? ¿Cómo se habla con la CPU para ponerse de acuerdo? :lips:

No tienen boca, por supuesto. :stuck_out_tongue: Pero tienen un sistema de comunicación que se llama **bus**... ¡muchos de ellos, de hecho! Y cada uno tiene un cierto tamaño, que se conoce como **ancho de bus**. :bus:

Algunos de los **buses** de la computadora son: 

* **Bus de control**, que tiene dos líneas hacia la memoria. Una es de **temporización**, y le informa cosas como *"quiero usar el bus"* o *"el bus de datos está ocupado"*. La otra línea, de **comando**, le indica qué quiere hacer con la memoria, si *leer* de ella o *escribir* en ella.
* **Bus de direcciones**, cuyo ancho de bus depende de la cantidad de direcciones que tiene la memoria. Por ejemplo, si hay 256 direcciones de memoria posibles, entonces las líneas serán ocho: ocho es la cantidad de bits que se necesitan para escribir 256 direcciones (de `00000000` a `11111111` en binario, o de `00` a `FF` en hexadecimal). Quizá recuerdes que para cada cantidad de bits hay un **rango** de números posibles: lo mismo aplica aquí. :relaxed:
* **Bus de datos**, cuyo ancho de bus depende del tamaño de celda de la memoria. Es igual que con las direcciones, pero más fácil: por ejemplo, si cada celda contiene 4 bits de información, entonces serán 4 las líneas.

> Teniendo en cuenta cómo se calcula cada ancho de bus, completá la siguiente oración.