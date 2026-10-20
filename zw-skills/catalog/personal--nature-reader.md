# nature-reader

Create source-grounded Chinese-English full-paper readers with figures, tables, and equations.

[Back to catalog](../README.md)

## Usage

Create source-grounded Chinese-English full-paper readers with figures, tables, and equations.

```text
Use $nature-reader to create a full Chinese-English reader for this PDF.
```

## Installation and links

Install the selected complete package and its sibling support dependencies. Current upstream may differ from this local snapshot.

```text
Use $skill-installer to install nature-reader and nature-shared from Yuan1z0825/nature-skills at skills/nature-reader and skills/nature-shared. Use ref 745c5f38d1b4a0600bd2f5f5682e394a34fc28b2 for the recorded snapshot, or main for the current upstream version.
```

- [Nature collection at recorded installation commit](https://github.com/Yuan1z0825/nature-skills/tree/745c5f38d1b4a0600bd2f5f5682e394a34fc28b2/skills) — opened public tree matching local receipt.
  Recorded upstream commit: `745c5f38d1b4a0600bd2f5f5682e394a34fc28b2`.
- [Nature collection installation guide](https://github.com/Yuan1z0825/nature-skills/blob/main/README_EN.md) — opened public page.
- [Codex skill documentation](https://learn.chatgpt.com/docs/build-skills) — opened public page.

## Local inventory

- App: Codex.
- Type: `personal`.
- Status: `installed_manifest`.
- Manifest/location: `~/.codex/skills/nature-reader/SKILL.md`.
  Declared version: `2.1.0`.
  Manifest SHA-256: `fb93710f348498f5e83aa4ef90761ee0fdc67cc0adc3c0aca7d3302074c6f71c`.

## Dependencies

- Related/support package: [nature-shared](personal--nature-shared.md).
- Python. Mentioned in `~/.codex/skills/nature-reader/static/core/output-contract.md`; workflow dependent and not runtime-tested.

## Subskills and commands

These belong to the parent package. Workflow variants are not independent installations.

| Name | Type / group | Package-relative definition | How to use |
| --- | --- | --- | --- |
| `pdf-text` | workflow_variant / source_format | `static/fragments/source/pdf-text.md` | Select this variant through the parent skill; not a separately registered skill. |
| `scanned-pdf` | workflow_variant / source_format | `static/fragments/source/scanned-pdf.md` | Select this variant through the parent skill; not a separately registered skill. |
| `html` | workflow_variant / source_format | `static/fragments/source/html.md` | Select this variant through the parent skill; not a separately registered skill. |
| `doi-arxiv` | workflow_variant / source_format | `static/fragments/source/doi-arxiv.md` | Select this variant through the parent skill; not a separately registered skill. |
| `pasted-text` | workflow_variant / source_format | `static/fragments/source/pasted-text.md` | Select this variant through the parent skill; not a separately registered skill. |

Supporting resource counts: references: 5, scripts: 1, agents: 1.

## Notes

- The recorded installation commit was recovered in the public repository. Local files may have changed after installation; no whole-package equality claim is made.
