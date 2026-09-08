lsattr muestra si un archivo tiene algún atributo especial
chattr permite modificar/asignar atributos especiales para ese archivo
-V muestra lo que está haciendo el comando

por lo que si hago un cp /etc/hosts prueba, y le meto chattr +i -V prueba, lo que hice fue hacerlo que sea inmortal no lo pueden borrar ni modificar
para borrar tendrian que hacer chattr -i -V prueba y listo hacen un rm prueba
