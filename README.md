# Market Reports

Public archive of Daily Market Intelligence reports prepared for GitHub Pages and Medium import.

## Publishing layout

Store every report under its report date. Do not use a `latest` directory.

```text
YYYY-MM-DD/
├── index.html
└── images/
    └── chart files
```

For example:

```text
2026-09-11/
├── index.html
└── images/
```

The public report URL will be:

```text
https://choudhary-s.github.io/market-reports/YYYY-MM-DD/
```

Copy the Medium-ready static HTML to `YYYY-MM-DD/index.html` and copy every image it references to `YYYY-MM-DD/images/`. Image paths inside the HTML should be relative, such as `images/nifty50-price.png`.

## GitHub Pages

Configure Pages to deploy from the `main` branch and the repository root (`/`).

## Prepare a Medium draft with Codex

In the Codex desktop app, replace the date in this prompt and run it:

```text
Use @Chrome to open Medium and import https://choudhary-s.github.io/market-reports/YYYY-MM-DD/ as a new story. Verify the title, index order, explanatory text, and every chart image. Fix only formatting issues introduced by Medium. Stop with the completed draft open for my review. Do not publish, schedule, submit it to a publication, change the canonical URL, or change monetization settings.
```
