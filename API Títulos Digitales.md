<img src="https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_titulos_digitales/titulos_digitales.png?raw=true" alt="Logo" style="width:100%;">

# Proyecto API Títulos Digitales

## 🛡️ Insignias

### Tecnologías Principales

| NestJS | TypeORM | JWT | gRPC |
| --- | --- | --- | --- |
| ![NestJS](https://img.shields.io/badge/NestJS-%5E10.0.0-red?style=for-the-badge&logo=nestjs) | ![TypeORM](https://img.shields.io/badge/TypeORM-%5E10.0.2-orange?style=for-the-badge&logo=typeorm) | ![JWT](https://img.shields.io/badge/JWT-%5E10.2.0-blue?style=for-the-badge&logo=jsonwebtokens) | ![gRPC](https://img.shields.io/badge/gRPC-%5E1.9.3-blue?style=for-the-badge&logo=grpc) |

### Herramientas de Desarrollo y Testing

| TypeScript | Jest | ESLint | Prettier |
| --- | --- | --- | --- |
| ![TypeScript](https://img.shields.io/badge/TypeScript-%5E5.1.3-blue?style=for-the-badge&logo=typescript) | ![Jest](https://img.shields.io/badge/Jest-%5E29.5.0-blue?style=for-the-badge&logo=jest) | ![ESLint](https://img.shields.io/badge/ESLint-%5E8.56.0-purple?style=for-the-badge&logo=eslint) | ![Prettier](https://img.shields.io/badge/Prettier-%5E3.0.0-ff69b4?style=for-the-badge&logo=prettier) |


### Docker - Producción

| Docker Pulls | Docker Automated build | Docker Image Size | Docker Image Version |
| --- | --- | --- | --- |
| ![Docker Pulls](https://img.shields.io/docker/pulls/upsti/api-titulosdigitales?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Automated build](https://img.shields.io/docker/automated/upsti/api-titulosdigitales?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Image Size](https://img.shields.io/docker/image-size/upsti/api-titulosdigitales?style=for-the-badge&logo=docker&color=blueviolet&link=https%3A%2F%2Fhub.docker.com%2Frepository%2Fdocker%2Fupsti%2Fapi-titulosdigitales%2Fgeneral) | ![Docker Image Version](https://img.shields.io/docker/v/upsti/api-titulosdigitales?style=for-the-badge&logo=docker&color=blueviolet) |

### Docker - DEV

| Docker Pulls | Docker Automated build | Docker Image Size | Docker Image Version |
| --- | --- | --- | --- |
| ![Docker Pulls](https://img.shields.io/docker/pulls/upsti/dev-api-titulosdigitales?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Automated build](https://img.shields.io/docker/automated/upsti/dev-api-titulosdigitales?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Image Size](https://img.shields.io/docker/image-size/upsti/dev-api-titulosdigitales?style=for-the-badge&logo=docker&color=blueviolet&link=https%3A%2F%2Fhub.docker.com%2Frepository%2Fdocker%2Fupsti%2Fdev-api-titulosdigitales%2Fgeneral) | ![Docker Image Version](https://img.shields.io/docker/v/upsti/dev-api-titulosdigitales?style=for-the-badge&logo=docker&color=blueviolet) |

### Website

<table>
  <tr>
    <th>Api Titulos Digitales</th>
    <th>Dev Api Titulos Digitales (solo con VPN)</th>
  </tr>
  <tr>
    <td>
      <a href="https://api.formosa.gob.ar/api-titulosdigitales/api/">
        <img src="https://img.shields.io/website?url=https%3A%2F%2Fapi.formosa.gob.ar%2Fapi-titulosdigitales%2Fapi%2F&up_message=ACTIVO&style=for-the-badge&label=api-titulosdigitales&logo=statuspage" alt="Website">
      </a>
    </td>
    <td>
      <a href="http://dev.formosa.gob.ar/api-titulosdigitales/api/">
        <img src="https://img.shields.io/website?url=https%3A%2F%2Fdev.formosa.gob.ar%2Fapi-titulosdigitales%2Fapi%2F&up_message=ACTIVO&style=for-the-badge&label=dev-api-titulosdigitales&logo=statuspage" alt="dev Website">
      </a>
    </td>
  </tr>
</table>

## 📄 Descripción del Proyecto

El proyecto "Títulos Digitales" está diseñado para facilitar la emisión y gestión de títulos académicos digitales mediante una API construida sobre una arquitectura de microservicios. Su función principal es proporcionar una interfaz de comunicación robusta para el intercambio de información entre diferentes entidades tanto nacionales como provinciales. La arquitectura de puertos y adaptadores (Hexagonal) permite a la API ser altamente adaptable y fácilmente integrable con diversas plataformas y sistemas externos, garantizando un flujo eficiente y seguro de datos académicos.

**Tecnologías Clave:**
- **Arquitectura de Puertos y Adaptadores (Hexagonal):** Esta arquitectura soporta la creación de sistemas desacoplados y mantenibles, facilitando la integración con otros sistemas y la evolución independiente de las tecnologías subyacentes.
- **PostgreSQL:** Base de datos relacional utilizada para el almacenamiento seguro y eficiente de datos académicos y de títulos.
- **NodeJS:** Entorno de ejecución de JavaScript del lado del servidor que impulsa la lógica de negocio de la API, ofreciendo rendimiento y escalabilidad.

Esta API está especialmente diseñada para soportar altos volúmenes de datos y transacciones, garantizando la integridad y confidencialidad de la información de títulos académicos, y proporcionando interfaces claras para la interacción con sistemas internos y externos. Su implementación mejora significativamente la eficiencia operativa de las instituciones educativas y organismos gubernamentales en la gestión de credenciales académicas.

## 🛠️ Tech Stack (tecnologías)

**Backend:**
- **NestJS:** Un framework progresivo para Node.js que utiliza TypeScript, ofreciendo una arquitectura bien estructurada para desarrollar servicios back-end eficientes y escalables.
- **TypeORM:** ORM que soporta tanto bases de datos SQL como NoSQL, facilitando la interacción con diversas fuentes de datos de manera eficaz y segura.

**Comunicación y Datos:**
- **gRPC:** Un marco de alto rendimiento para conectar servicios, ideal para microservicios y APIs inter-servicios.
- **JWT:** Utilizado para la autenticación y la autorización segura a través de tokens.

**Pruebas y Calidad de Código:**
- **Jest:** Un marco de pruebas para JavaScript enfocado en la simplicidad y el soporte para pruebas de aplicaciones de gran escala.
- **ESLint y Prettier:** Herramientas para garantizar la calidad del código, mantener el estilo y detectar errores antes de la ejecución.


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

- **Gestión de Títulos Digitales:** Creación y administración segura de títulos y certificaciones digitales.
- **Validación y Verificación:** Procesos integrados para la validación de credenciales y verificación de la autenticidad de documentos.
- **Interoperabilidad:** Capacidad para integrarse con sistemas externos mediante gRPC, facilitando la colaboración entre diversas plataformas educativas y gubernamentales.
- **Seguridad Robusta:** Implementación de medidas de seguridad avanzadas, incluyendo la autenticación basada en JWT.
- **Reportes y Análisis de Datos:** Funcionalidades para generar reportes detallados y realizar análisis de datos para mejorar la toma de decisiones.

## 📸 Capturas de pantalla

![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_titulos_digitales/Screenshot_1.png)
![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_titulos_digitales/Screenshot_2.png)
![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_titulos_digitales/Screenshot_3.png)

## 🌐 Demo

![Insert gif or link to demo](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_titulos_digitales/api_titulos_digitales.gif)

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
- La imagen se encuentra en: `upsti/api-titulosdigitales:v0.0.15` `upsti/dev-api-titulosdigitales:v0.0.10` .

#### 2. Configurar Variables de Entorno
- Crea un archivo `.env` con las variables de entorno necesarias. Por ejemplo:

```bash
HOST_DATA_ANALYTICS=
WITH_SSL=
GRPC_MESSAGE_SIZE_MB=
URL_ACCESS_TOKEN=
GRANT_TYPE=
CLIENT_ID=
CLIENT_SECRET=
USER=
PASSWORD=
SERVER=https:
```
#### 3. Crear y Aplicar Configuración para Kubernetes
- Utiliza los siguientes archivos YAML para configurar el despliegue en Kubernetes.

##### Deployment
```yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: api-titulosdigitales
  namespace: api
  labels:
    k8s-app: api-titulosdigitales
spec:
  replicas: 1
  selector:
    matchLabels:
      k8s-app: api-titulosdigitales
  template:
    metadata:
      name: api-titulosdigitales
      labels:
        k8s-app: api-titulosdigitales
    spec:
      containers:
      - name: api-titulosdigitales
        image: upsti/api-titulosdigitales:v0.0.15
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
            name: secret-api-titulosdigitales
```

##### Horizontal Pod Autoscaler

```yaml
apiVersion: autoscaling/v2
kind: HorizontalPodAutoscaler
metadata:
  name: api-titulosdigitales-hpa
  namespace: api
spec:
  scaleTargetRef:
    apiVersion: apps/v1
    kind: Deployment
    name: api-titulosdigitales
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
  name: api-titulosdigitales
  namespace: api
  annotations:
    nginx.ingress.kubernetes.io/backend-protocol: "HTTP"
    nginx.ingress.kubernetes.io/rewrite-target: /$2
    nginx.ingress.kubernetes.io/configuration-snippet: |
      rewrite ^(/api-titulosdigitales)$ $1/ redirect;
spec:
  ingressClassName: "public"
  rules:
  - host: api.formosa.gob.ar
    http:
      paths:
      - path: /api-titulosdigitales(/|$)(.*)
        pathType: ImplementationSpecific
        backend:
          service:
            name: api-titulosdigitales
            port:
              number: 3000
```

##### Service

```yaml
apiVersion: v1
kind: Service
metadata:
  name: api-titulosdigitales
  namespace: api
spec:
  selector:
    k8s-app: api-titulosdigitales
  ports:
  - name: tcp-80-Titulos Digitales
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
kubectl get service api-titulosdigitales -n api
```
- Obtén la IP del servicio para acceder a la aplicación.

#### Consideraciones de Seguridad
- Asegúrate de que todas las conexiones a la base de datos y las comunicaciones entre los servicios estén encriptadas.
- Implementa medidas de seguridad para proteger las credenciales y datos sensibles.

## 🔗 Links

### Docker

| Producción | dev |
| --- | --- |
| [![Docker Hub](https://img.shields.io/badge/hub.docker.com-api%20titulos%20digitales-blue?style=for-the-badge&logo=docker)](https://hub.docker.com/repository/docker/upsti/api-titulosdigitales/general) | [![Docker Hub](https://img.shields.io/badge/hub.docker.com-dev%20api%20titulos%20digitales-blue?style=for-the-badge&logo=docker)](https://hub.docker.com/repository/docker/upsti/dev-api-titulosdigitales/general) |

### Web-API

| Producción | dev |
| --- | --- |
| [![Web Producción](https://img.shields.io/badge/Web.api%20Producción-api%20titulos%20digitales-blue?style=for-the-badge&logo=googlechrome)](https://api.formosa.gob.ar/api-titulosdigitales/api/) | [![Web dev](https://img.shields.io/badge/Web.api%20dev-dev%20api%20titulos%20digitales-blue?style=for-the-badge&logo=googlechrome)](https://dev.formosa.gob.ar/api-titulosdigitales/api/) |

### Repositorio

| GitHub |
| --- |
| [![Repositorio GitHub](https://img.shields.io/badge/GitHub-Repositorio-blue?style=for-the-badge&logo=github)](https://github.com/UPSTI-DESA/api-titulosdigitales) |

### Proyecto

| ClickUp | Slack |
| --- | --- |
| [![ClickUp](https://img.shields.io/badge/ClickUp-Proyecto-blue?style=for-the-badge&logo=clickup)](https://app.clickup.com/12911606/v/b/ca0zp-1214) | [![Slack](https://img.shields.io/badge/Slack-Canal%20del%20Proyecto-blue?style=for-the-badge&logo=slack)](https://app.slack.com/client/T03P90TBF5Y/C03P2CMQNH4) |

### Kubernetes

| Producción | dev |
| --- | --- |
| [![Kubernetes Producción](https://img.shields.io/badge/Kubernetes%20Producción-Dashboard-blue?style=for-the-badge&logo=kubernetes)](https://web.formosa.gob.ar/dashboard/#/deployment/api/api-titulosdigitales?namespace=_all) | [![Kubernetes dev](https://img.shields.io/badge/Kubernetes%20dev-Dashboard-blue?style=for-the-badge&logo=kubernetes)](https://web.formosa.gob.ar/dashboard/#/deployment/api/dev-api-titulosdigitales?namespace=_all) |

### Documentos

| Google Drive |
| --- |
| [![Google Drive](https://img.shields.io/badge/Google%20Drive-Carpeta-blue?style=for-the-badge&logo=googledrive)](https://drive.google.com/drive/folders/17wu47ARmHhooShAPUs7_4GTa0yui7ulz?usp=sharing) |

## 📖 Documentacion

### MANUALES

| Manual de Usuario |
| --- |
| [![manual de usuario](https://img.shields.io/badge/Manual%20de%20Usuario%20Titulos%20Digitales-grey?style=for-the-badge&logo=google-docs)](https://drive.google.com/file/d/1fI4u9EzIeWi9bU7wZtWG9EKrYnbYG1A6/view?usp=sharing) |

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

- [Swagger: API Documentation](https://api.formosa.gob.ar/api-titulosdigitales/api/)
- [Swagger: DEV API Documentation](https://dev.formosa.gob.ar/api-titulosdigitales/api/)

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

* Integración con otros sistemas de gestión.
* Mejora de la interfaz de usuario.
  
## 🛣️ Roadmap

<img src="https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_titulos_digitales/roadmap.jpg?raw=true" alt="Logo" style="width:100%;">

### Fase 1: Desarrollo y Lanzamiento Inicial
- **Completo:** Implementación de la estructura básica con NestJS y conexiones de bases de datos.
- **Completo:** Desarrollo de los primeros endpoints y pruebas básicas de integración.

### Fase 2: Expansión de Funcionalidades y Seguridad
- **Completo:** Añadir más endpoints específicos para gestión avanzada de títulos.
- **Completo:** Reforzar la seguridad y la implementación de mejores prácticas de autenticación.

### Fase 3: Optimización y Mejoras
- **En Progreso:** Optimización de la performance y escalabilidad del sistema.
- **Futuro:** Integración con plataformas de blockchain para la verificación y seguridad de títulos.

### Fase 4: Innovación y Nuevas Tecnologías
- **Futuro:** Exploración de nuevas tecnologías para la automatización de la emisión de títulos.
- **Futuro:** Desarrollo de interfaces de API para terceros, expandiendo la funcionalidad y accesibilidad.

## 👥 Autores

| [![Guillermo Valdes](https://avatars.githubusercontent.com/u/38038911?v=4&s=100)](https://github.com/wowfoxz) | [![Eliseo](https://avatars.githubusercontent.com/u/14987410?v=4&s=100)](https://github.com/Ghenry15) | [![Emiliano Cáceres Miranda](https://avatars.githubusercontent.com/u/22036309?v=4&s=100)](https://github.com/EmilianoCM) | [![Tobías Zacarías](https://avatars.githubusercontent.com/u/22036461?v=4&s=100)](https://github.com/TobiasZacarias) | [![Julian Sanabria](https://avatars.githubusercontent.com/u/22036568?v=4&s=100)](https://github.com/nsanabriaJulian)| [![Gaston schneider](https://avatars.githubusercontent.com/u/22667685?v=4&s=100)](https://github.com/GastonSch) | [![Marcos Vera](https://avatars.githubusercontent.com/u/95255332?v=4&s=100)](https://github.com/MarcosVera22) | [![Leonardo Paredes](https://avatars.githubusercontent.com/u/147510738?v=4&s=100)](https://github.com/LeoxGP)
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| [Guillermo Valdes](https://github.com/wowfoxz) | [Eliseo Rahn](https://github.com/Ghenry15) | [Emiliano Cáceres](https://github.com/maria) | [Tobías Zacarías](https://github.com/TobiasZacarias)| [Julian Sanabria](https://github.com/nsanabriaJulian) | [Gaston schneider](https://github.com/GastonSch) | [Marcos Vera](https://github.com/MarcosVera22)| [Leonardo Paredes](https://github.com/LeoxGP)

## 👫 Usado por

Este proyecto es utilizado por las siguientes oficinas:

- **Ministerio de Cultura y Educación**
  - **Subsecretaría de Educación**
    - **Dirección de Coordinación de Personal Docente**
      - **Sector Registro y Certificación de Títulos**

  
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

A continuación se detallan las versiones del proyecto api-titulosdigitales que actualmente reciben actualizaciones de seguridad.

| Ver. PROD | Soportada     | 
| ------- | ------------------ |
| 0.0.15  | :white_check_mark: |
| 0.0.14  | :white_check_mark: |
| 0.0.13  | :white_check_mark: |
| 0.0.12  | :white_check_mark: |
| 0.0.11  | :white_check_mark: |
| 0.0.10  | :white_check_mark: |
| 0.0.9   | :white_check_mark: |
| 0.0.8   | :white_check_mark: |
| 0.0.7   | :white_check_mark: |
| 0.0.6   | :white_check_mark: |
| 0.0.5   | :white_check_mark: |
| 0.0.4   | :white_check_mark: |
| 0.0.3   | :white_check_mark: |
| 0.0.2   | :white_check_mark: |
| 0.0.1   | :x:  |


| Ver. dev | Soportada       |
| ------- | ------------------ |
| 0.0.10  | :white_check_mark: |
| 0.0.9   | :white_check_mark: |
| 0.0.8   | :white_check_mark: |
| 0.0.7   | :white_check_mark: |
| 0.0.6   | :white_check_mark: |
| 0.0.5   | :white_check_mark: |
| 0.0.4   | :white_check_mark: |
| 0.0.3   | :white_check_mark: |
| 0.0.2   | :white_check_mark: |
| 0.0.1   | :white_check_mark: |

## Reporte de Vulnerabilidades

Para reportar una vulnerabilidad en el proyecto api-titulosdigitales, por favor sigue los siguientes pasos:

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
