# Paquetito

Todo lo que se necesita para arrancar una aplicación en node.js

## Dependencias

(nodejs)[https://nodejs.org/es/] - Descargar la versión "Actual"
(git)[https://git-scm.com/download/win] - Descargar la versión 64 bits de "setup"
(VSCode)[https://code.visualstudio.com/Download] - Descargar la versión "User Installer" de 64 bits

Instalar todo.

## Clonar repositorio

Despues de instalar nodejs y git, abrir una "Línea de comandos" en windows o una Terminal en MacOS o Linux y ejecutar

```bash
git clone github.com/javiercbk/paquetito
```

Eso comando va a clonar el repositorio en la carpeta donde lo ejecuten (en windows generalmente es la carpeta del usuario).

## Carpetas

paquetito/
├─ node_modules/ <= contiene librerías y dependencias (ignorar hasta instalar librerías)
├─ public/ <= contiene archivos públicos (ignorar hasta no tener un server andando)
├─ src/ <= "source": contiene el código javascript

## Ejecutar

* Abrir VSCode y hacer click en "File > Open Folder"
* Seleccionar la carpeta "paquetito"
* Clickear en el cuarto ícono de la izquierda
* Clickear el botón verde de Play que dice "Debug App".

