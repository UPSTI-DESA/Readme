<img src="https://github.com/UPSTI-DESA/imagenes_readme/blob/main/app_refsa/refsa.png?raw=true" alt="Logo" style="width:100%;">

# Proyecto APP REFSA Sistema de Tickets 

## 🛡️ Insignias

### Tecnologías Principales

| React Native | Redux | Firebase | Axios | Formik |
| --- | --- | --- | --- | --- |
| ![React Native](https://img.shields.io/badge/React_Native-%5E0.69.3-blue?style=for-the-badge&logo=react) | ![Redux](https://img.shields.io/badge/Redux-%5E1.8.3-purple?style=for-the-badge&logo=redux) | ![Firebase](https://img.shields.io/badge/Firebase-%5E15.3.0-yellow?style=for-the-badge&logo=firebase) | ![Axios](https://img.shields.io/badge/Axios-%5E0.27.2-green?style=for-the-badge&logo=axios) | ![Formik](https://img.shields.io/badge/Formik-%5E2.2.9-blue?style=for-the-badge&logo=formik) |

### Herramientas de Desarrollo

| TypeScript | Jest | ESLint |
| --- | --- | --- |
| ![TypeScript](https://img.shields.io/badge/TypeScript-%5E4.4.4-blue?style=for-the-badge&logo=typescript) | ![Jest](https://img.shields.io/badge/Jest-%5E26.6.3-blue?style=for-the-badge&logo=jest) | ![ESLint](https://img.shields.io/badge/ESLint-%5E7.32.0-purple?style=for-the-badge&logo=eslint) |

## 📄 Descripción del proyecto

La aplicación móvil de REFSA es una herramienta esencial para técnicos y supervisores en la gestión de tickets. Permite a los usuarios ver y modificar los tickets asignados, adjuntar fotos y documentos, y gestionar la localización y el stock de herramientas en tiempo real. Actualizaciones del sistema y del diseño son constantemente implementadas para mejorar la funcionalidad y la interfaz de usuario.

## 🛠️ Tech Stack (tecnologías)

**Frontend:**
- **React Native:** Marco de desarrollo de aplicaciones móviles que permite desarrollar aplicaciones nativas para Android y iOS usando React.
- **Redux Toolkit:** Gestión avanzada del estado de la aplicación con facilidades para configurar store, reducers y middleware.

**Funcionalidades y Servicios:**
- **Firebase:** Utilizado para autenticación, almacenamiento de datos, y comunicación en tiempo real.
- **Axios:** Biblioteca de cliente HTTP para hacer solicitudes a APIs externas.
- **Formik:** Manejo de formularios con validación usando Yup para una gestión eficiente del estado del formulario.

**Testing y Calidad:**
- **Jest:** Herramienta de testing para JavaScript diseñada para garantizar la correcta ejecución de la lógica de la aplicación.
- **ESLint:** Herramienta de linting para identificar y reportar patrones problemáticos encontrados en el código JavaScript.

**Internacionalización:**
- **i18next/React-i18next:** Framework para la internacionalización de las aplicaciones React Native.

**Geolocalización y Mapas:**
- **react-native-maps:** Para mostrar mapas y realizar operaciones geográficas.
- **Geolocation Service:** Servicio para acceder a la ubicación del dispositivo.


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

- Visualización y modificación de tickets asignados a técnicos.
- Funcionalidad para adjuntar fotos y documentos a los tickets.
- Gestión de localización de equipos de trabajo en tiempo real.
- Sistema de reporte y control de stock de herramientas de trabajo.
- Interfaz de usuario diseñada con Adobe Illustrator para una navegación fácil y atractiva.
- Actualizaciones constantes para mejorar funcionalidades y diseño de la interfaz.
- Publicación directa y gestión en la Play Store.


## 📸 Capturas de pantalla

![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/app_refsa/Screenshot_1.png)
![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/app_refsa/Screenshot_2.png)
![App Screenshot](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/app_refsa/Screenshot_3.png)

## 🌐 Demo

![Insert gif or link to demo](https://github.com/UPSTI-DESA/imagenes_readme/blob/main/app_refsa/app_refsa.gif)

## 🚀 Deployment

El proceso de despliegue de la aplicación móvil de REFSA se ha optimizado para garantizar una implementación eficiente y segura en las plataformas Android e iOS. A continuación se describen los pasos principales para el despliegue en Android, utilizando herramientas de automatización y scripts para facilitar el proceso.

### Preparativos Generales
Antes de iniciar el despliegue, asegúrate de que todas las dependencias estén actualizadas y de que el entorno de desarrollo esté configurado correctamente:

```bash
yarn install
```

### Despliegue en Android

#### 1. Limpieza de caché y preparación del entorno:
Limpia la caché de Gradle y node_modules para evitar conflictos y asegurar que todos los módulos estén actualizados.

```bash
yarn android:clean
```

#### 2. Preparación de los assets:
Genera el bundle de React Native que incluirá todos los assets necesarios para la aplicación.

```bash
  yarn android:prepare-bundle
```
#### 3.Compilación y empaquetado de la aplicación:
Ejecuta el proceso de construcción para generar el APK de la aplicación.

```bash
  yarn android:prod
```

#### 4. Publicación:
Una vez que el APK está listo y probado, puedes proceder a subirlo a la Google Play Store. Asegúrate de seguir las directrices de Google para la publicación de aplicaciones.

```bash
  yarn android:publish
```

## 🔗 Links

### APP

| Producción |
| --- |
| [![play store](https://img.shields.io/badge/app%20refsa-blue?style=for-the-badge&logo=googlechrome)](https://play.google.com/store/apps/details?id=com.desaupsti.refsatechnicalRN)

### Repositorio

| GitHub |
| --- |
| [![Repositorio GitHub](https://img.shields.io/badge/GitHub-Repositorio-blue?style=for-the-badge&logo=github)](https://github.com/UPSTI-DESA/app-refsa) |

### Proyecto

| ClickUp | Slack |
| --- | --- |
| [![ClickUp](https://img.shields.io/badge/ClickUp-Proyecto-blue?style=for-the-badge&logo=clickup)](https://app.clickup.com/12911606/v/b/ca0zp-1214) | [![Slack](https://img.shields.io/badge/Slack-Canal%20del%20Proyecto-blue?style=for-the-badge&logo=slack)](https://app.slack.com/client/T03P90TBF5Y/C03P2CMQNH4) |

### Documentos

| Google Drive |
| --- |
| [![Google Drive](https://img.shields.io/badge/Google%20Drive-Carpeta-blue?style=for-the-badge&logo=googledrive)](https://drive.google.com/drive/folders/1rofnke66-FRhaMTkC4W4EcZr0zc9niOw) |

## 📖 Documentacion

### MANUALES

| Manual de Usuario |
| --- |
| [![ep300](https://img.shields.io/badge/Manual%20de%20Usuario-grey?style=for-the-badge&logo=google-docs)](https://drive.google.com/drive/folders/1a9h_1EwpBLy87dbCeZD9j83s2AFOZLyP) |

## 📚 API Referencia

- [Swagger: API Documentation](https://api.formosa.gob.ar/api-refsa/api/)

## 💻 Instalacion

Pasos para instalar el proyecto localmente:

1. Clona el repositorio.
   
   Asegúrate de tener acceso al repositorio y clona el código fuente a tu máquina local.
   
   ```bash
      git clone https://github.com/UPSTI-DESA/app-refsa.git
      cd app-refsa
   ```

2. Instala las dependencias:
   
   Utiliza yarn para instalar todas las dependencias necesarias para el proyecto.
   
```bash
  yarn install
```

3. Configura las variables de entorno.
   
   Establece las variables de entorno necesarias para el proyecto. Esto podría incluir       
configuraciones para conexiones a bases de datos, APIs externas, y otros servicios.
   
4. Prepara el entorno de desarrollo:
   
   Ejecuta cualquier script necesario para preparar tu entorno, como configuraciones específicas para Android o iOS.
   
```bash
  yarn preandroid  # Para Android
  yarn preios      # Para iOS
```

## 🏃 Ejecutar localmente

Pasos para ejecutar el proyecto en un entorno local:

1. Inicia el servidor de desarrollo:
   Utiliza yarn para iniciar el servidor de desarrollo. Esto lanzará la aplicación en un emulador o dispositivo conectado.
   
```bash
 yarn start
```

2. Ejecuta la aplicación:
   Para ejecutar la aplicación en dispositivos específicos, puedes utilizar comandos para Android o iOS.
   
```bash
 yarn android    # Para Android
 yarn ios        # Para iOS
```

## 🧪 Ejecución de pruebas

Instrucciones para ejecutar las pruebas unitarias y de integración:

1.Ejecuta las pruebas:
  Usa yarn para correr las pruebas definidas en tu proyecto.

```bash
  yarn test
```

## 📋 Uso/Ejemplos

Ejemplos de cómo utilizar las funcionalidades principales de la aplicación, como la navegación entre pantallas o el uso de componentes específicos.

```javascript
import React from 'react';
import { NavigationContainer } from '@react-navigation/native';
import { HomeScreen, DetailsScreen } from './screens';

function App() {
  return (
    <NavigationContainer>
      <Stack.Navigator>
        <Stack.Screen name="Home" component={HomeScreen} />
        <Stack.Screen name="Details" component={DetailsScreen} />
      </Stack.Navigator>
    </NavigationContainer>
  );
}
```

Este código muestra un ejemplo básico de cómo configurar la navegación en una aplicación React Native usando @react-navigation/native.

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

### Fase 1: Desarrollo Inicial
- **Completo:** Configuración inicial de React Native y Redux.
- **Completo:** Integración básica con Firebase para autenticación y almacenamiento.

### Fase 2: Mejoras y Expansión de Funcionalidades
- **Completo:** Añadir soporte multilingüe con i18next.
- **Completo:** Integración de mapas y servicios de geolocalización avanzados.
- **En progreso:** Expansión de funcionalidades de chat y notificaciones en tiempo real.

### Fase 3: Optimización y Refinamiento
- **Planeado:** Mejoras en la interfaz de usuario y experiencia del usuario.
- **Planeado:** Optimización del rendimiento de la aplicación en dispositivos de gama baja.
- **Planeado:** Refuerzo de las medidas de seguridad y privacidad de los datos de los usuarios.

### Fase 4: Lanzamiento y Post-Lanzamiento
- **Futuro:** Preparación para el lanzamiento en tiendas de aplicaciones.
- **Futuro:** Estrategias y obtención de feedback inicial.
- **Futuro:** Mantenimiento continuo y actualizaciones basadas en el feedback de los usuarios.

Este roadmap proporciona una estructura para el desarrollo continuado y la mejora de la aplicación móvil, garantizando que se atiendan las necesidades de los usuarios mientras se mantienen al día con las últimas tecnologías y prácticas del mercado.


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

A continuación se detallan las versiones del proyecto app-refsa que actualmente reciben actualizaciones de seguridad.

| Ver. | Soportada     | 
| ------- | ------------------ |
| 0.2.7   | :white_check_mark: |


## Reporte de Vulnerabilidades

Para reportar una vulnerabilidad en el proyecto app-refsa, por favor sigue los siguientes pasos:

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
