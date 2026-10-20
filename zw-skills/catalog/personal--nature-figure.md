# nature-figure

Create and audit scientific plots, manuscript figures, and graphical abstract drafts.

[Back to catalog](../README.md)

## Usage

Create and audit scientific plots, manuscript figures, and graphical abstract drafts.

```text
Use $nature-figure with Python to create a publication-ready figure from results.csv.
```

## Installation and links

Install the selected complete package and its sibling support dependencies. Current upstream may differ from this local snapshot.

```text
Use $skill-installer to install nature-figure and nature-shared from Yuan1z0825/nature-skills at skills/nature-figure and skills/nature-shared. Use ref 745c5f38d1b4a0600bd2f5f5682e394a34fc28b2 for the recorded snapshot, or main for the current upstream version.
```

- [Nature collection at recorded installation commit](https://github.com/Yuan1z0825/nature-skills/tree/745c5f38d1b4a0600bd2f5f5682e394a34fc28b2/skills) — opened public tree matching local receipt.
  Recorded upstream commit: `745c5f38d1b4a0600bd2f5f5682e394a34fc28b2`.
- [Nature collection installation guide](https://github.com/Yuan1z0825/nature-skills/blob/main/README_EN.md) — opened public page.
- [Codex skill documentation](https://learn.chatgpt.com/docs/build-skills) — opened public page.

## Local inventory

- App: Codex.
- Type: `personal`.
- Status: `installed_manifest`.
- Manifest/location: `~/.codex/skills/nature-figure/SKILL.md`.
  Declared version: `2.6.0`.
  Manifest SHA-256: `4e159bb7284cff2c10a1ac2c74f605f8d526f5c819b25c4d1aecf01ba2367d44`.

## Dependencies

- Related/support package: [nature-shared](personal--nature-shared.md).
- Python. Mentioned in `~/.codex/skills/nature-figure/SKILL.md`; workflow dependent and not runtime-tested.
- R plotting runtime. Mentioned in `~/.codex/skills/nature-figure/SKILL.md`; workflow dependent and not runtime-tested.

## Subskills and commands

These belong to the parent package. Workflow variants are not independent installations.

| Name | Type / group | Package-relative definition | How to use |
| --- | --- | --- | --- |
| `python` | workflow_variant / backend | `static/fragments/backend/python.md` | Select this variant through the parent skill; not a separately registered skill. |
| `r` | workflow_variant / backend | `static/fragments/backend/r.md` | Select this variant through the parent skill; not a separately registered skill. |
| `graphical_abstract_workflow` | workflow_route | `references/ai-graphical-abstract-workflow.md` | Request this workflow through the parent skill. |
| `openrouter_image_generation` | workflow_route | `references/openrouter-image-generation.md` | Request this workflow through the parent skill. |

Supporting resource counts: references: 19, scripts: 6, assets: 85, agents: 1.

## Notes

- The recorded installation commit was recovered in the public repository. Local files may have changed after installation; no whole-package equality claim is made.
