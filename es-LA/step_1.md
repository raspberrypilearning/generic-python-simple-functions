Al codificar, algunas veces querrás utilizar las mismas líneas de código varias veces dentro de tu secuencia de comandos o script. Alternativamente, puedes querer tener las mismas líneas de código ejecutadas cada vez que ocurre un cierto evento. Por ejemplo, cuando se presiona una tecla específica, o se escribe una frase en particular. Para tareas como esta, tal vez quieras considerar el uso de una **función**.

Las funciones son **nombradas** como bloques de código que realizan una tarea definida. La función más simple que puedes crear en Python se ve como esta:

```python
def hola():
    print('¡Hola Mundo!')
```

Tu le dices a Python que estás creando una nueva función usando la palabra clave `def`, seguida del nombre de la función. En este caso se llama `hola`. Los paréntesis después del nombre de la función son importantes.

Los dos puntos al final de la línea indican que el código dentro de la función se le agrega una sangría en la siguiente línea, igual como en un bucle `for` ó `while` o en `if`/`elif`/`else` bucle condicional.

Puedes **llamar** una función escribiendo su nombre con los paréntesis incluidos. Así que, para ejecutar la función de ejemplo, debes escribir `hola()`. Aquí está el programa completo:

```python
def hola():
     print("¡Hola Mundo!")

hola()
```


