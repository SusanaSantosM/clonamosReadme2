# Ejercicio de clase

## Pasos para clonar un repositorio
1. Abrimos la terminal.
2. Abrimos el repositorio que queremos copiar de git hub.
3. En la terminal ponemos _$ git clone -o pruebasReadme https://github.com/danielcastelao/pruebasReadme_.
4. Nos ubicamos en la carpeta clonada _$ cd audacity_.
5. Creamos nuestro repositorio en git hub.
6. Lo añadimos en la terminal _$ git remote add origin https://github.com/miusuario/mirepo.git_.
7. Luego con _$ git remote -v_ vemos los repositorios copiados configurados
    origin https://github.com/SusanaSantosM/clonamosPruebas.git (fetch)
    origin https://github.com/SusanaSantosM/clonamosPruebas.git (push)
    pruebasReadme https://github.com/danielcastelao/pruebasReadme.git (fetch)
    pruebasReadme https://github.com/danielcastelao/pruebasReadme.git (push)
8. Ahora podemos subir cualquier modificacion al repositorio con _git push -u origin master_.
9. En caso que el autor modifique el codigo de su repositorio lo podemos lo actualizariamos con un pull _$ git pull --rebase repo_auda master_.

## Con fork y clonar
1. El fork lo encontramos en git hub.
2. Vamos al repositorio que queremos clonar y le damos en el boton *fork*.
3. Luego se abrira un repositorio en nuestro github donde podemos modificar el nombre.
4. Ahora ya podemos clonar el respositorio desde nuestro propio github _$ git clone https://github.com/miusuario/audacity.git_ .
5. Nos ubicamos en la carpeta creada en nuestro computador _$ cd audacity_.
6. Ahora podemos hacer modificaciones y hacer commits.
7. Lo actualizamos con _$ git push origin master_.


