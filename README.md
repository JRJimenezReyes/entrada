# Entrada


## Autor

José Ramón Jiménez Reyes 2022


## Licencia


Este proyecto tiene licencia del MIT - veáse el fichero de [licencia](LICENSE.md) para más detalles.


## Propósito

Librería que facilita las lecturas por consola de diferentes tipos de datos, permitiendo a los alumnos obviar dichos detalles.

Realiza lecturas de diferentes tipos de datos forzando que el usuario introduzca el tipo de datos esperado.


## Métodos

- `static String cadena()`
    
    Método estático que lee una cadena por teclado.
    
- `static char caracter()`

    Método estático que lee un caracter por teclado y se asegura que el valor introducido es compatible con un caracter.
    
- `static int entero()`

    Método estático que lee un entero por teclado y se asegura que el valor introducido es compatible con un entero.
    
- `static long enteroLargo()`

    Método estático que lee un entero largo (long) por teclado y se asegura que el valor introducido es compatible con un entero largo.
    
- `static float real()`

    Método estático que lee un real (float) por teclado y se asegura que el valor introducido es compatible con un real.
    
- `static double realDoble()`

    Método estático que lee un real de doble precisión (double) por teclado y se asegura que el valor introducido es compatible con un real de doble precisión.

## Uso con gradle

El fichero `build.gradle` debe contener lo siguiente:

~~~gradle
repositories {
    ...
	maven { url 'https://jitpack.io' }
}

dependencies {
    ...
	api 'com.github.JRJimenezReyes:entrada:+'
}
~~~

Se puede sustituir el `+`por la versión concreta: `api 'com.github.JRJimenezReyes:entrada:1.0.2'`
