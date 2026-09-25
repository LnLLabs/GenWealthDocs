# GenWealthDocs

MkDocs Material documentation for [GenWealth](https://genwealth.app/) — self-custodial Cardano vaults for inheritance and crypto recovery.

## Publish with GitHub Pages

1. Markdown under [`docs/`](docs/) is the site content (`docs_dir: docs` in [`mkdocs.yml`](mkdocs.yml)).
2. Navigation lives in `mkdocs.yml` (`nav`).
3. Push to `main`. [`.github/workflows/pages.yml`](.github/workflows/pages.yml) builds with MkDocs and deploys `site/`.
4. In the GitHub repo: **Settings → Pages → Source → GitHub Actions**.

Site URL: [https://lnllabs.github.io/GenWealthDocs/](https://lnllabs.github.io/GenWealthDocs/). A custom domain such as `docs.genwealth.app` can be added later with a `CNAME` in this repo and DNS at the registrar.

## SEO and LLM files

| File | Purpose |
| --- | --- |
| [`docs/robots.txt`](docs/robots.txt) | Allow crawlers; point to the sitemap |
| [`docs/llms.txt`](docs/llms.txt) | Structured index for language models |

MkDocs emits `sitemap.xml` into `site/` on each build. Keep `robots.txt` and `llms.txt` URLs in sync when pages are added or renamed. Page `description` frontmatter is used for meta tags by Material for MkDocs.

## Source of truth

User guides and **How GenWealth works** follow the GenWealth UI and Cardano contracts. The whitepaper keeps the company narrative and is corrected where the product has moved on.

Theme colors match the GenWealth app dark palette ([`docs/stylesheets/extra.css`](docs/stylesheets/extra.css)).

Do not commit secrets, private keys, or internal fee schedules meant only for demos.
