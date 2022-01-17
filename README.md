# Proyecto Flutter

## Instalar el SDK de Flutter
Para instalar Flutter de una manera rapida y sencilla puedes utilizar snapd.

### Instalar Snap
En Debian 10 (Buster) y Debian 9 (Stretch), snap puede ser instalado desde la consola:
```sh
$ sudo apt update
$ sudo apt install snapd
```
Reinicia tu sistema, de esta forma aseguraras que las rutas de acceso instantáneo se actualicen correctamente.

Despues, debes instalar el paquete snap `core` para obtener el último snapd.
```sh
$ sudo snap install core
core 16-2.52.1 from Canonical✓ installed
```

### Instalar Flutter usando snapd
Despues de descargar snapd, puedes instalar flutter usando la Snap Store, o desde la consola:
```sh
$ sudo snap install flutter --classic
flutter 0+git.671983f from Flutter Team✓ installed
```
> Nota: Al tener snap instalado en tu sistema, puedes utilizar el siguiente comando para mostrar la ruta del Flutter SDK.
```sh
  $ flutter sdk-path
```
