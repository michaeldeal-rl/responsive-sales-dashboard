# Claude Project Instructions

## Project overview
This repository is a responsive sales dashboard built with plain HTML, CSS, and JavaScript. It is a front-end-only project with no framework, bundler, or backend.

## Important files
- `index.html` — page structure and dashboard layout
- `css/styles.css` — dashboard styling, spacing, colors, and responsiveness
- `js/scripts.js` — sidebar behavior and ApexCharts configuration

## Working style
- Keep changes small and focused.
- Preserve the existing dark admin-dashboard design.
- Prefer vanilla JavaScript and CSS rather than introducing frameworks or build tooling.
- Maintain responsive behavior for smaller screens.
- Reuse the existing DOM IDs, classes, and chart conventions.

## Common edits
- Update statistics cards in `index.html`.
- Adjust chart data or labels in `js/scripts.js`.
- Tune layout, colors, or spacing in `css/styles.css`.

## Validation
- Run the app using Live Server in VS Code.
- Review it in the browser at `http://127.0.0.1:5500/index.html`.
- Confirm the sidebar toggle and charts still render correctly after changes.
