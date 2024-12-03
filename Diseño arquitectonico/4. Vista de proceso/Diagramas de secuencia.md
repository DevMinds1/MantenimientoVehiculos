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

![Diagrama_Secuencia_Registro](https://github.com/user-attachments/assets/e18e175b-db6c-4a36-b8b9-cc0fe7a0098e)

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

