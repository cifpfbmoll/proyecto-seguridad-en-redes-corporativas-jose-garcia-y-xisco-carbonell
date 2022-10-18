# proyecto-seguridad-en-redes-corporativas-jose-garcia-y-xisco-carbonell
proyecto-seguridad-en-redes-corporativas-jose-garcia-y-xisco-carbonell created by GitHub Classroom

1. INSTALACIÓN DEL S.O. UBUNTU
2. Configuración del arranque GRUB:
  2.1  Establecer contraseña de arranque:
  2.2 Establecer permisos fichero de configuración de arranque
  2.3 Obligar al uso de contraseña en el modo “single user”
    2.3.1 Establecemos una contraseña al usuario root
    2.3.2 Establecemos permisos de solo lectura al Usuario root para el fichero de arranque
    2.3.3 Para que te aparezca el GRUB:
3. Configuración de usuarios y grupos.
  3.1 Creacion de nuevo usuario 
  3.2 Añadimos el usuario nuevo a sudoers.
  3.3 Añadimos al usuario al grupo sudo.
  3.4 Complejidad
    3.4.1 Instalación de libpam-pwquality
    3.4.2 Editamos el archivo de configuración pwquality.conf que está en /etc/security/
    3.4.2.1 Editamos el archivo common-password que esta en /etc/pam.d . Donde esta retry lo dejamos en 3.
  3.5 Reutilizacion de contraseñas
  3.6 Crackear contraseña
  3.7 CIFRAR CONTRASEÑAS EN SHA512
  3.8 CADUCIDAD E INTERVALO DE TIEMPO PARA CAMBIO
  3.9 CONFIGURACIÓN DEL ENTORNO
    3.9.1 Tiempo de bloqueo
    3.9.2 TIMEOUT
    3.9.3 Bloqueo de cuenta tras varios fallos de auntenticacion
    3.9.4 Configurar las cuentas de servicio con el parámetro nologin
    3.9.5 Establecer los valores por defecto del parámetro umask
    3.9.6 Restringir el acceso al comando su
4.ACTUALIZACIONES DE SOFTWARE
  4.1 CONFIGURACIÓN DE ADVANCED PACKAGE TOOL
  4.2 REGISTROS
    4.2.1 Configurar SYSTEM AUDITING
    4.2.2 CONFIGURACION RSYSLOG
    
  




  



