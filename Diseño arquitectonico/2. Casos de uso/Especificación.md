<p align='center'>
  <img src='https://github.com/user-attachments/assets/899a06d7-01dd-4f33-b0cf-48b36b632b6f' height="150">
</p>

<h1 align='center'>
  Diagrama de casos de uso
  <br>
  "Aplicación mantenimiento de flotas"
</h1>

## ¿Qué es un diagrama de casos de uso?

Un diagrama de casos de uso es una representación gráfica empleada en el modelado de sistemas para describir las interacciones entre los actores (usuarios, sistemas externos u otros componentes) y las funcionalidades principales que ofrece un sistema. Este tipo de diagrama, basado en el estándar UML (Lenguaje Unificado de Modelado), se utiliza para documentar qué hace el sistema desde la perspectiva de los usuarios, sin entrar en detalles sobre cómo se implementa.

## ¿Para qué sirve un diagrama de casos de uso?

El diagrama de casos de uso es una herramienta clave para el desarrollo y documentación de sistemas, ya que permite:

1. Especificar requisitos funcionales: Identificar y detallar las funcionalidades principales que debe cumplir el sistema.
2. Facilitar la comunicación: Servir como un medio común entre los interesados, desarrolladores y analistas para garantizar la comprensión de los requisitos.
3. Definir el alcance del sistema: Determinar los límites del sistema, especificando qué incluye y qué excluye.
4. Identificar actores clave: Describir quiénes interactuarán con el sistema, ya sean usuarios humanos o sistemas externos.
5. Priorizar funcionalidades: Ayudar a evaluar y clasificar las funcionalidades en función de su importancia o impacto para los usuarios.

## Estructura de un diagrama de casos de uso

La estructura de un diagrama de casos de uso incluye los siguientes componentes principales: 
1. Actores:
   + Representan las entidades externas que interactúan con el sistema.
   + Pueden ser personas, organizaciones o sistemas.
   + Se representan gráficamente como una figura humana o una etiqueta que los identifica.
   + Ejemplo: Usuario, Administrador, Sistema Externo.
2. Casos de uso:
   + Representan las funcionalidades o servicios específicos que el sistema proporciona a los actores.
   + Se representan como óvalos con un nombre que describe la acción.
   + Ejemplo: Registrar Usuario, Generar Informe, Procesar Pago.
3. Relaciones:
   + Asociación: Representa la interacción entre un actor y un caso de uso (línea sólida).
   + Inclusión (<< include >>): Indica que un caso de uso incluye la funcionalidad de otro, generalmente para evitar redundancia.
   + Extensión (<< extend >>): Señala un caso de uso opcional que extiende la funcionalidad de otro principal, dependiendo de ciertas condiciones.
   + Generalización: Define relaciones de herencia entre actores o entre casos de uso.
4. Sistema:
   + Representa los límites del sistema modelado.
   + Se ilustra como un rectángulo que contiene los casos de uso.
## 1. Diagrama de caso de uso (Registro)

![Caso de uso Registro](https://github.com/JonathanCoronel/uploadimg/blob/main/Imagenes%20Arquitectura/Diagrama%20de%20Caso1.drawio.png?raw=true)

## Especificación (Registro)

<table>
  <tr>
    <th>Nombre</th>
    <th>Registro</th>
  </tr>
  <tr>
    <td>Actores</td>
    <td>
       - Usuario<br>- UTPL
    </td>
  </tr>
  <tr>
    <td>Flujo normal</td>
    <td>
      - Usuario registra las credenciales a UTPL
      <br>
      - UTPL valida las credenciales y notifica al Usuario
      <br>
       - Usuario registra un Taller (Concesionario/Mecánica) en UTPL
      <br>
      - UTPL notifica de la creación del Taller al Usuario
      <br>
      - Usuario registra un Vehículo (Liviano/Pesado) en UTPL
      <br>
      - UTPL notifica de la creación del Vehículo al Usuario
    </td>
  </tr>
</table>

## 2. Diagrama de caso de uso (Orden de mantenimiento)

![Diagrama de caso de uso Orden Mantenimiento drawio](https://github.com/JonathanCoronel/uploadimg/blob/main/Imagenes%20Arquitectura/Diagrama%20de%20Caso2.drawio.png?raw=true)

## Especificación (Orden de mantenimiento)

<table>
  <tr>
    <th>Nombre</th>
    <th>Orden de mantenimiento</th>
  </tr>
  <tr>
    <td>Actores</td>
    <td>
       - Usuario<br>- UTPL
    </td>
  </tr>
  <tr>
    <td>Flujo normal</td>
    <td>
      - Usuario crea una orden de Mantenimiento en UTPL
      <br>
      - UTPL carga el formulario del Mantenimiento al Usuario
      <br>
      - Usuario Selecciona un Vehículo en UTPL
      <br>
      - UTPL carga el vehículo seleccionado por Usuario
      <br>
       - Usuario Selecciona un Encargado en UTPL
      <br>
      - UTPL carga el Encargado seleccionado por Usuario
      <br>
       - Usuario Selecciona un taller en UTPL
      <br>
      - UTPL carga el taller seleccionado por Usuario
      <br>
       - Usuario Selecciona una Orden de Mantenimiento (Preventivo/Correctivo) en UTPL
      <br>
      - UTPL carga el Formulario del mantenimiento al Usuario
      <br>
      - Usuario ingresa los datos que solicita y Genera la Orden de Mantenimiento en UTPL
      <br>
      - UTPL notifica de la creación de Orden de Mantenimiento al Usuario
    </td>
  </tr>
</table>

## 3. Diagrama de caso de uso (Verificación)

![Diagrama de caso de uso Verificacion drawio](https://github.com/JonathanCoronel/uploadimg/blob/main/Imagenes%20Arquitectura/Diagrama%20de%20Caso3.drawio.png?raw=true)

## Especificación (Verificación)

<table>
  <tr>
    <th>Nombre</th>
    <th>Verificación</th>
  </tr>
  <tr>
    <td>Actores</td>
    <td>
       -Encargado<br>- UTPL
    </td>
  </tr>
  <tr>
    <td>Flujo normal</td>
    <td>
     - Usuario (Encargado) Recepta el Vehículo para el proceso de verificación en UTPL
      <br>
     - UTPL despliega los datos de verificación al Usuario (Encargado)
      <br>
     - Usuario (Encargado) completa la verificación en UTPL
      <br>
     - UTPL notifica la finalización de la verificación al Usuario (Encargado)
      <br>
     - Usuario (Encargado) Ingresa el Costo de Mantenimiento en UTPL
      <br>
     - UTPL notifica el ingreso del Costo al Usuario (Encargado)
      <br>
     - Usuario (Encargado) Toma Foto de Factura en UTPL
      <br>
     - UTPL notifica el ingreso de Foto al Usuario (Encargado)
      <br>
     - Usuario (Encargado) genera un Reporte de verificación a UTPL
      <br>
     - UTPL notifica de la creación del reporte al Usuario (Encargado)
    </td>
  </tr>
</table>

## 4. Diagrama de caso de uso (Resumen)

![Diagrama de caso de uso Resumen drawio](https://github.com/JonathanCoronel/uploadimg/blob/main/Imagenes%20Arquitectura/Diagrama%20de%20Caso4.drawio.png?raw=true)

## Especificación (Resumen)

<table>
  <tr>
    <th>Nombre</th>
    <th>Resumen</th>
  </tr>
  <tr>
    <td>Actores</td>
    <td>
       -Usuario<br>- UTPL<br>- Administrador
    </td>
  </tr>
  <tr>
    <td>Flujo normal</td>
    <td>
     - Usuario Visualiza un resumen de los Mantenimientos en UTPL
      <br>
     - UTPL despliega los datos de los Mantenimientos al Usuario
      <br>
     - Usuario Visualiza los costos en UTPL
      <br>
     - UTPL despliega los datos de los costos al Usuario
    </td>
  </tr>
</table>





