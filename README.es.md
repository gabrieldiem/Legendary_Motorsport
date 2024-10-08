<div align="center">

<img src="./docs/img/lm_banner.png" alt="Legendary Motorsport Banner" width="500">

</div>

# Trabajo Práctico - Teoría del Lenguaje

[![en](https://img.shields.io/badge/read_in-english_%F0%9F%87%AC%F0%9F%87%A7-darkblue?style=flat)](https://github.com/walgab/Legendary_Motorsport#readme)

Proyecto de Ecommerce desarrollado en Ruby on Rails - Trabajo práctico para la materia Teoría de Lenguaje [75.31 - 95.07] curso Ferrigno - FIUBA, 2C 2021.

Se puede ver la presentación en video que acompaña a este proyecto [en este enlace de YT](https://youtu.be/-0cxWvMj58c).

## Integrantes:
- Balmaceda, Fernando - [ferbalmaceda23](https://github.com/ferbalmaceda23)
- Craviotto, Mateo - [MateoCraviotto](https://github.com/MateoCraviotto)
- Diem, Walter Gabriel - [gabrieldiem](https://github.com/gabrieldiem)
- Lazzaro, Melina - [Melzr](https://github.com/Melzr)

## Corrector:
- Ferrigno, Leandro

## Ejecución
Una vez realizada la clonación del repositorio, se deberán instalar los programas necesarios para poder ejecutar el trabajo. Entre ellos, se encuentran:

- Ruby (versión 3.0.0)
- Ruby on Rails (versión 6.1.4.1)
- MySQL y MySQLd (mysql2 versión 0.5) 

Además, se deben instalar las dependencias de NodeJS, requeridas para que funcione Ruby on Rails, con el comando ```yarn install```.
<br><br>

### Instalación de Gemas
Se deben instalar las Gemas utilizadas con el comando ```bundle install```.
Para más detalles sobre las gemas y sus versiones, ver el [gemfile](https://github.com/MateoCraviotto/TP-Ruby-TDL/blob/main/ecommerce/Gemfile).
<br><br>

### Configuración de la base de datos

Primero, se debe ejecutar el setup de la base de datos, que carga los datos del archivo ```seeds.rb``` al inicio, para que aparezca una cuenta administradora con autos precargados al iniciar el servidor. Esto se hace con el comando ```rails db:setup```.

Luego, se deberán ejecutar las migraciones de la base de datos, lo que se hace con el comando ```rails db:migrate```.
<br><br>

### Ejecución del servidor

Finalmente, para ejecutar el servidor que muestra el sitio web en local, se debe ejecutar el comando ```rails s```.

Esto iniciará el servidor para que el sitio web se vea en ```http://localhost:3000/```.

## Imágenes

![Imagen 1](./docs/img/img1.jpg)

![Imagen 2](./docs/img/img2.jpg)

![Imagen 3](./docs/img/img3.jpg)

![Imagen 4](./docs/img/img4.jpg)

![Imagen 5](./docs/img/img5.jpg)

![Imagen 6](./docs/img/img6.jpg)

## Assets de terceros

Este proyecto incluye imágenes y contenido visual derivados de Grand Theft Auto V.

### Atribución

Algunas imágenes y contenido visual en esta página web están derivados de Grand Theft Auto V y son propiedad con derechos de autor de Rockstar Games, una subsidiaria de Take-Two Interactive Software, Inc. Todos los derechos sobre estos activos están completamente reservados por Rockstar Games. Este proyecto no está afiliado, respaldado ni asociado de ninguna manera con Rockstar Games. El uso de estas imágenes tiene como único propósito fines no comerciales.
