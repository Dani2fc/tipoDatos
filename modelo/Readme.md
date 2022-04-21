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