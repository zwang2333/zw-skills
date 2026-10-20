# nature-paper2ppt

Build a Chinese scientific presentation from a paper, with figures, speaker notes, and layout checks.

[Back to catalog](../README.md)

## Usage

Build a Chinese scientific presentation from a paper, with figures, speaker notes, and layout checks.

```text
Use $nature-paper2ppt to turn this paper into a Chinese journal-club presentation.
```

## Installation and links

Install the selected complete package and its sibling support dependencies. Current upstream may differ from this local snapshot.

```text
Use $skill-installer to install nature-paper2ppt and nature-shared from Yuan1z0825/nature-skills at skills/nature-paper2ppt and skills/nature-shared. Use ref 745c5f38d1b4a0600bd2f5f5682e394a34fc28b2 for the recorded snapshot, or main for the current upstream version.
```

- [Nature collection at recorded installation commit](https://github.com/Yuan1z0825/nature-skills/tree/745c5f38d1b4a0600bd2f5f5682e394a34fc28b2/skills) — opened public tree matching local receipt.
  Recorded upstream commit: `745c5f38d1b4a0600bd2f5f5682e394a34fc28b2`.
- [Nature collection installation guide](https://github.com/Yuan1z0825/nature-skills/blob/main/README_EN.md) — opened public page.
- [Codex skill documentation](https://learn.chatgpt.com/docs/build-skills) — opened public page.

## Local inventory

- App: Codex.
- Type: `personal`.
- Status: `installed_manifest`.
- Manifest/location: `~/.codex/skills/nature-paper2ppt/SKILL.md`.
  Declared version: `2.0.0`.
  Manifest SHA-256: `945136f112001f3584360956a3dc8c98575bc426b7252e2fd0ccc4abc30e77a8`.

## Dependencies

- Related/support package: [nature-shared](personal--nature-shared.md).
- Python. Mentioned in `~/.codex/skills/nature-paper2ppt/SKILL.md`; workflow dependent and not runtime-tested.
- LibreOffice. Mentioned in `~/.codex/skills/nature-paper2ppt/static/core/toolchain.md`; workflow dependent and not runtime-tested.

## Subskills and commands

These belong to the parent package. Workflow variants are not independent installations.

| Name | Type / group | Package-relative definition | How to use |
| --- | --- | --- | --- |
| `discovery` | workflow_variant / paper_type | `static/fragments/paper_type/discovery.md` | Select this variant through the parent skill; not a separately registered skill. |
| `methods` | workflow_variant / paper_type | `static/fragments/paper_type/methods.md` | Select this variant through the parent skill; not a separately registered skill. |
| `resource` | workflow_variant / paper_type | `static/fragments/paper_type/resource.md` | Select this variant through the parent skill; not a separately registered skill. |
| `clinical` | workflow_variant / paper_type | `static/fragments/paper_type/clinical.md` | Select this variant through the parent skill; not a separately registered skill. |
| `materials` | workflow_variant / paper_type | `static/fragments/paper_type/materials.md` | Select this variant through the parent skill; not a separately registered skill. |
| `review` | workflow_variant / paper_type | `static/fragments/paper_type/review.md` | Select this variant through the parent skill; not a separately registered skill. |

Supporting resource counts: references: 3, scripts: 1, agents: 1.

## Notes

- The recorded installation commit was recovered in the public repository. Local files may have changed after installation; no whole-package equality claim is made.
