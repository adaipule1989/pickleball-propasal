# Law School Pickleball Pilot Proposal

A static, decision-focused website presenting a reversible pickleball pilot for a law school community.

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

The site adapts `Law_School_Pickleball_Proposal_Benefits_Highlighted.docx`. Embedded proposal diagrams are included under `assets/document-images/`.

Photography is bundled locally so the page has no runtime image dependency:

- “Pickleball Players” by TheVillagesFL, CC BY-SA 4.0, via Wikimedia Commons.
- “Willy Chung playing pickleball” by EasonChou0621, CC0, via Wikimedia Commons.
Repo for pickleball proposale
