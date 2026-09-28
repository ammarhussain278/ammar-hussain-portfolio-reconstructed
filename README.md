# Ammar Hussain Portfolio — reconstructed editable source

This folder is an **editable reconstruction** of the published portfolio at:

https://ammar-hussain-design.uzain818062.chatgpt.site/

## Important provenance note

The ChatGPT Site Library entry is a **Site projection** and does not expose the original uncompiled project folder through the available export/materialization interface. The public deployment was inspected to recover its routes, copy structure, project metadata and public visual asset URLs. This reconstruction is therefore intended for continued editing in Codex/VS Code, not as a claim that these are the exact original source files.

## Included

- Astro 4.5.3 static site project
- Homepage
- `/work` index
- All 26 project routes via `src/pages/work/[slug].astro`
- Central project data in `src/data/projects.js`
- Responsive styling in `src/styles/global.css`
- Current public project images referenced from the live `chatgpt.site` deployment
- Current public project PDF links

## Run

```bash
npm install
npm run dev
```

Production build:

```bash
npm run build
npm run preview
```

## Best place for Codex to edit

- `src/data/projects.js` — projects, titles, descriptions, image URLs
- `src/pages/index.astro` — homepage structure
- `src/pages/work/[slug].astro` — case-study template
- `src/styles/global.css` — visual system

## Assets

Images currently use absolute URLs from the existing published site so the reconstructed project remains lightweight and visually connected to the live portfolio. For a fully independent deployment, download those assets into `public/work/...` and replace the absolute URLs with local paths.

## Existing published-site facts recovered

- 26 work routes
- Project categories/descriptions
- Homepage service/about/process copy
- Public project image naming patterns
- Public project PDF naming patterns
- Portfolio PDF URL

## Publication-specialization work

This source is ready for the planned **eBook, Book & Publication Design** expansion. Codex can add that specialization by editing the project data and templates without rebuilding the website from scratch.
