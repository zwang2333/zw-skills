# academic-research-suite

Plan research, review literature, draft papers, simulate peer review, and plan experiments through the ARS router.

[Back to catalog](../README.md)

## Usage

Plan research, review literature, draft papers, simulate peer review, and plan experiments through the ARS router.

```text
Use $academic-research-suite: ars-plan a study of reproducibility in scientific machine learning.
```

## Installation and links

Upstream sources are verified, but this installed package is a custom Codex adapter. Restore the complete local academic-research-suite/ directory to reproduce the adapter. For the upstream Claude Code edition, follow the upstream README installation instructions; it is not an identical Codex package.

- [academic-research-skills (upstream)](https://github.com/Imbad0202/academic-research-skills) — opened public page.
  Recorded upstream commit: `828ef3b613b0e8b91830da3328a1e33d4eb5ab4c`.
- [experiment-agent (upstream)](https://github.com/Imbad0202/experiment-agent) — opened public page.
  Recorded upstream commit: `9b063fa895eaf1f63ac99ac03f924f8d31aa8d26`.
- [Codex skill documentation](https://learn.chatgpt.com/docs/build-skills) — opened public page.

## Local inventory

- App: Codex.
- Type: `personal`.
- Status: `installed_manifest`.
- Manifest/location: `~/.codex/skills/academic-research-suite/SKILL.md`.
  Declared version: `0.1.22`.
  Manifest SHA-256: `cbd0039781d86992e06c1863f3e03a6de3cb98d46bfdb600b4810683fa0238fd`.

## Dependencies

- Python. Mentioned in `~/.codex/skills/academic-research-suite/SKILL.md`; workflow dependent and not runtime-tested.

## Subskills and commands

These belong to the parent package. Workflow variants are not independent installations.

| Name | Type / group | Package-relative definition | How to use |
| --- | --- | --- | --- |
| `academic-paper` | bundled_workflow | `ars/academic-paper/WORKFLOW.md` | Use $academic-research-suite and describe the task. |
| `academic-paper-reviewer` | bundled_workflow | `ars/academic-paper-reviewer/WORKFLOW.md` | Use $academic-research-suite and describe the task. |
| `academic-pipeline` | bundled_workflow | `ars/academic-pipeline/WORKFLOW.md` | Use $academic-research-suite and describe the task. |
| `deep-research` | bundled_workflow | `ars/deep-research/WORKFLOW.md` | Use $academic-research-suite and describe the task. |
| `experiment-agent` | bundled_workflow | `ars/experiment-agent/WORKFLOW.md` | Use $academic-research-suite and describe the task. |
| `ars-3w` | command_alias | `ars/commands/ars-3w.md` | Use $academic-research-suite: ars-3w … |
| `ars-abstract` | command_alias | `ars/commands/ars-abstract.md` | Use $academic-research-suite: ars-abstract … |
| `ars-cache-invalidate` | command_alias | `ars/commands/ars-cache-invalidate.md` | Use $academic-research-suite: ars-cache-invalidate … |
| `ars-citation-check` | command_alias | `ars/commands/ars-citation-check.md` | Use $academic-research-suite: ars-citation-check … |
| `ars-disclosure` | command_alias | `ars/commands/ars-disclosure.md` | Use $academic-research-suite: ars-disclosure … |
| `ars-format-convert` | command_alias | `ars/commands/ars-format-convert.md` | Use $academic-research-suite: ars-format-convert … |
| `ars-full` | command_alias | `ars/commands/ars-full.md` | Use $academic-research-suite: ars-full … |
| `ars-lit-review` | command_alias | `ars/commands/ars-lit-review.md` | Use $academic-research-suite: ars-lit-review … |
| `ars-mark-read` | command_alias | `ars/commands/ars-mark-read.md` | Use $academic-research-suite: ars-mark-read … |
| `ars-outline` | command_alias | `ars/commands/ars-outline.md` | Use $academic-research-suite: ars-outline … |
| `ars-plan` | command_alias | `ars/commands/ars-plan.md` | Use $academic-research-suite: ars-plan … |
| `ars-rebuttal-audit` | command_alias | `ars/commands/ars-rebuttal-audit.md` | Use $academic-research-suite: ars-rebuttal-audit … |
| `ars-reviewer` | command_alias | `ars/commands/ars-reviewer.md` | Use $academic-research-suite: ars-reviewer … |
| `ars-revision-coach` | command_alias | `ars/commands/ars-revision-coach.md` | Use $academic-research-suite: ars-revision-coach … |
| `ars-revision` | command_alias | `ars/commands/ars-revision.md` | Use $academic-research-suite: ars-revision … |
| `ars-unmark-read` | command_alias | `ars/commands/ars-unmark-read.md` | Use $academic-research-suite: ars-unmark-read … |

Supporting resource counts: agents: 1.

## Notes

- ARS aliases are interpreted by the Codex router; they are not native Codex slash commands. Bundled agent prompts are supporting resources, not separately installed skills.
