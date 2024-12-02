<p align='center'>
  <img src='https://github.com/user-attachments/assets/899a06d7-01dd-4f33-b0cf-48b36b632b6f' height="150">
</p>

<h1 align='center'>
  Mapa de capacidades
  <br>
  "Aplicación mantenimiento de flotas"
</h1>

### ¿Qué es un mapa de capacidaes?

Un **Mapa de Capacidades** es una herramienta visual que ayuda a estructurar y definir las funciones y habilidades esenciales de un sistema o aplicación. Su propósito es ofrecer una visión clara de las capacidades que un sistema debe tener para cumplir sus objetivos. En el contexto de una aplicación de software, un mapa de capacidades permite identificar las áreas clave de funcionalidad, agrupar actividades relacionadas y visualizar cómo se interconectan los diferentes módulos del sistema.

### Estructura de un mapa de capacidades

Un mapa de capacidades generalmente se divide en módulos o áreas de alto nivel que representan conjuntos de funcionalidades interrelacionadas. Cada módulo tiene una serie de subfunciones o componentes que especifican en mayor detalle las capacidades que el sistema debe proporcionar. Estos módulos suelen estar organizados de manera jerárquica y permiten a los desarrolladores, diseñadores y stakeholders entender el alcance de las funcionalidades de la aplicación.

![WhatsApp Image 2024-12-02 at 17 58 13](https://github.com/user-attachments/assets/7f6e137b-b883-4859-80aa-4e78f52969c0)

Este mapa de capacidades se ha diseñado para una aplicación móvil enfocada en el mantenimiento de flotas vehiculares, está organizada en cuatro módulos principales:

**1. Registro**
<br>
**2. Orden de mantenimiento**
<br>
**3. Verificación**
<br>
**4. Resumen**
<br>

## Descripción de los modulos

## 1. Registro
**Objetivo**: Gestionar la información inicial necesaria para realizar el mantenimiento.

### Capacidades:
- **Verificar usuario**: Validar las credenciales del usuario responsable.
- **Buscar responsable**: Identificar quién será responsable de gestionar el mantenimiento.
- **Registrar taller**: Añadir la información del taller que realizará el mantenimiento.
  - Registrar concesionario.
  - Registrar mecánica.
- **Registrar vehículo**: Añadir la información del vehículo que se someterá a mantenimiento.
  - Ingresar vehículo liviano.
  - Ingresar vehículo pesado.

---

## 2. Orden de Mantenimiento
**Objetivo**: Crear una orden de trabajo para el mantenimiento del vehículo.

### Capacidades:
- **Seleccionar vehículo**: Escoger el vehículo que recibirá el mantenimiento.
- **Seleccionar encargado**: Definir quién será el encargado del mantenimiento.
- **Seleccionar taller**: Asociar el taller que llevará a cabo el mantenimiento.
- **Preventivo**: Gestión de mantenimiento preventivo.
  - Seleccionar fecha para el mantenimiento.
  - Generar checklist de verificaciones.
- **Correctivo**: Gestión de mantenimiento correctivo.
  - Generar checklist de fallas.
  - Generar observación sobre las fallas identificadas.
- **Generar orden**: Emitir la orden de mantenimiento final.

---

## 3. Verificación
**Objetivo**: Asegurar la calidad y documentación del mantenimiento realizado.

### Capacidades:
- **Recepcionar vehículo**: Confirmar la recepción del vehículo en el taller.
- **Verificar checklist**: Validar que se hayan cumplido todos los puntos del checklist.
- **Ingresar costo de mantenimiento**: Registrar el costo total asociado al mantenimiento.
- **Tomar foto de factura**: Documentar el recibo o factura del servicio.
- **Generar reporte**: Crear un informe detallado del mantenimiento realizado.

---

## 4. Resumen
**Objetivo**: Proporcionar una visión general de los mantenimientos realizados y sus costos.

### Capacidades:
- **Visualizar mantenimientos**: Consultar el historial de mantenimientos realizados.
- **Visualizar costos**: Obtener un desglose de los costos asociados a cada mantenimiento.

