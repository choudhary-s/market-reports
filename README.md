# Market Reports

## Medium import URL — configure this first

Set the URL below to the published `medium/` page for the report being imported. For example:

```text
https://choudhary-s.github.io/market-reports/2026-09-11/broad-market/medium/
```

Use this pattern for subsequent reports:

```text
https://choudhary-s.github.io/market-reports/YYYY-MM-DD/REPORT-SLUG/medium/
```

`YYYY-MM-DD` is the report date and `REPORT-SLUG` is the report category, such as `broad-market`, `automobiles`, or `financial-services`. Keep the trailing slash: it ensures relative chart-image paths resolve correctly during Medium's import.

## Repository layout

This repository is a public archive of Daily Market Intelligence reports and their Medium-ready pages. Keep each report in its date and category directory; do not use a `latest` directory.

```text
YYYY-MM-DD/
└── REPORT-SLUG/
    ├── charts/          # source chart assets, if retained
    ├── diagnostics.md   # report notes, if applicable
    └── medium/
        ├── index.html   # page imported into Medium
        └── images/      # every image referenced by index.html
```

Before publishing, place the final static HTML in `medium/index.html`, copy all referenced images to `medium/images/`, and use relative paths in the HTML, for example `images/nifty50-price.png`. Open the GitHub Pages URL once and confirm that the page and every chart load before starting the Medium import.

## GitHub Pages

Configure GitHub Pages to deploy from the `main` branch and repository root (`/`). After pushing the report files, wait for the deployment to finish, then use the published `medium/` URL above—not a local file path or a GitHub file-view URL.

## Prepare a Medium draft with Codex

1. Update the configurable URL at the top of this README for the report you are about to import. Confirm it opens publicly and that its images are visible.
2. In the Codex desktop app, open Chrome and use Medium's **Import a story** flow with that URL. Importing the public static page lets Medium create an editable draft while retaining the article structure and hosted chart images.
3. Review the imported draft from top to bottom. Check the title, section order, explanatory text, chart order, chart visibility, captions, links, and spacing. Correct only import-related presentation issues, such as an unintended heading level, extra blank line, or broken image placement.
4. Leave the completed draft open for review. Do not publish or schedule it, submit it to a publication, change the canonical URL, or change monetization settings.

If you want Codex to perform the import, replace the URL in this prompt and run it:

```text
Use @Chrome to open Medium and import https://choudhary-s.github.io/market-reports/YYYY-MM-DD/REPORT-SLUG/medium/ as a new story. Verify the title, section order, explanatory text, chart order, captions, links, and every chart image. Fix only formatting issues introduced by Medium. Stop with the completed draft open for my review. Do not publish, schedule, submit it to a publication, change the canonical URL, or change monetization settings.
```
