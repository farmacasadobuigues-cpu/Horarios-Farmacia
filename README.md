# Farmacia Carlos Casado Buigues · Cuadrante de turnos

Aplicación web para organizar los turnos del equipo de una farmacia comunitaria y las guardias.

Abre `index.html` en cualquier navegador: no necesita instalación ni servidor. Los datos se guardan en el propio navegador (en **Ajustes** puedes copiarlos como copia de seguridad o pasarlos a otro equipo).

## Qué hace

- **Cuadrante semanal**: horario de 12 h dividido en mañana y tarde (09:00–15:00 y 15:00–21:00 por defecto). Genera automáticamente 3 personas por turno con al menos un farmacéutico, y reparte la responsabilidad de cada uno: mostrador, administración o gestión. Todo se puede cambiar a mano y avisa si un turno queda incompleto, sin farmacéutico, con alguien doblando turno o con quien sale de guardia.
- **Ahora**: quién está trabajando en este momento y qué hace (o quién está de guardia).
- **Equipo**: dar de alta y de baja con roles (titular, farmacéutico adjunto, auxiliar, estudiante en prácticas). No permite dar de baja al último farmacéutico adjunto. Al dar de baja a alguien se reasignan sus turnos y guardias pendientes.
- **Guardias**: nocturnas o de 24 h, con reparto automático equilibrado entre farmacéuticos.
- **Ajustes**: hora de apertura, días que abre la farmacia y copia de seguridad.

Los estudiantes en prácticas van como refuerzo tutorizado y no cuentan para las 3 personas mínimas.

## Equipo inicial

| Nombre | Rol | Turno |
|---|---|---|
| Ramiro González | Farmacéutico adjunto | Mañana |
| Lucía Rojo | Técnico en farmacia | Tarde |
| Anastasia | Auxiliar | Mañana |
| Aizane | Auxiliar | Mañana |
| Lorena | Auxiliar | Tarde |

Hasta la temporada alta se trabaja con 3 personas de mañana y 2 de tarde (se cambia en Ajustes).
