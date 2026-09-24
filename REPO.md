# GenWealthDocs

GitBook documentation for [GenWealth](https://genwealth.app/) — self-custodial Cardano vaults for inheritance and crypto recovery.

## Publish with GitBook

1. Create or open a GitBook **site** with Git Sync to this repository.
2. Root [`gitbook-docs.yaml`](gitbook-docs.yaml) defines **one space** (`space-docs`) whose content is the repository root (`./`).
3. [`SUMMARY.md`](SUMMARY.md) is the single table of contents (whitepaper first, then get started, guides, how it works, team).
4. Point the custom domain to **docs.genwealth.app**.

Do not split the book into one space per folder unless you also add a per-folder `SUMMARY.md` and accept separate sidebars — that is what made only “Cardano and wallets” appear before.

## SEO and LLM files

| File | Purpose |
| --- | --- |
| [`robots.txt`](robots.txt) | Allow crawlers; point to the sitemap |
| [`sitemap.xml`](sitemap.xml) | Canonical URL list for `https://docs.genwealth.app` |
| [`llms.txt`](llms.txt) | Structured index for language models |

Keep these in sync when you add or rename pages. GitBook also generates sitemap / llms exports from the published space; page titles and `description` frontmatter make those exports useful.

## Source of truth

User guides and **How GenWealth works** follow the GenWealth UI and Cardano contracts. The whitepaper keeps the company narrative and is corrected where the product has moved on.

Do not commit secrets, private keys, or internal fee schedules meant only for demos.
