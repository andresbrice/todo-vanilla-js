# Proyecto 02 — Todo App

Aplicación de gestión de tareas construida con HTML, CSS y JavaScript vanilla.
Segundo proyecto del portfolio — primer proyecto implementado de principio a fin.

---

## Stack tecnológico

- **HTML5** semántico
- **CSS3** con variables, BEM, Flexbox y diseño responsivo
- **JavaScript ES6+** puro (sin frameworks ni librerías)
- **localStorage** para persistencia de datos
- **Quotable.io API** para frases motivacionales

---

## Lo que hace la aplicación

- Agregar, completar y eliminar tareas
- Limpiar todas las tareas completadas de una vez
- Filtrar por estado: todas / pendientes / completadas
- Ordenar por fecha o alfabéticamente
- Frase motivacional desde la API cuando no hay tareas
- Persistencia automática en localStorage (las tareas sobreviven al recargar)
- Sistema de notificaciones para feedback de acciones

---

## Estructura del proyecto

```
02-todo-vanilla-js/
├── index.html
├── css/
│   └── styles.css
└── js/
    ├── app.js       ← entrada y coordinación
    ├── store.js     ← estado de la aplicación
    ├── storage.js   ← lectura y escritura en localStorage
    ├── ui.js        ← manipulación del DOM
    └── api.js       ← llamadas a Quotable.io
```

---

## Demo

→ [Ver en vivo](https://andresbriceño.github.io/02-todo-vanilla-js/) *(disponible al hacer deploy)*

---

## Desarrollo local

Abrí `index.html` con Live Server desde VS Code.

> Requiere Live Server por el uso de ES6 modules (`type="module"`).
