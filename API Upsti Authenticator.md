<img src="https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api-upsti-authenticator/upsti_authenticator.png?raw=true" alt="Logo" style="width:100%;">

# Proyecto API Upsti Authenticator

## 🛡️ Insignias

### Tecnologías Principales

| NestJS | TypeORM | JWT | PostgreSQL |
| --- | --- | --- | --- |
| ![NestJS](https://img.shields.io/badge/NestJS-%5E10.0.0-red?style=for-the-badge&logo=nestjs) | ![TypeORM](https://img.shields.io/badge/TypeORM-%5E10.0.2-orange?style=for-the-badge&logo=typeorm) | ![JWT](https://img.shields.io/badge/JWT-%5E10.2.0-blue?style=for-the-badge&logo=jsonwebtokens) | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-blue?style=for-the-badge&logo=postgresql) |

### Herramientas de Desarrollo y Testing

| TypeScript | Jest | ESLint | Prettier |
| --- | --- | --- | --- |
| ![TypeScript](https://img.shields.io/badge/TypeScript-%5E5.1.3-blue?style=for-the-badge&logo=typescript) | ![Jest](https://img.shields.io/badge/Jest-%5E29.5.0-blue?style=for-the-badge&logo=jest) | ![ESLint](https://img.shields.io/badge/ESLint-%5E8.56.0-purple?style=for-the-badge&logo=eslint) | ![Prettier](https://img.shields.io/badge/Prettier-%5E3.2.5-ff69b4?style=for-the-badge&logo=prettier) |

### Docker - Producción

| Docker Pulls | Docker Automated build | Docker Image Size | Docker Image Version |
| --- | --- | --- | --- |
| ![Docker Pulls](https://img.shields.io/docker/pulls/upsti/api-upsti-authenticator?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Automated build](https://img.shields.io/docker/automated/upsti/api-upsti-authenticator?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Image Size](https://img.shields.io/docker/image-size/upsti/api-upsti-authenticator?style=for-the-badge&logo=docker&color=blueviolet&link=https%3A%2F%2Fhub.docker.com%2Frepository%2Fdocker%2Fupsti%2Fapi-upsti-authenticator%2Fgeneral) | ![Docker Image Version](https://img.shields.io/docker/v/upsti/api-upsti-authenticator?style=for-the-badge&logo=docker&color=blueviolet) |

### Docker - QA

| Docker Pulls | Docker Automated build | Docker Image Size | Docker Image Version |
| --- | --- | --- | --- |
| ![Docker Pulls](https://img.shields.io/docker/pulls/upsti/qa-api-upsti-authenticator?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Automated build](https://img.shields.io/docker/automated/upsti/qa-api-upsti-authenticator?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Image Size](https://img.shields.io/docker/image-size/upsti/qa-api-upsti-authenticator?style=for-the-badge&logo=docker&color=blueviolet&link=https%3A%2F%2Fhub.docker.com%2Frepository%2Fdocker%2Fupsti%2Fqa-api-upsti-authenticator%2Fgeneral) | ![Docker Image Version](https://img.shields.io/docker/v/upsti/qa-api-upsti-authenticator?style=for-the-badge&logo=docker&color=blueviolet) |

### Website

<table>
  <tr>
    <th>Web Autenticador de usuarios</th>
    <th>QA Web Autenticador de usuarios</th>
  </tr>
  <tr>
    <td>
      <a href="https://api.formosa.gob.ar/api-upsti-authenticator/swagger/">
        <img src="https://img.shields.io/website?url=https%3A%2F%2Fapi.formosa.gob.ar%2Fapi-upsti-authenticator%2Fswagger%2F&up_message=ACTIVO&style=for-the-badge&label=api-upsti-authenticator&logo=statuspage" alt="Website">
      </a>
    </td>
    <td>
      <a href="https://qa.formosa.gob.ar/api-upsti-authenticator/swagger/">
        <img src="https://img.shields.io/website?url=https%3A%2F%2Fqa.formosa.gob.ar%2Fapi-upsti-authenticator%2Fswagger%2F&up_message=ACTIVO&style=for-the-badge&label=qa-api-upsti-authenticator&logo=statuspage" alt="QA Website">
      </a>
    </td>
  </tr>
</table>

## 📄 Descripción del Proyecto

El proyecto "Autenticador de Usuarios" es una API diseñada para facilitar la gestión integral de la autenticación y autorización de usuarios dentro de un entorno de microservicios. Esta solución robusta permite no solo registrar nuevos usuarios y administrar sus roles y permisos, sino también manejar de forma segura las sesiones de autenticación a través de una interfaz de API REST.

### Función Principal

- **Registro de Usuarios:** Permite la creación de cuentas de usuario, asegurando que toda la información sea almacenada de forma segura.
- **Gestión de Roles y Permisos:** Administra los niveles de acceso y los permisos de los usuarios, permitiendo una configuración flexible según las necesidades del sistema.
- **Autenticación de Sesiones:** Verifica las credenciales de los usuarios y proporciona tokens de sesión para mantener una experiencia de usuario segura y consistente.

### Tecnologías Utilizadas

**Backend:**
- **NodeJS y Express:** Estos forman la base del servidor, proporcionando una plataforma poderosa y eficiente para manejar solicitudes HTTP y gestionar la lógica del negocio.
  
**Base de Datos:**
- **MongoDB:** Utilizada para almacenar y gestionar los datos de los usuarios de forma no relacional, lo que facilita escalabilidad y flexibilidad.

**Seguridad:**
- **JWT (JSON Web Tokens):** Se utiliza para manejar la autenticación de sesiones, asegurando que cada solicitud al servidor esté debidamente autorizada.
- **OAuth2:** Implementa estándares de autorización para servicios externos, permitiendo a los usuarios acceder de manera segura sin exponer sus credenciales directamente.

Este sistema está diseñado para ser altamente escalable y seguro, adecuándose a un amplio rango de aplicaciones que requieren gestión rigurosa de usuarios y sesiones en diversos contextos operativos.

## 🛠️ Tech Stack (tecnologías)

**Backend:**
- **NestJS:** Framework de desarrollo server-side en Node.js que facilita la construcción de aplicaciones de backend escalables y mantenibles.
- **TypeORM:** ORM para TypeScript que facilita la interacción con varias bases de datos SQL como PostgreSQL, simplificando las operaciones CRUD y las migraciones.

**Autenticación:**
- **JWT (JSON Web Tokens):** Utilizado para la autenticación y transmisión segura de información entre partes.

**Testing y Calidad de Código:**
- **Jest:** Utilizado para pruebas unitarias y de integración.
- **ESLint y Prettier:** Herramientas para asegurar la calidad del código y mantener un estilo coherente.

**Otros:**
- **axios:** Cliente HTTP basado en promesas para realizar solicitudes a otros servicios web.
- **dotenv:** Utilizado para gestionar variables de entorno de manera local.

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

- **Autenticación Segura:** Implementa procesos de login y manejo de sesiones utilizando JWT para asegurar todas las comunicaciones entre clientes y el servidor.
- **Integración de Servicios:** Capacidad para conectarse con múltiples bases de datos y APIs externas asegurando interoperabilidad.
- **Gestión de Usuarios:** Permite la administración de usuarios, incluyendo registros, actualizaciones, y la recuperación de contraseñas de manera segura.
- **Monitoreo y Auditoría:** Facilita la trazabilidad de acciones a través de logs y auditorías integradas para cumplir con estándares de seguridad.
- **Alta Disponibilidad y Escalabilidad:** Diseñado para manejar altas cargas de tráfico y ser escalable según las necesidades organizacionales.

## 📸 Capturas de pantalla

![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api-upsti-authenticator/Screenshot_1.png)
![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api-upsti-authenticator/Screenshot_2.png)
![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api-upsti-authenticator/Screenshot_3.png)

## 🌐 Demo

![Insert gif or link to demo](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api-upsti-authenticator/api_authenthicator.gif)

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
- La imagen se encuentra en: `upsti/api-upsti-authenticator:v0.0.1`.

#### 2. Configurar Variables de Entorno
- Crea un archivo `.env` con las variables de entorno necesarias. Por ejemplo:

```bash
NODE_TLS_REJECT_UNAUTHORIZED=
NODE_ENV=
PORT=
PROXY_ENABLED=
CONTEXT=
ORIGINS=
CORS_ENABLED=
CORS_CREDENTIALS=
LOG_LEVEL=
LOG_LEVEL_STRING=
CLAIMS_ORIGINS=
CLAIMS_SECRET=
SWAGGER_PATH=
SWAGGER_ENABLED=
JAEGER_ENABLED=
JAEGER_HOST=
JAEGER_PORT=
JAEGER_AGENT_EXCLUDES=
DB_CONNECTION=
DB_HOST=
DB_PORT=
DB_USERNAME=
DB_PASSWORD=
DB_DATABASE=
DB_URL=
DB_LOGGING=
DB_SSL=
DB_SCHEMA=
BASE_URL_WS=
WS_IASEP=
WS_IUR=
WS_REFSA=
WS_RPI=
WS_SALUD_MATRICULAS=
WS_SIP_INSERT_PERSON=
WS_SIP_PERSONAS=p
JWT_SECRET=
JWT_EXPIRATION=
JWT_REFRESH=
JWT_REFRESH_EXPIRATION=
CODE_SECRET=
CODE_EXPIRATION=
MAILER_HOST=
MAILER_PORT=
MAILER_SECURE=
MAILER_USER=
MAILER_PWD=
MAILER_DEFAULT_FROM=
FTP_HOST=
FTP_PORT=
FTP_USER=
FTP_PASSWORD=
BASE_URL_IMAGES=
RELATIVE_PATH_IMAGES=
CANAL=
JWT_PRIVATE_KEY=
BASE_URL_PORTAL=

```
#### 3. Crear y Aplicar Configuración para Kubernetes
- Utiliza los siguientes archivos YAML para configurar el despliegue en Kubernetes.

##### Deployment
```yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: api-upsti-authenticator
  namespace: api
  labels:
    k8s-app: api-upsti-authenticator
spec:
  replicas: 1
  selector:
    matchLabels:
      k8s-app: api-upsti-authenticator
  template:
    metadata:
      name: api-upsti-authenticator
      labels:
        k8s-app: api-upsti-authenticator
    spec:
      containers:
      - name: api-upsti-authenticator
        image: upsti/api-upsti-authenticator:v0.0.1
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
  name: api-upsti-authenticator-hpa
  namespace: api
spec:
  scaleTargetRef:
    apiVersion: apps/v1
    kind: Deployment
    name: api-upsti-authenticator
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
  name: api-upsti-authenticator
  namespace: api
  annotations:
    nginx.ingress.kubernetes.io/backend-protocol: "HTTP"
    nginx.ingress.kubernetes.io/rewrite-target: /$2
    nginx.ingress.kubernetes.io/configuration-snippet: |
      rewrite ^(/api-upsti-authenticator)$ $1/ redirect;
spec:
  ingressClassName: "public"
  rules:
  - host: api.formosa.gob.ar
    http:
      paths:
      - path: /api-upsti-authenticator(/|$)(.*)
        pathType: ImplementationSpecific
        backend:
          service:
            name: api-upsti-authenticator
            port:
              number: 3000
```

##### Service

```yaml
apiVersion: v1
kind: Service
metadata:
  name: api-upsti-authenticator
  namespace: api
spec:
  selector:
    k8s-app: api-upsti-authenticator
  ports:
  - name: tcp-3000-upsti-authenticator
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
kubectl get service api-upsti-authenticator -n api
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
| [![Docker Hub](https://img.shields.io/badge/hub.docker.com-web%20upsti%20authenticator-blue?style=for-the-badge&logo=docker)](https://hub.docker.com/repository/docker/upsti/api-upsti-authenticator/general) | [![Docker Hub](https://img.shields.io/badge/hub.docker.com-qa%20web%20upsti%20authenticator-blue?style=for-the-badge&logo=docker)](https://hub.docker.com/repository/docker/upsti/qa-api-upsti-authenticator/general) |

### Web-API

| Producción | QA |
| --- | --- |
| [![Web Producción](https://img.shields.io/badge/Web.api%20Producción-api%20upsti%20authenticator-blue?style=for-the-badge&logo=googlechrome)](https://api.formosa.gob.ar/api-upsti-authenticator/swagger/) | [![Web QA](https://img.shields.io/badge/Web.api%20QA-api%20upsti%20authenticator-blue?style=for-the-badge&logo=googlechrome)](https://qa.formosa.gob.ar/api-upsti-authenticator/swagger/) |

### Repositorio

| GitHub |
| --- |
| [![Repositorio GitHub](https://img.shields.io/badge/GitHub-Repositorio-blue?style=for-the-badge&logo=github)](https://github.com/UPSTI-DESA/api-upsti-authenticator) |

### Proyecto

| ClickUp | Slack |
| --- | --- |
| [![ClickUp](https://img.shields.io/badge/ClickUp-Proyecto-blue?style=for-the-badge&logo=clickup)](https://app.clickup.com/12911606/v/o/s/54943912) | [![Slack](https://img.shields.io/badge/Slack-Canal%20del%20Proyecto-blue?style=for-the-badge&logo=slack)](https://app.slack.com/client/T03P90TBF5Y/C03P2CMQNH4) |

### Kubernetes

| Producción | QA |
| --- | --- |
| [![Kubernetes Producción](https://img.shields.io/badge/Kubernetes%20Producción-Dashboard-blue?style=for-the-badge&logo=kubernetes)](https://web.formosa.gob.ar/dashboard/#/deployment/api/api-upsti-authenticator?namespace=_all) | [![Kubernetes QA](https://img.shields.io/badge/Kubernetes%20QA-Dashboard-blue?style=for-the-badge&logo=kubernetes)](https://web.formosa.gob.ar/dashboard/#/deployment/api/qa-api-upsti-authenticator?namespace=_all) |

## 📖 Documentacion

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

- [Swagger: API Documentation](https://api.formosa.gob.ar/api-upsti-authenticator/swagger/)
- [Swagger: QA API Documentation](https://qa.formosa.gob.ar/api-upsti-authenticator/swagger/)

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

<img src="https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api-upsti-authenticator/roadmap.jpg?raw=true" alt="Logo" style="width:100%;">

## 🛣️ Roadmap

### Fase 1: Desarrollo Inicial y Configuración Básica
- **Completo:** Configuración del entorno de desarrollo utilizando NodeJS y Express.
- **Completo:** Implementación de la conexión inicial con la base de datos MongoDB.
- **Completo:** Creación de la arquitectura básica para registro y autenticación de usuarios.

### Fase 2: Implementación de Seguridad y Funciones Avanzadas
- **En Progreso:** Integración de JWT para la gestión segura de sesiones.
- **Planeado:** Desarrollo e implementación del sistema OAuth2 para autorización de terceros.
- **Planeado:** Aumentar las funcionalidades de gestión de roles y permisos.

### Fase 3: Optimización y Expansión
- **Planeado:** Refinamiento de la API para mejorar el rendimiento y la seguridad.
- **Planeado:** Extender la API para soportar más tipos de autenticación y personalización de roles.
- **Futuro:** Desarrollo de interfaces de usuario administrativas para una gestión más fácil de los usuarios y roles.

### Fase 4: Escalabilidad y Preparación para el Lanzamiento
- **Futuro:** Preparar la API para el despliegue a gran escala, asegurando su compatibilidad y rendimiento en diferentes entornos.
- **Futuro:** Implementar pruebas exhaustivas para garantizar la seguridad y la robustez del sistema.
- **Futuro:** Lanzamiento oficial y continuación del monitoreo y mantenimiento regular para asegurar la operatividad y actualización del sistema.

Cada una de estas fases está diseñada para asegurar que el sistema de autenticación no solo cumpla con los estándares actuales de seguridad y funcionalidad, sino que también pueda adaptarse y evolucionar según las necesidades futuras de la organización y cambios tecnológicos.

## 👥 Autores

| [![Guillermo Valdes](https://avatars.githubusercontent.com/u/38038911?v=4&s=100)](https://github.com/wowfoxz) | [![Eliseo](https://avatars.githubusercontent.com/u/14987410?v=4&s=100)](https://github.com/Ghenry15) | [![Emiliano Cáceres Miranda](https://avatars.githubusercontent.com/u/22036309?v=4&s=100)](https://github.com/EmilianoCM) | [![Tobías Zacarías](https://avatars.githubusercontent.com/u/22036461?v=4&s=100)](https://github.com/TobiasZacarias) | [![Julian Sanabria](https://avatars.githubusercontent.com/u/22036568?v=4&s=100)](https://github.com/nsanabriaJulian)| [![Gaston schneider](https://avatars.githubusercontent.com/u/22667685?v=4&s=100)](https://github.com/GastonSch) | [![Marcos Vera](https://avatars.githubusercontent.com/u/95255332?v=4&s=100)](https://github.com/MarcosVera22) | [![Leonardo Paredes](https://avatars.githubusercontent.com/u/147510738?v=4&s=100)](https://github.com/LeoxGP)
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| [Guillermo Valdes](https://github.com/wowfoxz) | [Eliseo Rahn](https://github.com/Ghenry15) | [Emiliano Cáceres](https://github.com/maria) | [Tobías Zacarías](https://github.com/TobiasZacarias)| [Julian Sanabria](https://github.com/nsanabriaJulian) | [Gaston schneider](https://github.com/GastonSch) | [Marcos Vera](https://github.com/MarcosVera22)| [Leonardo Paredes](https://github.com/LeoxGP)

## 👫 Usado por

Este proyecto es utilizado por las siguientes oficinas:

* Gobierno de la Provincia de Formosa.

  
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

A continuación se detallan las versiones del proyecto api-upsti-authenticator que actualmente reciben actualizaciones de seguridad.

| Ver. PROD | Soportada        |
| ------- | ------------------ |
| 0.0.1   | :white_check_mark: |

| Ver. QA | Soportada          |
| ------- | ------------------ |
| 0.0.4   | :x:                |
| 0.0.3   | :white_check_mark: |
| 0.0.2   | :x:                |
| 0.0.1   | :white_check_mark: |

## Reporte de Vulnerabilidades

Para reportar una vulnerabilidad en el proyecto api-upsti-authenticator, por favor sigue los siguientes pasos:

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
