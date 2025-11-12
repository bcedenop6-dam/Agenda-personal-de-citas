<h1 align="center"> AGENDA PERSONAL DE CITAS </h1>

## Descripcion
El proyecto consiste en desarrollar una **aplicación de Agenda Personal de Citas**, que permita al usuario **registrar, consultar, modificar y eliminar citas** de manera rápida y organizada.  
El sistema busca facilitar la gestión del tiempo, evitando olvidos y mejorando la productividad personal o profesional.

## Objetivos
- Permitir al usuario administrar sus citas diarias, semanales o mensuales.
- Enviar recordatorios automáticos de las citas próximas.
- Facilitar la búsqueda de citas por fecha, tema o tipo.
- Garantizar que los datos sean seguros y se almacenen correctamente.


## Requerimientos Funcionales
| ID | Tipo | Descripción |
|----|------|-------------|
| RF1 | Entrada y almacenamiento | El sistema debe permitir al usuario registrar una nueva cita indicando fecha, hora, descripción y lugar |
| RF2 | Consulta | El sistema debe permitir visualizar las citas programadas por día, semana o mes |
| RF3 | Modificacion | El sistema debe permitir editar la información de una cita existente |
| RF4 | Eliminacion | El sistema debe permitir eliminar una cita seleccionada por el usuario |
| RF5 | notificacion | El sistema debe mostrar un recordatorio automático minutos antes del inicio de cada cita |

## Requerimientos no Funcionales
| ID | Tipo | Descripción |
|----|------|-------------|
| RNF1 | Usabilidad | La interfaz debe ser intuitiva y fácil de usar, con botones claramente identificados |
| RNF2 | Rendimiento | El sistema debe responder a las acciones del usuario en menos de 2 segundos |
| RNF3 | Seguridad de datos | El sistema debe guardar la información de las citas de manera local y segura, evitando pérdida de datos por cierres inesperados |

## tabla de Prueba
| Nº | Requerimiento asociado | Datos de Entrada | Resultado esperado | Validacion |
|----|------------------------|------------------|--------------------|------------|
| 1. | RF1 – Registrar cita | Fecha: 15/11/2025<br>Hora: 09:00<br>Asunto: “Cita médica”<br>Descripción: “Chequeo general” | La cita se registra correctamente en la base de datos y se muestra en la lista de citas | Cita creada y visualizada correctamente en la agenda |
| 2. | RF2 – Consultar cita | Buscar: “médica” | El sistema muestra la cita registrada que contiene la palabra clave “médica” | Cita encontrada correctamente por palabra clave |
| 3. | RF3 – Editar cita | Cita seleccionada: “Cita médica”<br>Nuevo asunto: “Chequeo odontológico” | Se actualiza la cita con el nuevo asunto sin errores | Cita modificada correctamente y actualizada en pantalla |

## Propuesta de Mantenimiento
Se propone realizar un **mantenimiento evolutivo** para incorporar nuevas funcionalidades, como sincronización con Google Calendar o integración con asistentes virtuales.
También se planifica un **mantenimiento preventivo** mensual, enfocado en respaldos automáticos y actualizaciones de seguridad.

## Reflexión sobre el control de versiones
El uso de **Git y GitHub** permite mantener un control detallado sobre los cambios realizados en el sistema y en la documentación.  
Cada actualización se registra con fecha, autor y descripción, lo cual mejora la **colaboración**, la **organización** y la **transparencia del desarrollo**.  
Además, el control de versiones evita errores por sobrescritura de archivos y facilita la restauración de versiones anteriores si es necesario.

# Sistema de Agenda Personal de Citas

## 1. Descripción del Caso
El sistema de agenda personal de citas permite a los usuarios **registrar, consultar, actualizar y eliminar citas personales** de manera sencilla.  
Su objetivo principal es **organizar y gestionar el tiempo de manera eficiente**, evitando conflictos de horarios y asegurando que todas las citas importantes sean recordadas.

## 2. Objetivos
- Facilitar la **gestión de citas personales**.  
- Permitir **consultar citas por fecha, hora o descripción**.  
- Ofrecer una **interfaz simple y amigable** para la administración de citas.  
- Mejorar la **organización y planificación del usuario**.

## 3. Requerimientos
### Funcionales
1. Registrar nuevas citas con: fecha, hora y descripción.  
2. Consultar citas por día o por rango de fechas.  
3. Modificar o eliminar citas existentes.  
4. Notificar al usuario sobre citas próximas.

### No funcionales
- La aplicación debe ser **fácil de usar** y **rápida**.  
- Los datos deben ser **almacenados de forma segura**.  
- La interfaz debe ser compatible con **dispositivos móviles y de escritorio**.

## 4. Tabla de Pruebas Funcionales

| Caso de Prueba | Acción | Resultado Esperado | Validación |
|----------------|--------|------------------|------------|
| Registrar cita | Ingresar fecha, hora y descripción | La cita se guarda correctamente | Verificar que la cita aparece en la agenda |
| Consultar citas | Buscar por fecha específica | Se muestran todas las citas de esa fecha | Comparar resultados con las citas registradas |
| Eliminar cita | Seleccionar una cita y eliminar | La cita desaparece de la agenda | Confirmar que la cita ya no aparece en la lista |

## 5. Tipo de Mantenimiento Propuesto
- **Mantenimiento correctivo:** Corregir errores de registro, edición o eliminación de citas.  
- **Mantenimiento evolutivo:** Añadir funcionalidades como recordatorios automáticos, exportación de citas o integración con calendarios externos.

## 6. Reflexión sobre el Control de Versiones
El control de versiones permite:
- **Rastrear cambios** realizados en el proyecto.  
- **Colaborar en equipo** sin sobrescribir el trabajo de otros.  
- **Revertir versiones** si ocurre un error o un fallo en la implementación.  
- Mantener un **historial documentado** de mejoras y correcciones, lo que aumenta la confiabilidad y facilita el mantenimiento del sistema.
