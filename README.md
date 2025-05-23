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

En nuestro proyecto creamos una página web donde los usuarios pueden publicar reseñas sobre películas para que otras personas puedan leerlas y conocer sus opiniones.

<div align="left">

# Idea seleccionada 💡💡

Página web de reseñas de películas, con la capacidad de crear listas personalizadas y en la que cada usuario pueda dar su opinión sobre las películas que publiquemos.

# ¿Hasta donde queremos llegar con el proyecto? 🏁🏁

Nuestra intención es tener una página en la que puedas hacer reseñas rápidas y sencillas. También queremos que puedas crear listas con tus contenidos favoritos que tienes pendientes por ver.
 
# ¿A quién va dirigido nuestro proyecto? 📫📫

Queremos centrarnos en un público joven, aunque no nos desagrada la idea de que sea para un público general. Nos enfocamos en que sea agradable para que todos los públicos estén cómodos al usar la página. Queremos que sea algo intuitivo y sencillo. 

# Módulos del ciclo que tengan que ver con el proyecto 📜📜

- Seguridad informática (copias de seguridad).

- Aplicaciones web (PHP y MySQL).

- Sistemas operativos en red y servicios en red (máquinas virtuales del proyecto).


# Materiales necesarios ⛏️⛏️

 Físicos: Varios ordenadores 

 Lógicos: Máquinas virtuales, ISO  

 # Especificar objetivos y las funcionalidades. 

Nuestra meta es crear una web donde se puedan hacer reseñas de películas. También queremos que los usuarios puedan crear listas de películas para organizar y ordenar mejor sus contenidos.
 

# Especificar listado de tareas.

- Crear los servidores y configurarlos para que ofrezcan los servicios que necesitamos.

- Crear páginas web con frontend y backend.

- Configurar la base de datos para que funcionen los registros.

 

# Asignar roles y responsabilidades del equipo. 

- Iván Martín: Web 

- Víctor Polo: Sistemas 

 

 # Diagrama de la red.

Este es el diagrama de la red, donde podemos apreciar el esquema de cómo estará estructurada nuestra red y las direcciones IP que utilizaremos.

En el diagrama de la red podemos ver cómo se estructura nuestra red y también las direcciones IP que usaremos.

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

Aún no sabemos con seguridad todo el hardware que usaremos al final del proyecto, pero por el momento podemos decir que será...

| COMPONENTE        | SO                  | ALMACENAMIENTO | CPU          | RAM  | IP                | GATEWAY      |
|-------------------|---------------------|----------------|---------------|------|-------------------|--------------|
| 🖥️ MAQUINA HOST  | Pfsense             | 50 GB          | 2             | 4 GB | 000.00.00.000     | 000.00.00.0  |
| 💻 CLIENTE       | Ubuntu 22.04.02     | 50 GB          | 4             | 4 GB | 000.000.0.00/00   | 000.000.0.0  |
| 🌐 DNS / DHCP    | Ubuntu 22.04.02     | 50 GB          | 2             | 4 GB | 000.000.0.0/00    | 000.000.0.0  |

# DNS/DHCP

- DNS: convierte los nombres de páginas web en direcciones que los PC entienden para conectarse.

- DHCP: asigna automáticamente las direcciones IP a los dispositivos cuando se conectan, sin configurarlos manualmente.
  

# Los servicios a implementar. 

- DNS: Para que nuestro servidor sea capaz de resolver direcciones web.

- DHCP: Para asignar las IP automáticamente al resto de las máquinas virtuales.


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
 
A lo largo del trabajo han surgido varios problemas; aquí describiremos todos ellos durante el proyecto:

- Al configurar el DNS y el DHCP cometimos varios errores al escribir códigos y comandos.

- Finalmente, cambiamos la forma de hacerlo, usando Pi-hole con una interfaz gráfica en nuestro servidor.

- Hemos descargado el navegador, pero también necesitamos instalar uno en el servidor.

</details>

<div align="left">

  <details>
    <summary><h2>FIREWALL 🐈🐈</h2></summary>

# INTRODUCCION A FIREWALL

## Concepto 

-pfSense es un sistema operativo de código abierto basado en FreeBSD, diseñado para funcionar como firewall y router. Es muy utilizado en redes pequeñas y grandes debido a su potencia, flexibilidad y facilidad de uso mediante su interfaz web.

## Características

Sus características principales son el soporte para VPN, balanceo de carga y la gestión de DNS y DHCP. Tiene muchas más características, pero estas son las más destacadas para nosotros.


## Instalación y puntos a tener en cuenta 

Para instalarlo, es tan fácil como ir a su web https://www.pfsense.org/download/ y desde ahí descargar la ISO fácilmente.

Luego, en VirtualBox solo tenemos que crear una nueva máquina con recursos normales, teniendo en cuenta que no tiene interfaz gráfica. Seleccionamos FreeBSD como sistema operativo y seguimos la instalación, que es bastante fácil e intuitiva.


![image](IMAGENES/descarga.png)

## Conclusión

pfSense permite publicar una página web de forma segura desde una red local, controlando el tráfico con reglas de firewall y NAT. Es fácil de usar y muy útil para proteger y gestionar redes, lo cual se adapta bien a lo que estamos buscando.

## Port Forward

El Port Forward permite que un servicio, que en nuestro caso será una página web, sea visible desde fuera de la red donde está configurada.

Es un método de redirección de puertos que se usa para que varios dispositivos puedan comunicarse; sobre todo se utiliza en dispositivos como cámaras de seguridad o para conectarnos a servidores de películas.

Lo configuramos creando una nueva regla en la sección NAT, configurando la interfaz en WAN para tráfico externo, usando los protocolos TCP/UDP, asignando el puerto HTTP a HTTP, redirigiendo a la IP que usamos, en nuestro caso 192.168.56.111, y listo.

Hemos configurado pfSense y un cliente, el cual conectamos a pfSense y nos brindó una dirección IP dentro del dominio.

![image](https://github.com/user-attachments/assets/5042db07-4b3f-4987-8f96-f4daa7d055d0)

Hemos usado el Port forward ya que permite acceder a servicios internos desde fuera de la red, asi todos nuestros clientes podran acceder a nuestra página web sin problema.

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

Durante la realización del apartado de Apache tuvimos múltiples problemas, todos debidos a que intentamos adelantarnos e instalar PHP y MySQL antes de que lo explicaran en clase. Esto nos causó confusión durante la instalación y la complicó demasiado, hasta que aparecieron muchos errores con los archivos. Al final, decidimos pasar todo de Debian a Ubuntu Server. Al hacer esto, la instalación fue mucho más fácil para nosotros y pudimos completarla sin mayor dificultad.

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

- DNS y DHCP: seguimos la guía de Punkymo de Alina.

- Apache: utilizamos una guía de DigitalOcean sobre Apache, PHP y MySQL: https://www.digitalocean.com/community/tutorials/how-to-install-lamp-stack-on-ubuntu

- Firewall: para el firewall usamos pfSense y nos guiamos por la guía de Punkymo.

- Copias de seguridad: usamos TrueNAS y nuevamente seguimos la guía de Punkymo.


   </details>

   <div align="left">

  <details>
    <summary><h2>Conclusiones👿👿</h2></summary>

Con este proyecto hemos aplicado lo aprendido sobre redes y servicios, creando una página web para compartir opiniones de películas. Hemos aprendido a preparar el servidor, gestionar la red y permitir el acceso desde fuera. Esto nos ha ayudado a entender mejor cómo funciona y se mantiene una página web real.

  </details>
