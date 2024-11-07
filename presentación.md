<h1 align="center"> Mantenimiento de Vehiculos </center></h1>

**_Authors_**
+ Mateo Valarezo, Quality Assurance - Software Architect

+ Oliver Pinos, Backend Developer

+ Jonathan Coronel, Frontend Developer

+ Edgar Espinoza, UX/UI Designer

+ Jostin Alvarado, Test and Security

## 1.0 Introducción
El mantenimiento preventivo y correctivo de los vehículos es fundamental para prolongar su vida útil y garantizar su funcionamiento seguro. Un aplicativo nativo nube dedicado a la gestión del mantenimiento permitirá programar y registrar todas las actividades de mantenimiento, asegurando que los vehículos estén siempre en óptimas condiciones. La nube permitirá el almacenamiento seguro de registros históricos y la generación de reportes detallados.

![software-para-talleres](https://github.com/user-attachments/assets/a0613dee-98aa-4a31-8ad9-891355135f55)

<p align="center">
<i>
Figura 1 - Mantenimiento de Vehiculos<br/>
</i>
</p>

## 3.0 Mapa de Capacidades
El mapa de capacidades representa las principales funciones de nuestro sistema de gestión para el mantenimiento vehicular, dividido en tres áreas clave: Registro, Mantenimiento y Verificación. Cada área agrupa una serie de capacidades específicas, organizadas en módulos y submódulos, que permiten la administración eficiente de usuarios, vehículos, talleres, y procesos de mantenimiento preventivo y correctivo.

1. Registro: Cubre el ingreso de usuarios, el registro de talleres (clasificados en concesionarios y mecánica) y la inscripción de vehículos (ligeros y pesados), incluyendo la asignación de talleres.
2. Mantenimiento: Este módulo se subdivide en mantenimiento preventivo y correctivo. En el preventivo, se generan órdenes de revisión, se selecciona el vehículo y la fecha, y se crea un checklist de verificación, asignando un encargado para llevarlo a cabo. En el correctivo, se emiten órdenes de reparación y se genera un checklist de fallas.
3. Verificación: Gestiona la generación de reportes, la carga y verificación de checklists, y se confirma la recepción de las revisiones y reparaciones por parte del encargado.
Cada una de estas capacidades contribuye a la optimización del flujo de trabajo dentro del sistema de mantenimiento de flotas, facilitando el control y seguimiento de las operaciones esenciales para la preservación y reparación de los vehículos en el tiempo.   
## 4.0 Mapa de Capacidades

<img width="715" alt="Captura de pantalla 2024-11-06 a la(s) 22 13 30" src="https://github.com/user-attachments/assets/cd1b70a0-4aab-4522-b622-d4bf9b5df038">



<p align="center">
<i>
Figura 2 - Mapa de capacidades <br/>
</i>
</p>

## 5.0 Diagrama de casos de uso

### 5.1 Registro

![Registro4](https://github.com/user-attachments/assets/46bef5a3-6a50-4067-9366-eb43d440333b)


### 5.2 Mantenimiento

![Mantenimiento4](https://github.com/user-attachments/assets/d80923d4-f731-4514-bba4-4db14d25b272)


### 5.3 Verificación

![Verificacion4](https://github.com/user-attachments/assets/d55867cf-16a2-4138-bd83-4fb12b339c91)


## 6.0 Especificaciones

- Usuario registra las credenciales a UTPL

- UTPL valida las credenciales y notifica al Usuario

- Usuario ingresa como Administrador

- Administrador registra un taller tipo Concesionario y se guarda en UTPL

- UTPL notifica de la creación al Administrador

- Administrador registra un taller tipo Mecánica y se guarda en UTPL

- UTPL notifica de la creación al Administrador

- Administrador registra un Vehículo Liviano y se guarda en UTPL

- UTPL notifica de la creación al Administrador

- Administrador registra un Vehículo Pesado y se guarda en UTPL

- UTPL notifica de la creación al Administrador

- Administrador Asigna un vehículo a un Taller y se guarda en UTPL

- UTPL notifica de la asignación del vehículo al Administrador

- Administrador Selecciona un Vehículo creado en UTPL

- UTPL carga el vehículo seleccionado por Administrador

- Administrador Selecciona un Mantenimiento Preventivo

- Mantenimiento Preventivo solicita Seleccionar una fecha y Generar Checklist de Verificaciones al Administrador

- Administrador ingresa los datos que solicita y Genera la Orden de Mantenimiento

- Orden de Mantenimiento se guarda en UTPL

- UTPL notifica de la creación de Orden de Mantenimiento

- Orden de Mantenimiento es asignada a un Encargado

- Encargado Recepta el Vehículo para el proceso de verificación y se carga los datos guardados en UTPL

- UTPL despliega los datos para la solicitud del Encargado

- Encargado completa la verificación del checklist y guarda en UTPL

- UTPL notifica la finalización de la verificación al Encargado

- Encargado genera un Reporte de verificación

- Reporte de verificación es generado y guardado en UTPL

- UTPL notifica de la creación del reporte al Encargado


## 7.0 Prototipo Figma

<img src="https://github.com/user-attachments/assets/14e7ed03-1537-4cf7-aec2-77aead87f634" alt="qrcode_133488899_720ae18b86c79d09d4187c2e8f481515" width="500"/>

https://www.figma.com/proto/vS4toA14JGxyBCA7eTW7qx/MantenimientoFlotas?node-id=0-1&node-type=canvas&viewport=776%2C-225%2C0.13&t=tpDSmNgDoSL2pmgt-0&scaling=min-zoom&content-scaling=fixed&starting-point-node-id=373%3A989


