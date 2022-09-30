# Curso Git

## Cuenta: Creación, sincronización, configuración de perfil y llaves SSH

El siguiente comando nos generara una llave **SSH** :

`chars@warMachine:~$ ssh-keygen -t rsa`

Nos pedira un nombre para el archivo y nos solicitara crear una contraseña, que es opcional.

**Todo esto se hizo desde la carpeta home, se llega con el siguiente comando `cd` y presionamos la tecla enter.**

Con el siguiente comando podremos acceder a la key **SSH**:

`chars@warMachine:~$ cat github.pub`

* Se debe tener en cuenta que solo se puede hacer una llave por maquina.