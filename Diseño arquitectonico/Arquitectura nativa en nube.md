# Aplicaciones Nativas en la Nube

Las aplicaciones nativas en la nube están diseñadas para aprovechar al máximo los entornos de computación en la nube. Estas aplicaciones se construyen con arquitecturas modernas, como microservicios, contenedores y orquestación, lo que permite escalabilidad, resiliencia y despliegues ágiles.

## Características de las Aplicaciones Nativas en la Nube

- **Microservicios**: Arquitectura basada en servicios independientes que se comunican entre sí.
- **Contenedores**: Uso de tecnologías como Docker y Kubernetes para facilitar la portabilidad y escalabilidad.
- **Orquestación y Automatización**: Herramientas como Kubernetes permiten la gestión automática de cargas de trabajo.
- **Despliegue Continuo (CI/CD)**: Integración y entrega continua para acelerar el desarrollo.
- **Escalabilidad y Elasticidad**: Capacidad de aumentar o reducir recursos según la demanda.
- **Resiliencia y Alta Disponibilidad**: Implementación en múltiples regiones y uso de estrategias de recuperación ante fallos.

---

# Caso de Estudio: Aplicación de Gestión de Mantenimientos de Vehículos

## Descripción de la Aplicación
Esta aplicación permite a los usuarios gestionar el mantenimiento de vehículos mediante una aplicación nativa en la nube. Incluye funcionalidades como:
- Programar y gestionar mantenimientos.
- Ingresar datos y cargar archivos externos relacionados con los mantenimientos.
- Gestionar solicitudes de mantenimiento.
- Registrar y monitorear el estado de los vehículos.

## Cómo la Nube Apoyó el Desarrollo de este Proyecto

### Arquitectura basada en Microservicios
La aplicación fue diseñada con una arquitectura de microservicios, lo que permitió:
- **Escalabilidad Independiente**: Cada servicio puede escalar según la demanda.
- **Desarrollo Ágil**: Equipos pueden trabajar en servicios separados sin interferencias.
- **Resiliencia**: Fallos en un servicio no afectan al sistema completo.

### Servicios en la Nube Utilizados
- **Google Cloud Run**: Para el despliegue de microservicios con escalado automático.
- **Cloud Storage**: Para almacenar documentos y archivos relacionados con los mantenimientos.
- **Cloud Firestore**: Para el almacenamiento de datos de usuarios y solicitudes de mantenimiento.

### Ciclo DevOps en el Desarrollo del Proyecto

El ciclo DevOps fue fundamental para el desarrollo y operación de la aplicación de gestión de mantenimientos de vehículos. A continuación, se detalla cómo se implementó cada fase del ciclo DevOps:

#### 1. PLAN
- **Herramientas Utilizadas**: Zapier, ClickUp, Discord.
- **Actividades**:
  - Planificación de tareas y asignación de responsabilidades utilizando ClickUp.
  - Automatización de flujos de trabajo y notificaciones con Zapier.
  - Comunicación y colaboración en tiempo real a través de Discord.

#### 2. CODE
- **Herramientas Utilizadas**: GitHub, FastAPI, React Native.
- **Actividades**:
  - Desarrollo del backend utilizando FastAPI para crear microservicios.
  - Desarrollo del frontend utilizando React Native para una aplicación móvil multiplataforma.
  - Control de versiones y colaboración en el código a través de GitHub.

#### 3. BUILD
- **Herramientas Utilizadas**: Docker.
- **Actividades**:
  - Creación de imágenes Docker para cada microservicio y la aplicación móvil.
  - Configuración de contenedores para garantizar la portabilidad y consistencia en diferentes entornos.

#### 4. TEST
- **Herramientas Utilizadas**: GitLab.
- **Actividades**:
  - Ejecución de pruebas automatizadas, incluyendo pruebas unitarias, de integración y de rendimiento.
  - Integración continua (CI) para asegurar la calidad del código con cada commit.

#### 5. RELEASE
- **Herramientas Utilizadas**: GitLab.
- **Actividades**:
  - Automatización del proceso de liberación (CD) para garantizar despliegues rápidos y confiables.
  - Gestión de versiones y etiquetado de releases en GitLab.

#### 6. DEPLOY
- **Herramientas Utilizadas**: Cloud Functions, Google Play Store.
- **Actividades**:
  - Despliegue de microservicios en Google Cloud Functions para aprovechar la escalabilidad automática.
  - Publicación de la aplicación móvil en Google Play Store para su distribución a los usuarios finales.

#### 7. OPERATE
- **Herramientas Utilizadas**: WSO2.
- **Actividades**:
  - Gestión y orquestación de servicios utilizando WSO2 para garantizar la operación continua y eficiente.
  - Automatización de tareas operativas y gestión de API.

#### 8. MONITOR
- **Herramientas Utilizadas**: Prometheus.
- **Actividades**:
  - Monitoreo en tiempo real del rendimiento y la salud de los servicios.
  - Configuración de alertas y paneles de control para identificar y resolver problemas rápidamente.

### Beneficios Clave
- **Optimización de Costos**: Pago por uso de recursos, evitando gastos innecesarios.
- **Alta Disponibilidad**: Despliegue en regiones múltiples para evitar tiempos de inactividad.
- **Despliegue Rápido**: Uso de CI/CD para mejorar la velocidad de entrega.
- **Mejora Continua**: Monitoreo y retroalimentación constante para optimizar el rendimiento y la experiencia del usuario.

## Conclusión
Gracias a la arquitectura nativa en la nube y el uso de microservicios, la aplicación logró escalabilidad, resiliencia y eficiencia operativa. La implementación de un ciclo DevOps completo permitió acelerar el desarrollo, mejorar la calidad del software y garantizar una operación continua y eficiente. La nube y las herramientas DevOps utilizadas fueron clave para el éxito del proyecto.

## Referencias
- [Google Books](https://books.google.com.ec/books?id=XSDCDwAAQBAJ&printsec=frontcover&source=gbs_ge_summary_r&cad=0#v=onepage&q&f=true)
- [WSO2 Slides](https://wso2.com/wso2_resources/wso2con2024-slides/architecting-cloud-native-applications.pdf)
- [WSO2 GitHub](https://github.com/wso2/reference-architecture/blob/master/reference-cloud-native-architecture-digital-enterprise.md)
