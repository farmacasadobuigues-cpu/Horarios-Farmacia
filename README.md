# Farmacia Carlos Casado Buigues · Cuadrante de turnos

Aplicación web para organizar los turnos del equipo de una farmacia comunitaria y las guardias.

Publicada en claude.ai con enlace público: el cuadrante va dentro de la propia página, así que el equipo la abre sin cuenta (también desde el móvil, añadiéndola a la pantalla de inicio) y solo puede consultarla. La propietaria edita y pulsa «Publicar para el equipo»; si no, se publica sola a los 2 minutos sin cambios o al salir de la app. Abierto como archivo suelto (`index.html`), funciona en local y guarda los datos en el navegador.

## Imagen

Colores y tipografía (Titillium Web) del manual de identidad de la farmacia, con el anagrama «Cb». Cada persona tiene un avatar friki en broma (Maestro Jedi, Once, La Duquesa, Madre de dragones, Miércoles, El niño mago, Droide), que se elige en Equipo. Con el botón «Foto» se puede poner una imagen propia a cada persona.

## Qué hace

- **Cuadrante semanal**: mañana de 08:30 a 15:00 y tarde de 14:30 a 21:00 (media hora de solape en el cambio de turno). Genera automáticamente 3 personas por turno con un farmacéutico o una persona responsable de turno, y reparte la responsabilidad de cada uno: mostrador, administración o gestión. Cada persona hace el mismo turno toda la semana. Todo se puede cambiar a mano y avisa si un turno queda incompleto, sin responsable o con alguien doblando turno.
- **Sábados**: de 09:00 a 14:00 con 2 personas. Rotan todas por igual (2 sábados de cada 5) y siempre entra al menos una persona que pueda llevar el sábado (Ramiro, Lucía o Anastasia), de modo que Aizane y Lorena no coinciden solas.
- **Año**: vista de todas las semanas del año con quién hace mañana, tarde y sábado, y el total de horas por persona. El año 2027 sigue el Excel «HORARIO 2027 turnos v2»: Ramiro y Luci alternan por semanas (Ramiro empieza de tarde el 4 de enero, siguiendo la rutina de 2026), Lorena y Aizane de mañana y Anastasia de tarde.
- **Festivos**: nacionales, autonómicos de la Comunitat Valenciana (San José, Lunes de Pascua y 9 de octubre) y locales (5 de agosto y 22 de octubre); la farmacia cierra y no se mueven los turnos: si un sábado es festivo, quienes tenían ese sábado libran. Se editan en Ajustes.
- **Mi horario**: cada persona elige quién es (se recuerda en su móvil) y ve su día de hoy, sus próximos 14 días, sus sábados, sus vacaciones y sus guardias.
- **Vacaciones**: 30 días naturales por persona y año; muestra los disfrutados, los que tienen fecha y los pendientes. No puede haber dos personas de vacaciones a la vez salvo aprobación expresa. En el cuadrante, la persona sale «De vacaciones» y el turno avisa de que falta alguien.
- **Guardias**: fechas, tipo (nocturna o 24 h) y quién las hace. Se pagan aparte y no cuentan en las horas.
- **Ahora**: quién está trabajando en este momento y qué hace.
- **Equipo**: dar de alta y de baja con roles (titular, farmacéutico adjunto, auxiliar, estudiante en prácticas). No permite dar de baja al último farmacéutico adjunto. Al dar de baja a alguien se reasignan sus turnos pendientes.
- **Ajustes**: hora de apertura, días que abre la farmacia y copia de seguridad.

Los estudiantes en prácticas van como refuerzo tutorizado y no cuentan para las 3 personas mínimas.

## Equipo inicial

| Nombre | Rol | Turno |
|---|---|---|
| Ramiro González | Farmacéutico adjunto | Semanas alternas (mañana / tarde) |
| Lucía Rojo | Técnico en farmacia · responsable de turno | Semanas alternas (al contrario que Ramiro) |
| Anastasia | Auxiliar | Mañana |
| Aizane | Auxiliar | Mañana |
| Lorena | Auxiliar | Tarde |

Hasta la temporada alta se trabaja con 3 personas de mañana y 2 de tarde (se cambia en Ajustes).

Las guardias se gestionan fuera de la aplicación.
