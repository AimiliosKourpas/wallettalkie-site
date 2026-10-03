# Wallet Talkie — public website

Static pages for the Wallet Talkie app: a home page, the Privacy Policy, the Terms of Use, and Support.

This repository is separate from the Wallet Talkie mobile app. It contains no app code, no build tooling and no secrets.

## Structure

```
index.html            home page
privacy/index.html    Privacy Policy
terms/index.html      Terms of Use
support/index.html    Support and FAQ
404.html              not-found page (uses a <base href> for project hosting)
assets/site.css       the only stylesheet
assets/icon-512.png   derived copy of the app icon
assets/icon-180.png   derived copy of the app icon
.nojekyll             tells GitHub Pages to serve the files as they are
```

## Rules for this repository

- Static HTML and CSS only. No JavaScript, analytics, cookies, forms, trackers, or external fonts or scripts.
- Use relative links, so the site works under a GitHub Pages project URL.
- Do not add anything that talks to a server, and do not put keys, tokens or other secrets here.
- The mobile app's original icon is not stored here as the source of truth. The icons are copies made from the app's `assets/icon.png`.

## Publishing

GitHub Pages deploys from the `main` branch, root folder. There is no build step.

Update the "Last updated" date on the Privacy Policy and the Terms whenever their text changes.

## Contact

wallettalkie@gmail.com
