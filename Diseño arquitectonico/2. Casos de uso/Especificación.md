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

![Caso de uso Registro](https://github.com/user-attachments/assets/17f5063e-6ab4-41be-a86d-1f6c6b92257f)

### Descripción (Registro)

| Nombre   |     | Verificar usuario |
| ------------- | ------------- |
| Actores | Usuario, UTPL |
| Fila 2, Celda 1 | Fila 2, Celda 2 |
| Fila 3, Celda 1 | Fila 3, Celda 2 |

