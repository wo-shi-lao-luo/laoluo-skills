# Folder Structure

This repository distributes selected Skills. It is not a working area for generated presentation decks, client assets, or brainstorming session records.

## Root

Keep the collection entry point, repository-wide conventions, and essential Git configuration here. `README.md` is the entry point for users; this document describes placement rather than listing individual deliverables or changes.

## skills/

Store one complete distributable package per Skill, using its lowercase, hyphenated name as the folder name. Each package contains `SKILL.md`, with `agents/`, `references/`, `scripts/`, or `assets/` only when needed by that Skill.

These are distribution sources. Do not move them into `.agents/skills/` merely to maintain the collection; repository-local activation and downstream installation are separate concerns.

## Working Material and Archives

Keep temporary validation dependencies, test transcripts, local installation backups, generated exports, and task scratch files outside the distribution packages and outside Git. Maintain one current source for each Skill in this repository rather than publishing backup copies beside it. Preserve existing source files and review relevant references before moving or replacing anything.
