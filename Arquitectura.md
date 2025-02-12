# ARQUITECTURA


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

En el diagrama de Gantt podemos ver como nos vamos a organizar las tareas y el tiempo que vamos a invertir en cada una de estas
 <br />
<div align="center">
  <a href="[[https://github.com/S0gt/MEDITACION-DE-GURU/blob/main/logo.png?raw=true](https://github.com/S0gt/MEDITACION-DE-GURU/blob/main/Dibujo.png?raw=true)](https://github.com/S0gt/MEDITACION-DE-GURU/blob/main/Diagrama.png?raw=true)">
    <img src="Diagrama.png" alt="Logo" width="500" height="300">
  </a>
<div align="left"
