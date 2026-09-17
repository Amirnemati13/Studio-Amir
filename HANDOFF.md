# Continuation record — 2026-09-17

## Owner and objective

- Owner: Amir Nemati, GitHub `Amirnemati13`.
- Brand: **Studio Amir**.
- User wants a professional English/Persian architecture portfolio on GitHub Pages, black/white themes, interactive project orbit around his full-body portrait, subtle motion, static pages, straightforward file editing, and strong protection against unauthorized changes.
- User specifically requested durable GitHub storage so work can resume after account usage limits. Keep this record updated with each substantive change.

## Confirmed decisions

- English default, Persian RTL.
- Dark project thumbnails on the clickable orbit; generated pictograms are available as supplementary marks.
- ARCHIVED ONLY — user removed homepage video. Portrait video starts with image 2 (white outfit/background, looking screen-right) and ends with image 1 (black background, looking screen-left). Higgsfield result is H.264, 1216x1632, 24fps, 5.042 seconds, no audio.
- Contact: `nematia13@gmail.com`, `+989210205126`. These replace older contact details in CVs.
- Social links were provided by the user and decoded from Instagram redirect URLs. Their page contents were not independently verified.
- Before public deployment, present the completed preview and active feature list for approval, per the user's supplied brief. Creating and backing up a PRIVATE repository is authorized now.

## Assets and exclusions

- Source folder on the owner's PC: `C:/Users/Amir/Desktop/WEB-AMIR`.
- 109 original files, all kept unchanged.
- 87 monochrome PNG/WebP conversions were previously created. This was conservative deterministic conversion, NOT a complete vector-like restyle. 31 full-scene renders retain their environment rather than a fully black background. Do not claim perfect compliance.
- Never recolor or generate replacements for contents of: `جوایز و تقدیر نامه ها`, `Sketches and Painting`, `marx pele-مارکس پله`, `cv`.
- Original assets from excluded folders used on the site are byte copies. CVs were read for profile copy; full CVs are not in the public site.
- Genuine vector architectural sources were not found. The Neighbourhood Center PDF is a raster image; do not mislabel it SVG.
- 9 proposed project marks and 6 category icons made in Higgsfield are RASTER assets, not official logos or vector SVGs. They are supplementary symbols, not replacements for original architectural drawings.

## Current implementation

- `docs/` contains 40 static bilingual pages: home, projects, about, services, contact, team, journal and 13 individual collections in each language.
- Project search/filter/sort, native modal lightbox, mobile menu, local theme preference, portrait transition, orbital project links and reduced-motion handling are implemented.
- Team/journal navigation is hidden by default because real team/article content has not been provided. Empty journal is explicit.
- Contact uses email/phone links, no fake form.
- Font is locally hosted Vazirmatn with OFL. Browser scripts/styles/media are local.
- Security CSP is set in HTML; no third-party execution, forms, embedded objects or runtime data fetches.
- Build and static validation pass. Desktop portrait light/dark preview inspected; mobile and Persian typography refinements applied. Final functional QA and live verification still required.
- `scripts/check.mjs` exists and passes 41 HTML pages, asset/link references, metadata, CSP, contact data, and secret-pattern checks.

## GitHub state

- Private repository created in authenticated browser: https://github.com/Amirnemati13/Studio-Amir
- The GitHub connector authenticated profile is Amirnemati13, but its initial accessible repository list was empty. Browser login has been completed by the owner.
- Local preview server was started on 127.0.0.1:4173.
- Public Pages deployment, repository rules, security options and account 2FA have NOT yet been verified/configured. Never claim otherwise.

## Content cautions

- CVs disagree on precise employment and award dates. Use undated verified employer names until reconciled.
- Do not infer a master's degree from an empty heading in an English CV.
- Do not invent project authorship, team, construction status, size, client testimony, award titles or counts.
- Project descriptions are short proposed descriptions based on supplied visual material, not externally verified project specifications.

## Next work

1. Complete GitHub checkpoint upload including source, content and recoverable site assets.
2. Run static validation and inspect the existing site in desktop/mobile English/Persian.
3. Fix layout, motion, navigation and CSP issues found by QA.
4. Inspect repository collaborators/security/Pages capability. Do not disable safeguards or expose private archives.
5. Show final preview; obtain the user-requested public-publication approval.
6. Publish, verify HTTPS/live pages, then record URL and deployment status here.

## Latest steering and actual status

- User approved the design and requested final publication. No further design approval needed.
- User requires a PUBLIC website URL with PRIVATE GitHub repository. GitHub Pages settings currently require an account upgrade. User chose to upgrade their account themselves; do not switch hosts or expose repository.
- Homepage video removed. Uses original complete photo background plate plus a foreground occlusion layer for orbit depth. Light background now pure white. Theme fades 500ms; originals untouched.
- Persian typography now has a separate smaller scale and mobile rules.
- First private commit confirmed: 45d3497d6a991bbc697ca808b37eef8ebe5bd5b5 (README, checkpoint.json, restore.mjs only). Archive segments were NOT yet confirmed committed. User clicked Commit before transfer completed; retry individually and verify.
- Initial archive segments predate these fixes. Restore base archive then overlay latest-source.zip (when uploaded). Do not claim full recovery until all segments are registered.
- Original 109-file source collection and full high-resolution output collection remain local; NOT fully backed up to GitHub yet.
