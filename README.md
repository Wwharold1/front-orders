# Orders

Este proyecto se basa de registrar ordenes a un usuario.

## Table of Contents

- [Tecnologías empleadas](#tecnologías-empleadas)
- [Requisitos Previos](#requisitos-previos)
- [Instalación y ejecutar localmente](#instalación-y-ejecutar-localmente)
- [Estructura de carpetas](#estructura-de-carpetas)
- [Build](#build)

## Tecnologías empleadas

- Next JS 13.4.7
- React 18.2.0
- Redux
- TailwindCSS
- .Net 8
- Sql Server
- Docker

## Requisitos Previos

- Docker Desktop
- [Next JS 13.4.7](https://nextjs.org/blog/next-13-4)
- [Node 18.20 or higher](https://nodejs.org/en/blog/release/v18.16.0)
- [Npm 9.5.1 or higher](https://www.npmjs.com/package/npm/v/9.5.1)

Es importante asegurarse de tener las versiones correctas de Node.js, Next JS y NPM para garantizar el correcto funcionamiento de su aplicación. También es necesario tener una conexión a Internet para descargar todas las dependencias necesarias.

## Instalación y ejecutar localmente

### Clonar proyecto

```shell
git clone https://github.com/Wwharold1/front-orders.git
cd front-orders
```

### Instalar proyecto

```shell
- Ir a la ruta front-orders
- Usar 'docker compose down' para limpiar los puertos usados.
- Usar 'docker compose up --build' para instalar la base de datos, backend y frontend.
- Se demorará unos minutos en cargar las instancias.
- Se levantar el servidor de base de datos con un usuario registrado, los datos del usuario es:
    EMAIL: harold1799@gmail.com
    CONTRASENA: Facil123
- Una vez cargado y levantado en docker, estas serian las URL:
    FRONTEND: http://localhost:3000/
    BACKEND: http://localhost:8081/

```