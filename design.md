# Exocortex Design

## Core Pattern

Every level of the exocortex follows the same triple: **Identity, Values, Product**.

Each level also has **inputs** (what it ingests) and **outputs** (what it produces/disseminates).

The levels nest — each one provides context for the level below it, and alignment can be checked structurally across levels.

---

## L1: Individual

**The pairing of a human and an agent.**

- [Attention.md](http://Attention.md) - what is my immediate focus
- [Organization.md](http://Organization.md) - where do i work
- [Values.md](http://Values.md) - what are my guiding values
- [Goals.md](http://Goals.md) - the projects I am working on
- Project folders - folders named after goals
  - [project/readme.md](http://readme.me) - description of the desired finished product
  - /project/changelog.md - the latest changes  


**The shared context everyone in the org operates within.**


|              |                                                               |
| ------------ | ------------------------------------------------------------- |
| **Identity** | What is this company?                                         |
| **Values**   | What guides us?                                               |
| **Product**  | What are we building?                                         |
| **Inputs**   | What do we take in? (research, market signals, user feedback) |
| **Outputs**  | What do we put into the world?                                |


*Example: We are Auki. We value increasing intercognitive bandwidth. We are building the real world web.*

---

## L3: Project

**A specific effort nested within the organization.**


|              |                                                              |
| ------------ | ------------------------------------------------------------ |
| **Identity** | What is this project?                                        |
| **Values**   | What are our constraints? (time, scope, quality, compliance) |
| **Product**  | What are we shipping concretely?                             |
| **Inputs**   | Requirements, dependencies, context from L2                  |
| **Outputs**  | Deliverables, artifacts, outcomes                            |


---

## Open Questions

- **Where does `attention` live?** A session-level "what I'm focused on right now" — is this individual-level only, or does each level have a current focus?
- **How deep does nesting go?** Projects could have sub-projects, tasks. Is the pattern recursive, or capped at three levels?
- **Alignment checks:** The nesting means Claude can flag when project-level work conflicts with org-level values. Is this an explicit feature or an emergent property?

