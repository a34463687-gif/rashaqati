# Rashaqati Agent Architecture & Conventions

## Architecture Overview
- **Type**: Static website (HTML5 / Vanilla CSS / RTL Arabic) deployed directly on Netlify.
- **Entry Point**: `index.html`.
- **Form Handling**: Native Netlify Forms with bot-field honeypot enabled.
- **Headers & Routing**: Managed via `netlify.toml`.

## Key Files
- `index.html`: Main landing page containing articles, product review card, medical disclaimer, and contact form.
- `favicon.svg`: Brand leaf & wellness logo vector icon.
- `netlify.toml`: Header security directives and cache configurations.
