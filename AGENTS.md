# AGENTS.md

## Project overview
- This repository is a static personal website built with plain HTML and CSS.
- Pages live at the repository root (for example, `index.html`, `career.html`, `cures.html`, `teaching.html`).
- Shared styling is centralized in `styles.css`.
- Supporting assets such as PDFs, images, and student work are stored under `files/`.

## Working conventions
- Keep changes small and targeted. This project is mostly content-driven; prefer direct edits to existing page structure instead of introducing frameworks or build tooling.
- Preserve the current visual identity: clean academic layout, red/white theme, centered content, and simple static-page behavior.
- Maintain accessibility and mobile-friendliness. Favor semantic HTML, descriptive link text, and layouts that still work on narrow screens.
- When editing or adding pages, keep filenames consistent with the site's existing style and update any relevant navigation links.
- Prefer relative links that work from the repository root and keep asset paths valid.

## Commit and review expectations
- Keep commits concise and specific. A good commit message explains the intent in one short sentence, not a long narrative.
- Prefer one logical change per commit: content update, styling fix, or file cleanup.
- For code review, be thorough: check markup correctness, CSS impact, broken links, missing assets, and regressions in page layout or responsiveness.
- Review for whether a change matches the academic tone and site purpose; avoid unnecessary complexity or decorative patterns that conflict with the established minimal style.
- If a page is updated, verify the change does not break nearby pages or shared styling.

## Useful commands
- There is no application build step for this project; the site is served as static files.
- Local verification should be done by opening the HTML pages in a browser or using a simple static web server if needed.

## Notes for future agents
- Do not assume a framework is present. This repository is intentionally lightweight.
- Keep edits close to the existing patterns in the HTML and CSS rather than rewriting the site structure.
- If a task involves new student-facing content, preserve the tone and clarity expected for an academic department webpage.
