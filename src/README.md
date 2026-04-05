# src/

This directory is the exocortex template. When a new colleague runs `git clone` and `bash setup.sh`, these files become their personal exocortex.

## What's here

| File | Function |
|------|----------|
| `CLAUDE.md` | Tells the AI agent how to use the exocortex: reading order, alignment checks, behavior rules. This is the entry point — the agent reads this first. |
| `attention.md` | Single-line file. The owner writes what they're focused on this session. The agent reads it and nudges them back if they drift. Only the owner edits this. |
| `identity.md` | Template for the owner's background, skills, and perspective. Includes placeholder prompts. |
| `values.md` | Template for personal values. Empty until the owner fills it in. |
| `organization.md` | Pre-populated with Auki's mission, protocol, economy, strategy, products, and values. Not a template — this is live content. |
| `role.md` | Template for the owner's responsibilities and routines. The CEO may provide a draft; the owner rewrites it in their own words. |
| `goals.md` | Template for daily habits, weekly routines, responsibilities, and projects. |
| `methods.md` | Template for personal heuristics and mental models. |
| `glossary.md` | Template for domain-specific vocabulary. |
| `contributing.md` | Logging rules: every change must be logged in the promptlog (first) and changelog. Defines field formats for both. |
| `changelog.md` | Seed changelog with one example entry. Append-only, latest on top. |
| `promptlog.md` | Seed promptlog with one example entry. Append-only, latest on top. Includes relevance scoring against attention. |
| `setup.sh` | Interactive setup script. Asks name, role, values, goals, and first attention focus. Populates template files with answers. |
| `examplenils/` | Filled-in example of identity.md, role.md, organization.md showing what a populated exocortex looks like. |

## How setup.sh works

1. Prompts the user for name, role, values, goals, and initial attention focus
2. Writes answers into the template files (identity.md, values.md, role.md, goals.md, attention.md)
3. User opens the repo in Claude Code or Cursor and starts working

## Dependencies

- Git
- Bash (for setup.sh)
- An AI coding tool that reads CLAUDE.md (Claude Code, Cursor, etc.)
