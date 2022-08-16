# Curso de Sistemas Operativos

## Pabloboset Montoya Marín
## Universidad Latinoamericana de Ciencia y Tecnología
## ULACIT
## 2022

Bitácota de comandos Debian más usados en clase

Ordenes basicas en terminal:
* -ls-  (Lista los ficheros de un directorio concreto)
* *cd nom_directorio*  (Cambia de directorio)
* *mv [ruta1]fichero1 [ruta2]fichero2*  (Mueve y/o renombra un fichero)
* *rm [archivo o directorio]*  (Elimina archivos o directorios)
* cp archivo1 archivo2  (Realiza una copia de un fichero)
* mkdir nom_directorio  (Crea un directorio)
* rmdir nom_directorio  (Elimina un directorio)
* chmod xxx nom_fichero  (Cambia los permisos de acceso de un fichero)
* chown usuario fichero/directorio  (Cambia el propietario de un fichero o directorio)
* chgrp grupo fichero/directorio  (Cambia el grupo)
* ps aux  (Muestra una lista de los procesos activos)
* kill -x  (Elimina un proceso)
* mount  (Se visualiza el listado de dispositivos montados)
* clear  (Borra la pantalla)
* sudo su  (Entrar a la sesión como root (necesario passwd))
* su nom_usuari  (inicio de sesión como otro usuario)


Ordenes de gestión de parquetes:
* apt-get install nom_paquete  (Instala un programa)
* apt-cache search nom_paquete  (Busca si está instalado un programa)
* apt-cache show nom_paquete  (Muestra la información de un progrema)
* apt-get update  (Actualiza lista de programas)
* apt-get dist-upgrade  (Actualiza todos los programas instalados)
* dpkg -l  (Lista todos los programas instalados)


Ordenes para la gestión de permisos:
* addgroup nom_grupo  (Crea un grupo)
* useradd -G nom_grupo nom_usuario
  passwd nom_usuario  (Crea un usuario y lo agrega a un grupo)
* deluser nom_usuario  (Elimina un usuario)
* chmod 777 nom_fichero  (Sa permisos de lectura, escritura y ejecución al fichero)
