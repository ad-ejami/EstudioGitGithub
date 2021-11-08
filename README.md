# instalacion de git en linux
```
sudo apt-get install git
```
# Creacion de proyecto git
```
git init //inicia un repositorio git vacio en el directorio donde se ejecuta el comando
```

# Saber el estado del archivo
```
git status //nos dice el estado del proyecto, siempre hay que estar pendiente de los cambios, es recomendable ejecutarlos antes de hacer un commit
```
# remove
```
git rm <name_file>
git rm --cached <name_file> //el usar este comando con (--cached) lo que hace es eliminar la version del archivo (mas no el archivo) de la memoria ram
//de esta forma se puede eliminar la version antes de hacer commit al repositorio
```

# Configuracion del usuario
```
git config --global user.name "user_name"  //Configuracion del nombre de usuario
git config --global user.email "user_email" //Configuracion del correo del usuario
#Hacer los primeros commits
git commit -m "mensaje" //subir los cambios al repositorio, es de buenas practicas el dejar un mensaje explicando los cambios que se realizo
git commit -am "mensaje" //guarda en stage y hace commit de una vez, solo funciona con archivos hechos git add anteriormente
```
# revisar la historia del archivo
```
$git log <name_file> //historia del los commits, nos muestra los tags
$git show <name_file> //nos muestra los ultimos cambios hechos en el archivo
$git diff <tag_name_file_v.a> <tag_name_file_v.b> //comparacion de los distintos commits hechos
$git diff //usar solo este comando me da los cambios que se hizo en staging y los cambios hechos en el disco duro
```
# recupera antiguas versiones
```
$git reset <tag_name_file_v> //nos permite volver a una version anterior
```
## hay dos tipos de reset
```
$git reset <tag_name_file_v> --hard //Todo vuelve al estado anterior
$git reset <tag_name_file_v> --solf //volvemos al estado anterior pero lo que tenemos en staging sigue en staging
```
**que es staging?** --> es el estado del archivo o archivos donde le hemos dado el comando (git add .) es decir tenemos un estado listo para hacer commit
tambien tenemos
```
$git reset HEAD //Sacamos los archivos del area del staging, No para borrarlos ni nada de eso, solo para que los últimos cambios de estos archivos no
```
se envíen al último commit, a menos que cambiemos de opinión y los incluyamos de nuevo en staging con git add, por supuesto
