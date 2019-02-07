#TUTORIAL

##**¿Como hacer un nuevo repositorio?**

- Primero entras al link de github [Entrar a github](https://github.com/)

![Interfaz](/img/interfaz.png)

- En la esquina de lado derecho esta el símbolo de mas(+) y aparece la opción de New Repository te mandara este formulario

![Repository](/img/createrepository.png)

En esta parte te pide que pongas el nombre del repositorio, una descripción opcional de tu repositorio y si sera publico o privado.
Cuando terminas de rellenar los campos le das click en el botón Create Repository.

-Como ultimo paso te aparece la siguiente ventana donde esta el repositorio creado:

![Repositorio creado](/img/repository.png)

***

##**¿Como subir proyectos al github?**

>Para empezar a subir tus proyectos a git debes primero crear tu repositorio, ¿No sabes como hacerlo? Sigue los pasos que se muestran anteriormente.<

- Como primer paso se necesita hacer una carpeta con el nombre que desees, donde guardaras todos tus proyectos que necesitas subir al git.

- Abrimos nuestra terminal desde la carpeta donde estés guardando tus proyectos o tambien por medio de comandos se puede entrar a la carpeta para hacer esto necesitas utilizar el comando:

~~~
cd (nombre de la carpeta)
~~~

- Cuando estemos adentro de la carpeta en la terminal pondremos los siguiente comandos:

'git init'

Este comando solo se utiliza solo cuando es un nuevo proyecto

 Despues ingresamos el siguiente comando:

 'git status'

 Este comando nos sirve para ver los archivos que tenemos en la carpeta de nuestro repositorio

 Despues con el siguiente comando:

 'git add .'

 Con este comando se agrega al Repositorio

 Una vez agregado al repositorio proseguimos ingresar el siguiente comando:

 'git commit -m "Un comentario del archivo"'

 Este comando es para poner un comentario descriptivo del archivo que agregamos

 Despues de hacer el comentario procedemos a subir el archivo al github

 'git push -u origin master'

 Y eso seria todo para subir el proyecto al git.
