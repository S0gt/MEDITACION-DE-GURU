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


En nuestro proyecto realizamos una página web en la cual nuestros clientes pueden publicar reseñas sobre películas. Para que así personas puedan echar un vistazo a las reseñas de la gente.

<div align="left">

# Idea seleccionada 💡💡

Página web de reseña de películas, con la capacidad de crear listas personalizadas y que cada usuario pueda dar su opinion de las peliculas que pongamos.

# ¿Hasta donde queremos llegar con el proyecto? 🏁🏁

Nuestra intención es tener una página en la que puedas hacer reseñas rápidas y sencillas, queremos que también puedas hacerte listas con tus contenidos favoritos que tienes pendientes por ver o jugar.
 
# ¿A quién va dirigido nuestro proyecto? 📫📫

Queremos centrarnos en un publico joven aunque no nos desagrada la idea de que sea para un publico general, nos queremos centrar en que sea agradable para que todos los publicos esten comodos al usar la pagina, queremos algo intuitivo y sencillo
 

# Módulos del ciclo que tengan que ver con el proyecto 📜📜

- Seguridad informática. (Copias de seguridad)

- Aplicaciones Web. (Php y mysql)

- Sistemas operativos en red y servicios en red. (máquinas virtuales del proyecto)


# Materiales necesarios ⛏️⛏️

 Físicos: Varios ordenadores 

 Lógicos: Máquinas virtuales, ISO  

 # Especificar objetivos y las funcionalidades. 

Nuestra meta es crear una web donde se puedan hacer reseñas de peliculas, también querémos que los usuarios puedan hacer listas de las películas, para llenar un orden u organización
 

# Especificar listado de tareas.

-Crear los servidores y configurarlos para que den los servicios que necesitamos
-Crear paginas web con frontend y backend
-Base de datos para que funcionen los registros

 

# Asignar roles y responsabilidades del equipo. 

- Iván Martín: Web 

- Víctor Polo: Sistemas 

 

 # Diagrama de la red.

Este es el diagrama de la red, donde podemos apreciar el esquema de como irá estructurada nuestra red y las direcciones IP que utilizaremos para esta. 

En el diagrama de la red podemos ver como se estructura nuestra red, también apreciamos las direcciones IP que usaremos.

 <br />
<div align="center">
  <a href="https://github.com/S0gt/MEDITACION-DE-GURU/blob/main/IMAGENES/diagrama%20red.png?raw=true">
    <img src="IMAGENES/diagrama red.png" alt="diagrama red">
  </a>
<div align="left">
 

 

# Las tecnologías a implementar. 

Apache, PHP y MySql (Para web) 

TRUENAS (Backups) 

PFsense (Firewall y DHCP)

Bind9 (DNS)

# El hardware que se va a utilizar. 

Aún no sabemos seguro todo el hardware que usaremos al final del proyecto, pero de momento podemos decir que será 

| COMPONENTE        | SO                  | ALMACENAMIENTO | CPU          | RAM  | IP                | GATEWAY      |
|-------------------|---------------------|----------------|---------------|------|-------------------|--------------|
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

# INTRODUCCION A FIREWALL

## Concepto 

-PfSense es un firewall de codigo abierto, se utiliza como firewall y enrutador, se usa por su interfaz sencilla y simple basado en FreeBSD, es un sistema operativo multiusuario capaz de tener multitarea

## Características

Sus características principales son su soporte para VPN, Balanceo de carga y su gestion de DNS y DHCP, tiene  muchas mas caracteristicas pero estas son las mas destacadas para nosotros 

## Instalación y puntos a tener en cuenta 

Para instalarlo es tan facil como ir a su web https://www.pfsense.org/download/ y desde ahi descargamos con facilidad la ISO

Luego en VirtualBox solo tenemos que crear una nueva maquina con recursos normales considerando que no tiene interfaz grafica 
seleccionamos FreeBSD como sistema y seguimos la instalacion que es bastante facil y intuitiva.
![image](IMAGENES/descarga.png)

## Conclusión

Pese a que PfSense es muy útil en nuestro caso a la hora de empresas hay opciones mas profesionales como podria ser Sophos, que es mas pesada pero tambien tiene muchas mas funciones, en el caso de redes domesticas consideramos que se podria usar PfSense sin ningun problema
 
## PortForward

Es un metodo de redireccion de puertos, se usa para que varios dispositivos se puedan interconectar, sobretodo se usa en cosas como camaras de seguridad o para poder conectarnos a servidores de juegos

Lo configuramos creando una nueva regla en la seccion NAT, configuramos la interfaz en WAN par trafico externo, protocolos usamos TCP/UDP, ponemos puerto de HTTP a HTTP, redirigimops a la ip que usamos en nuestro caso 10.28.38.100 y ya estaria 

# PRACTICA
Hemos configurado el PFSense y un cliente, el cual hemos conectado al PFSense y nos ha brindado una dirección IP dentro del dominio.

![image](https://github.com/user-attachments/assets/5042db07-4b3f-4987-8f96-f4daa7d055d0)

</details>

 <div align="left">

  <details>
    <summary><h2>DNS/DHCP 😶‍🌫️😶‍🌫️</h2></summary>
    
# Introducción al servicio (DNS y al DHCP)

  DNS (Domain Name System): Es un servicio que traduce nombres de dominio en direcciones IP. Facilita la navegación en internet y la gestión de redes.

  DHCP (Dynamic Host Configuration Protocol): Es un protocolo que asigna automáticamente direcciones IP y puertas de enlace y DNS a los dispositivos de una red.

## ¿Por qué es necesario?

DNS: Permite que los usuarios accedan a sitios web y recursos de red usando nombres en lugar de números difíciles de recordar.

DHCP: Simplifica la administración de redes al asignar IPs automáticamente, evitando conflictos de direcciones y configuraciones manuales.

## ¿Dónde hay información oficial?

- Al usar Linux para clientes y server en todo el trabajo, Bind9 se podria adaptar perfectamente a nuestras necesidades

  DNS: https://bind9.readthedocs.io/en/v9.20.7/ 

  DHCP: https://documentation.ubuntu.com/server/how-to/networking/install-isc-dhcp-server/index.html

## Instalación (DNS y del DHCP)

  DNS:

  DHCP:

## Detalles de la MV

  Servidor: 
  
· 2 CPU 

· 2 GB de memoria RAM 

· 25 GB de disco duro 

· 2 interfaces de red (ad.pnte y red interna) 


  </details>

  <details>
    <summary><h2>TRUENAS ⛈️⛈️</h2></summary>

  ## ¿Qué es?
  
  TrueNAS es un programa gratuito que puedes instalar en un ordenador para convertirlo en un servidor donde se guardan archivos. Es como tener un disco duro gigante al que se pueden conectar otros ordenadores de la misma red para guardar, copiar o ver archivos, sin necesidad de usar internet. Es parecido a tener tu propia nube personal, pero solo accesible dentro de tu casa, instituto o empresa.


  ## ¿Por qué usarlo?
  
- Es gratis y de código abierto.

- Funciona en ordenadores normales.

- Es muy estable y seguro.

- Permite ahorrar dinero en lugar de comprar soluciones comerciales caras.

- Se usa tanto en hogares como en empresas.

  ##Información oficial
  
https://www.truenas.com

## Guía de instalación

## Descarga e instalación:
Descarga la ISO de TrueNAS SCALE y crea una máquina virtual en VirtualBox con sistema FreeBSD 64-bit usando esa ISO para instalar.

## Configura discos y red:
Agrega dos discos virtuales pequeños adicionales. Configura un adaptador de red en modo NAT y otro en modo puente para comunicación con internet y tu equipo.

## Instala TrueNAS en la VM:
Arranca la VM, instala TrueNAS seleccionando el disco de instalación, crea la contraseña root, apaga y retira la ISO para que arranque solo TrueNAS.

## Clona la máquina virtual:
Haz una copia idéntica para usarla en pruebas de replicación y respaldo entre ambas usando rsync.

## Accede a la interfaz web:
Desde otro equipo, entra a la IP que muestra TrueNAS e inicia sesión como root.

Crea un pool de almacenamiento con los discos disponibles (RAID 1 o RAID 5).

Crea un usuario para las tareas de respaldo.

Activa y configura servicios SMB, SSH y rsync, creando un módulo con permisos adecuados.

## Tareas automáticas con rsync:
Crea una tarea rsync para enviar datos a la VM clonada en horarios programados.

## Automatiza con cron y scripts:
Crea un cronjob que ejecute un script backup.sh que contenga comandos rsync para hacer copias de seguridad de forma automática.
Resumen final
Con esto tendrás un sistema de almacenamiento TrueNAS funcionando en dos máquinas virtuales, configurado para hacer copias de seguridad usando rsync, tanto manualmente como programadas automáticamente con cron y scripts personalizados.


  </details>

<div align="left">

  <details>
    <summary><h2>Página Web 🤡🤡</h2></summary>

# Apache

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
- Copias de seguridad: Usamos TrueNas y nos guiamos con la guia de punkymo nuevamente 


   </details>
