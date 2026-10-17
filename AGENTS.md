# Project rules

- Keep the quiz self-contained in `index.html`; do not add a server, build step, or dependency unless the project requirements change.
- Keep question content in the shared `questions` array. Avoid duplicating quiz data in rendering or result logic.
- Keep HTML structure, CSS styling, and JavaScript behavior clearly separated within the file. Use descriptive names and small functions with one responsibility.
- Prefer shared CSS variables and existing UI patterns over repeated values or one-off styling.
- Preserve keyboard access, semantic controls, readable contrast, responsive layout, reduced-motion support, and light/dark theme support when changing the UI.
- Handle quiz state in one place; keep score, progress, answer feedback, results, and restart behavior consistent.
- Add comments only to explain non-obvious decisions. Avoid unrelated changes and unnecessary abstractions.
- After behavior changes, smoke-test answering correctly and incorrectly, score/progress updates, results, and restart in the browser. Check keyboard focus and light/dark appearance when practical.
