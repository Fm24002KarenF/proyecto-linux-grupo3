# Proyecto Linux - Grupo 3
Documentación del proyecto final de Introducción al Software Libre.
# Proyecto Linux – Grupo 3  
### Servidor Linux Automatizado con Docker + NGINX  
**Universidad de El Salvador – Facultad Multidisciplinaria de Occidente**  
**Materia:** Introducción al Software Libre – Ciclo II 2025  

---

## Badges del Proyecto
![Linux](https://img.shields.io/badge/Linux-Ubuntu%20%7C%20Mint-orange?logo=linux)
![Docker](https://img.shields.io/badge/Docker-Containerization-blue?logo=docker)
![Git](https://img.shields.io/badge/Git-Version%20Control-red?logo=git)
![NGINX](https://img.shields.io/badge/Nginx-Web%20Server-green?logo=nginx)
![Shell Script](https://img.shields.io/badge/Shell-Scripting-yellow?logo=gnubash)

---

# Tabla de Contenido
- [1. Descripción General](#-descripción-general)
- [2. Preparación del Entorno](#-preparación-del-entorno)
- [3. Estructura del Proyecto](#-estructura-del-proyecto)
- [4. Script de Monitoreo](#-script-de-monitoreo)
- [5. Control de Versiones (Git)](#-control-de-versiones-git)
- [6. Implementación con Docker](#-implementación-con-docker)
- [7. Servidor Web con HTML + CSS](#-servidor-web-con-html--css)
- [8. Integrantes](#-integrantes)
- [9. Licencia](#-licencia)

---

# Descripción General
Este proyecto consiste en la creación de un **servidor Linux automatizado**, implementado con:

- Administración de usuarios y grupos  
- Directorios con permisos heredables (setgid)  
- Scripts de monitoreo del sistema  
- Automatización con **cron**  
- Control de versiones utilizando **Git + GitHub**  
- Contenedores con **Docker**  
- Servidor web con **NGINX**  
- Redes y volúmenes personalizados  
- Imagen personalizada mediante **Dockerfile**

El objetivo principal es aplicar los conocimientos del curso para crear un entorno funcional, modular y gestionado con buenas prácticas.

---

# Preparación del Entorno
### Configuración del hostname
```bash
sudo hostnamectl set-hostname servidor-grupo3
/proyecto
   ├── datos/
   ├── web/
   ├── scripts/
   └── capturas/
sudo chmod 2775 /proyecto/datos
sudo chmod 2775 /proyecto/web
/proyecto
├── datos/
├── web/
│   ├── index.html
│   └── style.css
├── scripts/
│   └── reporte_sistema.sh
├── capturas/
└── Dockerfile
git init
git add .
git commit -m "Primer commit del proyecto"
git remote add origin https://github.com/Fm24002KarenF/proyecto-linux-grupo3.git
git push -u origin main
Incluye:

Instalación de Docker

Ejecución de hello-world

Agregar usuarios al grupo docker

Contenedor NGINX en puerto 8080

Imagen personalizada con Dockerfile → puerto 8081
Servidor Web con HTML + CSS

Página generada con diseño moderno:

Encabezado con gradiente

Tarjetas estilizadas

Diseño responsive

Separación clara entre contenido

Archivos:
/proyecto/web/index.html
/proyecto/web/style.css
Servido desde:

http://localhost:8080
