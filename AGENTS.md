# Project rules

- Keep the quiz self-contained in `index.html`; do not add a server, build step, or dependencies.
- Use semantic HTML and native controls. Preserve keyboard access, visible focus, and clear accessible status updates.
- Keep the responsive, narrow-column layout and support both `prefers-color-scheme` themes.
- Respect `prefers-reduced-motion` for animations and transitions.
- Keep quiz questions, scoring, progress, feedback, results, and restart behavior working together.
- After UI or behavior changes, smoke-test the quiz in the integrated browser, including answer feedback and results.
