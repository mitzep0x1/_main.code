# LLM-CONTEXT

Personal monorepo of scripts and automations for cybersecurity.

## Conventions
- All documentation and context files in English
- Code, comments, and scripts in English

## Structure
- Each folder is independent with its own README
- On session start: read this file and stop — do not explore folders
- Wait for the user to indicate which folder to work in, then read that folder's README

## Stack
- Python managed with `uv` — always run scripts with `uv run <script>`

## Workflow
- Commit directly to `main`, no branches
- GitHub as backup (`origin`)
- Update `ZLOG.md` at the end of each session
