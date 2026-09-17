# Studio Amir

Bilingual architecture portfolio for Amir Nemati, designed for GitHub Pages.

## Continue the project

Read `HANDOFF.md` before making changes. The editable source is in `src/`, content is in `content/`, and the static website is in `docs/`. This repository is private while the preview is reviewed. No public deployment has been approved or verified yet.

Requirements: Node.js 22 or newer. There are no npm dependencies and no installation step.

```sh
npm run build
npm run check
npm run preview
```

Preview: http://127.0.0.1:4173

## Edit content

- `content/profile.json`: bilingual bio, contact information, social links and professional background.
- `content/projects.json`: projects, image captions, descriptions and metadata. Empty metadata means not supplied; never invent it.
- `content/settings.json`: navigation, default theme, optional pages, canonical deployment URL.
- `src/site.css`: design tokens, layouts and motion.
- `src/site.js`: theme transition, project orbit, filters, gallery, mobile menu.

Run the build after editing. The generated HTML is intentionally static: there is no public content editor, upload endpoint, database, tracking script or client-side secret.

## Deployment

After preview approval, set `baseUrl` to the actual Pages URL, rebuild, and publish the `docs` directory from the protected main branch. Private repository Pages availability depends on the account plan. Do not change repository visibility without checking what would become public.

## Rights

Portfolio images and generated marks were supplied or commissioned by the owner. No new public redistribution license is granted by this repository. Preserve original project and collaborator credits. Vazirmatn is bundled under the SIL Open Font License; see `licenses/`.
