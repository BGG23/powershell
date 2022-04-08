# Practica de Powershell

## Script 1

![image](https://user-images.githubusercontent.com/91567318/162516995-1b260729-da25-46d0-8e0d-74f9ffee6906.png)

- Este script nos muestra cuatro variables, usando el "$number" imprime por pantalla con un "write-host" que nos mostrara el numero correcto.

---

## Script 2

![image](https://user-images.githubusercontent.com/91567318/162515592-0beb9744-0bfa-4e12-806b-9a6940e19c21.png)


- El For lo que hace es reproducir el bucle en el que repite el string 'Hello' hasta que la variable "counter" sea uno menos que "repeat".

- El siguiente bucle While hace lo mismo que el For pero esta vez el contador está incluido dentro del bucle.

- El Do Wile hace lo mismo pero sustituyendo el For / While. La declaración de variables es separada. En el do está la acción y en el while está el condicional del bucle.

- En el ForEach usa una variable de tipo string, pero luego utiliza un foreach, que básicamente lo que hace es imprimir cada letra del string.

---

## Script 3
![image](https://user-images.githubusercontent.com/91567318/162516161-092c01ea-e1ff-4bd8-95b7-c606267d4bbe.png)

![image](https://user-images.githubusercontent.com/91567318/162516889-421783c2-ae1b-44ee-a1c5-a84d3f47b425.png)

![image](https://user-images.githubusercontent.com/91567318/162516938-0e8c2411-a448-42b0-9f61-72521db382bc.png)


### Condicionales simples
- El primer condicional es del tipo if. Lo que hace es comparar si 4 es igual a 4. En caso de ser correcto, reproduce el Write-Host e imprime que "4 es lo mismo que 4".

- El segundo condicional es también es un if pero esta vez compara strings. En este caso compara si el string "Hello" es lo mismo que "Hello". Al ser afirmativo, usa otra vez el Write-Host con el mensaje "Ambos strings son iguales"

- El tercer condicional usa un if-else. Si las variables x e y son iguales, dará un mensaje, y si no lo son, el else tomará el protagonismo.

### Comparison Operators
Aquí utiliza las expresiones de comparación.

-eq comprueba si son iguales.

-gt comprueba cual de las variables es mayor.

-ge comprueba cual de las variables es mayor o igual.

### Comprobación de Strings
- like comprueba si un string empieza con el otro string.

- -notlike hace justo lo contrario al de arriba.

- -match comprueba si una string contiene otra string.

- -notmatch comprueba si una string no contiene otra string.

- -constains comprueba si una lista contiene un número o un string.

- -notcontains comprueba si una lista no contiene un número o un string.

- -in devuelve un boolean con true si hay un string o número dentro de una lista y uno con false si es que no.
