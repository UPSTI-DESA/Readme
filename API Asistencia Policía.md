<img src="https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_asistencia_policia/asistencia_policia.png?raw=true" alt="Logo" style="width:100%;">

# Proyecto API Asistencia Policía

## 🛡️ Insignias

### Tecnologías Principales

| NestJS | TypeORM | MySQL | MongoDB | MSSQL |
| --- | --- | --- | --- | --- |
| ![NestJS](https://img.shields.io/badge/NestJS-%5E9.4.0-red?style=for-the-badge&logo=nestjs) | ![TypeORM](https://img.shields.io/badge/TypeORM-%5E0.2.25-orange?style=for-the-badge&logo=typeorm) | ![MySQL](https://img.shields.io/badge/MySQL-%5E2.3.3-blue?style=for-the-badge&logo=mysql) | ![MongoDB](https://img.shields.io/badge/MongoDB-%5E4.12.1-green?style=for-the-badge&logo=mongodb) | ![MSSQL](https://img.shields.io/badge/MSSQL-%5E9.1.1-blue?style=for-the-badge&logo=microsoftsqlserver) |

### Herramientas de Desarrollo y Testing

| TypeScript | Jest | ESLint | Prettier |
| --- | --- | --- | --- |
| ![TypeScript](https://img.shields.io/badge/TypeScript-%5E4.3.5-blue?style=for-the-badge&logo=typescript) | ![Jest](https://img.shields.io/badge/Jest-%5E28.0.3-blue?style=for-the-badge&logo=jest) | ![ESLint](https://img.shields.io/badge/ESLint-%5E8.0.1-purple?style=for-the-badge&logo=eslint) | ![Prettier](https://img.shields.io/badge/Prettier-%5E2.3.2-ff69b4?style=for-the-badge&logo=prettier) |

### Docker - Producción

| Docker Pulls | Docker Automated build | Docker Image Size | Docker Image Version |
| --- | --- | --- | --- |
| ![Docker Pulls](https://img.shields.io/docker/pulls/upsti/api-asistencia-policia?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Automated build](https://img.shields.io/docker/automated/upsti/api-asistencia-policia?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Image Size](https://img.shields.io/docker/image-size/upsti/api-asistencia-policia?style=for-the-badge&logo=docker&color=blueviolet&link=https%3A%2F%2Fhub.docker.com%2Frepository%2Fdocker%2Fupsti%2Fapi-asistencia-policia%2Fgeneral) | ![Docker Image Version](https://img.shields.io/docker/v/upsti/api-asistencia-policia?style=for-the-badge&logo=docker&color=blueviolet) |

### Docker - QA

| Docker Pulls | Docker Automated build | Docker Image Size | Docker Image Version |
| --- | --- | --- | --- |
| ![Docker Pulls](https://img.shields.io/docker/pulls/upsti/qa-api-asistencia-policia?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Automated build](https://img.shields.io/docker/automated/upsti/qa-api-asistencia-policia?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Image Size](https://img.shields.io/docker/image-size/upsti/qa-api-asistencia-policia?style=for-the-badge&logo=docker&color=blueviolet&link=https%3A%2F%2Fhub.docker.com%2Frepository%2Fdocker%2Fupsti%2Fqa-api-asistencia-policia%2Fgeneral) | ![Docker Image Version](https://img.shields.io/docker/v/upsti/qa-api-asistencia-policia?style=for-the-badge&logo=docker&color=blueviolet) |

### Website

<table>
  <tr>
    <th>Web Asistencia Policía</th>
    <th>QA Web Asistencia Policía</th>
  </tr>
  <tr>
    <td>
      <a href="https://api.formosa.gob.ar/api-asistencia-policia/api/">
        <img src="https://img.shields.io/website?url=https%3A%2F%2Fapi.formosa.gob.ar%2Fapi-asistencia-policia%2Fapi%2F&up_message=ACTIVO&style=for-the-badge&label=api-asistencia-policia&logo=statuspage" alt="Website">
      </a>
    </td>
    <td>
      <a href="https://qa.formosa.gob.ar/api-asistencia-policia/api/">
        <img src="https://img.shields.io/website?url=https%3A%2F%2Fqa.formosa.gob.ar%2Fapi-asistencia-policia%2Fapi%2F&up_message=ACTIVO&style=for-the-badge&label=qa-api-asistencia-policia&logo=statuspage" alt="QA Website">
      </a>
    </td>
  </tr>
</table>

## 📄 Descripción del Proyecto

El proyecto es una API robusta desarrollada con NestJS, diseñada para gestionar y procesar datos de asistencia policial. Esta API facilita la interacción entre las bases de datos y las api cliente, proporcionando un punto de acceso centralizado para la manipulación de datos relacionados con incidentes, reportes y seguimientos de actividades. La API está construida para ser altamente escalable, segura y eficiente, con el fin de responder a las demandas en tiempo real de los servicios de asistencia policial.

## 🛠️ Tech Stack (tecnologías)

**Backend:**
- **NestJS:** Framework de Node.js para construir api de servidor eficientes y escalables usando TypeScript.
- **TypeORM:** ORM para TypeScript y JavaScript que soporta SQL y NoSQL, facilitando la interacción con MySQL, MSSQL y MongoDB.
- **MySQL, MSSQL, MongoDB:** Bases de datos utilizadas para almacenar datos estructurados y no estructurados.

**Seguridad y Validación:**
- **Class-validator:** Utilizado para validar datos entrantes basados en simples decoradores.
- **JWT (JSON Web Tokens):** Para autenticación y autorización segura de los usuarios.

**Pruebas:**
- **Jest:** Marco de pruebas para JavaScript con un enfoque en la simplicidad y el soporte para pruebas de api de gran escala.

**Automatización y Entorno:**
- **Cross-env:** Utilizado para manejar variables de entorno en scripts.
- **Rimraf:** Para la eliminación de archivos y directorios en scripts de node.

**Desarrollo y Formateo de Código:**
- **ESLint:** Análisis de código para identificar problemas problemáticos.
- **Prettier:** Herramienta de formateo de código para mantener la consistencia del estilo.

**Integración Biométrica:**

* Lector de huellas digitales (Anviz EP300)
* SDK para integración con el sistema web

## 📑 Índice

* [🖼️ Título e imagen de portada](#proyecto-web-asistencia-policía)
* [🛡️ Insignias](#%EF%B8%8F-insignias)
* [📄 Descripción del proyecto](#-descripción-del-proyecto)
* [🛠️ Tech Stack (tecnologías)](#%EF%B8%8F-tech-stack-tecnologías)
* [📑 Índice](#-índice)
* [✨ Features](#-features-características)
* [📸 Capturas de pantalla](#-capturas-de-pantalla)
* [🌐 Demo](#-demo)
* [🚀 Deployment](#-deployment)
* [🔗 Links](#-links)
* [📖 Documentacion](#-documentacion)
* [📚 API Referencia](#-api-referencia)
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

- **Autenticación y Autorización:** Implementación de medidas de seguridad robustas para garantizar que solo los usuarios autorizados puedan acceder a la información.
- **Reportes y Estadísticas:** Generación de reportes dinámicos y análisis estadístico de los datos para apoyar la toma de decisiones.
- **Integración con Sistemas Externos:** Facilidades para integrar con otras plataformas y servicios, mejorando la interoperabilidad del sistema.

## 📸 Capturas de pantalla

![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_asistencia_policia/Screenshot_1.png)
![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_asistencia_policia/Screenshot_2.png)
![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_asistencia_policia/Screenshot_3.png)

## 🌐 Demo

![Insert gif or link to demo](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_asistencia_policia/api_asistencia_policia.gif)

## 🚀 Deployment

### Prerrequisitos
1. **Infraestructura:**
   - Un clúster de Kubernetes configurado.
   - Acceso a Docker Hub para obtener la imagen del contenedor.
   - Lector de huellas digitales configurado y conectado.

2. **Credenciales y Configuraciones:**
   - Variables de entorno necesarias para la aplicación.
   - Archivos de configuración para Kubernetes.

### Pasos para el Despliegue

#### 1. Obtener la Imagen del Contenedor
- Asegúrate de tener acceso a Docker Hub y de que la imagen de la aplicación esté disponible.
- La imagen se encuentra en: `upsti/api-asistencia-policia:v0.0.3`.

#### 2. Configurar Variables de Entorno
- Crea un archivo `.env` con las variables de entorno necesarias. Por ejemplo:

```bash
DB_HOST=
DB_PORT=
DB_USERNAME=
DB_PASSWORD=
DB_DATABASE=
JWT_SECRET=
EXPIRES_IN=
STAGE=
```
#### 3. Crear y Aplicar Configuración para Kubernetes
- Utiliza los siguientes archivos YAML para configurar el despliegue en Kubernetes.

##### Deployment
```yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: api-asistencia-policia
  namespace: api
  labels:
    k8s-app: api-asistencia-policia
spec:
  replicas: 1
  selector:
    matchLabels:
      k8s-app: api-asistencia-policia
  template:
    metadata:
      name: api-asistencia-policia
      labels:
        k8s-app: api-asistencia-policia
    spec:
      containers:
      - name: api-asistencia-policia
        image: upsti/api-asistencia-policia:v0.0.3
        securityContext:
          privileged: false
        resources:
          requests:
            memory: "4Mi"
            cpu: "26m"
          limits:
            memory: "6Mi"
            cpu: "200m"
```

##### Horizontal Pod Autoscaler

```yaml
apiVersion: autoscaling/v2
kind: HorizontalPodAutoscaler
metadata:
  name: api-asistencia-policia-hpa
  namespace: api
spec:
  scaleTargetRef:
    apiVersion: apps/v1
    kind: Deployment
    name: api-asistencia-policia
  minReplicas: 1
  maxReplicas: 5
  metrics:
    - type: Resource
      resource:
        name: cpu
        target:
          type: Utilization
          averageUtilization: 95
```

##### Ingress

```yaml
apiVersion: networking.k8s.io/v1
kind: Ingress
metadata:
  name: api-asistencia-policia
  namespace: api
  annotations:
    nginx.ingress.kubernetes.io/backend-protocol: "HTTP"
    nginx.ingress.kubernetes.io/rewrite-target: /$2
    nginx.ingress.kubernetes.io/configuration-snippet: |
      rewrite ^(/api-asistencia-policia)$ $1/ redirect;
spec:
  ingressClassName: "public"
  rules:
  - host: api.formosa.gob.ar
    http:
      paths:
      - path: /api-asistencia-policia(/|$)(.*)
        pathType: ImplementationSpecific
        backend:
          service:
            name: api-asistencia-policia
            port:
              number: 3000
```

##### Service

```yaml
apiVersion: v1
kind: Service
metadata:
  name: api-asistencia-policia
  namespace: api
spec:
  selector:
    k8s-app: api-asistencia-policia
  ports:
  - name: tcp-3000-asistencia-policia
    protocol: TCP
    port: 3000
    targetPort: 3000
  type: LoadBalancer
```

#### 4. Desplegar en Kubernetes
- Aplica la configuración de Kubernetes usando los archivos YAML proporcionados:
```sh
kubectl apply -f deployment.yaml
kubectl apply -f hpa.yaml
kubectl apply -f ingress.yaml
kubectl apply -f service.yaml
```
- Verifica que los pods estén corriendo:
```sh
kubectl get pods -n api
```
#### 5. Configurar el Servicio y Acceso a la Aplicación

- Configura un servicio para exponer tu aplicación:
```sh
kubectl get service api-asistencia-policia -n api
```
- Obtén la IP del servicio para acceder a la aplicación.

#### Integración del Lector de Huellas
- Asegúrate de que el lector de huellas esté correctamente configurado y conectado al servidor.
- Verifica que el SDK del lector de huellas esté integrado en la aplicación y funcionando correctamente.
#### Consideraciones de Seguridad
- Asegúrate de que todas las conexiones a la base de datos y las comunicaciones entre los servicios estén encriptadas.
- Implementa medidas de seguridad para proteger las credenciales y datos sensibles.

## 🔗 Links

### Docker

| Producción | QA |
| --- | --- |
| [![Docker Hub](https://img.shields.io/badge/hub.docker.com-web%20asistencia%20policia-blue?style=for-the-badge&logo=docker)](https://hub.docker.com/repository/docker/upsti/api-asistencia-policia/general) | [![Docker Hub](https://img.shields.io/badge/hub.docker.com-qa%20web%20asistencia%20policia-blue?style=for-the-badge&logo=docker)](https://hub.docker.com/repository/docker/upsti/qa-api-asistencia-policia/general) |

### Web-API

| Producción | QA |
| --- | --- |
| [![Web Producción](https://img.shields.io/badge/Web.api%20Producción-api%20asistencia%20policia-blue?style=for-the-badge&logo=googlechrome)](https://api.formosa.gob.ar/api-asistencia-policia/api/) | [![Web QA](https://img.shields.io/badge/Web.api%20QA-api%20asistencia%20policia-blue?style=for-the-badge&logo=googlechrome)](https://qa.formosa.gob.ar/api-asistencia-policia/api/) |

### Repositorio

| GitHub |
| --- |
| [![Repositorio GitHub](https://img.shields.io/badge/GitHub-Repositorio-blue?style=for-the-badge&logo=github)](https://github.com/UPSTI-DESA/api-asistencia-policia) |

### Proyecto

| ClickUp | Slack |
| --- | --- |
| [![ClickUp](https://img.shields.io/badge/ClickUp-Proyecto-blue?style=for-the-badge&logo=clickup)](https://app.clickup.com/12911606/v/b/ca0zp-1214) | [![Slack](https://img.shields.io/badge/Slack-Canal%20del%20Proyecto-blue?style=for-the-badge&logo=slack)](https://app.slack.com/client/T03P90TBF5Y/C03P2CMQNH4) |

### Kubernetes

| Producción | QA |
| --- | --- |
| [![Kubernetes Producción](https://img.shields.io/badge/Kubernetes%20Producción-Dashboard-blue?style=for-the-badge&logo=kubernetes)](https://web.formosa.gob.ar/dashboard/#/deployment/api/api-asistencia-policia?namespace=_all) | [![Kubernetes QA](https://img.shields.io/badge/Kubernetes%20QA-Dashboard-blue?style=for-the-badge&logo=kubernetes)](https://web.formosa.gob.ar/dashboard/#/deployment/api/qa-api-asistencia-policia?namespace=_all) |

### Documentos

| Google Drive |
| --- |
| [![Google Drive](https://img.shields.io/badge/Google%20Drive-Carpeta-blue?style=for-the-badge&logo=googledrive)](https://drive.google.com/drive/folders/1X_NjF0LgeNovX1rOGKIbg62tE4Yb4mUH?usp=sharing) |

## 📖 Documentacion

### MANUALES

| Manual de Usuario |
| --- |
| [![manual de usuario](https://img.shields.io/badge/Manual%20de%20Usuario%20-grey?style=for-the-badge&logo=google-docs)](https://bioupsti.formosa.gob.ar/manual/asistencia_policia.pdf) |

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

## 📚 API Referencia

- [Swagger: API Documentation](https://api.formosa.gob.ar/api-asistencia-policia/api/)
- [Swagger: QA API Documentation](https://qa.formosa.gob.ar/api-asistencia-policia/api/)

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

Instrucciones para ejecutar las pruebas unitarias y de integración:

1.Ejecuta las pruebas: 

```bash
  npm run test
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

<img src="https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_asistencia_policia/roadmap.jpg?raw=true" alt="Logo" style="width:100%;">

### Fase 1: Desarrollo Inicial y Lanzamiento
- **Completo:** Configuración inicial de NestJS y conexión con bases de datos.
- **Completo:** Desarrollo de endpoints básicos y estructura de seguridad.

### Fase 2: Expansión de Funcionalidades
- **Completo:** Añadir más endpoints para cobertura completa de funcionalidades.
- **Completo:** Implementar análisis avanzados y reportes de datos.

### Fase 3: Optimización y Escalabilidad
- **En Progreso:** Refactorización del código para mejorar la escalabilidad y el rendimiento.
- **Planeado:** Expansión a más regiones y integración con más sistemas externos.

### Fase 4: Innovación y Nuevas Tecnologías
- **Futuro:** Explorar el uso de IA para predicción de patrones.
- **Futuro:** Implementación de tecnologías de blockchain para mejorar la seguridad y la transparencia de los datos.

## 👥 Autores

| [![Guillermo Valdes](https://avatars.githubusercontent.com/u/38038911?v=4&s=100)](https://github.com/wowfoxz) | [![Eliseo](https://avatars.githubusercontent.com/u/14987410?v=4&s=100)](https://github.com/Ghenry15) | [![Emiliano Cáceres Miranda](https://avatars.githubusercontent.com/u/22036309?v=4&s=100)](https://github.com/EmilianoCM) | [![Tobías Zacarías](https://avatars.githubusercontent.com/u/22036461?v=4&s=100)](https://github.com/TobiasZacarias) | [![Julian Sanabria](https://avatars.githubusercontent.com/u/22036568?v=4&s=100)](https://github.com/nsanabriaJulian)| [![Gaston schneider](https://avatars.githubusercontent.com/u/22667685?v=4&s=100)](https://github.com/GastonSch) | [![Marcos Vera](https://avatars.githubusercontent.com/u/95255332?v=4&s=100)](https://github.com/MarcosVera22) | [![Leonardo Paredes](https://avatars.githubusercontent.com/u/147510738?v=4&s=100)](https://github.com/LeoxGP)
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| [Guillermo Valdes](https://github.com/wowfoxz) | [Eliseo Rahn](https://github.com/Ghenry15) | [Emiliano Cáceres](https://github.com/maria) | [Tobías Zacarías](https://github.com/TobiasZacarias)| [Julian Sanabria](https://github.com/nsanabriaJulian) | [Gaston schneider](https://github.com/GastonSch) | [Marcos Vera](https://github.com/MarcosVera22)| [Leonardo Paredes](https://github.com/LeoxGP)

## 👫 Usado por

Este proyecto es utilizado por las siguientes oficinas:

* Instituto Superior de Formación Policial.
* Otros institutos educativos que requieran control de asistencia biométrica.
  
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

A continuación se detallan las versiones del proyecto api-asistencia-policia que actualmente reciben actualizaciones de seguridad.

| Ver. PROD | Soportada        |
| ------- | ------------------ |
| 0.0.3   | :white_check_mark: |
| 0.0.2   | :x:                |
| 0.0.1   | :x:                |

| Ver. QA | Soportada          |
| ------- | ------------------ |
| 0.0.3   | :white_check_mark: |
| 0.0.2   | :x:                |
| 0.0.1   | :x:                |

## Reporte de Vulnerabilidades

Para reportar una vulnerabilidad en el proyecto api-asistencia-policia, por favor sigue los siguientes pasos:

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
