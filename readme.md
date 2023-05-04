Para subir un repositorio a git hay que seguir los siguientes pasos:
    1-abres la consola de la carpeta que quieras subir y creas un repositorio con el mismo nombre en git
    2- en la consola pones git init, estp creará un repositorio de git en una carpeta oculta llamada .git
    3-en la pagina de github copias el texto que hay en el cuadrado que hay bajo este texto"…or create a new repository on the command line"
    y lo pegas en la consola.


    si quieres actualizar los archivos en los que estás trabajando.

    1- en la consola pones git add seguido del nombre del archivo o archivos que quieres añadir(separados con espacios). Si quieres añadir todos los archivos de la carpeta hay que poner "add ."IMPORTANTE EL ESPACIO ANTES DEL PUNTO. esto aun no sube del todo el archivo, lo deja en el "storage" que es un estado que indica que los cambios están preparados
    2- en la consola, escribes "git commit"(sin las comillas) esto es una confirmación del git add, los archivos están a punto de subirse pero aun no es el ultimo paso. el git commit te obliga a poner un comentario, para facilitar su uso es recomendable poner /git commit -m"el comentario que quieras"/ sin las barras. el git commit sirve para tener preparados los archivos que quieras para subir a git pero seguir trabajando con otros.
    3- por ultimo escribimos en la consola "git push" esto ya subirá definitivamente el archivo a git. si pones -m y un texto puedes incluir un mensaje para describir los cambios.

    para saber en que estado están los archivos puedes usar un "git status" en la consola y te imprimirá el estado de los archivos.
    también en el directorio de la izquierda hay indicadores para saber en que estado están los archivos.
    git init

aa