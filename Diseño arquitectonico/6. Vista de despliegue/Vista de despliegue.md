<h1>Diagrama de despliegue</h1>

## ¿Qué es un diagrama de despliegue?

<p>El diagrama de despliegue ayuda a modelar el aspecto físico de un sistema de software orientado a objetos. Modela la configuración en tiempo de ejecución en una vista estática y visualiza la distribución de los componentes en una aplicación. En la mayoría de los casos, implica modelar las configuraciones de hardware junto con los componentes de software existentes</p>

## Diagrama de despliegue (Mantenimiento de flotas)

![Diagrama de despliegue Flotas-2 (1) drawio](https://github.com/user-attachments/assets/2902b39a-e0fe-427f-9c2a-19b9f82c1ced)

<p>El diagrama de despliegue presentado describe la arquitectura de una aplicación móvil orientada a la gestión de flotas vehiculares. A continuación, se explican los componentes y la interacción entre ellos de manera detallada y formal:</p>

### 1. Smartphone
* Descripción:
  * Representa el dispositivo del usuario final donde se ejecuta la aplicación móvil.
  * Este dispositivo interactúa directamente con el sistema mediante solicitudes HTTP.
* Componentes:
  * React Native App:
    * Es la aplicación móvil desarrollada en React Native, cuyo propósito principal es ofrecer una interfaz interactiva para la gestión de flotas.
* Subcomponentes:
  * Styles:
    * Conjunto de estilos visuales que definen la apariencia de la interfaz de usuario.
    * Scripts: Código de la lógica funcional que habilita las funcionalidades de la aplicación.
### 2. WSO2 API Manager
* Descripción:
  * Este componente actúa como un Gateway API encargado de recibir y gestionar las solicitudes HTTP provenientes de la aplicación móvil.
  * Funciona como intermediario entre la aplicación móvil y los microservicios alojados en el servidor de productos, garantizando la seguridad, el control de accesos y la gestión de las API.
* Funciones principales:
  * Redirigir solicitudes REST al microservicio correspondiente en el servidor de productos.
  * Proveer una capa de abstracción entre la aplicación móvil y los servicios backend.
## 3. Product Server
* Descripción:
  * Servidor dedicado a alojar los microservicios que implementan la lógica de negocio de la aplicación.
  * Cada microservicio se comunica con una instancia de Firebase para el almacenamiento de datos persistentes mediante el protocolo TCP.
* Microservicios:
  * Microservice Users:
    * Responsable de la gestión de datos relacionados con los usuarios, como autenticación, roles y permisos.
    * Utiliza Firestore/Storage para el almacenamiento de información del usuario.
  * Microservice repairShops:
    * Administra los datos de talleres de reparación, incluyendo su ubicación e información en general.
    * Depende de Firestore/Storage para la persistencia de estos datos.
  * Microservice Orders:
    * Encargado del manejo de órdenes o solicitudes relacionadas con la gestión de flotas.
    * Firestore/Storage almacena la información de las órdenes procesadas.
  * Microservice Vehicles:
    * Diseñado para gestionar la información de los vehículos de la flota, como su estado y mantenimiento.
    * Se conecta a Firestore/Storage para almacenar y recuperar datos de los vehículos.
