# Taller_gitbash
mi primer taller de git

1. lo primero que se debe hacer es Crear un directorio que en este caso fue  llamado "Taller_gitbash":
   - El comando `mkdir Taller_gitbash` crea un nuevo directorio llamado "Taller_gitbash".
  
2. se cambia al directorio "Taller_gitbash":
   - El comando `cd Taller_gitbash' mueve al directorio recién creado.

3. El comando `git init Taller_gitbash` crea un repositorio Git vacío dentro del directorio "Taller_gitbash".


4. se Configura el nombre de usuario y correo electrónico globalmente para Git:
   - El comando `git config --global user.name "valentina-06"` establece el nombre de usuario.
   - El comando `git config --global user.email "valentinaquinterov06@gmail.com"` establece la dirección de correo electrónico.

5.  El comando `git config --list` muestra la configuración actual de Git, incluyendo el nombre de usuario y correo electrónico.

6. se Crea una nueva rama llamada "feature":
   - El comando `git checkout -b feature` crea una nueva rama llamada "feature".

7. Creación de un archivo "index.html":
   - El comando `touch index.html` crea un archivo vacío llamado "index.html" en el directorio actual.

8. El comando `git status` muestra el estado actual del repositorio.

9. El comando `git add index.html` agrega el archivo "index.html" al área de preparación para el próximo commit.

10. - El comando `git commit -m "mi primer commit"` crea un commit con el mensaje "mi primer commit".
    - El commit contiene el archivo "index.html" en su estado actual.

11. Verifica nuevamente el estado del repositorio:
    - El comando `git status` muestra que no hay cambios pendientes y que no hay archivos no rastreados.
