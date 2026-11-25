# Tim Haley Consulting

Website refresh for Tim Haley Consulting (thermal processing consulting). Scope, audiences,
pages and features are in `documents/PRD.md`.

## Design phase (now)

The work lives in `design/`: a living style guide (`design/index.html`) and page comps, plain
HTML and CSS with no build step.

- Tokens are CSS custom properties in `design/styles.css`; every page in `design/` uses only
  that stylesheet. Show each component once in the style guide and reuse it in comps.
- Copy comes from the PRD or the plan. No lorem ipsum, and no claims about Tim or his work that
  aren't in the PRD.
- Check with `static-check design` (every local link and asset exists).

## Later

The site itself will be a Prism CMS (Laravel + Filament) app at the repo root, built from the
style guide's tokens and components.
