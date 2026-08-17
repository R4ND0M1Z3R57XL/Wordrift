# WordRift

**WordRift** is a free browser-based word scrambler and arrangement generator.

## Features

- Every Arrangement — generate possible arrangements.
- Random Arrangement — create a random rearrangement.
- Valid Words — find arrangements recognized as valid words.
- Arrangement Count — calculate possible arrangements.
- Fast browser-based processing.
- Responsive design.
- GitHub Pages compatible.
- No database, user accounts, AI, file storage, or complicated backend.

## How to use

1. Enter the letters or supported characters.
2. Choose a mode.
3. Click **Generate**.
4. Explore or copy the results.

Example:

```text
Input: CAT

CAT
CTA
ACT
ATC
TCA
TAC

Total: 6
```

For three unique characters:

```text
3! = 3 × 2 × 1 = 6
```

## How it works

WordRift uses permutation logic in JavaScript to generate arrangements directly in the browser.

For `n` unique characters, the maximum number of arrangements is `n!`.

Repeated characters are handled so duplicate arrangements can be avoided.

Valid Words mode can use an external dictionary service for live validation. External services remain subject to their own terms, licenses, limits, and attribution requirements.

## Run locally

No package manager or build process is required.

1. Download or clone the repository.
2. Open `index.html` in a modern browser.

## Deploy with GitHub Pages

1. Create a GitHub repository.
2. Upload the project.
3. Open **Settings → Pages**.
4. Select the `main` branch and root folder.
5. Save.
6. Open the GitHub Pages URL provided by GitHub.

## Project structure

```text
WordRift/
├── index.html
├── 404.html
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── CHANGELOG.md
├── robots.txt
├── sitemap.xml
└── assets/
    ├── wordrift-logo.png
    ├── wordrift-icon.svg
    └── wordrift-preview.png
```

## Privacy

WordRift is designed without user accounts or a database. Avoid entering sensitive information.

If live dictionary validation is enabled, word-validation requests may be sent to the external dictionary service. Check the site's Privacy Policy and the service's current documentation for details.

## License

Original WordRift source code is released under the MIT License. See `LICENSE`.

Third-party dictionaries, services, fonts, images, libraries, and other resources are not automatically covered by the WordRift license and remain subject to their own licenses and terms.

## Contributing

See `CONTRIBUTING.md`.

## Changelog

See `CHANGELOG.md`.

---

**WordRift — Generate. Scramble. Discover.**
