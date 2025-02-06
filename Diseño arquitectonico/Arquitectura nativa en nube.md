# Aplicaciones Nativas en la Nube

Las aplicaciones nativas en la nube están diseñadas para aprovechar al máximo los entornos de computación en la nube. Estas aplicaciones se construyen con arquitecturas modernas, como microservicios, contenedores y orquestación, lo que permite escalabilidad, resiliencia y despliegues ágiles. Su enfoque principal es la capacidad de adaptarse rápidamente a las demandas del mercado y ofrecer una experiencia de usuario óptima.

## Características de las Aplicaciones Nativas en la Nube

- **Microservicios**: Arquitectura basada en servicios independientes que se comunican entre sí a través de APIs. Esto permite que cada servicio se desarrolle, despliegue y escale de manera independiente.
- **Contenedores**: Uso de tecnologías como Docker para empaquetar aplicaciones y sus dependencias en un entorno aislado, lo que facilita la portabilidad entre diferentes entornos de ejecución.
- **Orquestación y Automatización**: Herramientas como Kubernetes permiten la gestión automática de cargas de trabajo, incluyendo el escalado, la recuperación ante fallos y la distribución de recursos.
- **Despliegue Continuo (CI/CD)**: Integración y entrega continua para acelerar el desarrollo y garantizar que las actualizaciones se implementen de manera rápida y segura.
- **Escalabilidad y Elasticidad**: Capacidad de aumentar o reducir recursos según la demanda, lo que permite optimizar costos y garantizar un rendimiento óptimo.
- **Resiliencia y Alta Disponibilidad**: Implementación en múltiples regiones y uso de estrategias de recuperación ante fallos, como la replicación de datos y el balanceo de carga.

---

# Caso de Estudio: Aplicación de Gestión de Mantenimientos de Vehículos

## Descripción de la Aplicación
Esta aplicación permite a los usuarios gestionar el mantenimiento de vehículos mediante una aplicación nativa en la nube. Incluye funcionalidades como:
- Programar y gestionar mantenimientos.
- Ingresar datos y cargar archivos externos relacionados con los mantenimientos, como facturas y reportes de inspección.
- Gestionar solicitudes de mantenimiento y asignar recursos.
- Registrar y monitorear el estado de los vehículos en tiempo real.

La aplicación está diseñada para ser utilizada por flotas de vehículos, talleres de mantenimiento y usuarios individuales que deseen mantener un registro detallado del estado de sus vehículos.

## Cómo la Nube Apoyó el Desarrollo de este Proyecto

### Arquitectura basada en Microservicios
La aplicación fue diseñada con una arquitectura de microservicios, lo que permitió:
- **Escalabilidad Independiente**: Cada servicio puede escalar según la demanda, lo que es especialmente útil para servicios como la gestión de notificaciones o el procesamiento de archivos.
- **Desarrollo Ágil**: Equipos pueden trabajar en servicios separados sin interferencias, lo que acelera el tiempo de desarrollo y facilita la incorporación de nuevas funcionalidades.
- **Resiliencia**: Fallos en un servicio no afectan al sistema completo, ya que los servicios están aislados y pueden recuperarse de manera independiente.

### Servicios en la Nube Utilizados
- **Google Cloud Run**: Para el despliegue de microservicios con escalado automático. Esto permite que la aplicación maneje picos de tráfico sin necesidad de intervención manual.
- **Cloud Storage**: Para almacenar documentos y archivos relacionados con los mantenimientos, como imágenes de inspecciones y facturas.
- **Cloud Firestore**: Para el almacenamiento de datos de usuarios y solicitudes de mantenimiento. Firestore ofrece una base de datos NoSQL escalable y de alto rendimiento.

### Ciclo DevOps en el Desarrollo del Proyecto

El ciclo DevOps fue fundamental para el desarrollo y operación de la aplicación de gestión de mantenimientos de vehículos. A continuación, se detalla cómo se implementó cada fase del ciclo DevOps:

![cvb](https://github.com/user-attachments/assets/b7a5762f-e70b-4c5c-ae73-762e5405db77)

#### 1. PLAN
- **Herramientas Utilizadas**: Zapier, ClickUp, Discord.
- **Actividades**:
  - Planificación de tareas y asignación de responsabilidades utilizando ClickUp, lo que permitió un seguimiento detallado del progreso del proyecto.
  - Automatización de flujos de trabajo y notificaciones con Zapier, lo que redujo el tiempo dedicado a tareas repetitivas.
  - Comunicación y colaboración en tiempo real a través de Discord, lo que facilitó la coordinación entre equipos distribuidos.

#### 2. CODE
- **Herramientas Utilizadas**: GitHub, FastAPI, React Native.
- **Actividades**:
  - Desarrollo del backend utilizando FastAPI para crear microservicios. FastAPI fue elegido por su rendimiento y facilidad de uso para construir APIs rápidas y escalables.
  - Desarrollo del frontend utilizando React Native para una aplicación móvil multiplataforma. Esto permitió reducir los costos de desarrollo al reutilizar código entre iOS y Android.
  - Control de versiones y colaboración en el código a través de GitHub, lo que facilitó la integración de cambios y la revisión de código.

#### 3. BUILD
- **Herramientas Utilizadas**: Docker.
- **Actividades**:
  - Creación de imágenes Docker para cada microservicio y la aplicación móvil. Esto garantizó que la aplicación se ejecutara de manera consistente en diferentes entornos, desde el desarrollo hasta la producción.
  - Configuración de contenedores para garantizar la portabilidad y consistencia en diferentes entornos, lo que simplificó el proceso de despliegue.

#### 4. TEST
- **Herramientas Utilizadas**: GitLab.
- **Actividades**:
  - Ejecución de pruebas automatizadas, incluyendo pruebas unitarias, de integración y de rendimiento. Esto aseguró que el código fuera robusto y libre de errores antes de su despliegue.
  - Integración continua (CI) para asegurar la calidad del código con cada commit. GitLab permitió automatizar la ejecución de pruebas cada vez que se realizaba un cambio en el código.

#### 5. RELEASE
- **Herramientas Utilizadas**: GitLab.
- **Actividades**:
  - Automatización del proceso de liberación (CD) para garantizar despliegues rápidos y confiables. GitLab permitió implementar pipelines de entrega continua que incluían pruebas, construcción y despliegue.
  - Gestión de versiones y etiquetado de releases en GitLab, lo que facilitó el seguimiento de las versiones desplegadas y la identificación de problemas.

#### 6. DEPLOY
- **Herramientas Utilizadas**: Cloud Functions, Google Play Store.
- **Actividades**:
  - Despliegue de microservicios en Google Cloud Functions para aprovechar la escalabilidad automática. Esto permitió que la aplicación manejara cargas de trabajo variables sin necesidad de intervención manual.
  - Publicación de la aplicación móvil en Google Play Store para su distribución a los usuarios finales. Esto garantizó que los usuarios pudieran acceder a las actualizaciones de manera rápida y sencilla.

#### 7. OPERATE
- **Herramientas Utilizadas**: WSO2.
- **Actividades**:
  - Gestión y orquestación de servicios utilizando WSO2 para garantizar la operación continua y eficiente. WSO2 permitió la integración de diferentes servicios y la gestión de APIs de manera centralizada.
  - Automatización de tareas operativas y gestión de API, lo que redujo la carga de trabajo del equipo de operaciones.

#### 8. MONITOR
- **Herramientas Utilizadas**: Prometheus.
- **Actividades**:
  - Monitoreo en tiempo real del rendimiento y la salud de los servicios. Prometheus permitió recopilar métricas clave y generar alertas en caso de problemas.
  - Configuración de alertas y paneles de control para identificar y resolver problemas rápidamente. Esto aseguró que el equipo pudiera responder de manera proactiva a cualquier incidencia.

### Beneficios Clave
- **Optimización de Costos**: Pago por uso de recursos, evitando gastos innecesarios. La escalabilidad automática permitió ajustar los recursos según la demanda, lo que redujo los costos operativos.
- **Alta Disponibilidad**: Despliegue en regiones múltiples para evitar tiempos de inactividad. Esto garantizó que la aplicación estuviera siempre disponible para los usuarios.
- **Despliegue Rápido**: Uso de CI/CD para mejorar la velocidad de entrega. Las actualizaciones se implementaron en cuestión de minutos, lo que permitió una respuesta rápida a las necesidades del mercado.
- **Mejora Continua**: Monitoreo y retroalimentación constante para optimizar el rendimiento y la experiencia del usuario. Las métricas recopiladas permitieron identificar áreas de mejora y realizar ajustes de manera proactiva.

## Conclusión
Gracias a la arquitectura nativa en la nube y el uso de microservicios, la aplicación logró escalabilidad, resiliencia y eficiencia operativa. La implementación de un ciclo DevOps completo permitió acelerar el desarrollo, mejorar la calidad del software y garantizar una operación continua y eficiente. La nube y las herramientas DevOps utilizadas fueron clave para el éxito del proyecto, permitiendo una entrega rápida y confiable de nuevas funcionalidades.

## Referencias
- [Google Books](https://books.google.com.ec/books?id=XSDCDwAAQBAJ&printsec=frontcover&source=gbs_ge_summary_r&cad=0#v=onepage&q&f=true)
- [WSO2 Slides](https://wso2.com/wso2_resources/wso2con2024-slides/architecting-cloud-native-applications.pdf)
- [WSO2 GitHub](https://github.com/wso2/reference-architecture/blob/master/reference-cloud-native-architecture-digital-enterprise.md)
