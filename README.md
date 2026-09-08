# Duplic8

**Portable digital identity and digital-self infrastructure.**

Duplic8 explores a simple question: how can a person's digital identity remain useful across different tools and environments while staying under their control?

Today, people repeatedly recreate profiles, preferences, and context across disconnected services. Duplic8's proposed direction is a portable digital self: a representation people can understand, manage, and choose to share.

## Status

**Concept / discovery.** This repository documents the project vision and proposed milestones. It contains no working application, deployed service, or verified integrations. Features below are design goals, not shipped capabilities.

## Proposed experience

1. Define a digital profile using information the user chooses to provide.
2. Review which parts of that profile are appropriate for a particular context.
3. Share a limited representation with a chosen destination.
4. Update the profile and understand the limits of changing information already shared.

For example, a fictional user might keep a general communication preference separate from a work-specific introduction, then choose which to include in an export.

## Design principles

- **User control:** make selection and sharing deliberate and understandable.
- **Portability:** explore documented formats without promising universal compatibility.
- **Minimal disclosure:** share only what a particular interaction needs.
- **Clear boundaries:** distinguish a person's stated information from inferred or generated content.
- **Honest limitations:** explain what happens to exported copies and what cannot be recalled.

These are intended product principles; they are not claims about implemented security controls.

## Explore the repository

| Location | Purpose |
| --- | --- |
| [Project brief](docs/project-brief.md) | Problem, audience hypothesis, scope, and open questions |
| [Roadmap](ROADMAP.md) | Proposed milestones and completion criteria |
| [Publication boundaries](docs/publication-boundaries.md) | Visibility recommendation and omitted material |
| [Designs](designs/README.md) | Planned public interaction studies |
| [Research](research/README.md) | Research questions and evidence standards |
| [Prototypes](prototypes/README.md) | Scope for a future synthetic-data demonstration |

## Getting started

Start with the project brief and roadmap. There is nothing to install or run yet. The first proposed prototype is a small profile-and-export walkthrough using fictional data.

## Feedback

Useful feedback includes concrete portability problems, confusing sharing decisions, and suggestions for a narrow first use case. Keep feedback free of credentials, personal identity records, confidential business information, and proprietary implementation details.

## Publication and licensing

Recommended visibility: **public for this concept-only repository**, with proprietary engineering work maintained separately in a private repository. See the publication boundaries for details.

No open-source license is included. A license decision is deferred until the owner chooses what rights to grant.
