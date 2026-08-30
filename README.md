# Sainy

Personal website for Sainy, a software engineer, researcher, and product builder working from Thailand.

The site is a static HTML portfolio with selected work, research, writing, and links to relevant profiles.

## Live site

- GitHub Pages: https://sainytk.github.io/sainy-website/
- Custom domain: https://sainytk.com

## Run locally

Serve the directory with any static file server.

```sh
python3 -m http.server 4173 --directory sainy-website-html
```

Then open http://localhost:4173.

## Project structure

```text
.
├── assets/      Local images and the CV
└── index.html   The complete site and its styles
```

## Deployment

GitHub Pages publishes the root of the `main` branch.

Pushing changes to `main` deploys the static site.
