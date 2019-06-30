---
title: Levantar Mis Herramientas Para Desarrollador en Xubuntu
image:
imageMeta:
  attribution:
  attributionLink:
featured: true
authors: 
  - diegoauyon
date: Sat Jun 29 2019 17:21:15 GMT-0600 (Central Standard Time)
tags:
  - new
---

# Como levantar xubuntu para desarrollar web

El conjunto de herramientas y configuraciones que utilizo para el desarrollo web. Está guía la realize utilizando xubuntu.

## [sudo] password for ...
Está configuración te evitara escribir tu contraseña una y otra vez en la terminal. Ejecutas `sudo visudo` buscas `write` y deberiá quedar así `write NOPASSWD:ALL`. Con eso solo sera necesario escribir una vez tu contraseña por sesión en la terminal.

## Instalar paquetes

Estos primeros paquetes nos permitiran seguir instalando con tranquilidad.
```bash
sudo apt install zsh curl git build-essential vim`
```

### Hey! Que tal un poco de azucar a nuestra terminal
Instalamos oh-my-zsh:

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
Previamente habíamos instalado zsh. Hace falta una de configuraciones para utilizar zsh, habilitar ciertos plugins en el archivo `~/.zshrc` editamos y agregamos los plugins a la lista `plugins=(git yarn z)`.

WIP Más detalle aquí de los plugins y zsh.

### Node
Instalaremos node que este fabuloso "node version manager" `nvm`.
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
```
En este caso es la versión `0.34.0`, pero la instrucciones estan aquí.

Después de instalar nvm debemos instalar node.
```bash
nvm ls-remote --lts # Lista las versiones LTS disponibles
nvm install 10.16.0
```

WIP explicar más sobre nvm, la versión por default.