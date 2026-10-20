# nature-academic-search

Search scholarly databases, verify citations, manage reference files, and audit independent citations.

[Back to catalog](../README.md)

## Usage

Search scholarly databases, verify citations, manage reference files, and audit independent citations.

```text
Use $nature-academic-search to find papers on reproducible single-cell analysis and export verified references.
```

## Installation and links

Install the selected complete package and its sibling support dependencies. Current upstream may differ from this local snapshot.

```text
Use $skill-installer to install nature-academic-search and nature-shared from Yuan1z0825/nature-skills at skills/nature-academic-search and skills/nature-shared. Use ref 745c5f38d1b4a0600bd2f5f5682e394a34fc28b2 for the recorded snapshot, or main for the current upstream version.
```

- [Nature collection at recorded installation commit](https://github.com/Yuan1z0825/nature-skills/tree/745c5f38d1b4a0600bd2f5f5682e394a34fc28b2/skills) — opened public tree matching local receipt.
  Recorded upstream commit: `745c5f38d1b4a0600bd2f5f5682e394a34fc28b2`.
- [Nature collection installation guide](https://github.com/Yuan1z0825/nature-skills/blob/main/README_EN.md) — opened public page.
- [Codex skill documentation](https://learn.chatgpt.com/docs/build-skills) — opened public page.

## Local inventory

- App: Codex.
- Type: `personal`.
- Status: `installed_manifest`.
- Manifest/location: `~/.codex/skills/nature-academic-search/SKILL.md`.
  Declared version: `2.0.0`.
  Manifest SHA-256: `65f44bb5d31f8b2d26687dcdcbc22d3def3ab2b5a26c810cd5e18a6a98d5e681`.

## Dependencies

- Related/support package: [nature-shared](personal--nature-shared.md).
- Python. Mentioned in `~/.codex/skills/nature-academic-search/static/core/routing-and-ops.md`; workflow dependent and not runtime-tested.
- MCP tools / connected services. Mentioned in `~/.codex/skills/nature-academic-search/SKILL.md`; workflow dependent and not runtime-tested.
- External API access (workflow dependent). Mentioned in `~/.codex/skills/nature-academic-search/README.md`; workflow dependent and not runtime-tested.
- uv. Mentioned in `~/.codex/skills/nature-academic-search/static/core/routing-and-ops.md`; workflow dependent and not runtime-tested.

## Subskills and commands

These belong to the parent package. Workflow variants are not independent installations.

| Name | Type / group | Package-relative definition | How to use |
| --- | --- | --- | --- |
| `multi-source-search` | workflow_variant / workflow | `references/workflows/wf1-multi-source-search.md` | Select this variant through the parent skill; not a separately registered skill. |
| `citation-verification` | workflow_variant / workflow | `references/workflows/wf2-citation-verification.md` | Select this variant through the parent skill; not a separately registered skill. |
| `mesh-strategy` | workflow_variant / workflow | `references/workflows/wf3-mesh-strategy.md` | Select this variant through the parent skill; not a separately registered skill. |
| `citation-file-mgmt` | workflow_variant / workflow | `references/workflows/wf4-citation-file-mgmt.md` | Select this variant through the parent skill; not a separately registered skill. |
| `reference-mgmt` | workflow_variant / workflow | `references/workflows/wf5-reference-mgmt.md` | Select this variant through the parent skill; not a separately registered skill. |
| `strict-other-citation-impact-audit` | workflow_variant / workflow | `references/workflows/wf6-strict-other-citation-impact-audit.md` | Select this variant through the parent skill; not a separately registered skill. |

Supporting resource counts: references: 14, scripts: 4, agents: 1.

## Notes

- The recorded installation commit was recovered in the public repository. Local files may have changed after installation; no whole-package equality claim is made.
