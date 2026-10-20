# Wajid Khan — AI Product Portfolio

A static portfolio with a rotating 3D system visual, responsive layout, project details, an expertise explorer, and email and LinkedIn contact links.

## Run locally

From this directory:

```sh
python3 -m http.server 8080
```

Open http://localhost:8080.

## Host anywhere

- Branch: `ai-portfolio`
- Project/root directory: repository root
- Framework: none (static HTML)
- Build command: none
- Publish/output directory: `.` (repository root)

Upload `index.html`, `style.css`, and `app.js` together, or connect this repository to a static host and select the `ai-portfolio` branch. No package installation, server, API keys, environment variables or build step is required.

## Edit

- `index.html`: page content, contact links, outcome metrics and section structure.
- `style.css`: colours, typography, layout and mobile styles.
- `app.js`: 3D canvas rendering, project/skill detail content, accessible tabs and dialogs.

Fonts load from Google Fonts, with local fallback fonts if unavailable. The 3D scene is rendered with Canvas using projected 3D coordinates; it has no external JavaScript dependencies. Reduced-motion preferences and a pause button are supported.

## Validation

JavaScript syntax and static checks for contact links, section anchors, unique IDs and all nine detail-panel targets passed. Visual browser testing has not yet been completed.

This branch contains the new portfolio; the repository's existing `main` branch is unchanged. The code is independent of the original Sites hosting service.
