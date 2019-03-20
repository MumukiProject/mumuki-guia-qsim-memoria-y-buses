La memoria no está sola: viene acompañada de una nueva forma de direccionamiento en nuestras instrucciones :satisfied:. Las direcciones de memoria se escriben entre corchetes `[]`, y podemos tanto leer de ellas como escribir en ellas.

Por ejemplo, para copiar el valor del registro `R3` a la dirección `0x425E`, escribimos...

`MOV [0x425E], R3`

O para multiplicar y guardar el valor del registro `R2` con el valor guardado en la dirección de memoria `0x7FFF`, la instrucción es...

`MUL R2, [0x7FFF]`

Este tipo de direccionamiento se llama **directo**, porque apunta *directamente* a la dirección de memoria donde está guardado el valor. :ok_hand:

> Marcá las opciones correctas.