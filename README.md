# Todo App

Task management app built with HTML, CSS and vanilla JavaScript.

---

## Tech Stack

- **HTML5** semantic markup
- **CSS3** with variables, BEM, Flexbox and responsive design
- **Vanilla JavaScript ES6+** (no frameworks or libraries)
- **localStorage** for data persistence
- **Quotable.io API** for motivational quotes

---

## Features

- Add, complete and delete tasks
- Clear all completed tasks at once
- Filter by status: all / pending / completed
- Sort by date or alphabetically
- Motivational quote from the API when there are no tasks
- Automatic persistence in localStorage (tasks survive page reload)
- Notification system for action feedback

---

## Project Structure

```
todo-vanilla-js/
├── index.html
├── css/
│   └── styles.css
└── js/
    ├── app.js       ← entry point and coordination
    ├── store.js     ← application state
    ├── storage.js   ← localStorage read/write
    ├── ui.js        ← DOM manipulation
    └── api.js       ← Quotable.io calls
```

---

## Demo

→ [Live demo](https://andresbrice.github.io/todo-vanilla-js/) *(available after deploy)*

---

## Local Development

Open `index.html` with Live Server from VS Code.

> Requires Live Server due to ES6 modules (`type="module"`).
