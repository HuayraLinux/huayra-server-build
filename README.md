huayra-server-build
====================

Entorno de live-build para generar iso de la edición servidor de Huayra GNU/Linux

Construir
=========

Usar sudo o permisos de root

$ sudo lb config
$ sudo lb build

En caso de tener un apt-cacher corriendo se puede hacer:

$ sudo CACHER=127.0.0.1:3142 lb config
$ sudo CACHER=127.0.0.1:3142 lb build




