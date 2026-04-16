# Adam Lyttle Marketing Skills

Unofficial Codex and Claude/Opus skills that distill Adam Lyttle's solo app strategy into reusable agent instructions.

Important: we are not Adam Lyttle, we are not affiliated with Adam Lyttle, and this is not an official Adam Lyttle project. We are simply big fans of his approach to building, validating, launching, and marketing solo apps.

## What This Contains

This repository contains two parallel skill packages:

- `skills/codex/adam-lyttle-marketing` for Codex.
- `skills/opus/adam-lyttle-marketing` for Claude/Opus-style skill directories.

Both versions currently contain the same core playbook:

- App idea generation and validation.
- Technical proof-of-concept checks.
- Market and App Store keyword research.
- Lean execution with real deadlines and a "then list".
- App flow, feedback, and design vision guidance.
- ASO, launch-week download velocity, Apple Search Ads visibility, X/Twitter launch strategy, and shareable in-app moments.

## Sources

The skill was created from local transcript files in `sources/`.

The `sources/` directory is intentionally ignored by Git and should not be published in the public repository. Keep source transcripts local unless you have the rights and explicit intent to publish them.

## Local Development

Develop the skill files in this repository, then symlink them into the local agent skill directories.

For Codex:

```bash
ln -s /Users/olivermark/git/adam_lyttle/skills/codex/adam-lyttle-marketing /Users/olivermark/.codex/skills/adam-lyttle-marketing
```

For Claude/Opus:

```bash
ln -s /Users/olivermark/git/adam_lyttle/skills/opus/adam-lyttle-marketing /Users/olivermark/.claude/skills/adam-lyttle-marketing
```

Restart the relevant agent after linking or changing skill metadata so the skill registry reloads.

## Validation

Validate a skill with:

```bash
python3 /Users/olivermark/.codex/skills/.system/skill-creator/scripts/quick_validate.py skills/codex/adam-lyttle-marketing
python3 /Users/olivermark/.codex/skills/.system/skill-creator/scripts/quick_validate.py skills/opus/adam-lyttle-marketing
```

## Usage

Example prompt:

```text
Use $adam-lyttle-marketing to plan a lean solo app strategy from idea validation through launch.
```

Or:

```text
Nutze $adam-lyttle-marketing und prüfe meine App-Idee, den Build-Scope und den Launch-Plan nach Adam Lyttles Ansatz.
```
