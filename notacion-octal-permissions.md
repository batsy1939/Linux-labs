drwxr-xr-x
d = directorio
rwx 111 (2^0 + 2^1 + 2^2) = 7
r-x 101 (2**0 + 0 + 2**2) = 5
r-x 101 (2**0 + 0 + 2**2) = 5
rwx == 111, en posciones 210

r-xr---w-
r-x 101 = 5
r-- 100 = 4
-w- 010 = 2
nuestro permiso seria 542

mas facil asigna este valor 421 a rwx, entonces si tenes 101 sumas 4+1=5
si tenes 010 -w- sabes que es 2, ya que r no esta y vale 4 y x que vale 1 tampoco esta
