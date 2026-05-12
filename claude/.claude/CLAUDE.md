# Claude Code Global Instructions

## Self-improvement: persist reusable workflows

At the end of any non-trivial task, bug fix, debugging session, refactor, setup, or investigation, briefly evaluate whether anything learned should be saved for future Claude Code sessions.

Save reusable multi-step workflows to `~/.claude/skills/<name>/SKILL.md` or project `.claude/skills/<name>/SKILL.md`.
Save project conventions to `./CLAUDE.md` or `.claude/rules/<topic>.md`.
Save global preferences to `~/.claude/CLAUDE.md` or `~/.claude/rules/<topic>.md`.
Do not save temporary task state, progress logs, one-off results, secrets, or credentials.

Claude Code skills live in their own directories and may include supporting files alongside `SKILL.md`. Create or patch a skill only when the workflow is likely to recur, has concrete steps/checks/decision rules, includes prerequisites/pitfalls/verification, is not merely a summary, and does not duplicate existing context. Prefer patching existing files over creating new narrow skills.
