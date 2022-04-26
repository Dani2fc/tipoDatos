# Tipo de datos en java 

## Java Virtual Machine (JVM)

* Realiza una gestión eficiente de la memoria.
* Distribuye la memoria en dos zonas: Stack (pila y heap(montón))

### Stack 
* Se almacenan: variables locales, llamadas a métodos (parámetros y resultados), variables primitivas, refernecias a objetos del git.
* Memoria estática.

### Heap
* Es gestionado por el carbrige collector.
* Espacio de memoria en tiempo de ejecución donde se registran los objetos.
* Memoria dinámica.
* No posee estructura de asignació  de espacios.

### Variable
* Contenedor de memoria donde se almacena información.
* En java se declara con un tipo que se conservará durante todo su ciclo de vida en el interior de la aplicación.
* La variable debe de tener un nombre.
* Existen de tipo primitivo y referenciado.

## Primitivos 
* Contenedores de tamaño específico que almacenan valores y no tienen métodos.
* Ejemplos: boolean, char, byte, short, float, double, long
## Referenciados
* Almacenan las referencias de los datos.
* Estos se almacenan en una memoria llamada heap.
* Accsesible desde otras instancias de clase.
* Su ciclo de vida termina cuando no se necesita más.
* Mientras exista al menos una referencia activa en la zona de datos esta se mantendrá.
* Tan pronto como no haya más referencias la zona se considera inutilizada y se procede a su destrucción por parte del carbage collector.
* Un tipo referenciado puede no referenciar nada -> null.
* El operador "new" es para instanciación de una clase, es decir, reserva una dirección de área de memoria.

## Variable de referencia
* Caracteriza una instancia de clase, es decir, la dirección donde está el objeto.
* Contiene la dirección de un objeto cuyo valor por defecto es null.
* Durante una prueba de igualdad entre dos variables por referencia, son las direcciones de los objetos lo que se conmparan y no el contenido de los objetos en si mismos.
* Cuando se una referencia como argumento de un método es la dirección del objeto la que se pasa, y no el objeto en si mismo.