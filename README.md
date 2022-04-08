# Practica de Powershell

## Script 1

![image](https://user-images.githubusercontent.com/91567318/162516995-1b260729-da25-46d0-8e0d-74f9ffee6906.png)

- Este script establece 4 variables, con $nombrevariable e imprime por pantalla con write-host concatenando una String con la variable correspondiente

---

## Script 2

![image](https://user-images.githubusercontent.com/91567318/162515592-0beb9744-0bfa-4e12-806b-9a6940e19c21.png)

For
Lo que hace es reproducir un bucle en el que repite el string 'Hello' hasta que la variable counter sea 1 menos que la variable repeat.

While
El siguiente bucle lo que hace es que repite otra vez "Hello" hasta que se cumpla lo mismo que el de arriba solo que en este, el contador está ncluido dentro del bucle en lugar de en la declaración del bucle. Eso es debido a que usa un while para hacer el bucle en lugar de un for.

Do While
La tercera declaración hace lo mismo pero usando do-while en lugar de un for o un while. Usa el mismo método que el anterior para declarar variables pero la declaración es separada. En el do está la acción y en el while está el condicional para el bucle.

ForEach
Se establece una variable de tipo string. Posteriormente, se usa un foreach, que básicamente lo que hace es imprimir cada letra de un string dado.

ForEach-Object
Se establece como anteriormente una variable de tipo string. Reproduce el mismo comportamiento que el anterior.

Lo primero que hace es definir una variable.

---

## Script 3
![image](https://user-images.githubusercontent.com/91567318/162516161-092c01ea-e1ff-4bd8-95b7-c606267d4bbe.png)

![image](https://user-images.githubusercontent.com/91567318/162516889-421783c2-ae1b-44ee-a1c5-a84d3f47b425.png)

![image](https://user-images.githubusercontent.com/91567318/162516938-0e8c2411-a448-42b0-9f61-72521db382bc.png)


- Condicionales simples
El primer condicional es del tipo if. Lo que hace en este caso es es comparar si 4 es equivalente a 4. Al ser afirmativo, reproduce el Write-Host e imprime que "4 es lo mismo que 4".

El segundo condicional es también es un if pero esta vez compara strings. En este caso compara si el string "Hello" es lo mismo que "Hello". Al ser afirmativo, usa otra vez el Write-Host con el mensaje "Ambos strings son iguales"

El tercer condicional usa un if-else. Si las variables x e y son iguales, dará un mensaje, y si no lo son, el else tomará el protagonismo.

El cuarto condicional conpara la variable yourName y tiene un if que compara la variable yourName con "Ian". Si es igual, imprimirá un mensaje. Si no lo es, el else imprimirá el mensaje alternativo.

Condicionales avanzados
Variables
Lo primero que hace es crear la variable de tipo String llamada $playerInput. Esa variable sirve como encabezado para que un Read-Host recoja el input de teclado y lo asigne a la variable. Y dependiendo de lo que se escriba en esa variable, pueden pasar varias cosas. Si escribimos left o right nos reproduce un mensaje propio de la elección, pero si escribimos algo diferente nos mostrará un mensaje extra, como si fuera a prueba de errores.

Comparison Operators
Aquí se nos introduce a las expresiones de comparación.

-eq comprueba si son iguales.

-ne comprueba si no son iguales.

-gt comprueba cual de las variables es mayor.

-ge comprueba cual de las variables es mayor o igual.

-lt comprueba cual de las variables es menor.

-le comprueba cual de las variables es menor o igual.

Comprobación de Strings
like comprueba si un string empieza con el otro string. Por ejemplo, si "hello how are you" empieza por "hello*" donde el asterisco es el comodín para decir cualquier cosa.

-notlike hace justo lo contrario al de arriba.

-match comprueba si una string contiene otra string.

-notmatch comprueba si una string no contiene otra string.

-constains comprueba si una lista contiene un número o un string.

-notcontains comprueba si una lista no contiene un número o un string.

-in devuelve un boolean con true si hay un string o número dentro de una lista y uno con false si es que no.

-notin devuelve un boolean con true si no hay un string o número de una lista y uno con false si es que sí.

-is devuelve true si una variable es del tipo que le preguntamos.

-isnot devuelve true si no es igual a la que le preguntamos.

Switch statementes
switch es una especie de menú de ifs pero con una sintaxis más corta y sencilla. Se puede hacer tanto con números como con strings y default si no corresponde a ninguna opción.


