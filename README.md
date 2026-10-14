# Todo App

A small browser Todo list: add tasks, mark them complete, delete them. Tasks are kept in the
browser's local storage. Plain HTML, CSS and JavaScript, no build step.

This is the shared codebase for SWEN-383 (Software Design Principles and Patterns) at RIT Kosovo.
Every student forks this repository in Week 1 and evolves it, week by week, as the course covers
new design principles and patterns.

## Running it

Open `index.html` with a live-reloading server, such as the VS Code "Live Server" extension, and it
runs in your browser. Nothing to install beyond Git, a browser, and an editor.

## Files

- `index.html` - page structure
- `style.css` - styling
- `src/TodoService.js` - task data, validation, task creation, and workload summary
- `src/TodoRenderer.js` - page rendering and callback-based row actions
- `src/LocalStorageHandler.js` - browser persistence through `load()` / `save(tasks)`
- `src/TodoController.js` - coordinates Add, Done/Undo, and Delete
- `src/main.js` - creates dependencies and wires input events
- `SMELLS.md` - three findings from the original Week 1 source, with line citations
- `docs/` - PlantUML diagrams, SVG previews, and completion/verification notes

## Weekly checkpoints

This fork is [ymorina/swen383-todo](https://github.com/ymorina/swen383-todo).
The original starter is [valonraca/swen383-todo](https://github.com/valonraca/swen383-todo).

Git tags preserve each design stage: `coursework/starter`, `coursework/week1`,
`coursework/week2`, `coursework/week3`, `coursework/week4`, and `coursework/week5`.
The Week 2 tag contains the original-code diagrams; the diagrams on `main`
describe the current implementation. Use `git show coursework/week2:docs/class-diagram.puml`
to inspect the original diagram without changing the working tree.

The feature branches are `feat/solid-refactoring`, `feat/grasp-controller`, and
`feat/w3-w4-refactor`. See [docs/COURSEWORK.md](docs/COURSEWORK.md) for the weekly
deliverables and GitHub Issues, and [docs/VERIFICATION.md](docs/VERIFICATION.md)
for the behavioral checks performed.

The OCP Issue stays open for Week 6, as required by the lab sheets.
The student handles the myCourses repository submission and team declaration;
teammates can be added to GitHub when their usernames are available.

## License

MIT - see `LICENSE`.
