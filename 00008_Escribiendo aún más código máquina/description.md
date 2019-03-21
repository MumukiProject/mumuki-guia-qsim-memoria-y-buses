Al igual que las instrucciones que trabajamos en la lección anterior, aquellas en las que usemos direccionamiento directo también deben poder **ensamblarse**, para traducirse a bits que la CPU pueda operar. :wrench:

Los seis bits que representan direccionamiento directo son `001000`. Luego, al final, se destinan 16 bits para escribir en binario la dirección de memoria correspondiente al operando.

Por ejemplo, el ensamblado de la instrucción `ADD R2, [0x1557]` es...

* `0010`, porque es el código de la instrucción ADD;
* `100`, porque el operando destino tiene direccionamiento de registro, y `010` porque el registro es `R2`;
* `010000` porque el operando origen tiene direccionamiento directo;
* `0001 0101 0101 0111` porque son los números hexadecimales de la dirección de memoria (`1`, `5`, `5` y `7`) convertidos a binario.

> ¡Es tu turno de ensamblar, otra vez! :muscle: Escribí en el editor el código máquina de la instrucción `ADD R2, [0x1550]`.