# "MITURNO"
## Sistema de reservas online para un club de golf

---

## 1. Descripción del proyecto

Mi Turno es una aplicación web diseñada para facilitar la gestión de reservas de un club de golf.

El sistema permite a los clientes consultar horarios, reservar turnos, seleccionar casillas del campo de prácticas e indicar si necesitan alquilar equipamiento.

El objetivo principal es evitar las reservas duplicadas, mejorar la organización del club y ofrecer una experiencia más cómoda a los usuarios.

## 2. Problema que se quiere resolver

Actualmente, las reservas se realizan por teléfono o presencialmente. Este procedimiento puede provocar que diferentes clientes reserven el mismo horario.

Esto genera conflictos, malestar entre los clientes y una mala imagen del club. Además, dificulta conocer con antelación las necesidades de material de cada usuario.

La solución propuesta es centralizar las reservas mediante una aplicación web.

## 3. Funcionalidades principales

- Reservas del campo de golf (selección de 9 o 18 hoyos)
- Reservas del campo de prácticas. (selección de casillas del al 15)
- Duraciones de 1, 2, 3 o 4 horas.
- Registro de datos personales.
- Selección de equipamiento propio o de alquiler.
- Identificación de socios.
- Validación de horarios.
- Comprobación de disponibilidad.
- Asistente virtual de preguntas frecuentes.

## 4. Horarios del club

| Día | Horario |
|---|---|
| Martes a sábado | 09:00–21:00 |
| Domingos y festivos | 09:00–20:00 |
| Lunes | Cerrado, salvo festivos con apertura |

Los turnos del campo de golf comienzan en intervalos de 20 minutos. Las reservas del campo de prácticas se realizan por horas.

## 5. Gestión del equipamiento

Durante el proceso de reserva, el cliente debe indicar una de estas opciones:

- Llevará su propio material.
- Necesita alquilar material.
- Llevará parte del material y alquilará el resto.

Esta información permitirá al club planificar mejor la disponibilidad de equipamiento.

## 6. Gestión de socios

Los socios podrán acceder a descuentos de acuerdo con las condiciones establecidas por el club.

La versión inicial incluye un campo para indicar la condición de socio y aportar su acreditación. Para utilizarlo en producción, deberá integrarse un procedimiento seguro de verificación.

## 7. Asistente virtual

La página incluye un asistente demostrativo que responde preguntas frecuentes sobre:

- Horarios de apertura.
- Alquiler de equipamiento.
- Descuentos para socios.
- Procedimiento para realizar una reserva.

Esta primera versión utiliza respuestas predefinidas. Para disponer de una inteligencia artificial real, será necesario conectarla a un servicio de IA mediante un servidor.

## 8. Base de datos y seguridad

La versión inicial almacena las reservas en el almacenamiento local del navegador.

Esta solución permite realizar pruebas, pero no garantiza que varios usuarios compartan una única agenda de reservas.

Para una versión de producción se recomienda incorporar:

- Una base de datos centralizada.
- Un servidor para procesar las reservas.
- Validación de disponibilidad en el servidor.
- Protección de datos personales.
- Verificación de socios.
- Notificaciones automáticas.
- Gestión de cancelaciones y modificaciones.
- Prevención de reservas simultáneas del mismo espacio.

## 9. Conclusión

Mi Turno propone una solución digital para mejorar la organización de las reservas de un club de golf.

La aplicación permite centralizar las solicitudes, consultar horarios, gestionar las necesidades de material y reducir los conflictos entre clientes.

La incorporación futura de una base de datos compartida y un asistente de inteligencia artificial permitirá convertir la demostración en un sistema de reservas completo y preparado para su uso real.