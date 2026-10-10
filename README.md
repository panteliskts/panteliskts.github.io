# panteliskts.github.io

The link page behind my NFC card: portfolio, LinkedIn, GitHub, Kaggle, email, CV, and a downloadable contact card.

Live at **https://panteliskts.github.io**. The full portfolio lives at [panteliskotsas.com](https://panteliskotsas.com).

## Structure

| File | Purpose |
| --- | --- |
| `index.html` | The whole page. Styles and script are inline so a tap loads in one request. |
| `pantelis-kotsas.vcf` | vCard behind "Save Contact". Opens the native "add contact" sheet on iOS and Android. |
| `404.html` | Not-found page. Also redirects old addresses (`/cv.pdf`, `/photos.html`) from the previous site. |
| `assets/` | Monogram, icons, the background video (portrait and landscape crops), posters, and the link-preview image. |

## Editing links

Each link is one `<li>` inside `<ul class="links">` in `index.html`. Copy a row, change the `href`, label, meta text, and icon (`#i-…` symbols are defined at the top of `<body>`). If you change contact details, update `pantelis-kotsas.vcf` as well.

The CV link points at the copy hosted on panteliskotsas.com, so it stays current without touching this repo.

## Deploy

GitHub Pages serves `main` from the repository root. Pushing to `main` publishes within a minute.

The previous portfolio site is preserved on the `legacy-portfolio` branch.
