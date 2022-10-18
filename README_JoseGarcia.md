# proyecto-seguridad-en-redes-corporativas-jose-garcia-y-xisco-carbonell
proyecto-seguridad-en-redes-corporativas-jose-garcia-y-xisco-carbonell created by GitHub Classroom

- INSTALACIÓN DEL S.O. UBUNTU
- CONFIGURACION DEL ARRANQUE GRUB:
   - Establecer contraseña de arranque:
   - Establecer permisos fichero de configuración de arranque
   - Obligar al uso de contraseña en el modo “single user”
   - Establecemos una contraseña al usuario root
   - Establecemos permisos de solo lectura al Usuario root para el fichero de arranque
   - Para que te aparezca el GRUB:
- CONFIGURACIÓN DE USUARIOS Y GRUPOS.
  - Creación de nuevo usuario 
  - Añadimos el usuario nuevo a sudoers.
  - Añadimos al usuario al grupo sudo.
  - Complejidad
    -  Instalación de libpam-pwquality
    -  Editamos el archivo de configuración pwquality.conf que está en /etc/security/
    -  Editamos el archivo common-password que esta en /etc/pam.d . Donde esta retry lo dejamos en 3.
  - Reutilizacion de contraseñas
  - Crackear contraseña
  - Cifrar contraseñas con SHA512
  - Caducidad e intervalo de tiempo para cambio
  - Configuracion del entorno
    -  Tiempo de bloqueo
    -  Timeout
    -  Bloqueo de cuenta tras varios fallos de auntenticacion
    -  Configurar las cuentas de servicio con el parámetro nologin
    -  Establecer los valores por defecto del parámetro umask
    -  Restringir el acceso al comando su
- ACTUALIZACIONES DE SOFTWARE
  - Configuración de Advanced Packaage Tool
  - Registros
    -   Configurar SYSTEM AUDITING
    -   Configuración RSYSLOG
    
  




  



