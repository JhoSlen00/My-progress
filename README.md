# Mi Progreso

Web app para medir mi avance diario en inglés, programación, ejercicio y lo que yo decida. Inspirada en la cuadrícula de contribuciones de GitHub.

**Abrir la app:** https://jhoslen00.github.io/My-progress/

## Funciones
- **Checklist diario** con tareas propias y días de la semana configurables
- **Cronómetro por área** con meta diaria; sigue contando aunque se cierre la app
- **Cuadrícula de actividad** de las últimas 18 semanas, con el detalle de cada día
- **Rachas y estadísticas**: racha actual, mejor racha, días activos, horas totales y horas de la semana por área
- **Respaldo** copiando y pegando los datos
- **Funciona sin internet** y se instala en el iPhone como app (PWA)

## Tecnología
HTML, CSS y JavaScript sin librerías. Los datos se guardan en `localStorage`; un service worker guarda la app en caché para usarla sin conexión.

## Instalar en iPhone
1. Abre el link en **Safari**.
2. Toca **Compartir** → **Agregar a pantalla de inicio**.
3. Deja activado **Abrir como app web** y toca **Agregar**.
