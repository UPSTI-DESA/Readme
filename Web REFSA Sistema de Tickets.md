<img src="https://github.com/UPSTI-DESA/imagenes_readme/blob/main/web_refsa/refsa.png?raw=true" alt="Logo" style="width:100%;">

# Proyecto Web REFSA Sistema de Tickets 

## 🛡️ Insignias

### Tecnologías y bibliotecas principales

| React | Material-UI | Redux | TypeScript | Axios | Formik |
| --- | --- | --- | --- | --- | --- |
| ![React](https://img.shields.io/badge/React-%5E18.1.0-blue?style=for-the-badge&logo=react) | ![Material-UI](https://img.shields.io/badge/Material--UI-%5E4.12.4-blue?style=for-the-badge&logo=material-ui) | ![Redux](https://img.shields.io/badge/Redux-%5E1.8.3-purple?style=for-the-badge&logo=redux) | ![TypeScript](https://img.shields.io/badge/TypeScript-%5E4.4.2-blue?style=for-the-badge&logo=typescript) | ![Axios](https://img.shields.io/badge/Axios-%5E0.27.2-green?style=for-the-badge&logo=axios) | ![Formik](https://img.shields.io/badge/Formik-%5E2.2.9-blue?style=for-the-badge&logo=formik) |

### Herramientas de desarrollo y testing

| Jest | React Testing Library | json-server |
| --- | --- | --- |
| ![Jest](https://img.shields.io/badge/Jest-%5E27.0.1-blue?style=for-the-badge&logo=jest) | ![React Testing Library](https://img.shields.io/badge/React%20Testing%20Library-%5E13.0.0-blue?style=for-the-badge&logo=testing-library) | ![json-server](https://img.shields.io/badge/json--server-%5E0.17.0-orange?style=for-the-badge&logo=json) |

### Gestión de paquetes

| React Scripts |
| --- |
| ![React Scripts](https://img.shields.io/badge/React_Scripts-5.0.1-blue?style=for-the-badge&logo=react) |

### Base de Datos

| MySQL |
| --- |
| ![Static Badge](https://img.shields.io/badge/DATABASE-Mysql-yellowgreen?style=for-the-badge&logo=mysql) |

### Docker - Producción

| Docker Pulls | Docker Automated build | Docker Image Size | Docker Image Version |
| --- | --- | --- | --- |
| ![Docker Pulls](https://img.shields.io/docker/pulls/upsti/web-refsa?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Automated build](https://img.shields.io/docker/automated/upsti/web-refsa?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Image Size](https://img.shields.io/docker/image-size/upsti/web-refsa?style=for-the-badge&logo=docker&color=blueviolet&link=https%3A%2F%2Fhub.docker.com%2Frepository%2Fdocker%2Fupsti%2Fweb-refsa%2Fgeneral) | ![Docker Image Version](https://img.shields.io/docker/v/upsti/web-refsa?style=for-the-badge&logo=docker&color=blueviolet) |

### Docker - QA

| Docker Pulls | Docker Automated build | Docker Image Size | Docker Image Version |
| --- | --- | --- | --- |
| ![Docker Pulls](https://img.shields.io/docker/pulls/upsti/qa-web-refsa?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Automated build](https://img.shields.io/docker/automated/upsti/qa-web-refsa?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Image Size](https://img.shields.io/docker/image-size/upsti/qa-web-refsa?style=for-the-badge&logo=docker&color=blueviolet&link=https%3A%2F%2Fhub.docker.com%2Frepository%2Fdocker%2Fupsti%2Fqa-web-refsa%2Fgeneral) | ![Docker Image Version](https://img.shields.io/docker/v/upsti/qa-web-refsa?style=for-the-badge&logo=docker&color=blueviolet) |

### Website

<table>
  <tr>
    <th>Web REFSA</th>
    <th>QA Web REFSA</th>
  </tr>
  <tr>
    <td>
      <a href="https://web.formosa.gob.ar/web-refsa/">
        <img src="https://img.shields.io/website?url=https%3A%2F%2Fweb.formosa.gob.ar%2Fweb-refsa%2F&up_message=ACTIVO&style=for-the-badge&label=web-refsa&logo=statuspage" alt="Website">
      </a>
    </td>
    <td>
      <a href="https://qa.formosa.gob.ar/web-refsaa/">
        <img src="https://img.shields.io/website?url=https%3A%2F%2Fqa.formosa.gob.ar%2Fweb-refsa%2F&up_message=ACTIVO&style=for-the-badge&label=qa-web-refsa&logo=statuspage" alt="QA Website">
      </a>
    </td>
  </tr>
</table>

## 📄 Descripción del proyecto

El sistema de administración de tickets de REFSA permite gestionar altas, bajas y modificaciones relacionadas con los tickets generados por el equipo de soporte de UPSTI y/o REFsa Telecomunicaciones. Facilita la asociación de equipos de trabajo, técnicos y supervisores, y permite hacer seguimiento completo del estado del ticket desde su creación hasta su archivo. El sistema se nutre de módulos de migraciones y conexiones con diversas bases de datos. Incluye un Sistema de Stock en constante mejora, que permite administrar los materiales usados por el equipo técnico y obtener métricas clave para la compra de futuros insumos.


## 🛠️ Tech Stack (tecnologías)

El proyecto web de REFSA utiliza una combinación de tecnologías modernas orientadas al desarrollo frontend con capacidades ricas en interactividad y diseño:

**Frontend:**
- **React:** Una biblioteca de JavaScript para construir interfaces de usuario, que permite la creación de aplicaciones web complejas y dinámicas.
- **Material-UI/MUI:** Una biblioteca de componentes de React que implementa Google's Material Design, proporcionando componentes listos para usar que son estéticamente atractivos y funcionales.
- **Redux Toolkit:** Un kit de herramientas para manejar de manera eficiente el estado de la aplicación en aplicaciones React.

**Gestión de Estado:**
- **React Redux:** Biblioteca para conectar componentes React con el estado de la aplicación gestionado por Redux, facilitando estados compartidos entre múltiples componentes.

**Ruteo:**
- **React Router Dom:** Biblioteca para manejar el enrutamiento en aplicaciones React, permitiendo la navegación entre diferentes componentes sin recargar la página.

**Internacionalización:**
- **i18next/React-i18next:** Marco de internacionalización para traducir el contenido de la aplicación a múltiples idiomas.

**Manejo de Formularios:**
- **Formik:** Biblioteca para construir formularios en React, maneja la lógica de formularios como el estado del formulario, la validación y el manejo de errores.
- **Yup:** Utilizado junto a Formik para la validación de esquemas.

**Testing:**
- **Jest:** Marco de pruebas de JavaScript que se enfoca en la simplicidad.
- **Testing Library:** Utilidades para probar componentes React de manera más consistente con las interacciones del usuario.

**Estilos:**
- **Styled Components:** Permite escribir código CSS dentro de componentes de JavaScript para estilizar aplicaciones de una manera más modular y escalable.
- **Emotion:** Biblioteca diseñada para escribir estilos CSS con JavaScript que también permite usar estilos dinámicos basados en el estado de la aplicación.

**Otros:**
- **Axios:** Cliente HTTP basado en promesas para el navegador y Node.js, utilizado para realizar solicitudes HTTP.
- **Luxon:** Biblioteca moderna para manejar fechas y horas en JavaScript.

Este stack tecnológico ofrece una plataforma robusta y flexible para desarrollar una aplicación web interactiva y atractiva, asegurando una experiencia de usuario fluida y moderna.```

Este detalle proporciona una visión integral de las herramientas y tecnologías que componen el proyecto web de REFSA, resaltando cómo cada tecnología contribuye a la funcionalidad y experiencia del usuario en la plataforma.


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

- Gestión de tickets completa incluyendo altas, bajas y modificaciones.
- Asociación y seguimiento en tiempo real de equipos de trabajo, técnicos y supervisores.
- Sistema de Stock para la administración de materiales e insumos técnicos.
- Integración con múltiples bases de datos para la sincronización y actualización de datos.
- Informes detallados y métricas de rendimiento para la optimización de recursos.
- Interfaz de usuario intuitiva y respaldada por Adobe Illustrator para una mejor experiencia visual.

## 📸 Capturas de pantalla

![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/web_refsa/Screenshot_1.png)
![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/web_refsa/Screenshot_2.png)
![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/web_refsa/Screenshot_3.png)

## 🌐 Demo

![Insert gif or link to demo](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/web_refsa/web_refsa.gif)

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
- La imagen se encuentra en: `upsti/web-refsa:v1.14` `upsti/qa-web-refsa:v0.0.8` .

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
  name: web-refsa
  namespace: aplicaciones
  labels:
    k8s-app: web-refsa
spec:
  replicas: 1
  selector:
    matchLabels:
      k8s-app: web-refsa
  template:
    metadata:
      name: web-refsa
      labels:
        k8s-app: web-refsa
    spec:
      containers:
      - name: web-refsa
        image: upsti/web-refsa:v1.14
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
            name: secret-web-refsa
```

##### Horizontal Pod Autoscaler

```yaml
apiVersion: autoscaling/v2
kind: HorizontalPodAutoscaler
metadata:
  name: web-refsa-hpa
  namespace: aplicaciones
spec:
  scaleTargetRef:
    apiVersion: apps/v1
    kind: Deployment
    name: web-refsa
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
  name: web-refsa
  namespace: aplicaciones
  annotations:
    nginx.ingress.kubernetes.io/backend-protocol: "HTTP"
    nginx.ingress.kubernetes.io/rewrite-target: /$2
    nginx.ingress.kubernetes.io/configuration-snippet: |
      rewrite ^(/web-refsa)$ $1/ redirect;
spec:
  ingressClassName: "public"
  rules:
  - host: qa.formosa.gob.ar
    http:
      paths:
      - path: /web-refsa(/|$)(.*)
        pathType: ImplementationSpecific
        backend:
          service:
            name: web-refsa
            port:
              number: 80
```

##### Service

```yaml
apiVersion: v1
kind: Service
metadata:
  name: web-refsa
  namespace: aplicaciones
spec:
  selector:
    k8s-app: web-refsa
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
kubectl get pods -n aplicaciones
```
#### 5. Configurar el Servicio y Acceso a la Aplicación

- Configura un servicio para exponer tu aplicación:
```sh
kubectl get service web-refsa -n aplicaciones
```
- Obtén la IP del servicio para acceder a la aplicación.

#### Consideraciones de Seguridad
- Asegúrate de que todas las conexiones a la base de datos y las comunicaciones entre los servicios estén encriptadas.
- Implementa medidas de seguridad para proteger las credenciales y datos sensibles.

## 🔗 Links

### Docker

| Producción | QA |
| --- | --- |
| [![Docker Hub](https://img.shields.io/badge/hub.docker.com-web%20refsa-blue?style=for-the-badge&logo=docker)](https://hub.docker.com/repository/docker/upsti/web-refsa/general) | [![Docker Hub](https://img.shields.io/badge/hub.docker.com-qa%20web%20refsa-blue?style=for-the-badge&logo=docker)](https://hub.docker.com/repository/docker/upsti/qa-web-refsa/general) |

### Web

| Producción | QA |
| --- | --- |
| [![Web Producción](https://img.shields.io/badge/Web%20Producción-web%20refsa-blue?style=for-the-badge&logo=googlechrome)](https://web.formosa.gob.ar/web-refsa/) | [![Web QA](https://img.shields.io/badge/Web%20QA-web%20refsa-blue?style=for-the-badge&logo=googlechrome)](https://qa.formosa.gob.ar/web-refsa/) |

### Repositorio

| GitHub |
| --- |
| [![Repositorio GitHub](https://img.shields.io/badge/GitHub-Repositorio-blue?style=for-the-badge&logo=github)](https://github.com/UPSTI-DESA/web-refsa) |

### Proyecto

| ClickUp | Slack |
| --- | --- |
| [![ClickUp](https://img.shields.io/badge/ClickUp-Proyecto-blue?style=for-the-badge&logo=clickup)](https://app.clickup.com/12911606/v/b/6-187785503-2) | [![Slack](https://img.shields.io/badge/Slack-Canal%20del%20Proyecto-blue?style=for-the-badge&logo=slack)](https://app.slack.com/client/T03P90TBF5Y/C03P2CMQNH4) |

### Kubernetes

| Producción | QA |
| --- | --- |
| [![Kubernetes Producción](https://img.shields.io/badge/Kubernetes%20Producción-Dashboard-blue?style=for-the-badge&logo=kubernetes)](https://web.formosa.gob.ar/dashboard/#/deployment/aplicaciones/web-refsa?namespace=_all) | [![Kubernetes QA](https://img.shields.io/badge/Kubernetes%20QA-Dashboard-blue?style=for-the-badge&logo=kubernetes)](https://web.formosa.gob.ar/dashboard/#/deployment/aplicaciones/qa-web-refsa?namespace=_all) |

### Documentos

| Google Drive |
| --- |
| [![Google Drive](https://img.shields.io/badge/Google%20Drive-Carpeta-blue?style=for-the-badge&logo=googledrive)](https://drive.google.com/drive/folders/1rofnke66-FRhaMTkC4W4EcZr0zc9niOw) |

## 📖 Documentacion

### MANUALES

| Manual de Usuario |
| --- |
| [![ep300](https://img.shields.io/badge/Manual%20de%20Usuario%20Anviz%20EP300-grey?style=for-the-badge&logo=google-docs)](https://drive.google.com/drive/folders/1a9h_1EwpBLy87dbCeZD9j83s2AFOZLyP) |

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

El desarrollo del proyecto web de REFSA está planificado en varias fases, cada una orientada a mejorar continuamente la plataforma y añadir nuevas funcionalidades:

### Fase 1: Lanzamiento Inicial
- **Completo:** Desarrollo de la interfaz básica con React y Material-UI.
- **Completo:** Implementación del manejo de estado con Redux Toolkit.
- **Completo:** Integración inicial con servicios backend.

### Fase 2: Mejoras y Expansión
- **En progreso:** Optimización de componentes para mejorar el rendimiento.
- **Planeado:** Expansión de la cobertura de pruebas con Jest y Testing Library.
- **Planeado:** Añadir soporte multilingüe con i18next.

### Fase 3: Funcionalidades Avanzadas
- **Planeado:** Desarrollo de módulos avanzados para manejo de formularios con Formik y Yup.
- **Planeado:** Integración de gráficos y análisis de datos con Chart.js.
- **Planeado:** Mejoras en la seguridad y manejo de sesión de usuarios.

### Fase 4: Refinamiento y Escalabilidad
- **Futuro:** Refactorización de código para adoptar microservicios o arquitecturas serverless.
- **Futuro:** Implementación de PWA para mejorar la accesibilidad y offline capabilities.
- **Futuro:** Expansión de la plataforma para soportar más usuarios concurrentes.

Estas fases están diseñadas para adaptarse y evolucionar según las necesidades de los usuarios y los avances tecnológicos en el desarrollo web.

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

A continuación se detallan las versiones del proyecto web-refsa que actualmente reciben actualizaciones de seguridad.

| Ver. PROD | Soportada     | 
| ------- | ------------------ |
| 1.14    | :white_check_mark: |
| 1.13    | :white_check_mark: |
| 1.12    | :x:                |
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

| Ver. QA | Soportada       |
| ------- | ------------------ |
| 0.0.10  | :white_check_mark: |
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

Para reportar una vulnerabilidad en el proyecto web-refsa, por favor sigue los siguientes pasos:

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
