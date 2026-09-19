# Propuesta de Pickleball para el Colegio de Abogadas y Abogados de Costa Rica

Sitio estático en español para presentar un plan piloto de pickleball sencillo, medible y reversible.

## Pages setup

This branch is deployment-ready: `index.html` and all assets live at the repository root and use relative paths.

To publish manually, configure Pages to serve:

- Branch: `proposal-pages`
- Directory: `/ (root)`

If your BBGitHub instance only publishes the `gh-pages` branch, create `gh-pages` from this branch and select the branch root.

## Local preview

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Source material and photography

The site adapts `Law_School_Pickleball_Proposal_Benefits_Highlighted.docx`.

Photography is bundled locally so the page has no runtime image dependency:

- Pickleball photography by [Jon Matthews](https://unsplash.com/@jkmatt), used under the Unsplash License.
