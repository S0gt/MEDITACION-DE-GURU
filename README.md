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
  <a href="https://github.com/S0gt/MEDITACION-DE-GURU/blob/main/IMAGENES/logo2.png?raw=true">
    <img src="IMAGENES/logo2.png" alt="Logo" width="250" height="250">
  </a>



<!-- SOBRE NUESTRO PROJECTO -->


<div align="left">

  <details>
    <summary><h2>SOBRE NUESTRO PROYECTO 🧐🧐</h2></summary>


En nuestro proyecto realizamos una página web en la cual nuestros clientes pueden publicar reseñas sobre películas, series y videojuegos. Para que así personas puedan echar un vistazo a las reseñas de la gente.

<div align="left">

# Idea seleccionada 💡💡

Página web de reseña de películas, series y videojuegos, con la capacidad de crear listas personalizadas 

# ¿Hasta donde queremos llegar con el proyecto? 🏁🏁

Nuestra intención es tener una página en la que puedas hacer reseñas rápidas y sencillas, queremos que también puedas hacerte listas con tus contenidos favoritos que tienes pendientes por ver o jugar.
 
# ¿A quién va dirigido nuestro proyecto? 📫📫

Queremos centrarnos en un publico joven aunque no nos desagrada la idea de que sea para un publico general, nos queremos centrar en que sea agradable para que todos los publicos esten comodos al usar la pagina, queremos algo intuitivo y sencillo
 

# Módulos del ciclo que tengan que ver con el proyecto 📜📜

- Seguridad informática.

- Aplicaciones Web.

- Servicios de red.

- Sistemas operativos en red.





# Materiales necesarios ⛏️⛏️

 Físicos: Varios ordenadores 

 Lógicos: Máquinas virtuales, ISO  

 # Especificar objetivos y las funcionalidades. 

Nuestra meta es una web donde se puedan hacer reseñas de peliculas, series y videojuegos, tambien queremos que los usuarios puedan hacer listas de las peliculas, series y juegos para llear un orden o organizacion
 

# Especificar listado de tareas.

-Crear los servidores y configurarlos para que den los servicios que necesitamos
-Crear paginas web con frontend y backend
-Base de datos para que funcionen los registros

 

# Asignar roles y responsabilidades del equipo. 

- Iván Martín: Sistemas 

- Víctor Polo: Web 

 

 # Diagrama de la red.

Este es el diagrama de la red, donde podemos apreciar el esquema de como irá estructurada nuestra red y las direcciones IP que utilizaremos para esta. 

En el diagrama de la red podemos ver como se estructura nuestra red, también apreciamos las direcciones IP que usaremos.

 <br />
<div align="center">
  <a href="[[https://github.com/S0gt/MEDITACION-DE-GURU/blob/main/logo.png?raw=true](https://github.com/S0gt/MEDITACION-DE-GURU/blob/main/Dibujo.png?raw=true)](https://github.com/S0gt/MEDITACION-DE-GURU/blob/main/IMAGENES/Dibujo.png?raw=true)">
    <img src="IMAGENES/Dibujo.png" alt="Dibujo" width="1200" height="500">
  </a>
<div align="left">
 

 

# Las tecnologías a implementar. 

Apache, PHP y MySql (Para web) 

TRUENAS (Backups) 

PFsense (Firewall y DNS)

DHCP (backup)

# El hardware que se va a utilizar. 

Aún no sabemos seguro todo el hardware que usaremos al final del proyecto, pero de momento podemos decir que será 

| COMPONENTE        | SO                  | ALMACENAMIENTO | CPU          | RAM  | IP                | GATEWAY      |
|------------------|---------------------|----------------|---------------|------|-------------------|--------------|
| 🖥️ MAQUINA HOST  | Pfsense             | 50 GB          | 2             | 4 GB | 000.00.00.000     | 000.00.00.0  |
| 💻 CLIENTE       | Ubuntu 22.04.02     | 50 GB          | 4             | 4 GB | 000.000.0.00/00   | 000.000.0.0  |
| 🌐 DNS / DHCP    | Ubuntu 22.04.02     | 50 GB          | 2             | 4 GB | 000.000.0.0/00    | 000.000.0.0  |

# Los servicios a implementar. 

- DNS: Para que nuestro servidor sea capaz de resolver direcciónes web 

- DHCP: Para asignar las ip automáticamente a el resto de las máquinas virtuales 


# Los sistemas operativos a utilizar. 

- Ubuntu Desktop 22.04.2

- Ubuntu Server 22.04.2

- Windows 10  22H2_Spanish

 

# Establecer un diagrama de Gantt con los objetivos y resultados a alcanzar. 
<div align="center">
  <a href="[[[https://github.com/S0gt/MEDITACION-DE-GURU/blob/main/logo.png?raw=true](https://github.com/S0gt/MEDITACION-DE-GURU/blob/main/Dibujo.png?raw=true)](https://github.com/S0gt/MEDITACION-DE-GURU/blob/main/IMAGENES/Dibujo.png?raw=true)](https://github.com/S0gt/MEDITACION-DE-GURU/blob/main/IMAGENES/Diagrama.png?raw=true)">
    <img src="IMAGENES/Diagrama.png" alt="Diagrama" width="1200" height="500">
  </a>
<div align="left">


 # Incidencias 🚧🚧
 
A lo largo del trabajo han surgido varios problemas, aquí redactaremos todos estos a lo largo del proyecto:

- Configurando el DNS y el DHCP cometimos varios errores a la hora de la escritura de códigos y de comandos.
- Al final hemos cambiado la manera de hacerlo, usando el pi-hole con una interfaz gráfica en nuestro servidor.
- Hemos descargado el navegador y tenemos que descargar un navedador en el servidor.

</details>

<div align="left">

  <details>
    <summary><h2>FIREWALL 🐈🐈</h2></summary>



Hemos configurado el PFSense y un cliente, el cual hemos conectado al PFSense y nos ha brindado una dirección IP dentro del dominio.

![image](https://github.com/user-attachments/assets/5042db07-4b3f-4987-8f96-f4daa7d055d0)

Configurar un firewall pfSense o Sophos según consideres: 

 

En la memoria tienes que escribir un resumen a partir de las preguntas teóricas de las actividades de M06 de pfSense. Esto es: 

 

## ¿Qué es pfSense y para qué se utiliza? 

 

-pfSense es usado como firewall y es de código abierto. Es utilizado principalmente para proteger nuestras redes de cualquier posible amenaza. 

 

## ¿En qué sistema se basa? 

 

-pfSense toma como base a FreeBSD, que es un sistema derivado de UNIX, el cual es muy estable y seguro 

 

## ¿Cuáles son las principales características de pfSense? 

 

Las características principales del pfSense son: 

Firewall con filtrado de paquetes 

VPN (OpenVPN e IPsec) 

Balanceo de carga y alta disponibilidad 

Servidor DHCP y DNS 

Captive Portal para control de acceso a redes 

IDS/IPS (detección y prevención de intrusos) 

Administración vía interfaz web 

 

 

## ¿Cómo se instala y configura pfSense? ¿Qué debemos tener en consideración al instalarlo en un entorno virtual? 

 

Lo primero que debemos hacer es instalar la ISO de la página principal de pfSense 

Requisitos mínimos de la máquina virtual para pfSense: 

· 1 CPU 

· 1 GB de memoria RAM 

· 10 GB de disco duro 

· 2 interfaces de red (ad.pnte y red interna) 

Después deberemos seguir toda la instalación del pfSense. 

Tendremos que configurar la red LAN para poder ver nuestra web, en nuestro caso la LAN es la 10.28.38.1 /24 y la WAN es la 100.77.20.56 /24 

Una vez establecida toda la configuración deberemos abrir nuestro PC cliente para podernos conectar, para ello, abriremos el navegador e introduciremos la dirección que nosotros hayamos establecido en la LAN 

 

## ¿Consideras pfSense una opción viable para empresas y redes domésticas? 

Nosotros consideramos que pfSense es una opción bastante buena y nos brinda bastante seguridad y encima su software es gratuito, así que cualquiera lo puede usar. Para empresas ofrece seguridad avanzada y VPN, y para el hogar permite controlar el tráfico, establecer reglas de firewall y mejorar la seguridad de la red. 

 

## ¿Qué es el port forward? Explica cómo lo has configurado. 

Es el reenvío de puertos, nos permite poder redirigir el tráfico de una IP a otra IP y nos ayuda a poder acceder a servidores internos desde el exterior, como si fuera un “puente”, a servidores como web o FTP. 

</details>

 <div align="left">

  <details>
    <summary><h2>DNS/DHCP 😶‍🌫️😶‍🌫️</h2></summary>
    
# Introducción al servicio (DNS y al DHCP)

## ¿Qué es?

  DNS (Domain Name System): Es un servicio que traduce nombres de dominio en direcciones IP. Facilita la navegación en internet y la gestión de redes.

  DHCP (Dynamic Host Configuration Protocol): Es un protocolo que asigna automáticamente direcciones IP y puertas de enlace y DNS a los dispositivos de una red.

## ¿Por qué es necesario?

DNS: Permite que los usuarios accedan a sitios web y recursos de red usando nombres en lugar de números difíciles de recordar.

DHCP: Simplifica la administración de redes al asignar IPs automáticamente, evitando conflictos de direcciones y configuraciones manuales.

## ¿Dónde hay información oficial?

- Al usar Linux para clientes y server en todo el trabajo, Bind9 se podria adaptar perfectamente a nuestras necesidades

  DNS: https://bind9.readthedocs.io/en/v9.20.7/ 

  DHCP: https://documentation.ubuntu.com/server/how-to/networking/install-isc-dhcp-server/index.html

## Extras

  DNS:

  DHCP:

## Instalación (DNS y del DHCP)

  DNS:

  DHCP:

## Detalles de la MV

  Servidor: 
  
· 2 CPU 

· 2 GB de memoria RAM 

· 25 GB de disco duro 

· 2 interfaces de red (ad.pnte y red interna) 


## Pasos a seguir

  DNS:

  DHCP:

## Incidencias

  DNS:

  DHCP:

  </details>

  <details>
    <summary><h2>TRUENAS </h2></summary>

  </details>

<div align="left">

  <details>
    <summary><h2>Página Web 🤡🤡</h2></summary>


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

Red: Red NAT "NatNetworkSMX2"

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


## Nuestro mapa de la web:

  <a href=https://github.com/S0gt/MEDITACION-DE-GURU/blob/main/IMAGENES/Mapa%20de%20la%20web.jpg>
  
  <img src="IMAGENES/Mapa de la web.jpg" alt="Mapa de la web" width="1200" height="500">
    
  </a>

## Preview del home de la web:

  <a href=https://github.com/S0gt/MEDITACION-DE-GURU/blob/main/IMAGENES/Mapa%20de%20la%20web.jpg>
  
  <img src="IMAGENES/pagina home.png" alt="pagina home">

## Preview del login de la página:

<a href=https://github.com/S0gt/MEDITACION-DE-GURU/blob/main/IMAGENES/login.png>

<img src="IMAGENES/login.png" alt="login">

## Preview de las reseñas de la web:

<a href=https://github.com/S0gt/MEDITACION-DE-GURU/blob/main/IMAGENES/login.png>

<img src="IMAGENES/pAGINA RESEÑAS.png" alt="pAGINA RESEÑAS">


 </details>

<div align="left">

  <details>
    <summary><h2>Recursos 🔎🔎</h2></summary>
    


Los recursos a los que hemos recurrido en la creación del proyecto son:

- DNS Y DHCP de la guia de punkymo de Alina
- Para Apache hemos usado la una guia de Digital Ocean sobre Apache, PHP y MySQL: https://www.digitalocean.com/community/tutorials/how-to-install-lamp-stack-on-ubuntu
- FIREWALL: Para firewall usamos pfsense y nos guiamos por la guia de punkymo
- Copias de seguridad: Usamos True Nas y nos guiamos con la guia de punkymo nuevamente 


   </details>
