# GenWealthDocs

GitBook documentation for [GenWealth](https://genwealth.app/) — self-custodial Cardano vaults for inheritance and crypto recovery.

## Publish with GitBook

1. Create or open a GitBook space.
2. Connect **Git Sync** to this repository (or import the markdown).
3. Use [`SUMMARY.md`](SUMMARY.md) as the table of contents.
4. Point the custom domain to **docs.genwealth.app** when ready (replacing [genwealth-3.gitbook.io](https://genwealth-3.gitbook.io)).

The reader-facing home page is [`README.md`](README.md) (Welcome).

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
