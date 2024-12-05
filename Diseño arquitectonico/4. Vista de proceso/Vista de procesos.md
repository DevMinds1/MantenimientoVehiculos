<p align='center'>
  <img src='https://github.com/user-attachments/assets/899a06d7-01dd-4f33-b0cf-48b36b632b6f' height="150">
</p>

<h1 align='center'>
  Diagramas de secuencia
  <br>
  "Aplicación mantenimiento de flotas"
</h1>

## ¿Qué es un diagrama de secuencia?

Los diagramas de secuencia son una herramienta de modelado en la Ingeniería de Software que forma parte del Lenguaje Unificado de Modelado (UML). Se utilizan para describir cómo los objetos de un sistema interactúan entre sí a través del tiempo, mostrando el flujo de mensajes o llamadas entre ellos. Estos diagramas son especialmente útiles para representar procesos y casos de uso en sistemas orientados a objetos.

## Estructura que sigue un diagrama de secuencia


1. **Actores y Objetos:** Representan las entidades que participan en la interacción. Los actores se representan como figuras humanas, y los objetos como rectángulos.
2. **Líneas de vida:** Indican la existencia de un actor u objeto durante el proceso. Son líneas verticales que comienzan debajo de cada actor u objeto.
3. **Mensajes:** Representan la comunicación entre actores y objetos mediante flechas horizontales.
4. **Bloques de ejecución:** Rectángulos sobre las líneas de vida que representan la ejecución de un proceso o método.
5. **Tiempo:** Se representa de forma implícita en la dirección descendente del diagrama.

## Diagramas de secuencia

### Diagrama: Registro

![Diagrama_Secuencia_Registro](https://github.com/JonathanCoronel/uploadimg/blob/main/Imagenes%20Arquitectura/secuenci1.drawio.png?raw=true)

### Explicación:

Este diagrama describe cómo los usuarios inician sesión en el sistema de la UTPL. Una vez autenticado, puede registrar talleres y vehículos. Los pasos clave incluyen:

+ Registrar credenciales.
+ Validar las credenciales del usuario.
+ Registrar talleres.
+ Registrar vehículos.


### Diagrama: Orden de mantenimiento

![Diagrama_Secuencia_Orden](https://github.com/user-attachments/assets/fb0b51f9-ab34-4705-8f23-246194004013)

### Explicación:

Este diagrama describe cómo los usuarios crean una orden de mantenimiento. Los pasos clave incluyen:

+ Buscar vehículo.
+ Buscar encargado.
+ Buscar taller.
+ Obtener tipo de orden.
+ Solicita los datos del formulario.
+ Completa formulario.
+ Notifica creación.

### Diagrama: Verificación

![Diagrama_Secuencia_Verificación](https://github.com/user-attachments/assets/147bd28a-eaea-46f4-9e85-38a0a4b4f4fe)

### Explicación:

Este diagrama describe cómo se verifican los mantenimientos. Los pasos clave incluyen:

+ Obtiene vehículo.
+ Despliega datos.
+ Obtiene verificación.
+ Notifica verificación.
+ Ingresa costo.
+ Toma foto de la factura.
+ Genera reporte.
+ Obtiene reporte.

### Diagrama: Resumen

![Diagrama_Secuencia_Resumen](https://github.com/user-attachments/assets/f524c071-f261-4a2c-99ad-528a610c01ea)

### Explicación:

Este diagrama describe cómo se dara el resumen sobre mantenimiento y costos. Los pasos clave incluyen:

+ Obtiene orden.
+ Despliega datos.

<h1>Diagramas de robustez</h1>

## ¿Qué son los diagramas de robustez?

Los diagramas de robustez son una herramienta de modelado utilizada en el diseño de software para detallar cómo los actores, objetos, y procesos interactúan dentro de un sistema. Sirven como un puente entre los diagramas de casos de uso y los diagramas de diseño detallado, permitiendo identificar elementos clave del sistema como actores, controladores y entidades.

## Estructura que siguen los diagramas de robustez

+ Actores: Representan los usuarios u otros sistemas que interactúan con el sistema principal. Se dibujan como figuras humanas o íconos.
+ Entidades: Son los elementos de datos o conceptos principales del dominio, representados como rectángulos.
+ Controladores: Representan la lógica de la aplicación y la interacción entre actores y entidades. Se muestran como círculos u óvalos.
+ Relaciones: Representan las conexiones entre actores, controladores y entidades mediante líneas con etiquetas que describen la          interacción.

### Diagrama Robustez: Registro
![Registro_Robustez](https://github.com/user-attachments/assets/af9b410a-2f9c-4380-9d5d-367e648fce70)

### Diagrama Robustez: Orden de Mantenimiento
![OrdenMantenimiento_Robustez](https://github.com/user-attachments/assets/afc5c3b1-f49a-44df-8c15-bb07fe375405)

### Diagrama Robustez: Visualización
![Visualizacion_Robustez](https://github.com/user-attachments/assets/8894c78d-3964-4785-8bf1-b4bda76705de)

