permiso del directorio que le precede, al mismo del archivo

en vez de prevalecer el del archivo prevalece el de la capeta contenedora del archivo

por ejemplo si un archivo tiene 777, vos estando fuera del root y fuera del grupo y propietario del archivo ya que es pepe:pepe, 
podes borrar un archivo que estaba dentro de la carpeta esta y eso que el archivo tenia 644 pero la carpeta tenia un wx, para otros, aun asi los puede borrar

para evitar esto puedo estando como pepe cambiar esa x por una t la cual chmod +t nombrecarpeta hara que si vuelvo y veo el archivo estando como usuario otro normal no lo pueda borrar o renombrarlos
