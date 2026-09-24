# Copilot Instructions for Responsive Sales Dashboard

## Project overview
This repository contains a responsive admin-style sales dashboard built with vanilla HTML, CSS, and JavaScript. It is a front-end-only project with no framework, bundler, or backend.

## Stack and file map
- HTML entry page: `index.html`
- JavaScript logic: `js/scripts.js`
- Stylesheet: `css/styles.css`
- Charts are rendered with ApexCharts from a CDN
- The app is meant to be served locally with Live Server in VS Code

## Working conventions
- Prefer small, targeted changes over broad rewrites.
- Keep the code vanilla, readable, and consistent with the existing structure.
- Preserve the dark dashboard theme and responsive layout behavior.
- Use the existing DOM IDs and CSS classes when adding UI updates or chart logic.
- When modifying charts, keep the configuration object style and legend/axis settings consistent with the current implementation.
- Avoid adding frameworks, build tooling, or package dependencies unless explicitly requested.

## Common tasks
- Update chart data or labels in `js/scripts.js`.
- Adjust layout, spacing, or colors in `css/styles.css`.
- Update cards or sidebar content in `index.html`.
- Keep functionality simple and dependable for a static local dashboard.

## Validation
- Run the app using Live Server and review the page in the browser.
- The project is normally previewed at `http://127.0.0.1:5500/index.html`.
- Verify that sidebar toggling and chart rendering still work after edits.
