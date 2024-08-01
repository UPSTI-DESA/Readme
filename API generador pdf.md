<img src="https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api-generador-pdf/generador-pdf.png?raw=true" alt="Logo" style="width:100%;">

# Proyecto API Generador PDF

## 🛡️ Insignias

### Tecnologías Principales

| Node.js | Express | PostgreSQL | PDFKit |
| --- | --- | --- | --- |
| ![Node.js](https://img.shields.io/badge/Node.js-%5E18.0.0-green?style=for-the-badge&logo=node.js) | ![Express](https://img.shields.io/badge/Express-%5E4.x-lightgrey?style=for-the-badge&logo=express) | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-blue?style=for-the-badge&logo=postgresql) | ![PDFKit](https://img.shields.io/badge/PDFKit-yellow?style=for-the-badge) |

### Herramientas de Desarrollo y Testing

| Jest | TypeScript | ESLint | Prettier |
| --- | --- | --- | --- |
| ![Jest](https://img.shields.io/badge/Jest-%5E29.5.0-C21325?style=for-the-badge&logo=jest) | ![TypeScript](https://img.shields.io/badge/TypeScript-%5E5.1.3-blue?style=for-the-badge&logo=typescript) | ![ESLint](https://img.shields.io/badge/ESLint-%5E8.57.0-4B32C3?style=for-the-badge&logo=eslint) | ![Prettier](https://img.shields.io/badge/Prettier-%5E3.2.5-F7B93E?style=for-the-badge&logo=prettier) |

### Docker - Producción

| Docker Pulls | Docker Automated build | Docker Image Size | Docker Image Version |
| --- | --- | --- | --- |
| ![Docker Pulls](https://img.shields.io/docker/pulls/upsti/api-generador-pdf?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Automated build](https://img.shields.io/docker/automated/upsti/api-generador-pdf?style=for-the-badge&logo=docker&color=blueviolet) | ![Docker Image Size](https://img.shields.io/docker/image-size/upsti/api-generador-pdf?style=for-the-badge&logo=docker&color=blueviolet&link=https%3A%2F%2Fhub.docker.com%2Frepository%2Fdocker%2Fupsti%2Fapi-generador-pdf%2Fgeneral) | ![Docker Image Version](https://img.shields.io/docker/v/upsti/api-generador-pdf?style=for-the-badge&logo=docker&color=blueviolet) |


### Website

<table>
  <tr>
    <th>api generador-pdf</th>
  </tr>
  <tr>
    <td>
      <a href="https://api.formosa.gob.ar/api-generador-pdf/swagger/">
        <img src="https://img.shields.io/website?url=https%3A%2F%2Fapi.formosa.gob.ar%2Fapi-generador-pdf%2Fswagger%2F&up_message=ACTIVO&style=for-the-badge&label=api-generador-pdf&logo=generador-pdfpage" alt="Website">
      </a>
    </td>
  </tr>
</table>

## 📄 Descripción del Proyecto

**Proyecto – Generador de PDF**

Es un microservicio diseñado para transformar datos estructurados en documentos PDF personalizados. Este servicio es ideal para organizaciones que necesitan generar automáticamente documentos como reportes o certificados a partir de datos en tiempo real.

### Función Principal:

- **Generación Automatizada de PDFs:** Convierte datos en formatos JSON o XML a PDFs formateados según plantillas predefinidas, facilitando la creación de documentos estandarizados.

## 🛠️ Tech Stack (tecnologías)

- **Backend:** Utiliza Node.js y Express para gestionar la lógica del servidor y manejar solicitudes API.
- **Base de Datos:** PostgreSQL, utilizado para almacenar plantillas y configuraciones de documentos PDF.
- **Generación de PDF:** Emplea PDFKit, una potente herramienta para la creación de PDFs personalizados.
- **API:** Implementa una API REST para la integración fácil con otros sistemas y frontends.

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

- **Soporte de Múltiples Formatos:** Capacidad para procesar datos en formatos JSON y XML.
- **Personalización de Documentos:** Permite la personalización de los PDFs generados mediante plantillas dinámicas.
- **Alta Disponibilidad y Escalabilidad:** Diseñado para soportar altos volúmenes de generación sin degradar el rendimiento.
- **Integración con Sistemas Existentes:** Fácil integración con cualquier plataforma que soporte llamadas API REST.

## 📸 Capturas de pantalla

![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api-generador-pdf/Screenshot_1.png)
![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api-generador-pdf/Screenshot_2.png)
![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api-generador-pdf/Screenshot_3.png)

## 🌐 Demo

![Insert gif or link to demo](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api-generador-pdf/api-generador-pdf.gif)

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
- La imagen se encuentra en: `upsti/api-generador-pdf:v0.0.7`.

#### 2. Configurar Variables de Entorno
- Crea un archivo `.env` con las variables de entorno necesarias. Por ejemplo:

```bash
 
```
#### 3. Crear y Aplicar Configuración para Kubernetes
- Utiliza los siguientes archivos YAML para configurar el despliegue en Kubernetes.

##### Deployment
```yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: api-generador-pdf
  namespace: api
  labels:
    k8s-app: api-generador-pdf
spec:
  replicas: 1
  selector:
    matchLabels:
      k8s-app: api-generador-pdf
  template:
    metadata:
      name: api-generador-pdf
      labels:
        k8s-app: api-generador-pdf
    spec:
      containers:
      - name: api-generador-pdf
        image: upsti/api-generador-pdf:v0.0.7
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
            name: secret-api-generador-pdf
```

##### Horizontal Pod Autoscaler

```yaml
apiVersion: autoscaling/v2
kind: HorizontalPodAutoscaler
metadata:
  name: api-generador-pdf-hpa
  namespace: api
spec:
  scaleTargetRef:
    apiVersion: apps/v1
    kind: Deployment
    name: api-generador-pdf
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
  name: api-generador-pdf
  namespace: api
  annotations:
    nginx.ingress.kubernetes.io/backend-protocol: "HTTP"
    nginx.ingress.kubernetes.io/rewrite-target: /$2
    nginx.ingress.kubernetes.io/configuration-snippet: |
      rewrite ^(/api-generador-pdf)$ $1/ redirect;
spec:
  ingressClassName: "public"
  rules:
  - host: api.formosa.gob.ar
    http:
      paths:
      - path: /api-generador-pdf(/|$)(.*)
        pathType: ImplementationSpecific
        backend:
          service:
            name: api-generador-pdf
            port:
              number: 3000
```

##### Service

```yaml
apiVersion: v1
kind: Service
metadata:
  name: api-generador-pdf
  namespace: api
spec:
  selector:
    k8s-app: api-generador-pdf
  ports:
  - name: tcp-3000-generador-pdf
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
kubectl get service api-generador-pdf -n api
```
- Obtén la IP del servicio para acceder a la aplicación.

#### Consideraciones de Seguridad
- Asegúrate de que todas las conexiones a la base de datos y las comunicaciones entre los servicios estén encriptadas.
- Implementa medidas de seguridad para proteger las credenciales y datos sensibles.

## 🔗 Links

### Docker

| Producción |
| --- |
| [![Docker Hub](https://img.shields.io/badge/hub.docker.com-web%20generador%20pdf-blue?style=for-the-badge&logo=docker)](https://hub.docker.com/repository/docker/upsti/api-generador-pdf/general) 

### Web-API

| Producción |
| --- |
| [![Web Producción](https://img.shields.io/badge/Web.api%20Producción-api%20generador%20pdf-blue?style=for-the-badge&logo=googlechrome)](https://api.formosa.gob.ar/api-generador-pdf/swagger/) 

### Repositorio

| GitHub |
| --- |
| [![Repositorio GitHub](https://img.shields.io/badge/GitHub-Repositorio-blue?style=for-the-badge&logo=github)](https://github.com/UPSTI-DESA/api-generador-pdf) |

### Proyecto

| ClickUp | Slack |
| --- | --- |
| [![ClickUp](https://img.shields.io/badge/ClickUp-Proyecto-blue?style=for-the-badge&logo=clickup)](https://app.clickup.com/12911606/v/b/ca0zp-1214) | [![Slack](https://img.shields.io/badge/Slack-Canal%20del%20Proyecto-blue?style=for-the-badge&logo=slack)](https://app.slack.com/client/T03P90TBF5Y/C03P2CMQNH4) |

### Kubernetes

| Producción |
| --- |
| [![Kubernetes Producción](https://img.shields.io/badge/Kubernetes%20Producción-Dashboard-blue?style=for-the-badge&logo=kubernetes)](https://web.formosa.gob.ar/dashboard/#/deployment/api/api-generador-pdf?namespace=_all) 

### Documentos

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

- [Swagger: API Documentation](https://api.formosa.gob.ar/api-generador-pdf/swagger/)

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

<img src="https://github.com/UPSTI-DESA/imagenes_readme/blob/main/api-generador-pdf/roadmap.jpg?raw=true" alt="Logo" style="width:100%;">


### Fase 1: Desarrollo y Pruebas Iniciales
- **Completo:** Configuración inicial y desarrollo de las funcionalidades básicas de generación de PDF.

### Fase 2: Expansión de Funcionalidades
- **En Curso:** Añadir soporte para más formatos de datos y plantillas complejas.

### Fase 3: Optimización y Mejoras de Seguridad
- **Planeado:** Optimizar el rendimiento para grandes volúmenes y mejorar las medidas de seguridad en la transferencia de datos.

### Fase 4: Integración Global y Automatización
- **Futuro:** Facilitar la integración con plataformas globales y automatizar más aspectos del proceso de generación de PDF.

Este roadmap detalla la progresión planificada para mejorar y expandir "api-generador-pdf", asegurando que cumpla con las necesidades cambiantes de los usuarios y las tendencias tecnológicas.

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

A continuación se detallan las versiones del proyecto api-generador-pdf que actualmente reciben actualizaciones de seguridad.

| Ver. PROD | Soportada     | 
| ------- | ------------------ |
| 0.0.7    | :white_check_mark: |
| 0.0.6    | :white_check_mark: |
| 0.0.5    | :x: 								|
| 0.0.4    | :white_check_mark: |
| 0.0.3    | :x:								|
| 0.0.2    | :x: 								|
| 0.0.1    | :x:                |

## Reporte de Vulnerabilidades

Para reportar una vulnerabilidad en el proyecto api-generador-pdf, por favor sigue los siguientes pasos:

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
