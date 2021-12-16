# GIT - GITHUB

### ¿Qué es Git y para qué sirve?

Git es un sistema de control de versiones distribuido de código abierto desarrollado por Linus Torvalds, el creador de Linux. El control de versiones distribuido permite a los desarrolladores descargar un software, realizar cambios y subir la versión que han modificado.
instalar git
https://git-scm.com/downloads # pagina oficial git
click en descarga for windows
ejecutar el instalador next - next
menu inicio escribir git click gitbas y escribir git --version

## ¿Qué es GITHub y para qué sirve?

Github es un repositorio online gratuito que permite gestionar proyectos y controlar versiones de código basados en git. Es muy utilizado por desarrolladores para almacenar sus trabajos dando así la oportunidad a millones de personas de todo el mundo a cooperar en ellos.

## Crear Cuenta:

https://github.com/ # pagina oficial de github

- Sign for GitHub - ingresar los email, password y name y listo cuenta creada
- email:xxxxx
- password: xxxxxxx
- username:xxxxxx

## Repositorio

- Un repositorio es la ubicación o ruta en la que se almacena toda la información de un proyecto como imágenes, código, carpetas, documentos, etc.
- Cada proyecto contaría con su propio repositorio único, por lo que la ruta de acceso será exclusiva para el proyecto.

### Cómo crear un repositorio en GitHub:

Con una cuenta en esta plataforma, cuyo registro es gratuito, puedes subir archivos a GitHub. Para ello, hay crear un repositorio en GitHub donde alojarlo siguiendo estos pasos:

- Utiliza el menú desplegable de la esquina superior derecha de cualquier página y selecciona Nuevo Repositorio. 🔔 ✚ click => 🔻
  Escribe un nombre para el repositorio. También puedes añadir una descripción al mismo
- Elige la visibilidad del repositorio: público, interno o privado.
- Selecciona Inicializar este repositorio con un README(opcional), que contendrá la información del proyecto y puede editarse en cualquier momento.
  Haz clic en Crear repositorio.

### Cómo subir el código de un proyecto al repositorio de GitHub:

Para subir un código previamente creado hay que hacer lo siguiente:

1. Abre la terminal en la carpeta donde se alojan los ficheros fuente y escribe el siguiente código:

- git init

2. Se habrá creado la carpeta .git con la información del proyecto. Añade los ficheros para subir el mismo con este comando:

- git add .

3. Prepara los ficheros que quieres subir con una pequeña explicación acerca de los cambios:

- git commit -m “Creado el proyecto inicial”

---

- git status: nos muestra el estado de una rama y qué cambios hay sin confirmar.
- git log # muestra los commit realizados
  si no crea los archivos y sale on fatal error escribir:
  - git config --global user.email "mail de la cuenta"
  - git config --global user.name xxxxx
- git branch -M main # indica subir a la rama principal

4. Debes subir los cambios a GitHub. Para ello tienes que saber la ruta del repositorio (acabada en .git) que está en Clone or Download, el botón verde de la página del proyecto. Luego añade el repositorio desde la terminal con este comando:

- git remote add origin URLrepositorio.git

5.  Sube los cambios con el siguiente comando:

- git push origin main. #hacer la sincronizacion del local con el remote
  click para sincronizar con el browser la cuenta

## Modificar Repositorio

- git status
- git add .
- git commit -m “Comentario”
- git push origin main

# MARKDOWN

### Que es Markdown?

Es un lenguaje de marcado que facilita la aplicación de formato a un texto empleando una serie de caracteres de una forma especial. En principio, fue pensado para elaborar textos cuyo destino iba a ser la web. pero también podemos emplearlo para cualquier tipo de texto.
Markdown es realmente dos cosas: por un lado, el lenguaje; por otro, una herramienta de software que convierte el lenguaje en HTML válido.
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet # pagina de tips markdown.

# VISUAL STUDIO CODE

### Principles extensiones de vscode

- JavaScript (ES6) snippets// estension para js
  HTML Snippets// extension para html
- css snippets // extension para css
- Python // extension para python
- Python for VSCode // extension para python
- Path IntelliSense // ayuda a encontrar la ruta de una manera muy rápida y dinámica.
- Auto Close Tag // soporte de etiqueta cerrada
- Auto Rename Tag // cambia automáticamente el nombre de una etiqueta HTML.
- Beautify //indenta código HTML, CSS, JavaScript y JSON
- Bracket Pair Colorizer 2 // parametrizar una serie de colores para identificar cada pareja de parentesis, llaves.
- Material Icon Theme // iconos de archivos
- Better Comment // colorea comentarios con los siguientes caracteres: \* color verde ! rojo
  ? celeste TODO naranja.
- Markdown All in One // atajos de codigo markdown.
- Import Cost // muestra el tamaño de la libreria
- ESLint // npm install -g eslint permite verifcar errores en el codigo(variables no usadas) sintaxis, etc.
- Prettier // formateo de codigo. ir a setting en el input escribir formatter y en la opcion default formatter seleccionar Prettier - Code Formatter. tambien click en on Paste y on Save
- Polacode // copia fragmentos de codigo en imagen
- Live Server // servidor de desarrollo local.
- https://app.diagrams.net // pagina ofical de draw.io (dibujar todo tipo de diagramas)
- Draw.io Integration// integracion de la herramienta de diagramas en vscode.
- kite// autocompletado para python, js, etc.

## EMMET.

Es un plugin que permite escribir código HTML como expresiones que pueden ser analizadas de forma dinámica, y producir una salida en función de lo que se escribe en la abreviatura.

- https://docs.emmet.io/cheat-sheet/ # ayuda de emmet
- nav.menu>a[href="seccion$"]\*5{Seccion$} # crea un nav con 5 etiquetas a con el href="seccion#" con el contenido de seccion#.
- main>section#seccion$.section*5>h2{section$} # crea una etiqueta main con 5 etiquetas section con un id
  seccion# con una clase section y con un hijo h2 con contenido section# dentro de cada section.
  Generador de colores.
- https://htmlcolorcodes.com/es/ # pagina que genera codigo de colores dinamicamente.
