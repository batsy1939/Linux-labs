Apuntes y comandos prácticos sobre la gestión de descriptores de archivos estándar y personalizados.

---

### Descriptores estandar:
  stdin: (0) entrada estandar, recibe datos de teclado
  stdout: (1) salida estándar, muestra resultado de comandos 
  stderr: (2) salida de erroe, muestra los mensajes de errroes de comandos

---

### Descriptores personalizados y redirecciones
  exec 4<> file => abre un archivo de lectura(<) y escritura(>) y lo asocia a ese descriptor (4)
  pwd 4>&1 => redirige la salida hacia el stdout
  exec 4>&- => para cerrar la salida 4
