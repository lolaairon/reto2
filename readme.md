Ejecuta git init en la terminal. Esto inicializará la carpeta/repositorio que tienes en tu computador local.
Ejecuta git add . en la terminal. Esto hará un seguimiento de los cambios realizados en la carpeta de tu sistema desde el último commit. Como es esta la primera vez que haces commit a los contenidos de la carpeta, se añadirán todos.
Ejecuta git commit -m "inserta Mensaje aquí". Esto preparará los cambios añadidos/rastreados en la carpeta de tu sistema para empujar a Github. Puedes reemplazar inserta el Mensaje aquí con cualquier mensaje de confirmación relevante de tu elección.
Ejecuta git remote add origin https://github.com/nombreDeUsuario/repositorio.git en la terminal. Aquí, nombreDeUsuario y repositorio serán reemplazados por los valores proporcionados en el enlace copiado. Esto conectará la carpeta existente en tu sistema local al repositorio de Github recién creado.
Ejecuta git remote -v. Esto hace algo de magia usando git pull y git push para garantizar que el contenido de tu nuevo repositorio de Github y la carpeta en tu sistema local sean los mismos.
Finalmente, ejecuta git push origin master para empujar tus archivos a Github. Ten en cuenta que la última palabra en el comando master, no es una entrada fija cuando se ejecuta git push, puede ser reemplazada por cualquier “nombre_de_rama” relevante.
He creado un aichivo de texto gitignore, en el las capturas.
Lo he dicho con un coomit lo que he hecho . 
Y ya esta subido al repositorio.
