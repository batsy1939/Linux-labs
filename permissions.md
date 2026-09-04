echo "hola probando" > file.txt te inserta lo que pongas en el archivo
echo "adios" >> file.txt no te pisa lo que metiste antes al archivo
touch puedes crear un archivo
nano tambien
^O guardas y ^X salis
ls -l muestra los archivos de la carpeta con sus respetctivos permisos a grupo pertenece y quien es el propietario y demas permisos
rwx| r leer w escribir x ejecutar
p g o propietario grupos y otros
adelante de todo aparece un . si es un archivo una d si es un directorio
propietario grupo esta ordenado el permiso
.rw-rw-r-- es un archivo con el permiso para propietario y personas afines al mismo grupo que puedan leer y escribir el archivo

---
intente redirigir a /etc/passwd uno de los archivos criticos del sistema pero el permiso fue denegado
solo tenemos permiso de lectura no escritura
-rw-r--r--
---
al archivo /etc/shadow por motivos de seguridad no lo mostrare pero ahi se encuentran todas las contrasenas hasheadas o encriptadas
tambien verifique que metodo de crifrado esta usando como se puede ver para la creacion y encriptacion de nuevos usuarios y contrasenas
---
Asignar permisos primero tenngo que acceder como root
