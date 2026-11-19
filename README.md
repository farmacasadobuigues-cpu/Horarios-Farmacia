# Farmacia Carlos Casado Buigues · Cuadrante de turnos

Aplicación web para organizar los turnos del equipo de una farmacia comunitaria y las guardias.

Abre `index.html` en cualquier navegador: no necesita instalación ni servidor. Los datos se guardan en el propio navegador (en **Ajustes** puedes copiarlos como copia de seguridad o pasarlos a otro equipo).

## Qué hace

- **Cuadrante semanal**: mañana de 08:30 a 15:00 y tarde de 14:30 a 21:00 (media hora de solape en el cambio de turno). Genera automáticamente 3 personas por turno con un farmacéutico o una persona responsable de turno, y reparte la responsabilidad de cada uno: mostrador, administración o gestión. Cada persona hace el mismo turno toda la semana. Todo se puede cambiar a mano y avisa si un turno queda incompleto, sin responsable o con alguien doblando turno.
- **Sábados**: de 09:00 a 14:00 con 2 personas. Rotan todas por igual (2 sábados de cada 5) y siempre entra al menos una persona que pueda llevar el sábado (Ramiro, Lucía o Anastasia), de modo que Aizane y Lorena no coinciden solas.
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
