# To-Do List

Minimal to-do list web app that lets you add and remove tasks.

## Files
- [Todo.html](Todo.html) — main HTML file.
- [Todo.css](Todo.css) — styling.
- [Todo.js](Todo.js) — behavior and logic.

## How to run
1. Open [Todo.html](Todo.html) in a web browser (double-click or use Live Server in VS Code).
2. Enter a task in the input field and click the "Add" button to create a task.
3. Click the trash icon next to a task to remove it.

## Implementation details
- The Add button calls the [`Add`](Todo.js) function defined in [Todo.js](Todo.js).
- The script uses the DOM references [`inputs`](Todo.js) and [`text`](Todo.js) to read the input and append task items.

## Notes & customization
- Styles are in [Todo.css](Todo.css). Modify colors, spacing, or fonts there.
- To add keyboard support (Enter key) or persist tasks, extend [Todo.js](Todo.js).

## License
MIT
