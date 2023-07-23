## <img width="48" height="48" src="https://img.icons8.com/color/48/open-book--v1.png" alt="open-book--v1"/>  1. Introducción a Node.js

Temas:


- Presentación del curso y objetivos

- ¿Qué es Node.js? Historia y por qué es relevante

- Instalación y configuración

- nvm y fnm, gestores de versiones

- "Hola Mundo" en Node.js

- package.json y npm

- Configuración de linter

- Tu primer servidor con Node.js


---

[Página oficial: https://nodejs.org/en](https://nodejs.org/en)

---

## ¿Qué es Node.js? Historia y por qué es relevante

Node NO es...

...un lenguaje

.. un framework

... un servidor

... un hosting

Node ES un **entorno de ejecución** de **JavaScript**, un sitio donde podes ejecutar JavaScript sin ser el navegador web, se puede ejecutar en el BackEnd, en la terminal, en dispositivos (ej.: Nintendo Switch).

Es de **código abierto**.

Es **multiplataforma**: McOs, Windows, Linux, televisión, etc.

Es **asíncrono**, orientado a **Eventos** (Event loop). Es un modelo de programación que tiene un bucle que va manejando las solicitudes que le van llegando cada vez que tiene un evento. En vez de boquearse, va ejecutando tareas mientra espera respuestas de otras tareas que ha dejado por ahi. Todo esto lo hace un **un solo thread** (no es multi hilo). Vahaciendo cosas en asíncrono, simula que hace más de una cosa a la vez.

El secreto es que utiliza el **motor V8**, el motor de JavaScript que ejecuta el navegador web de Chrome. Es el mismo motro, pero no el mismo entorno,


---

## ¿Por qué aprender Nodejs?

- Demanda del mercado, muchas empresas lo utilizan, todos de alguna forma o otra lo usan. VSC utiliza Nodejs, el ESLinter también lo usa.

- Se puede usar todos los conocimientos de JavaScript, pero en este nuevo entorno de ejecución.

- Se crean aplicaciones web, servidores, Pis, hacer scraping, etc.

- Una comunidad inmensa y un ecosistama más grande aun (paquetes npm).

- Es rápido, escalable, fácil de desplegar y muy barato(hasta gratis).

---

## Instalación y configuración

---