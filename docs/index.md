# ⛳ LAS ENCINAS CLUB DE GOLF
## Sistema de reservas online para un club de golf

---

## 1. Descripción del proyecto

mI tURNO es una aplicación web diseñada para facilitar la gestión de reservas de un club de golf.

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

## 5. Estructura del proyecto

### Función de cada archivo

- `index.html`: estructura y contenido de la página.
- `style.css`: diseño, colores y adaptación a diferentes pantallas.
- `script.js`: validación de formularios y gestión local de reservas.
- `README.md`: documentación del proyecto.

## 6. Instalación y ejecución

1. Crear una carpeta llamada `club-golf`.
2. Abrir la carpeta con Visual Studio Code.
3. Crear los archivos `index.html`, `style.css`, `script.js` y `README.md`.
4. Pegar el código correspondiente en cada archivo.
5. Guardar todos los archivos.
6. Abrir `index.html` en un navegador o utilizar la extensión Live Server.

## 7. Tecnologías utilizadas

### HTML5

Se utiliza para crear la estructura de la aplicación, los formularios y las secciones informativas.

### CSS3

Se utiliza para definir los colores corporativos, las tarjetas, los botones, la distribución de contenidos y el diseño adaptable.

### JavaScript

Se utiliza para validar los datos, generar horarios, comprobar conflictos de reservas y guardar datos de demostración en el navegador.

### Markdown

Se utiliza para documentar el proyecto, explicar sus funcionalidades y facilitar su mantenimiento.

## 8. Flujo de una reserva aceptada

```text
Cliente
   |
   v
Abre la aplicación web
   |
   v
Selecciona el servicio
   |
   v
Introduce los datos
   |
   v
El sistema valida la información
   |
   v
Comprueba la disponibilidad
   |
   v
¿Está disponible?
   |
   v
Sí: registra la reserva
   |
   v
Muestra el resultado
```

## 9. Flujo de una reserva rechazada

```text
Cliente selecciona una fecha y hora
   |
   v
El sistema consulta las reservas
   |
   v
Detecta un horario ocupado
   |
   v
Informa al cliente
   |
   v
Propone otra hora o casilla
   |
   v
El cliente selecciona una alternativa
```

## 10. Gestión del equipamiento

Durante el proceso de reserva, el cliente debe indicar una de estas opciones:

- Llevará su propio material.
- Necesita alquilar material.
- Llevará parte del material y alquilará el resto.

Esta información permitirá al club planificar mejor la disponibilidad de equipamiento.

## 11. Gestión de socios

Los socios podrán acceder a descuentos de acuerdo con las condiciones establecidas por el club.

La versión inicial incluye un campo para indicar la condición de socio y aportar su acreditación. Para utilizarlo en producción, deberá integrarse un procedimiento seguro de verificación.

## 12. Asistente virtual

La página incluye un asistente demostrativo que responde preguntas frecuentes sobre:

- Horarios de apertura.
- Alquiler de equipamiento.
- Descuentos para socios.
- Procedimiento para realizar una reserva.

Esta primera versión utiliza respuestas predefinidas. Para disponer de una inteligencia artificial real, será necesario conectarla a un servicio de IA mediante un servidor.

## 13. Base de datos y seguridad

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

## 14. Conclusión

Green Club propone una solución digital para mejorar la organización de las reservas de un club de golf.

La aplicación permite centralizar las solicitudes, consultar horarios, gestionar las necesidades de material y reducir los conflictos entre clientes.

La incorporación futura de una base de datos compartida y un asistente de inteligencia artificial permitirá convertir la demostración en un sistema de reservas completo y preparado para su uso real.