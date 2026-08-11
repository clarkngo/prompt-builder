# Prompt Workshop

Static site of interactive **prompt builders** for educators — ready to deploy on GitHub Pages.

## Pages

| Page | Path | Purpose |
|------|------|---------|
| Home | [`index.html`](index.html) | Landing page and builder directory |
| Educator | [`builders/educator.html`](builders/educator.html) | Prompts for interactive HTML activities or text assignments |
| Academic | [`builders/academic.html`](builders/academic.html) | Prompts for institutional / professional writing |
| Lesson | [`builders/lesson.html`](builders/lesson.html) | Prompts that draft full OT & cybersecurity lesson pages |
| Graphics | [`builders/graphics.html`](builders/graphics.html) | Prompts for instructional diagrams, flowcharts, and classroom visuals |
| Cheatsheets | [`builders/cheatsheets.html`](builders/cheatsheets.html) | Prompts for glossaries, term tables, and quick-reference handouts |
| Activities | [`builders/activities.html`](builders/activities.html) | Prompts for labs, simulations, discussions, and classroom exercises |

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## GitHub Pages

This repo includes [`.github/workflows/static.yml`](.github/workflows/static.yml), which deploys the site on pushes to `main`.

1. In the GitHub repo: **Settings → Pages → Source: GitHub Actions**
2. Push to `main` (or run the workflow manually)
3. Visit the Pages URL once the deploy finishes

All links are relative so the site works at both `username.github.io` and `username.github.io/prompt-builder/`.

## Design notes

- Shared styles: `assets/css/site.css`
- No build step — plain HTML, CSS, and vanilla JS
- Source/reference HTML lives in `references/` (not required to run the site)
