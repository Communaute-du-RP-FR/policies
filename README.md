# Communauté du RP FR - Policies

This repository is the single source of truth for the legal documents (Privacy Policies and Terms of Service) of every bot operated by **Communauté du RP FR**.

## Structure

- [`docs/privacy/`](docs/privacy) — one Privacy Policy per bot, detailing what personal data is processed, why, how long it is kept, and how to request its deletion.
- [`docs/terms/`](docs/terms) — one Terms of Service per bot, defining the rules of use, liability, and other legal terms.

Each document is bilingual (French, then English) and named after its bot:

| Bot | Privacy Policy | Terms of Service |
| --- | --- | --- |
| Liste du RP FR | [docs/privacy/liste-du-rp-fr.md](docs/privacy/liste-du-rp-fr.md) | [docs/terms/liste-du-rp-fr.md](docs/terms/liste-du-rp-fr.md) |
| Moderator | [docs/privacy/moderator.md](docs/privacy/moderator.md) | [docs/terms/moderator.md](docs/terms/moderator.md) |
| Modmail | [docs/privacy/modmail.md](docs/privacy/modmail.md) | [docs/terms/modmail.md](docs/terms/modmail.md) |
| Restore | [docs/privacy/restore.md](docs/privacy/restore.md) | [docs/terms/restore.md](docs/terms/restore.md) |

## Why a dedicated repository

Each bot used to ship its own copy of these documents (or link to an external note-taking app), which made them easy to lose track of and to let drift out of sync with the actual code. Centralizing them here means:

- a single, versioned, linkable source for every document,
- one place to check when a bot's behavior changes and its policy needs updating,
- consistent cross-references between bots that share data or infrastructure (e.g. Moderator and Modmail both process ticket data referenced from Liste du RP FR's policy).

## Updating a document

When a bot's data handling changes, update the corresponding file(s) in `docs/privacy/` and, if relevant, `docs/terms/`. Each bot's own repository links to its documents here via their GitHub URL, so no changes are needed on the bot side once this repo is updated.

## Contact

Questions about any of these documents can be sent to:
- [martin.devolder2@gmail.com](mailto:martin.devolder2@gmail.com)
- [virgile.devolder2@gmail.com](mailto:virgile.devolder2@gmail.com)
