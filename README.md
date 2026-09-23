# Optativa-Pedro-Morilla
---
## Parte 1: Instalación y configuración

1. **Instala Visual Studio Code**  
   Descarga e instala VS Code desde [code.visualstudio.com](https://code.visualstudio.com/).
   ![Visual Studio Code Instalado](/Optativa-Pedro-Morilla/img/VS.png)

## Parte 2: Primeros pasos con la consola del navegador

1. Abre tu navegador web (Chrome, Firefox, Edge, etc.).
  ![Navegador](/img/navegador.png)
2. Accede a cualquier página web y pulsa `F12` o `Ctrl+Shift+I` para abrir las herramientas de desarrollo.
  ![f12](/img/f12.png)
3. Haz clic en la pestaña "Consola".
  ![console](/img/console.png)
4. Prueba los siguientes comandos uno por uno y observa el resultado:
   ```js
   2 + 2
   console.log("¡Hola, mundo!")
   let nombre = "Anita"
   nombre
   ```
  ![Pruebas](/img/pruebas.png)
## Parte 3: Tu primer archivo HTML + JavaScript

1. Crea una carpeta llamada `00JSyEntorno` dentro de tu espacio de trabajo.
  ![carpeta](/img/Carpeta.png)
2. Dentro de esa carpeta, crea un archivo llamado `hola.html`.
  ![html](/img/html.png)

3. Escribe el siguiente código en `hola.html`:
   ```html
   <!DOCTYPE html>
   <html lang="es">
   <head>
     <meta charset="UTF-8">
     <title>Hola JS</title>
   </head>
   <body>
     <script>
       console.log("¡Hola, mundo!");
       let nombre = "Ana";
       console.log("Bienvenida, " + nombre);
     </script>
   </body>
   </html>
   ```
   ![escribir html](/img/escribir-html.png)
4. Desde VSCode abre el archivo `hola.html` en tu navegador.
![live](/img/open.png)
![nav](/img/nav.png)

5. Observa el resultado en la consola del navegador.
  ![salida](/img/salida.png)

## Parte 4: Experimenta

- Cambia el valor de la variable `nombre` por el tuyo y recarga la página.
- Añade una línea que sume dos números y muestre el resultado con `console.log`.
- Añade otra variable con tu apellido y muestra un saludo completo.
- Modifica el saludo para que incluya el apellido en mayúsculas. Busca en la consola cómo convertir una cadena a mayúsculas. Para ello usa un literal de cadena (con tu nombre) seguido del operador punto (`.`) 
- Modifica el archivo para que el saludo se muestre en la página web en lugar de la consola. Usa `document.body.innerHTML` para esto:
   ```js
   document.body.innerHTML = "<h1>¡Hola, " + nombre + "!</h1>";
   ```
- Publica tu proyecto en el repositorio de GitHub y usa GitHub Pages para alojarlo. Sigue [esta guía](https://docs.github.com/es/pages/getting-started-with-github-pages/creating-a-github-pages-site) para hacerlo.
![mod html](/img/parte4-html.png)
![nav 4](parte4.png)
## parte 5: formulario HTML + JavaScript
1. Crea un archivo llamado `formulario.html` en la misma carpeta `00JSyEntorno`.
2. Crea un archivo llamado `formulario.js` en la misma carpeta `00JSyEntorno`.
  ![ficheros](/img/ficheros.png)
3. Escribe el siguiente código en `formulario.html`:
4
5. Escribe el siguiente código en `formulario.js`:
 
   ![html](/img/texto-html.png)
   ![alt text](/img/texto-js.png)
6. Desde VSCode abre `formulario.html` en tu navegador y prueba el formulario.
![form](/img/formulario.png)
   
## Parte 6: Preguntas de reflexión

1. ¿Qué hace `console.log`?
  Hace que te muestre por la consola el resultado que le asignes
2. ¿Qué ocurre si cambias el valor de la variable desde la consola? ¿Se puede?
  Se ha podido desde la consola porque ahí puedes definir de nuevo las funciones 
3. ¿Para qué sirve la consola del navegador en este contexto?
  Para comprobar que el formulario funciona correctamente 
4. Para qué sirve el archivo HTML en este contexto?
  Para poder usar las funciones del formulario
5. ¿Por qué es una buena práctica separar el código JavaScript del HTML?
  Para tener un código más limpio y más velocidad de carga
6. Por qué se llama Vanilla JavaScript?
  Porque se usa el lenguaje nativo, sin aditivos
7. Cuándo se usa JavaScript puro y cuándo se usan frameworks o librerías como REACT?
8. Cómo se define una función en JS
  function nombre_funcion(){'lo que le pidas a la función';}
9. Sobre el código demuestra la diferencia entre let y const
  Con el const al ser constante no se pueden reasignar y el let si se puede reasignar 
  ![const](/img/constante.png)
  ![let](/img/let.png)
10. Indica en el código:
   1. Si puede evitarse el uso de let. Qué hace
   2. Cuántos eventos hay en el código, cuáles son y para qué sirven



