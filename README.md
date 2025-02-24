# MEDITACION GURÚ 
<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->




<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="[https://github.com/S0gt/MEDITACION-DE-GURU/blob/main/logo.png?raw=true](https://github.com/S0gt/MEDITACION-DE-GURU/blob/main/logo2.png?raw=true)">
    <img src="logo2.png" alt="Logo" width="250" height="250">
  </a>



<!-- SOBRE NUESTRO PROJECTO -->
## SOBRE NUESTRO PROYECTO 🧐🧐

En nuestro proyecto realizamos una página web con su propio sistema de emulación multijugador online

<div align="left">

# Idea seleccionada 💡💡

-Página web con un sistema de emulación multijugador para juegos de GameCube y Wii. 

-Esta idea la hemos elegido porque a los dos nos apasiona el mundo de los videojuegos, y una parte importante de ellos son los videojuegos antiguos que no pudimos llegar a disfrutar, coneste proyecto lo que queremos hacer es revivir esos juegos y poderlos jugar con un multijugador para poder disfrutar de la experiencia original.

-Los juegos seleccionados para la página son nuestros juegos favoritos de la plataforma como; Super Smash Bros. Melee, Mario Kart: Double Dash!!, New Super Mario Bros. Wii, Donkey Kong Coutry Returns, entere otros.
 

# ¿Hasta donde queremos llegar con el proyecto? 🏁🏁

Nuestra intención es desarrollar una plataforma web dedicada que incorpore un emulador funcional, diseñado específicamente para permitir que dos equipos clientes se conecten de manera fluida y estable a un servidor central. De esta forma, los usuarios podrán interactuar entre si, disfrutando de una experiencia de juego compartida en línea, en tiempo real. Esta solución no solo fomentará la conectividad entre los jugadores, sinó que también garantizará un entorno de juego sincronizado y sin interrupciones, brindando una experiencia de alta calidad para ambos participantes.

 

# ¿A quién va dirigido nuestro proyecto? 📫📫


Nuestro público objetivo abarca desde adolescentes hasta adultos de diversas edades, ya que estamos convencidos de que nuestra propuesta tiene un atractivo universal que puede captar el interés de una amplia gama de personas. Creemos firmemente que nuestra idea tiene el potencial de resonar tanto en los jóvenes, quienes buscan nuevas experiencias de entretenimiento, como en los adultos que valoran la nostalgia, la interacción social y la calidad en las opciones de ocio. Este enfoque inclusivo nos permite dirigirnos a un espectro diverso de usuarios, maximizando el impacto de nuestra propuesta. 

 

# Módulos del ciclo que tengan que ver con el proyecto 📜📜

- Seguridad informática.

- Aplicaciones Web.

- Servicios de red.

- Sistemas operativos en red.





# Materiales necesarios ⛏️⛏️


 Físicos: Varios ordenadores 

 Lógicos: Máquinas virtuales, ISO  

 # Especificar objetivos y las funcionalidades. 

Nuestra meta es la creación de una página web que implemente un emulador de WII (Dolphin), nuestro objetivo principal es hacer que el emulador pueda tener modo online 

 

# Especificar listado de tareas. 

- Crear web 

- Configurar RetroArch 

- Hacer arquitectura de la web: navegabilidad del sitio web, mockup 

- Integrar RetroArch y Dolphin a la web 

- Pruebas y correcciones del rendimiento 

 

# Asignar roles y responsabilidades del equipo. 

- Iván Martín: Sistemas 

- Víctor Polo: Web 

 

 # Diagrama de la red.


Este es el diagrama de la red, donde podemos apreciar el esquema de como irá estructurada nuestra red y las direcciones IP que utilizaremos para esta. 

En el diagrama de la red podemos ver como se estructura nuestra red, también apreciamos las direcciones IP que usaremos.

 <br />
<div align="center">
  <a href="[https://github.com/S0gt/MEDITACION-DE-GURU/blob/main/logo.png?raw=true](https://github.com/S0gt/MEDITACION-DE-GURU/blob/main/Dibujo.png?raw=true)">
    <img src="Dibujo.png" alt="Logo" width="500" height="300">
  </a>
<div align="left">
 

 

# Las tecnologías a implementar. 

Apache (Para web) 

TRUENAS (Backups) 

POSTGRESQL (Bases de datos) 

 

# El hardware que se va a utilizar. 

Aún no sabemos seguro todo el hardware que usaremos al final del proyecto, pero de momento podemos decir que será 

| COMPONENTE        | SO                  | ALMACENAMIENTO | CPU          | RAM  | IP                | GATEWAY      |
|------------------|---------------------|----------------|--------------|------|-------------------|--------------|
| 🖥️ MAQUINA HOST  | Proxmox             | 465 GB         | 4            | 8 GB | 000.00.00.000     | 000.00.00.0  |
| 💻 CLIENTE       | Ubuntu 22.04.02     | 150 GB         | 4            | 4 GB | 000.000.0.00/00   | 000.000.0.0  |
| 🌐 DNS / DHCP    | Ubuntu 22.04.02     | 14 GB          | 1            | 2 GB | 000.000.0.0/00    | 000.000.0.0  |

# Los servicios a implementar. 

- DNS: Necesario para montar el servidor.



- DHCP:  

 

# Los sistemas operativos a utilizar. 

- Ubuntu Desktop 22.04.2

- Ubuntu Server 22.04.2

- Windows 10  22H2_Spanish

 

# Establecer un diagrama de Gantt con los objetivos y resultados a alcanzar. 
<img src="GANT.jpg" />


 # Incidencias 🚧🚧
 
A lo largo del trabajo han surgido varios problemas, aquí redactaremos todos estos a lo largo del proyecto:

- Configurando el DNS y el DHCP cometimos varios errores a la hora de la escritura de códigos y de comandos.
- Al final hemos cambiado la manera de hacerlo, usando el pi-hole con una interfaz gráfica en nuestro servidor.
- Hemos descargado el navegador y tenemos que descargar un navedador en el servidor.


# FIREWALL 🐈🐈

Hemos configurado el PFSense y un cliente, el cual hemos conectado al PFSense y nos ha brindado una dirección IP dentro del dominio.

![image](https://github.com/user-attachments/assets/5042db07-4b3f-4987-8f96-f4daa7d055d0)

# DNS/DHCP 😶‍🌫️😶‍🌫️



# Introducción a Apache 🤡🤡

## ¿Qué es?

Apache es un servidor web de código abierto ampliamente utilizado para alojar sitios web y aplicaciones.

## ¿Por qué usarlo?

Fiabilidad y seguridad

Modularidad y compatibilidad con distintos lenguajes

Uso en entornos locales e internet

## Documentación oficial

https://httpd.apache.org/docs/

# Instalación en Ubuntu Server

## Configuración de la MV

SO: Ubuntu Server 20.04

RAM: 2GB

Disco: 20GB

Red: NAT "NatNetworkSMX2"

# Pasos

## Actualizar paquetes:

sudo apt update && sudo apt upgrade -y

## Instalar Apache:

sudo apt install apache2 -y

## Habilitar y verificar el servicio:

sudo systemctl enable --now apache2
sudo systemctl status apache2

## Configurar firewall:

sudo ufw allow 'Apache'
sudo ufw enable

# INCIDENCIAS (APACHE)⚠️⚠️

Durante la realizacion de el apartado de apache tubimos multiples problemas, todos devido a que nos quisimos adelantar y intentamos instalar PHP y MySQL antes de que lo explicaran en clase, esto nos hizo confundirnos a la hora de la instalacion y acabar complicandola demasiado hasta que salieron muchos errores con los archivos, lo que decidimos hacer al final es pasar todo de un debian a un ubuntu server, al hacer esto la instalacion fue mucho mas facil para nosotros y pudimos completarla sin mayor dificultad


# Recursos 🔎🔎

Los recursos a los que hemos recurrido en la creación del proyecto son:

- DNS: Consultar a los profes fallos ocurridos, y que nos aconsejaran que seria lo mejor, y utilizar el ChatGPT para no cometer errores a la hora de ls escritura de los comandos.
- Servidor: Una parte del firewall ya la tenemos creada gracias al pfsense 
- Clientes:
- Creación de la web:
- Implemetar emulador Dolphin en la web:

