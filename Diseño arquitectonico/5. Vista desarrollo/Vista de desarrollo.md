<p align='center'>
  <img src='https://github.com/user-attachments/assets/899a06d7-01dd-4f33-b0cf-48b36b632b6f' height="150">
</p>

<h1 align='center'>
  Modelo de datos
  <br>
  "Aplicación mantenimiento de flotas"
</h1>

## ¿Qué es CI/CD?

**CI/CD** es un acrónimo que engloba las prácticas de Integración Continua y Entrega/Despliegue Continuo. Estas metodologías, basadas en la automatización, buscan optimizar los procesos de desarrollo de software a través de la integración frecuente de cambios de código, la automatización de pruebas y la implementación automatizada de aplicaciones.

**Integración Continua (CI):** Consiste en la fusión frecuente de los cambios de código de múltiples desarrolladores en un repositorio compartido. Cada integración se verifica mediante una compilación automática y pruebas unitarias, lo que permite detectar y solucionar errores de manera temprana en el ciclo de desarrollo.

**Entrega/Despliegue Continuo (CD):** Amplía la CI al automatizar el proceso de entrega de software a un entorno de producción o preproducción. Los cambios de código que han superado las pruebas de CI se despliegan de forma automática, lo que reduce el tiempo de salida al mercado y mejora la calidad del software.

## ¿Qué es DEVOPS?

DevOps es una metodología de desarrollo de software que busca acortar el ciclo de vida del desarrollo de sistemas y proporcionar una entrega continua de alta calidad. A través de la automatización de procesos, la colaboración entre equipos de desarrollo y operaciones, y la adopción de una cultura de mejora continua, DevOps permite a las organizaciones responder más rápidamente a las necesidades del mercado y entregar productos de software de mayor calidad.

Características clave de DevOps:

- Colaboración entre equipos: DevOps fomenta una cultura de colaboración entre los equipos de desarrollo y operaciones, rompiendo los silos tradicionales y promoviendo una visión compartida.
- Automatización: La automatización de tareas repetitivas, como la integración continua, las pruebas automatizadas y el despliegue, reduce el riesgo de errores humanos y acelera los procesos.
- Entrega continua: DevOps busca entregar software de forma continua y frecuente, lo que permite obtener feedback más rápido de los usuarios y realizar ajustes de manera ágil.
- Mejora continua: DevOps es un proceso iterativo que se basa en la mejora continua. Los equipos utilizan métricas y datos para identificar áreas de mejora y realizar ajustes en sus procesos.
- Cultura de la fiabilidad: DevOps pone énfasis en la fiabilidad del software, asegurando que las aplicaciones funcionen de manera correcta y estén disponibles en todo momento.

## Flujo DEVOPS

![Diseño sin título](https://github.com/user-attachments/assets/d2588bb4-c358-4322-801f-485aa09fa81c)

### Descripción

| **Fase**   | **Herramienta(s)**                                          | **Descripción**                                                                                                            |
|------------|------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|
| Plan       | ClickUp, Zapier                                            | Herramientas de gestión de proyectos y automatización de tareas para planificar y coordinar el desarrollo del software.    |
| Code       | GitHub, Go, FastAPI,React                                  | Plataformas de control de versiones y lenguajes de programación utilizados para escribir el código fuente.                 |
| Build      | Docker                                                     | Tecnología de contenedores para empaquetar aplicaciones y sus dependencias, facilitando la portabilidad y el despliegue.  |
| Test       | GitLab, JMeter                                             | Plataformas de integración continua y herramientas de pruebas de rendimiento para garantizar la calidad del software.      |
| Deploy     | Docker, WSO2                                              | Plataformas de contenedores y servidores de aplicaciones para desplegar el software en entornos de producción.             |
| Operate    | Prometheus                                                 | Herramienta de monitoreo para supervisar el rendimiento de las aplicaciones en producción.                                 |
| Monitor    | Prometheus                                                 | Herramienta de monitoreo para supervisar el rendimiento de las aplicaciones en producción.                                 |


## Cronograma

<h3>Backend</h3>

1. Requerimientos y diseño
•	Análisis de requisitos: Identificar las funcionalidades necesarias del sistema.
•	Diseño de la arquitectura: Seleccionar la estructura del backend (microservicios, monolito).
•	Definición de modelos de datos: Diseñar las bases de datos y las relaciones.
•	Definición de la API: Crear un contrato API (endpoints, métodos, formatos).
2. Configuración inicial
•	Configuración del entorno de desarrollo (IDE, dependencias, frameworks).
•	Creación de repositorios (Git, CI/CD pipelines).
•	Configuración del entorno de Cloud Functions
•	Configuración de la base de datos (Firebase).
3. Desarrollo
•	Implementación de modelos y esquemas de base de datos.
•	Desarrollo de endpoints:
o	Autenticación y autorización (registro, inicio de sesión).
o	Operaciones CRUD (Create, Read, Update, Delete).
o	Integraciones externas (APIs de terceros, servicios de pago).
•	Implementación de lógica de negocio.
•	Manejo de errores y validación de datos.
4. Pruebas y validación
•	Creación de pruebas unitarias para servicios.
•	Pruebas de integración con la base de datos.
•	Pruebas de rendimiento y escalabilidad.
•	Validación de seguridad.
5. Implementación y despliegue
•	Preparación de la base de datos.
•	Despliegue en producción.
•	Configuración de monitoreo y logs.
 
<h3>Frontend</h3>

1. Requerimientos y diseño
•	Análisis de requisitos: Definir la experiencia del usuario (UX).
•	Wireframes y prototipos: Crear bocetos visuales y prototipos interactivos.
•	Definición de arquitectura: Estructura de componentes, rutas y estados.
2. Configuración inicial
•	Configuración del entorno de desarrollo).
•	Instalación de dependencias y configuración de herramientas.
•	Configuración del diseño base.
3. Desarrollo
•	Creación de componentes base.
•	Implementación de rutas y navegación.
•	Integración con APIs del backend.
•	Desarrollo de lógica de estado.
•	Estilizado y responsividad.
4. Pruebas y validación
•	Pruebas unitarias de componentes.
•	Pruebas funcionales y de interacción.
•	Validación de diseño responsivo y accesibilidad.
•	Pruebas de rendimiento en el navegador.
5. Implementación y despliegue
•	Construcción del proyecto para producción.
•	Despliegue en Google Play.
•	Validación en entornos reales.
•	Configuración de monitoreo.
 
<h3>Actividades Entregables</h3>

**Backend**

1.	Diseñar los modelos de datos y endpoints.(Fecha inicio: 27/11/2024, Fecha Finalización: 04/12/2024)
2.	Implementar el endpoint de autenticación. (Fecha inicio: 11/12/2024, Fecha Finalización: 18/12/2024)
3.	Crear lógica de negocio para los flujos principales. (Fecha inicio: 20/12/2024, Fecha Finalización: 02/12/2024)
4.	Integrar servicios externos. (Fecha inicio: 02/01/2025, Fecha Finalización: 09/01/2025)
5.	Probar y validar la seguridad. (Fecha inicio: 09/01/2025, Fecha Finalización: 16/01/2025)

**Frontend**

1.	Crear componentes clave como formularios y dashboards. (Fecha inicio: 04/12/2024, Fecha Finalización: 10/12/2024)
2.	Implementar autenticación y manejo de sesiones. (Fecha inicio: 11/12/2024, Fecha Finalización: 18/12/2024)
3.	Integrar APIs y validar datos del backend. (Fecha inicio: 02/01/2025, Fecha Finalización: 09/01/2025)
4.	Asegurar la responsividad y accesibilidad. (Fecha inicio: 16/01/2025, Fecha Finalización: 20/01/2025)
5.	Realizar pruebas funcionales y visuales. (Fecha inicio: 20/01/2025, Fecha Finalización: 23/01/2025)



