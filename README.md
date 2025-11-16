
<h1 align="center"> AGENDA PERSONAL DE CITAS </h1>

El proyecto consiste en desarrollar una **aplicación de Agenda Personal de Citas**, que permita al usuario **registrar, consultar, modificar y eliminar citas** de manera rápida y organizada.  
El sistema busca facilitar la gestión del tiempo, evitando olvidos y mejorando la productividad personal o profesional.

## Objetivos
- Permitir al usuario administrar sus citas diarias, semanales o mensuales.
- Enviar recordatorios automáticos de las citas próximas.
- Facilitar la búsqueda de citas por fecha, tema o tipo.
- Garantizar que los datos sean seguros y se almacenen correctamente.

## Requerimientos no Funcionales
| ID | Tipo | Descripción |
|-|-|-|
| RNF1 | Usabilidad | La interfaz debe ser intuitiva y fácil de usar para usuarios no técnicos. |
| RNF2 | Rendimiento | El sistema debe cargar la agenda y las citas en menos de 3 segundos. |
| RNF3 | Seguridad de datos | Los datos de las citas deben mantenerse privados y protegidos. |
| RNF4 | Disponibilidad | La interfaz debe ser intuitiva y fácil de usar para usuarios no técnicos. | Los usuarios deben poder crear una cita en menos de 3 clics |
| RNF5 | Mantenibilidad | El sistema debe funcionar en diferentes dispositivos y navegadores. |

## Tabla de Prueba
| Nº | Requerimiento asociado | Datos de Entrada | Resultado esperado | Validacion |
|----|------------------------|------------------|--------------------|------------|
| 1. | RF1 – Registrar cita | Fecha: 15/11/2025<br>Hora: 09:00<br>Asunto: “Cita médica”<br>Descripción: “Chequeo general” | La cita se registra correctamente en la base de datos y se muestra en la lista de citas | Cita creada y visualizada correctamente en la agenda |
| 2. | RF2 – Consultar cita | Buscar: “médica” | El sistema muestra la cita registrada que contiene la palabra clave “médica” | Cita encontrada correctamente por palabra clave |
| 3. | RF3 – Editar cita | Cita seleccionada: “Cita médica”<br>Nuevo asunto: “Chequeo odontológico” | Se actualiza la cita con el nuevo asunto sin errores | Cita modificada correctamente y actualizada en pantalla |

## Propuesta de Mantenimiento
Se propone realizar un **mantenimiento evolutivo** para incorporar nuevas funcionalidades, como sincronización con Google Calendar o integración con asistentes virtuales.
También se planifica un **mantenimiento preventivo** mensual, enfocado en respaldos automáticos y actualizaciones de seguridad.

## Reflexión sobre el control de versiones
El uso de **Git** y **GitHub** permite mantener un control detallado sobre los cambios realizados en el sistema y en la documentación.  
Cada actualización se registra con fecha, autor y descripción, lo cual mejora la **colaboración**, la **organización** y la **transparencia del desarrollo**.  
Además, el control de versiones evita errores por sobrescritura de archivos y facilita la restauración de versiones anteriores si es necesario.



