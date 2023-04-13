Inicialmente el programa no desplegaba ninguna información al momento de ingresar algún valor alfanumérico y dar clic en el botón, por lo que se realizaron los siguientes cambios correctivos
y preventivos:

1. Línea 45: Fue comentada para tener un control de la versión anterior, el error era que el número generado al azar siempre era 1. En la línea 46 se corrigió el error permitiendo generar un número aleatorio del 1 al 100.

2. Líneas 74-79: Se comentó debido a que no permitía el correcto funcionamiento del programa por lo que la solución fue comentar el fragmento de código.

3. Línea 83: El error consistía en el mensaje, ya que a pesar de adivinar el número se mostraba el texto que se había perdido el juego. La solución fue corregir el texto.

4. Línea 84: No existía un error, únicamente por estética se cambió de color negro a verde.

5. Línea 87: El error consistía en que, al momento de dar clic en el botón para jugar nuevamente no se generaba un número nuevo, la solución fue agregar la función correspondiente para generar un número entero aleatorio.

6. Línea 90: Se encontraron 2 errores, 1 era la falta de ortografía por lo que la solución fue sustituir "Pérdistes" por "Perdiste". El 2do error era el mensaje, ya que al finalizar le juego mostraba el texto de felicitaciones en lugar de Perdiste.
    6.1 Se agregó la funcionalidad de mostrar el número aleatorio correcto, concatenando la variable randomNumber.

7. Línea 92: No existía un error, únicamente por estética se cambió de color verde a rojo.

8. Línea 97: Se cambió el color a negro.

9. Línea 109 y 117: El error consistía en la interpretación de mayúsculas y minúsculas ya que la letra "e" de event se encontraba en minúscula (addeventListener) y la solución fue cambiarla por mayúscula (addEventListener).

10. Línea 136: Fue comentada para un control de versión y el error consistía en que aún se cargara de nuevo la página seguía mostrando el mismo número aleatorio. La solución se encuentra en la línea 138 en donde al momento de dar clic en el botón "comienza un juego nuevo" cambia el número aleatorio.