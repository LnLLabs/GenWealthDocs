# GenWealthDocs

Documentation for [GenWealth](https://genwealth.app/) — self-custodial Cardano vaults for inheritance and crypto recovery.

**Published site:** [https://lnllabs.github.io/GenWealthDocs/](https://lnllabs.github.io/GenWealthDocs/)

## Local preview

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/).

## Build

```bash
mkdocs build
```

Static files land in `site/`. GitHub Actions builds and deploys that folder to GitHub Pages on every push to `main`.

See [REPO.md](REPO.md) for structure and publishing notes.
