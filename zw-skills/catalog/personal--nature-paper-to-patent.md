# nature-paper-to-patent

Develop evidence-grounded Chinese patent disclosures and invention drafts from research materials.

[Back to catalog](../README.md)

## Usage

Develop evidence-grounded Chinese patent disclosures and invention drafts from research materials.

```text
Use $nature-paper-to-patent to prepare a Chinese technical disclosure from these research materials.
```

## Installation and links

Install the selected complete package and its sibling support dependencies. Current upstream may differ from this local snapshot.

```text
Use $skill-installer to install nature-paper-to-patent from Yuan1z0825/nature-skills at skills/nature-paper-to-patent. Use ref 745c5f38d1b4a0600bd2f5f5682e394a34fc28b2 for the recorded snapshot, or main for the current upstream version.
```

- [Nature collection at recorded installation commit](https://github.com/Yuan1z0825/nature-skills/tree/745c5f38d1b4a0600bd2f5f5682e394a34fc28b2/skills) — opened public tree matching local receipt.
  Recorded upstream commit: `745c5f38d1b4a0600bd2f5f5682e394a34fc28b2`.
- [Nature collection installation guide](https://github.com/Yuan1z0825/nature-skills/blob/main/README_EN.md) — opened public page.
- [Codex skill documentation](https://learn.chatgpt.com/docs/build-skills) — opened public page.

## Local inventory

- App: Codex.
- Type: `personal`.
- Status: `installed_manifest`.
- Manifest/location: `~/.codex/skills/nature-paper-to-patent/SKILL.md`.
  Declared version: `1.0.0`.
  Manifest SHA-256: `1a57ae613bb545debba02ce4d9d36a53974e717cdafb1a5feb2cbd341bcf36b0`.

## Dependencies

- Python. Mentioned in `~/.codex/skills/nature-paper-to-patent/SKILL.md`; workflow dependent and not runtime-tested.

## Subskills and commands

These belong to the parent package. Workflow variants are not independent installations.

| Name | Type / group | Package-relative definition | How to use |
| --- | --- | --- | --- |
| `pdf-text` | workflow_variant / source_format | `static/fragments/source/pdf-text.md` | Select this variant through the parent skill; not a separately registered skill. |
| `scanned-pdf` | workflow_variant / source_format | `static/fragments/source/scanned-pdf.md` | Select this variant through the parent skill; not a separately registered skill. |
| `pasted-text` | workflow_variant / source_format | `static/fragments/source/pasted-text.md` | Select this variant through the parent skill; not a separately registered skill. |
| `mixed-project` | workflow_variant / source_format | `static/fragments/source/mixed-project.md` | Select this variant through the parent skill; not a separately registered skill. |
| `full-draft` | workflow_variant / task_mode | `static/fragments/task/full-draft.md` | Select this variant through the parent skill; not a separately registered skill. |
| `claim-set` | workflow_variant / task_mode | `static/fragments/task/claim-set.md` | Select this variant through the parent skill; not a separately registered skill. |
| `disclosure-analysis` | workflow_variant / task_mode | `static/fragments/task/disclosure-analysis.md` | Select this variant through the parent skill; not a separately registered skill. |
| `technical-disclosure` | workflow_variant / task_mode | `static/fragments/task/technical-disclosure.md` | Select this variant through the parent skill; not a separately registered skill. |
| `disclosure-iteration` | workflow_variant / task_mode | `static/fragments/task/disclosure-iteration.md` | Select this variant through the parent skill; not a separately registered skill. |
| `paper-patent-audit` | workflow_variant / task_mode | `static/fragments/task/paper-patent-audit.md` | Select this variant through the parent skill; not a separately registered skill. |
| `algorithm-software` | workflow_variant / invention_type | `static/fragments/invention/algorithm-software.md` | Select this variant through the parent skill; not a separately registered skill. |
| `apparatus-system` | workflow_variant / invention_type | `static/fragments/invention/apparatus-system.md` | Select this variant through the parent skill; not a separately registered skill. |
| `process-material` | workflow_variant / invention_type | `static/fragments/invention/process-material.md` | Select this variant through the parent skill; not a separately registered skill. |
| `mixed` | workflow_variant / invention_type | `static/fragments/invention/mixed.md` | Select this variant through the parent skill; not a separately registered skill. |

Supporting resource counts: references: 18, scripts: 20, agents: 1.

## Notes

- The recorded installation commit was recovered in the public repository. Local files may have changed after installation; no whole-package equality claim is made.
