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
