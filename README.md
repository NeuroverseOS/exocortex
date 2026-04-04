# Exocortex

A personal exocortex — an external memory and focus system for intercognitive human-AI pairs, designed to be read and written by both humans and their AI agent collaborators.

## What is an exocortex?

An exocortex is a structured external memory that helps you:

- **Stay focused** — your `attention.md` declares what you're working on right now
- **Track progress** — your `goals.md` tracks your current projects
- **Stay aligned** — your `values.md` keeps your work connected to what matters
- **Collaborate with AI** — your `claude.md` teaches AI agents how to work with you

## Getting started

```bash
git clone https://github.com/Broodsugar/exocortex.git my-exocortex
cd my-exocortex
bash setup.sh
```

The setup script walks you through the basics — your name, role, values, and current focus. After that, open each file and expand on the guiding prompts inside. Check out `examplenils/` for a filled-in example to see what a complete exocortex looks like.

## Structure

```
exocortex/
├── README.md              ← You are here
├── claude.md              ← Instructions for AI agents (reading order, alignment checks)
├── attention.md           ← Current focus (one thing, right now)
├── identity.md            ← Who you are, how you see the world
├── values.md              ← Guiding principles
├── organization.md        ← Your org's mission and values
├── role.md                ← Your responsibilities and routines
├── goals.md               ← Current projects and objectives
├── methods.md             ← Mental models and frameworks you use
├── glossary.md            ← Domain-specific terms
└── examplenils/           ← Filled-in example (Nils Pihl, CEO of Auki Labs)
```

## Philosophy

The exocortex is built on a few principles:

**Singular attention.** You can only focus on one thing at a time. `attention.md` forces that choice and helps both you and your AI agent resist drift.

**Values-aligned work.** Every goal should connect to a value. If it doesn't, question why you're doing it.

**AI as collaborator.** Your AI agent reads your exocortex at the start of every session. It knows your focus, your goals, and your values. It will nudge you back on track when you drift and challenge your assumptions when you need it.

**Your content, your structure.** The template provides guiding prompts, but the content must be yours. An exocortex only works if it reflects how you actually think, what you actually do, and what you actually care about.

## For teams

When everyone on a team maintains their own exocortex, collaboration becomes legible without meetings or status updates. You can see what someone is focused on by reading their `attention.md`. Project repos can have their own exocortex-like structure that individual exocortices point into.
