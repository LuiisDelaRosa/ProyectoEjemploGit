# Proyecto Ejemplo Git

## Descripción
Este proyecto contiene un programa simple en Java llamado `HolaMundo.java`, que imprime un mensaje en la consola. El objetivo de esta tarea es aprender a usar Git para crear, modificar y gestionar un repositorio, así como a ignorar archivos innecesarios.

## Instrucciones de uso
Para ejecutar el programa `HolaMundo.java`, sigue estos pasos:
1. Asegúrate de tener **Java** instalado en tu sistema.
2. Navega hasta la carpeta donde se encuentra el archivo `HolaMundo.java`.
3. Compila el archivo usando el siguiente comando:
   ```bash
   javac HolaMundo.java

## Comandos utilizados
1. git init - Inicializa un nuevo repositorio en la carpeta.
2. git add <archivo> - Añade archivos al área de preparación.
3. git commit -m "<mensaje>" - Realiza un commit con el mensaje especificado.
4. git remote add origin <URL> - Conecta el repositorio local a un repositorio remoto.
5. git push -u origin main - Sube los cambios al repositorio remoto en la rama main.
6. git status - Verifica el estado del repositorio y muestra los archivos rastreados y no rastreados.

## Notas sobre el archivo
El archivo .gitignore se creó para evitar que ciertos archivos sean rastreados y subidos al repositorio. En este caso, se configuró para ignorar todos los archivos con la extensión .log, como debug.log, ya que este tipo de archivo suele contener información temporal o de depuración que no es necesario incluir en el repositorio.
