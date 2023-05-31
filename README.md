# Encriptador-Texto

Challenges-Oracle-One: 

La aplicación forma parte del primer Challenge propuesto por Alura Latam para las capacitaciones presentes en el programa elaborado por Oracle Next Education (ONE).

Este código es un ejemplo de una función de encriptación que toma un mensaje de texto y lo encripta utilizando reglas específicas de sustitución. Aquí está la explicación paso a paso del código:

Se declaran varias variables que almacenan referencias a elementos del documento HTML utilizando el método querySelector de la interfaz document. Estos elementos se seleccionan mediante selectores de clase (.) o identificadores (#):

botonEncriptar: hace referencia al botón con la clase "btn-encriptar".
muneco: hace referencia a un contenedor con la clase "contenedor-muneco".
h3: hace referencia a un contenedor con la clase "contenedor-h3".
parrafo: hace referencia a un contenedor con la clase "contenedor-parrafo".
resultado: hace referencia a un elemento con el id "resultado-final".
Se asigna la función encriptar al evento onclick del botón botonEncriptar. Esto significa que cuando se haga clic en el botón, se ejecutará la función encriptar.

La función encriptar se define y se ejecuta cuando se hace clic en el botón. Realiza los siguientes pasos:

Llama a la función ocultarSeccionDos para ocultar ciertas secciones de la página.
Llama a la función recuperarTextoArea para obtener el texto ingresado en un área de texto con la clase "area".
Llama a la función encriptarTexto pasando el texto obtenido del área de texto.
Asigna el resultado de la encriptación al contenido del elemento resultado utilizando la propiedad textContent.
La función recuperarTextoArea obtiene el valor del área de texto con la clase "area" utilizando el método querySelector y devuelve ese valor.

La función ocultarSeccionDos agrega la clase "ocultar" a los elementos muneco, h3 y parrafo. Esto oculta esos elementos en la página al agregarles esa clase.

La función encriptarTexto toma un mensaje de texto como argumento y realiza una encriptación utilizando una serie de reglas de sustitución. La encriptación se realiza mediante un bucle for que recorre cada carácter del texto. Dependiendo del carácter, se realiza una sustitución específica según las reglas establecidas. El texto encriptado se va construyendo y se almacena en la variable textoFinal. Al final, se devuelve el texto encriptado en minúsculas.

En resumen, este código implementa una función de encriptación que sustituye ciertos caracteres del texto original según reglas específicas y muestra el resultado en un elemento HTML.


