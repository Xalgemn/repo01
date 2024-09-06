1.1: He creado el directorio usando "mkdir", luego usando "git init repo01" para convertirlo en repositorio, cpn "cd repo01" entramos dentro del repositorio.
1.2 He creado el documento "readme.md" dentro del repositorio clicando "New file" e introduciendo el nombre del archivo
1.3 Primero se ha llevado el archivo al staging area usando "git add" para luego llevarlo al repositorio local usando "$git commit", en estos momentos se encuentra en el lifecycle del repositorio local
1.4 No deja hacer el push debido a que primero hay que preparar el repositorio remoto y asociar uno con el otro
1.5 No aparece nada porque aun no estan asociados
1.6 Se ha creado el repositorio en github, se han añadido el usuario y correo de la cuenta de github usando "git config --global user.name" y "git config --global user.email" y se han vinculaod los repositorios con "git remote add origin https://github.com/Xalgemn/repo01.git"
1.7 El comando ahora funciona debido a que ambos repositorios estan vinculados
1.8 se ha usado "git push origin" para subir los cambios al repositorio remoto
1.9 En el repositorio se muestra el archivo que hemos subido, el mensaje que hemos puesto en el commit y hace cuanto fue creado, ademas indica cuantos commits se han hecho y permite volver a los anteriores