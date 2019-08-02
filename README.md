# linux
Comandos basicos

```
sudo useradd -m -g Usuarios -G gestion - s /bin/bash usuario

-m: Crear automáticamente la carpeta del usuario el la carpeta /Home/<NombreUsuario>
-g: grupo principal al que sera agregado
-G: Grupos secundarios al que pertenecerá.
-s: Shell que utilizara por defecto el usuario.
usuario: Nombre del usuario.
```

```
groupadd grupo
sudo useradd -m -g grupo_ -s /bin/bash usuario
passwd usuario
```
Encontar archivo de mas de 100M
```
find . -type f -size +100M -ls
```
