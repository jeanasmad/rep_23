# ORBIT

Tablero personal de gestión basado en una matriz de Eisenhower, Kanban y burndown semanal.

## Funciones

- 46 tareas iniciales tomadas de la matriz de trabajo.
- Backlog organizado en cuatro cuadrantes Eisenhower.
- Drag & drop entre cuadrantes y estados Kanban.
- Estimación de esfuerzo en horas.
- Conversión automática de esfuerzo a puntos Fibonacci:
  - ≤ 0.5 h → 1 pt
  - ≤ 1 h → 2 pt
  - ≤ 2 h → 3 pt
  - ≤ 4 h → 5 pt
  - ≤ 8 h → 8 pt
  - > 8 h → 13 pt
- Al pasar una tarea a `Done`, se registra su peso y fecha.
- Burndown semanal con línea ideal y trabajo restante real.
- Persistencia local mediante `localStorage`.
- Sin backend ni dependencias externas.

## Uso

La aplicación es un sitio estático: abrir `index.html` es suficiente. Los cambios se guardan en el navegador.

Doble clic sobre una tarjeta para editarla.
