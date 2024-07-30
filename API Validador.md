<img src="https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_validador/validador.png?raw=true" alt="Logo" style="width:100%;">

# Proyecto API Validador

## 🛡️ Insignias

### Tecnologías Principales

| NestJS | TypeORM | MongoDB | PostgreSQL |
| --- | --- | --- | --- |
| ![NestJS](https://img.shields.io/badge/NestJS-%5E8.4.7-red?style=for-the-badge&logo=nestjs) | ![TypeORM](https://img.shields.io/badge/TypeORM-%5E7.1.5-orange?style=for-the-badge&logo=typeorm) | ![MongoDB](https://img.shields.io/badge/MongoDB-%5E3.0-green?style=for-the-badge&logo=mongodb) | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%5E8.6.0-blue?style=for-the-badge&logo=postgresql) |

### Herramientas de Desarrollo y Testing

| TypeScript | Jest | ESLint | Prettier |
| --- | --- | --- | --- |
| ![TypeScript](https://img.shields.io/badge/TypeScript-%5E4.3.5-blue?style=for-the-badge&logo=typescript) | ![Jest](https://img.shields.io/badge/Jest-%5E28.0.3-blue?style=for-the-badge&logo=jest) | ![ESLint](https://img.shields.io/badge/ESLint-%5E8.0.1-purple?style=for-the-badge&logo=eslint) | ![Prettier](https://img.shields.io/badge/Prettier-%5E2.3.2-ff69b4?style=for-the-badge&logo=prettier) |

### Docker - Producción

| Docker Pulls | Docker Automated build | Docker Image Size | Docker Image Version |
| --- | --- | --- | --- |
| ![Docker Pulls](https://img.shields.io/docker/pulls/upsti/api-validador?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Automated build](https://img.shields.io/docker/automated/upsti/api-validador?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Image Size](https://img.shields.io/docker/image-size/upsti/api-validador?style=for-the-badge&logo=docker&color=blueviolet&link=https%3A%2F%2Fhub.docker.com%2Frepository%2Fdocker%2Fupsti%2Fapi-validador%2Fgeneral) | ![Docker Image Version](https://img.shields.io/docker/v/upsti/api-validador?style=for-the-badge&logo=docker&color=blueviolet) |


### Website

<table>
  <tr>
    <th>api validador</th>
    
  </tr>
  <tr>
    <td>
      <a href="https://api.formosa.gob.ar/api-validador/api/">
        <img src="https://img.shields.io/website?url=https%3A%2F%2Fapi.formosa.gob.ar%2Fapi-validador%2Fapi%2F&up_message=ACTIVO&style=for-the-badge&label=api-validador&logo=statuspage" alt="Website">
      </a>
    </td>
  </tr>
</table>

## 📄 Descripción del Proyecto

El proyecto "Validador de documentos QR" está diseñado como una solución móvil para la validación segura de documentos a través de códigos QR. Esta aplicación permite a los usuarios utilizar la cámara de su dispositivo móvil para escanear códigos QR en documentos y verificar su autenticidad en tiempo real. Esta tecnología busca proporcionar una herramienta eficaz para prevenir fraudes y confirmar la integridad de documentos importantes en diversos sectores, incluidos educativo, gubernamental y corporativo.

### Función Principal:

- **Validación de Documentos:** Los usuarios pueden escanear códigos QR en documentos para verificar su autenticidad. La aplicación procesa los datos encriptados dentro del código QR y valida su veracidad contra bases de datos seguras.

### Actualizaciones del Sistema:

- **Nuevas Funciones de Escaneo:** Implementación de tecnología avanzada para mejorar la precisión y la velocidad del escaneo de códigos QR.
- **Mejoras en la Interfaz de Usuario:** Actualizaciones en el diseño de la interfaz para ofrecer una experiencia de usuario más intuitiva y fluida durante el proceso de validación.
- **Integración con Nuevas Bases de Datos:** Expansión en la capacidad de validación al integrar nuevas fuentes de datos, permitiendo un espectro más amplio de verificación de documentos.

### Tecnologías Utilizadas:

**Frontend:**
- **React Native:** Utilizado para desarrollar una aplicación móvil multiplataforma que ofrece una experiencia de usuario coherente tanto en Android como en iOS.

**Backend:**
- **NodeJS y Express:** Estos forman el núcleo del servidor, manejando la lógica de negocio, las operaciones de base de datos y la autenticación.
- **JWT (JSON Web Tokens):** Se utiliza para asegurar la comunicación entre el cliente y el servidor, autenticando cada solicitud para proteger contra el acceso no autorizado.

**Base de Datos:**
- **MongoDB y Firebase:** Bases de datos utilizadas para almacenar y gestionar datos de validación de forma segura y escalable.

**Comunicación:**
- **API REST:** Permite la interacción eficiente entre el frontend móvil y el backend, asegurando una comunicación rápida y segura.

Esta solución integral no solo mejora la seguridad en la validación de documentos sino que también agiliza el proceso, haciéndolo accesible desde cualquier lugar y en cualquier momento a través de dispositivos móviles.

## 🛠️ Tech Stack (tecnologías)

- **Backend:** NestJS con Express como framework de servidor.
- **Base de Datos:** PostgreSQL para almacenamiento de datos estructurados y MongoDB para datos no estructurados.
- **Autenticación:** JWT para manejo de sesiones y Passport para diversas estrategias de autenticación.
- **Testing:** Jest para pruebas unitarias y de integración.
- **Calidad de Código:** ESLint para análisis de código y Prettier para formateo.

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

- **Registro y Manejo de Usuarios:** Capacidad para registrar y gestionar usuarios, roles y permisos.
- **Autenticación Segura:** Implementa JWT y OAuth2 para asegurar las sesiones y los accesos a la API.
- **Integración con Múltiples Bases de Datos:** Utiliza TypeORM para facilitar las operaciones en MongoDB y PostgreSQL.
- **Documentación API:** Swagger para generar documentación interactiva y útil para los desarrolladores.

## 📸 Capturas de pantalla

![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_validador/Screenshot_1.png)
![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_validador/Screenshot_2.png)
![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_validador/Screenshot_3.png)

## 🌐 Demo

![Insert gif or link to demo](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_validador/api_validador.gif)

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
- La imagen se encuentra en: `upsti/api-validador:v0.0.2` .

#### 2. Configurar Variables de Entorno
- Crea un archivo `.env` con las variables de entorno necesarias. Por ejemplo:

```bash
DB_HOST=
DB_PORT=
DB_USERNAME=
DB_PASSWORD=
DB_DATABASE=
DB_TYPE=
STAGE=
PORT=
JWT_SECRET=
```
#### 3. Crear y Aplicar Configuración para Kubernetes
- Utiliza los siguientes archivos YAML para configurar el despliegue en Kubernetes.

##### Deployment
```yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: api-validador
  namespace: api
  labels:
    k8s-app: api-validador
spec:
  replicas: 1
  selector:
    matchLabels:
      k8s-app: api-validador
  template:
    metadata:
      name: api-validador
      labels:
        k8s-app: api-validador
    spec:
      containers:
      - name: api-validador
        image: upsti/api-validador:v0.0.2
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
            name: secret-api-validador
```

##### Horizontal Pod Autoscaler

```yaml
apiVersion: autoscaling/v2
kind: HorizontalPodAutoscaler
metadata:
  name: api-validador-hpa
  namespace: api
spec:
  scaleTargetRef:
    apiVersion: apps/v1
    kind: Deployment
    name: api-validador
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
  name: api-validador
  namespace: api
  annotations:
    nginx.ingress.kubernetes.io/backend-protocol: "HTTP"
    nginx.ingress.kubernetes.io/rewrite-target: /$2
    nginx.ingress.kubernetes.io/configuration-snippet: |
      rewrite ^(/api-validador)$ $1/ redirect;
spec:
  ingressClassName: "public"
  rules:
  - host: api.formosa.gob.ar
    http:
      paths:
      - path: /api-validador(/|$)(.*)
        pathType: ImplementationSpecific
        backend:
          service:
            name: api-validador
            port:
              number: 3000
```

##### Service

```yaml
apiVersion: v1
kind: Service
metadata:
  name: api-validador
  namespace: api
spec:
  selector:
    k8s-app: api-validador
  ports:
  - name: tcp-3000-validador
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
kubectl get service api-validador -n api
```
- Obtén la IP del servicio para acceder a la aplicación.

#### Consideraciones de Seguridad
- Asegúrate de que todas las conexiones a la base de datos y las comunicaciones entre los servicios estén encriptadas.
- Implementa medidas de seguridad para proteger las credenciales y datos sensibles.

## 🔗 Links

### Docker

| Producción |
| --- |
| [![Docker Hub](https://img.shields.io/badge/hub.docker.com-web%20validador-blue?style=for-the-badge&logo=docker)](https://hub.docker.com/repository/docker/upsti/api-validador/general)

### Web-API

| Producción |
| --- |
| [![Web Producción](https://img.shields.io/badge/Web.api%20Producción-api%20validador-blue?style=for-the-badge&logo=googlechrome)](https://api.formosa.gob.ar/api-validador/api/) 

### Repositorio

| GitHub |
| --- |
| [![Repositorio GitHub](https://img.shields.io/badge/GitHub-Repositorio-blue?style=for-the-badge&logo=github)](https://github.com/UPSTI-DESA/api-validador) |

### Proyecto

| ClickUp | Slack |
| --- | --- |
| [![ClickUp](https://img.shields.io/badge/ClickUp-Proyecto-blue?style=for-the-badge&logo=clickup)](https://app.clickup.com/12911606/v/b/ca0zp-1214) | [![Slack](https://img.shields.io/badge/Slack-Canal%20del%20Proyecto-blue?style=for-the-badge&logo=slack)](https://app.slack.com/client/T03P90TBF5Y/C03P2CMQNH4) |

### Kubernetes

| Producción |
| --- |
| [![Kubernetes Producción](https://img.shields.io/badge/Kubernetes%20Producción-Dashboard-blue?style=for-the-badge&logo=kubernetes)](https://web.formosa.gob.ar/dashboard/#/deployment/api/api-validador?namespace=_all) 

## 📖 Documentacion

### MANUALES

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

- [Swagger: API Documentation](https://api.formosa.gob.ar/api-validador/api/)

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

<img src="https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api_validador/roadmap.jpg?raw=true" alt="Logo" style="width:100%;">

### Fase 1: Desarrollo Inicial y Pruebas de Prototipo
- **Completo:** Configuración del entorno de desarrollo con React Native y NodeJS.
- **Completo:** Implementación inicial del escaneo de códigos QR y la verificación básica de documentos.
- **Completo:** Pruebas de prototipo en dispositivos móviles para validar funcionalidad básica.

### Fase 2: Mejoras de Funcionalidad y UX
- **En Progreso:** Mejora de la interfaz de usuario para facilitar una experiencia más intuitiva y fluida.
- **Planeado:** Ampliación de las funciones de escaneo para incluir validaciones avanzadas y detección de anomalías.
- **Planeado:** Integración de feedback inicial de los usuarios para refinar la aplicación.

### Fase 3: Expansión de la Capacidad de Validación
- **Planeado:** Integración con nuevas bases de datos, tanto MongoDB como Firebase, para ampliar el espectro de validación de documentos.
- **Futuro:** Implementación de algoritmos avanzados para mejorar la precisión y velocidad del proceso de validación.
- **Futuro:** Desarrollo de características adicionales basadas en requerimientos del mercado y normativas legales.

### Fase 4: Optimización y Lanzamiento Global
- **Futuro:** Optimización de la aplicación para asegurar alta eficiencia en diferentes dispositivos y plataformas.
- **Futuro:** Preparación para el lanzamiento global, incluyendo localización y pruebas multirregionales.
- **Futuro:** Monitoreo continuo y actualizaciones regulares post-lanzamiento para garantizar el mantenimiento de la seguridad y la funcionalidad.

Cada fase del roadmap está diseñada para asegurar un desarrollo estructurado y sistemático del "Validador de documentos QR", maximizando su eficacia y asegurando su relevancia en un entorno tecnológico en constante evolución.

## 👥 Autores

| [![Guillermo Valdes](https://avatars.githubusercontent.com/u/38038911?v=4&s=100)](https://github.com/wowfoxz) | [![Eliseo](https://avatars.githubusercontent.com/u/14987410?v=4&s=100)](https://github.com/Ghenry15) | [![Emiliano Cáceres Miranda](https://avatars.githubusercontent.com/u/22036309?v=4&s=100)](https://github.com/EmilianoCM) | [![Tobías Zacarías](https://avatars.githubusercontent.com/u/22036461?v=4&s=100)](https://github.com/TobiasZacarias) | [![Julian Sanabria](https://avatars.githubusercontent.com/u/22036568?v=4&s=100)](https://github.com/nsanabriaJulian)| [![Gaston schneider](https://avatars.githubusercontent.com/u/22667685?v=4&s=100)](https://github.com/GastonSch) | [![Marcos Vera](https://avatars.githubusercontent.com/u/95255332?v=4&s=100)](https://github.com/MarcosVera22) | [![Leonardo Paredes](https://avatars.githubusercontent.com/u/147510738?v=4&s=100)](https://github.com/LeoxGP)
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| [Guillermo Valdes](https://github.com/wowfoxz) | [Eliseo Rahn](https://github.com/Ghenry15) | [Emiliano Cáceres](https://github.com/maria) | [Tobías Zacarías](https://github.com/TobiasZacarias)| [Julian Sanabria](https://github.com/nsanabriaJulian) | [Gaston schneider](https://github.com/GastonSch) | [Marcos Vera](https://github.com/MarcosVera22)| [Leonardo Paredes](https://github.com/LeoxGP)

## 👫 Usado por

Este proyecto es utilizado por la siguiente oficina:

- *Administración Centralizada*
  - *Ministerio de Gobierno, Justicia, Seguridad y Trabajo*
    - *Dependiente del Mº G.J.yT.*
      - *Subsecretaría de Justicia*
        - **Dirección del Registro Civil y Capacidad de las Personas**
  
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

A continuación se detallan las versiones del proyecto api-validador que actualmente reciben actualizaciones de seguridad.

| Ver. PROD | Soportada     | 
| ------- | ------------------ |
| 0.0.2   | :white_check_mark: |
| 0.0.1   | :white_check_mark: |

## Reporte de Vulnerabilidades

Para reportar una vulnerabilidad en el proyecto api-validador, por favor sigue los siguientes pasos:

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
