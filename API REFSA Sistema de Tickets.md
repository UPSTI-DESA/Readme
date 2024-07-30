<img src="https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_refsa/refsa.png?raw=true" alt="Logo" style="width:100%;">

# Proyecto API REFSA Sistema de Tickets 

## 🛡️ Insignias

### Tecnologías y herramientas

| Node.js | NestJS | PostgreSQL | MySQL | MongoDB | Firebase |
| --- | --- | --- | --- | --- | --- |
| ![Node.js](https://img.shields.io/badge/Node.js-%5E18-green?style=for-the-badge&logo=node.js) | ![NestJS](https://img.shields.io/badge/NestJS-%5E8.4.7-red?style=for-the-badge&logo=nestjs) | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%5E8.6.0-blue?style=for-the-badge&logo=postgresql) | ![MySQL](https://img.shields.io/badge/MySQL-%5E3.2.0-blue?style=for-the-badge&logo=mysql) | ![MongoDB](https://img.shields.io/badge/MongoDB-3-green?style=for-the-badge&logo=mongodb) | ![Firebase](https://img.shields.io/badge/Firebase-%5E11.0.1-yellow?style=for-the-badge&logo=firebase) |

### Gestión de paquetes y pruebas

| Yarn | Jest | TypeScript |
| --- | --- | --- |
| ![Yarn](https://img.shields.io/badge/Yarn-%5E1.22-blue?style=for-the-badge&logo=yarn) | ![Jest](https://img.shields.io/badge/Jest-%5E26.6.3-blue?style=for-the-badge&logo=jest) | ![TypeScript](https://img.shields.io/badge/TypeScript-%5E5.4.5-blue?style=for-the-badge&logo=typescript) |

### Herramientas de desarrollo

| ESLint | Prettier | TypeORM |
| --- | --- | --- |
| ![ESLint](https://img.shields.io/badge/ESLint-%5E7.12.1-purple?style=for-the-badge&logo=eslint) | ![Prettier](https://img.shields.io/badge/Prettier-%5E2.1.2-ff69b4?style=for-the-badge&logo=prettier) | ![TypeORM](https://img.shields.io/badge/TypeORM-%5E0.3.16-orange?style=for-the-badge&logo=typeorm) |

### Docker - Producción

| Docker Pulls | Docker Automated build | Docker Image Size | Docker Image Version |
| --- | --- | --- | --- |
| ![Docker Pulls](https://img.shields.io/docker/pulls/upsti/api-refsa?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Automated build](https://img.shields.io/docker/automated/upsti/api-refsa?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Image Size](https://img.shields.io/docker/image-size/upsti/api-refsa?style=for-the-badge&logo=docker&color=blueviolet&link=https%3A%2F%2Fhub.docker.com%2Frepository%2Fdocker%2Fupsti%2Fapi-refsa%2Fgeneral) | ![Docker Image Version](https://img.shields.io/docker/v/upsti/api-refsa?style=for-the-badge&logo=docker&color=blueviolet) |

### Docker - QA

| Docker Pulls | Docker Automated build | Docker Image Size | Docker Image Version |
| --- | --- | --- | --- |
| ![Docker Pulls](https://img.shields.io/docker/pulls/upsti/qa-api-refsa?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Automated build](https://img.shields.io/docker/automated/upsti/qa-api-refsa?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Image Size](https://img.shields.io/docker/image-size/upsti/qa-api-refsa?style=for-the-badge&logo=docker&color=blueviolet&link=https%3A%2F%2Fhub.docker.com%2Frepository%2Fdocker%2Fupsti%2Fqa-api-refsa%2Fgeneral) | ![Docker Image Version](https://img.shields.io/docker/v/upsti/qa-api-refsa?style=for-the-badge&logo=docker&color=blueviolet) |

### Website

<table>
  <tr>
    <th>api REFSA</th>
    <th>QA api REFSA</th>
  </tr>
  <tr>
    <td>
      <a href="https://api.formosa.gob.ar/api-refsa/api/">
        <img src="https://img.shields.io/website?url=https%3A%2F%2Fapi.formosa.gob.ar%2Fapi-refsa%2Fapi%2F&up_message=ACTIVO&style=for-the-badge&label=api-refsa&logo=statuspage" alt="Website">
      </a>
    </td>
    <td>
      <a href="https://qa.formosa.gob.ar/api-refsaa/">
        <img src="https://img.shields.io/website?url=https%3A%2F%2Fqa.formosa.gob.ar%2Fapi-refsa%2Fapi%2F&up_message=ACTIVO&style=for-the-badge&label=qa-api-refsa&logo=statuspage" alt="QA Website">
      </a>
    </td>
  </tr>
</table>

## 📄 Descripción del proyecto

La API de REFSA Ticket System sirve como puente de comunicación entre las api de frontend y las bases de datos backend, permitiendo la gestión eficiente y segura de datos de tickets, usuarios y stock. Soporta operaciones de alta, baja y modificación a través de endpoints seguros y optimizados.


## 🛠️ Tech Stack (tecnologías)

El proyecto de API de REFSA utiliza una combinación de tecnologías modernas para garantizar eficiencia, seguridad y escalabilidad:

**Backend:**
- **NestJS:** Un marco progresivo de Node.js para construir api del lado del servidor eficientes y escalables.
- **TypeORM:** ORM para TypeScript y JavaScript (ES7, ES6, ES5) que soporta MySQL, PostgreSQL, MongoDB y muchas otras bases de datos.
- **Node.js:** Entorno de ejecución para JavaScript construido con el motor de JavaScript V8 de Chrome.

**Bases de datos:**
- **PostgreSQL:** Sistema de gestión de bases de datos relacional robusto y con cumplimiento de ACID.
- **MySQL:** Sistema de gestión de bases de datos relacional, conocido por su velocidad y fiabilidad.
- **MongoDB:** Base de datos NoSQL, basada en documentos, que ofrece alta performance y fácil escalabilidad.

**Autenticación y Seguridad:**
- **Passport:** Middleware de autenticación para Node.js extremadamente flexible y modular.
- **@nestjs/jwt:** Módulo JWT para api NestJS, que facilita la implementación de autenticación basada en tokens.

**Testing y Calidad de Código:**
- **Jest:** Marco de pruebas de JavaScript con un enfoque en la simplicidad.
- **ESLint:** Herramienta de linting para identificar y reportar patrones encontrados en código ECMAScript/JavaScript.

**Integración con servicios externos:**
- **Firebase Admin:** Conjunto de capacidades de backend para interactuar con los servicios de Firebase, incluyendo la autenticación y el almacenamiento en la nube.

Estas tecnologías proporcionan una base sólida para el desarrollo de una API robusta, segura y de fácil mantenimiento que puede servir eficazmente a una variedad de clientes y consumidores de servicios.```

Este Tech Stack muestra un equilibrio entre la elección de frameworks modernos, gestión de bases de datos y herramientas de seguridad, asegurando que la API pueda manejar eficientemente las necesidades operativas y de seguridad de REFSA.


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

- API robusta y segura para la gestión de tickets.
- Endpoints para la creación, actualización y eliminación de datos de tickets.
- Integración con bases de datos Oracle y PostgreSQL para una gestión eficaz de la información.
- Soporte para múltiples clientes simultáneos manteniendo un alto rendimiento.
- Seguridad reforzada para proteger datos sensibles y transacciones.
- Documentación completa disponible para facilitar la integración y el desarrollo.
- Monitorización y mantenimiento continuo para garantizar la disponibilidad y la eficiencia del servicio.

## 📸 Capturas de pantalla

![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_refsa/Screenshot_1.png)
![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_refsa/Screenshot_2.png)
![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_refsa/Screenshot_3.png)

## 🌐 Demo

![Insert gif or link to demo](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_refsa/api_refsa.gif)

## 🚀 Deployment

### Prerrequisitos
1. **Infraestructura:**
   - Un clúster de Kubernetes configurado.
   - Acceso a Docker Hub para obtener la imagen del contenedor.

2. **Credenciales y Configuraciones:**
   - Variables de entorno necesarias para la aplicación.
   - Archivos de configuración para Kubernetes.

### Pasos para el Despliegue

#### 1. Obtener la Imagen del Contenedor
- Asegúrate de tener acceso a Docker Hub y de que la imagen de la aplicación esté disponible.
- La imagen se encuentra en: `upsti/api-refsa:v0.0.17` `upsti/qa-api-refsa:v0.0.9` .

#### 2. Configurar Variables de Entorno
- Crea un archivo `.env` con las variables de entorno necesarias. Por ejemplo:

```bash
  REACT_APP_CLIENT_ID=
  REACT_APP_CLIENT_SECRET=
  REACT_APP_BASE_URL_ACCOUNT=
  REACT_APP_BASE_URL_API=
  REACT_APP_BASE_URL_API_DEV=
  REACT_APP_MANUAL_URL=
  REACT_APP_BASE_URL_API_PROD=
  REACT_APP_ID_SYSTEM=
  PORT=
  NODE_ENV=
```
#### 3. Crear y Aplicar Configuración para Kubernetes
- Utiliza los siguientes archivos YAML para configurar el despliegue en Kubernetes.

##### Deployment
```yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: api-refsa
  namespace: api
  labels:
    k8s-app: api-refsa
spec:
  replicas: 1
  selector:
    matchLabels:
      k8s-app: api-refsa
  template:
    metadata:
      name: api-refsa
      labels:
        k8s-app: api-refsa
    spec:
      containers:
      - name: api-refsa
        image: upsti/api-refsa:v0.0.17
        securityContext:
          privileged: false
        resources:
          requests:
            memory: "4Mi"
            cpu: "26m"
          limits:
            memory: "6Mi"
            cpu: "200m"
        envFrom:
        - secretRef:
            name: secret-api-refsa
```

##### Horizontal Pod Autoscaler

```yaml
apiVersion: autoscaling/v2
kind: HorizontalPodAutoscaler
metadata:
  name: api-refsa-hpa
  namespace: api
spec:
  scaleTargetRef:
    apiVersion: apps/v1
    kind: Deployment
    name: api-refsa
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
  name: api-refsa
  namespace: api
  annotations:
    nginx.ingress.kubernetes.io/backend-protocol: "HTTP"
    nginx.ingress.kubernetes.io/rewrite-target: /$2
    nginx.ingress.kubernetes.io/configuration-snippet: |
      rewrite ^(/api-refsa)$ $1/ redirect;
spec:
  ingressClassName: "public"
  rules:
  - host: api.formosa.gob.ar
    http:
      paths:
      - path: /api-refsa(/|$)(.*)
        pathType: ImplementationSpecific
        backend:
          service:
            name: api-refsa
            port:
              number: 80
```

##### Service

```yaml
apiVersion: v1
kind: Service
metadata:
  name: api-refsa
  namespace: api
spec:
  selector:
    k8s-app: api-refsa
  ports:
  - name: tcp-80-refsa
    protocol: TCP
    port: 80
    targetPort: 80
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
kubectl get service api-refsa -n api
```
- Obtén la IP del servicio para acceder a la aplicación.

#### Consideraciones de Seguridad
- Asegúrate de que todas las conexiones a la base de datos y las comunicaciones entre los servicios estén encriptadas.
- Implementa medidas de seguridad para proteger las credenciales y datos sensibles.

## 🔗 Links

### Docker

| Producción | QA |
| --- | --- |
| [![Docker Hub](https://img.shields.io/badge/hub.docker.com-web%20refsa-blue?style=for-the-badge&logo=docker)](https://hub.docker.com/repository/docker/upsti/api-refsa/general) | [![Docker Hub](https://img.shields.io/badge/hub.docker.com-qa%20web%20refsa-blue?style=for-the-badge&logo=docker)](https://hub.docker.com/repository/docker/upsti/qa-api-refsa/general) |

### Web-API

| Producción | QA |
| --- | --- |
| [![Web Producción](https://img.shields.io/badge/Web.api%20Producción-api%20refsa-blue?style=for-the-badge&logo=googlechrome)](https://api.formosa.gob.ar/api-refsa/api/) | [![Web QA](https://img.shields.io/badge/Web.api%20QA-api%20refsa-blue?style=for-the-badge&logo=googlechrome)](https://qa.formosa.gob.ar/api-refsa/api/) |

### Repositorio

| GitHub |
| --- |
| [![Repositorio GitHub](https://img.shields.io/badge/GitHub-Repositorio-blue?style=for-the-badge&logo=github)](https://github.com/UPSTI-DESA/api-refsa) |

### Proyecto

| ClickUp | Slack |
| --- | --- |
| [![ClickUp](https://img.shields.io/badge/ClickUp-Proyecto-blue?style=for-the-badge&logo=clickup)](https://app.clickup.com/12911606/v/b/ca0zp-1214) | [![Slack](https://img.shields.io/badge/Slack-Canal%20del%20Proyecto-blue?style=for-the-badge&logo=slack)](https://app.slack.com/client/T03P90TBF5Y/C03P2CMQNH4) |

### Kubernetes

| Producción | QA |
| --- | --- |
| [![Kubernetes Producción](https://img.shields.io/badge/Kubernetes%20Producción-Dashboard-blue?style=for-the-badge&logo=kubernetes)](https://web.formosa.gob.ar/dashboard/#/deployment/api/api-refsa?namespace=_all) | [![Kubernetes QA](https://img.shields.io/badge/Kubernetes%20QA-Dashboard-blue?style=for-the-badge&logo=kubernetes)](https://web.formosa.gob.ar/dashboard/#/deployment/api/qa-api-refsa?namespace=_all) |

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

## 📚 API Referencia

- [Swagger: API Documentation](https://api.formosa.gob.ar/api-refsa/api/)

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

<img src="https://github.com/UPSTI-DESA/imagenes_readme/blob/main/web_refsa/roadmap.jpg?raw=true" alt="Logo" style="width:100%;">

El desarrollo de la API de REFSA está estructurado para soportar de manera eficiente tanto el crecimiento en funcionalidades como la escalabilidad en el manejo de datos:

### Fase 1: Estructura y Fundamentos
- **Completo:** Configuración inicial de NestJS con Node.js.
- **Completo:** Integración con bases de datos PostgreSQL y MongoDB.
- **Completo:** Implementación de autenticación básica y seguridad con JWT y Passport.

### Fase 2: Expansión y Robustez
- **En progreso:** Desarrollo de endpoints adicionales para nuevas funcionalidades.
- **Planeado:** Mejoras en la gestión de errores y validaciones con class-validator.
- **Planeado:** Integración con sistemas de monitorización y logging avanzados.

### Fase 3: Optimización y Escalabilidad
- **Planeado:** Implementación de caching para mejorar el rendimiento.
- **Planeado:** Optimización de consultas a la base de datos para manejo de grandes volúmenes de datos.
- **Planeado:** Adopción de arquitecturas basadas en microservicios para mejorar la escalabilidad.

### Fase 4: Seguridad y Conformidad
- **Futuro:** Refuerzo de medidas de seguridad y cumplimiento de normativas.
- **Futuro:** Implementación de auditorías automáticas y tests de penetración.
- **Futuro:** Mejoras continuas basadas en feedback de seguridad.

Este roadmap está diseñado para garantizar que la API pueda manejar con eficacia tanto las necesidades actuales como futuras, escalando adecuadamente a medida que aumentan los requisitos y la carga del sistema.


## 👥 Autores

| [![Guillermo Valdes](https://avatars.githubusercontent.com/u/38038911?v=4&s=100)](https://github.com/wowfoxz) | [![Eliseo](https://avatars.githubusercontent.com/u/14987410?v=4&s=100)](https://github.com/Ghenry15) | [![Emiliano Cáceres Miranda](https://avatars.githubusercontent.com/u/22036309?v=4&s=100)](https://github.com/EmilianoCM) | [![Tobías Zacarías](https://avatars.githubusercontent.com/u/22036461?v=4&s=100)](https://github.com/TobiasZacarias) | [![Julian Sanabria](https://avatars.githubusercontent.com/u/22036568?v=4&s=100)](https://github.com/nsanabriaJulian)| [![Gaston schneider](https://avatars.githubusercontent.com/u/22667685?v=4&s=100)](https://github.com/GastonSch) | [![Marcos Vera](https://avatars.githubusercontent.com/u/95255332?v=4&s=100)](https://github.com/MarcosVera22) | [![Leonardo Paredes](https://avatars.githubusercontent.com/u/147510738?v=4&s=100)](https://github.com/LeoxGP)
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| [Guillermo Valdes](https://github.com/wowfoxz) | [Eliseo Rahn](https://github.com/Ghenry15) | [Emiliano Cáceres](https://github.com/maria) | [Tobías Zacarías](https://github.com/TobiasZacarias)| [Julian Sanabria](https://github.com/nsanabriaJulian) | [Gaston schneider](https://github.com/GastonSch) | [Marcos Vera](https://github.com/MarcosVera22)| [Leonardo Paredes](https://github.com/LeoxGP)

## 👫 Usado por

Este proyecto es utilizado por las siguientes oficinas:

* REFSA TELECOMUNICACIONES (Recursos y Energía Formosa S.A.).
  
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

A continuación se detallan las versiones del proyecto api-refsa que actualmente reciben actualizaciones de seguridad.

| Ver. PROD | Soportada     | 
| ------- | ------------------ |
| 1.17    | :x:                |
| 1.16    | :x:                |
| 1.14    | :x:                |
| 1.13    | :x:                |
| 1.12    | :white_check_mark: |
| 1.11    | :x:                |
| 1.10    | :x:                |
| 1.9     | :x:                |
| 1.8     | :x:                |
| 1.7     | :x:                |
| 1.6     | :x:                |
| 1.5     | :x:                |
| 1.4     | :x:                |
| 1.3     | :x:                |
| 1.2     | :x:                |
| 1.1     | :x:                |
| 1       | :x:                |
| 1.3.36  | :x:                |

| Ver. QA | Soportada       |
| ------- | ------------------ |
| 0.0.9   | :white_check_mark: |
| 0.0.8   | :white_check_mark: |
| 0.0.7   | :white_check_mark: |
| 0.0.6   | :x:                |
| 0.0.5   | :x:                |
| 0.0.4   | :x:                |
| 0.0.3   | :x:                |
| 0.0.2   | :x:                |
| 0.0.1   | :x:                |


## Reporte de Vulnerabilidades

Para reportar una vulnerabilidad en el proyecto api-refsa, por favor sigue los siguientes pasos:

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
