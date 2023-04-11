# undiasinluismi
git clone https://github.com/Javi-Prieto/undiasinluismi.git
touch README.md
git add .
git commit -m "Initial Commit"

Creamos el archivo para ignorar los documentos y ficheros
touch .gitignore
Creamos los archivos ocultos
touch privado.txt
mkdir privada
Editamos el archivo .gitignore y añadimos los nombres de los archivos y directorios

Añadimos los cambios
git add .
Añadimos la etiqueta y le hacemos un commit a la vez
git tag -a "v0.1" -m "I've done the private files"
Le realizamos el commit a los cambios
git commit -m "I've done the private files"
Subimos los cambios
git push

Creamos una nueva rama
git checkout -b v0.2
Creamos el fichero en la rama
touch 2.txt
Añadimos y commiteamos
git add .
git commit -m "Initial Commit"
Creamos la rama remota y la conectamos con la local a su vez subimos los cambios
git push --set-upstream origin v0.2

