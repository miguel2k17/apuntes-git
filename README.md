## Curso Git desde Cero
Sistema de control de versiones para el mantenimiento eficiente y
confiable de archivos.

## Zonas de Git
1.Directorio de trabajo
2.Zona de preparacion.
3.Directorio Git

## Algo sobre GIT
Como se observa se confirma que el archivo a sido cambiado. Y más adelante en el tiempo será posible regresar a este punto del estado del repositorio.

## Terceros cambios al archivo
Es recomendable (NO obligatorio)  crear un archivo con este nombre  ya que este es el archivo “index” que lee GITHUB

## Aportes desde otra cuenta
Este texto fue apostado desde la cuenta pegasus2k14

## Conexion via SSH a Github

## Esta linea se agrego desde un equipo Windows conectando el repositorio local con el repositorio remoto via HTTPS.

## Este cambio nos permitira probar una conexion al repositorio remoto via SSH

## Confoguracion SSH en Windows
1. Creamos una carpeta llamada 'llaves-ssh' en el disco 'C' para evitar problemas de rutas 

2. configuramos el comando 'ssh-keygen -t rsa -C "miCorreo@ejemplo.com"'. El correo debe ser el mismo con el que nos registramos en GITHUB, dejamos el passprase vacio y damos Enter
Cuando nos pida la ruta escribimos '/c/laves-ssh/github_rsa'

3. Iniciamos ssh-agenten background ejecutando el comando 'eval $(ssh-agent -s)'.

4. Agregamos la llave ssh generada al ssh-agent ejecutando el comando 'ssh-add /c/llaves-ssh/github_rsa'.

5. Desde ahora  podemos hacer  PULL y PUSH sin que GITHUB nos pida datos e acceso
