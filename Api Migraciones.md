<img src="https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_migraciones/api_migraciones.png?raw=true" alt="Logo" style="width:100%;">

# Proyecto API Migraciones

## 🛡️ Insignias

### Tecnologías Principales

| Node.js | MariaDB | Oracle | PostgreSQL | MySQL |
| --- | --- | --- | --- | --- |
| ![Node.js](https://img.shields.io/badge/Node.js-%5E18.0.0-green?style=for-the-badge&logo=node.js) | ![MariaDB](https://img.shields.io/badge/MariaDB-database-lightgrey?style=for-the-badge&logo=mariadb) | ![Oracle](https://img.shields.io/badge/Oracle-database-red?style=for-the-badge&logo=oracle) | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-database-blue?style=for-the-badge&logo=postgresql) | ![MySQL](https://img.shields.io/badge/MySQL-database-blue?style=for-the-badge&logo=mysql) |

### Herramientas de Desarrollo y Testing

| Jest | TypeScript | ESLint | Prettier |
| --- | --- | --- | --- |
| ![Jest](https://img.shields.io/badge/Jest-%5E26.6.3-C21325?style=for-the-badge&logo=jest) | ![TypeScript](https://img.shields.io/badge/TypeScript-%5E4.0.5-blue?style=for-the-badge&logo=typescript) | ![ESLint](https://img.shields.io/badge/ESLint-%5E7.12.1-4B32C3?style=for-the-badge&logo=eslint) | ![Prettier](https://img.shields.io/badge/Prettier-%5E2.1.2-F7B93E?style=for-the-badge&logo=prettier) |


## 📄 Descripción del Proyecto
Proyecto – Apis migraciones

Función Principal: 
Generar una interfaz de comunicación para el intercambio de información con las distintas bases de datos para luego volcar los datos en un data warehouse o donde sea requerida (por ejemplo: datos de postgreSQL a Oracle para la liquidación de los 45’ de docentes.)

## 🛠️ Tech Stack (tecnologías)
- Arquitectura de puertos y adaptadores (Hexagonal).
- Base de datos MariaDB.
- Base de datos Oracle.
- Base de datos PostgreSQL.
- Base de datos MySQL.
- NodeJS.

## 📦 Dependencias
- @nestjs/common: ^8.4.7
- @nestjs/core: ^8.4.7
- @nestjs/typeorm: ^7.1.5
- typeorm: ^0.2.32
- pg: ^8.6.0
- mysql2: ^2.3.3
- oracledb: ^6.5.1

## 📑 Índice

* [🖼️ Título e imagen de portada](#proyecto-web-asistencia-policía)
* [🛡️ Insignias](#%EF%B8%8F-insignias)
* [📄 Descripción del proyecto](#-descripción-del-proyecto)
* [🛠️ Tech Stack (tecnologías)](#%EF%B8%8F-tech-stack-tecnologías)
* [📑 Índice](#-índice)
* [✨ Features](#-features-características)
* [🚀 Deployment](#-deployment)
* [🔖 Releases](#-releases)
* [🔗 Links](#-links)
* [📖 Documentacion](#-documentacion)
* [💻 Instalacion](#-instalacion)
* [🏃 Ejecutar localmente](#-ejecutar-localmente)
* [🧪 Ejecución de pruebas](#-ejecución-de-pruebas)
* [📋 Uso/Ejemplos](#-usoejemplos)
* [⚙️ Optimizaciones](#%EF%B8%8F-optimizaciones)
* [🔮 Futuros cambios](#-futuros-cambios)
* [🛣️ Roadmap](#%EF%B8%8F-roadmap)
* [👥 Autores](#-autores)
* [👫 Usado por](#-usado-por)
* [🆘 Support](#-support)
* [⚖️ Licencia](#%EF%B8%8F-licencia)
* [🔒 Política de Seguridad](#-política-de-seguridada)

## ✨ Features (Características)
- Interfaz unificada para múltiples sistemas de bases de datos.
- Capacidad de migración y sincronización entre bases de datos.
- Seguridad y gestión robusta de la transferencia de datos.
- Integración con data warehouses para análisis avanzados.


## 🚀 Deployment

```json
{
  "prebuild": "rimraf dist",
  "format": "prettier --write 'src/**/*.ts' 'test/**/*.ts'",
  "start": "nest start",
  "start:dev": "cross-env STAGE=dev nest start --watch",
  "start:debug": "STAGE=dev nest start --debug --watch",
  "start:prod": "NODE_ENV=production node -r esm dist/main",
  "build": "nest build",
  "lint": "eslint '{src,apps,libs,test}/**/*.ts' --fix",
  "test": "jest",
  "test:watch": "jest --watch",
  "test:cov": "jest --coverage",
  "test:debug": "node --inspect-brk -r tsconfig-paths/register -r ts-node/register node_modules/.bin/jest --runInBand",
  "test:e2e": "jest --config ./test/jest-e2e.json"
}
```
## 🔖 Releases

Para ver las versiones anteriores y las notas de lanzamiento completas de cada release, haz clic en el botón abajo:

[![Releases](https://img.shields.io/badge/ver%20releases-%20%20%E2%9E%A1-blue?style=for-the-badge)](https://github.com/UPSTI-DESA/api-migraciones/releases)

Este apartado proporciona un acceso directo a todas las actualizaciones importantes, correcciones de errores, y nuevas características que han sido formalmente publicadas.

## 🔗 Links

### Repositorio

| GitHub |
| --- |
| [![Repositorio GitHub](https://img.shields.io/badge/GitHub-Repositorio-blue?style=for-the-badge&logo=github)](https://github.com/UPSTI-DESA/api-migraciones) |

### Proyecto

| ClickUp | Slack |
| --- | --- |
| [![ClickUp](https://img.shields.io/badge/ClickUp-Proyecto-blue?style=for-the-badge&logo=clickup)](https://app.clickup.com/12911606/v/b/ca0zp-1214) | [![Slack](https://img.shields.io/badge/Slack-Canal%20del%20Proyecto-blue?style=for-the-badge&logo=slack)](https://app.slack.com/client/T03P90TBF5Y/C03P2CMQNH4) |

### Kubernetes

| Producción | QA |
| --- | --- |
| [![Kubernetes Producción](https://img.shields.io/badge/Kubernetes%20Producción-Dashboard-blue?style=for-the-badge&logo=kubernetes)](https://web.formosa.gob.ar/dashboard/#/deployment/api/api-migraciones?namespace=_all) | [![Kubernetes QA](https://img.shields.io/badge/Kubernetes%20QA-Dashboard-blue?style=for-the-badge&logo=kubernetes)](https://web.formosa.gob.ar/dashboard/#/deployment/api/qa-api-migraciones?namespace=_all) |

### Documentos

| Google Drive |
| --- |
| [![Google Drive](https://img.shields.io/badge/Google%20Drive-Carpeta-blue?style=for-the-badge&logo=googledrive)](https://drive.google.com/drive/folders/1rofnke66-FRhaMTkC4W4EcZr0zc9niOw) |

## 📖 Documentacion

### MANUALES

| Manual de Usuario |
| --- |
| [![manual de usuario](https://img.shields.io/badge/Manual%20de%20Usuario%20refsa-grey?style=for-the-badge&logo=google-docs)](https://drive.google.com/drive/folders/1a9h_1EwpBLy87dbCeZD9j83s2AFOZLyP) |

| Kubernetes | secret |
| --- | --- |
| [![Instalación MicroK8s - Kubernetes](https://img.shields.io/badge/Instalación%20MicroK8s-grey?style=for-the-badge&logo=google-docs)](https://docs.google.com/document/d/1q5Hya5zYzFNKTljB1k6hhWGGQOW1X_DKpdO9tQI112c/edit?usp=drive_link) | [![Encriptación de .env a secret](https://img.shields.io/badge/Encriptación%20de%20.env%20a%20secret-grey?style=for-the-badge&logo=google-docs)](https://docs.google.com/document/d/1aVxIZ-3Nk-dAOo1cA3sILGmUzplO6TkBg3tHoIrPKYw/edit?usp=drive_link) |

| Manual Creación de Proyectos| Manual Despliegue de Proyectos |
| --- | --- |
| [![Script creación de Proyectos y Docker](https://img.shields.io/badge/Creación%20de%20Proyectos%20y%20Docker-grey?style=for-the-badge&logo=google-docs)](https://docs.google.com/document/d/1ejDmcxjG1EeAoPAn-eqSzw4h3jngW5j4C7cWiKYYtX8/edit?usp=drive_link) | [![Manual de Despliegue de Proyectos.sh](https://img.shields.io/badge/Despliegue%20de%20Proyectos-grey?style=for-the-badge&logo=google-docs)](https://docs.google.com/document/d/1EZS__mt2hpbA4M2gJ19jGzhvJUYOVi_iMip9SeiLikY/edit?usp=drive_link) |

### Scripts

| Script para instalar kubernetes en nodo master | Script para instalar kubernetes en nodos esclavos | Script para convertir .env a .secrets |
| --- | --- | --- |
| [![instalar_kubernetes_master.sh](https://img.shields.io/badge/instalar_kubernetes_master.sh-grey?style=for-the-badge&logo=google-drive)](https://drive.google.com/file/d/1pBH-2SrZ9Ac3LmveDd2XnQdiO6rrRNBo/view?usp=drive_link) | [![instalar_kubernetes_esclavo.sh](https://img.shields.io/badge/instalar_kubernetes_esclavo.sh-grey?style=for-the-badge&logo=google-drive)](https://drive.google.com/file/d/1j7kiZKoCNouIO-c9YyQFK8cIX32RAhZT/view?usp=drive_link) | [![create_sealed_secret.sh](https://img.shields.io/badge/create_sealed_secret.sh-grey?style=for-the-badge&logo=google-drive)](https://drive.google.com/file/d/1PLi9Fz4bsd6xIUdfunsIm3DSc9RMI5WH/view?usp=drive_link)

| Script para Crear Proyecto en docker hub | Script para Desplegar de Proyectos en kubernetes |
| --- | --- |
| [![Crear_Proyecto.sh](https://img.shields.io/badge/Crear_Proyecto.sh-grey?style=for-the-badge&logo=google-drive)](https://drive.google.com/file/d/1lbnrmkFYWSYG6skAMF3ZUYOdqkfwGynD/view?usp=drive_link) | [![Despliegue_de_Proyectos.sh](https://img.shields.io/badge/Despliegue_de_Proyectos.sh-grey?style=for-the-badge&logo=google-drive)](https://drive.google.com/file/d/1_jR4RBUUdYKScaXhF51i9Mx5lbLNUtK0/view?usp=drive_link) 


## 💻 Instalacion

Pasos para instalar el proyecto localmente:

1. Clona el repositorio.

2. Instala las dependencias:
   
```bash
  npm install
```
3. Configura las variables de entorno.
   
4. Ejecuta la migración de la base de datos:
   
```bash
  npx sequelize db:migrate
```

## 🏃 Ejecutar localmente

Pasos para ejecutar el proyecto en un entorno local:

1. Inicia el servidor de desarrollo:
```bash
 npm start
``` 
2. Accede a http://localhost:3000 en tu navegador.

## 🧪 Ejecución de pruebas

```bash
jest: 28.0.3
@types/jest: 27.5.0
ts-jest: 28.0.1
testEnvironment: node
```
## 📋 Uso/Ejemplos

Ejemplos de cómo utilizar las funcionalidades principales del sistema, incluyendo la gestión de empleados y el registro de accesos.

```javascript
import Component from 'my-project'

function App() {
  return <Component />
}
```

## ⚙️ Optimizaciones

* Sugerencias y mejoras para optimizar el rendimiento y la escalabilidad del sistema.
* Futuras mejoras y Optimizaciones

## 🔮 Futuros cambios

Escribir los posibles y futuros modulos funcionales

* Implementación de alertas y notificaciones.
* Integración con otros sistemas de gestión.
* Mejora de la interfaz de usuario.
  
## 🛣️ Roadmap

<img src="https://github.com/UPSTI-DESA/imagenes_readme/blob/main/web_refsa/roadmap.jpg?raw=true" alt="Logo" style="width:100%;">

### Fase 1: Configuración Inicial
- Configuración del proyecto y establecimiento de conexiones básicas con las bases de datos.

### Fase 2: Implementación de Funcionalidades Básicas
- Desarrollo de las funciones básicas de migración de datos entre diferentes sistemas.

### Fase 3: Expansión y Optimización
- Añadir soporte para migraciones más complejas y optimización del rendimiento.

### Fase 4: Integración y Automatización
- Automatización de procesos de migración y mejora de la interfaz de usuario para operaciones sin supervisión.


## 👥 Autores

| [![Guillermo Valdes](https://avatars.githubusercontent.com/u/38038911?v=4&s=100)](https://github.com/wowfoxz) | [![Eliseo](https://avatars.githubusercontent.com/u/14987410?v=4&s=100)](https://github.com/Ghenry15) | [![Emiliano Cáceres Miranda](https://avatars.githubusercontent.com/u/22036309?v=4&s=100)](https://github.com/EmilianoCM) | [![Tobías Zacarías](https://avatars.githubusercontent.com/u/22036461?v=4&s=100)](https://github.com/TobiasZacarias) | [![Julian Sanabria](https://avatars.githubusercontent.com/u/22036568?v=4&s=100)](https://github.com/nsanabriaJulian)| [![Gaston schneider](https://avatars.githubusercontent.com/u/22667685?v=4&s=100)](https://github.com/GastonSch) | [![Marcos Vera](https://avatars.githubusercontent.com/u/95255332?v=4&s=100)](https://github.com/MarcosVera22) | [![Leonardo Paredes](https://avatars.githubusercontent.com/u/147510738?v=4&s=100)](https://github.com/LeoxGP)
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| [Guillermo Valdes](https://github.com/wowfoxz) | [Eliseo Rahn](https://github.com/Ghenry15) | [Emiliano Cáceres](https://github.com/maria) | [Tobías Zacarías](https://github.com/TobiasZacarias)| [Julian Sanabria](https://github.com/nsanabriaJulian) | [Gaston schneider](https://github.com/GastonSch) | [Marcos Vera](https://github.com/MarcosVera22)| [Leonardo Paredes](https://github.com/LeoxGP)

## 👫 Usado por

Este proyecto es utilizado por las siguientes oficinas:

* UPSTI DESASISTEMA. 
  
## 🆘 Support

Contacta con el equipo de soporte para obtener ayuda:

Email: desasistemas@formosa.gob.ar

Teléfono: +123456789

## ⚖️ Licencia

Este proyecto es un desarrollo privado perteneciente al grupo de desarrollo de software del estado de la provincia de Formosa, Argentina. Todos los derechos están reservados.

El acceso al código fuente y su uso está restringido exclusivamente al equipo de desarrollo autorizado y a las entidades gubernamentales pertinentes. No está permitido compartir, distribuir o modificar el código sin la autorización expresa del grupo de desarrollo de software del estado de la provincia de Formosa.

Para obtener más información o solicitar acceso, por favor, contacta con el grupo de desarrollo de software a través del correo electrónico: [desasistemas@formosa.gob.ar].

## 🔒 Política de Seguridad

## Versiones Soportadas

A continuación se detallan las versiones del proyecto api-migraciones que actualmente reciben actualizaciones de seguridad.

| Ver. PROD | Soportada     | 
| ------- | ------------------ |
| 0.0.0    | :white_check_mark: |


| Ver. QA | Soportada       |
| ------- | ------------------ |
| 0.0.0   | :white_check_mark: |


## Reporte de Vulnerabilidades

Para reportar una vulnerabilidad en el proyecto api-migraciones, por favor sigue los siguientes pasos:

1. Envía un correo electrónico a [desasistemas@formosa.gob.ar](mailto:desasistemas@formosa.gob.ar) con los detalles de la vulnerabilidad.
2. Incluye en el correo una descripción detallada del problema, incluyendo pasos para reproducir la vulnerabilidad, impacto potencial y cualquier otra información relevante.
3. Nos comprometemos a responder a tu reporte dentro de 5 días hábiles.

### Proceso de Manejo de Vulnerabilidades

- **Confirmación:** Una vez recibido el reporte, confirmaremos la recepción del mismo y comenzaremos la evaluación.
- **Evaluación:** Evaluaremos la vulnerabilidad reportada para determinar su impacto y la urgencia de una solución.
- **Actualización:** Mantendremos informado al remitente del reporte sobre el progreso de la evaluación y las medidas tomadas.
- **Resolución:** Si la vulnerabilidad es confirmada, trabajaremos para desarrollar y desplegar una solución lo antes posible.
- **Divulgación:** Una vez solucionada la vulnerabilidad, publicaremos un informe detallado y actualizaremos las versiones afectadas.

Gracias por contribuir a la seguridad y mejora continua de nuestro proyecto.
