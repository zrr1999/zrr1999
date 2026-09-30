# Contributing

This file is the organization default. If a project has its own `CONTRIBUTING.md`, follow that file. The commands and environments for a repository stay in that repository.

## Before you change anything

- Look for an existing issue or discussion that already covers the change.
- For a substantial change, start that discussion before a large diff. A substantial change alters a public result, a measured claim, or the boundary of a component.
- Keep the pull request focused on one change.

## In the pull request

- Say what changed and what a reader of the result can observe.
- Provide the evidence you actually ran. If nothing was run, say so, and say why.
- State compatibility and risk directly.
- Name follow-up work when it is concrete and outside this pull request.

## Experiments and claims

- A result another person is expected to rely on needs enough information to reproduce it: revision, command, data or shape, and any seed or hardware the result depends on.
- A numerical result should say what was compared and how disagreement is judged.
- A performance conclusion should state the condition it was measured under, including what was held constant. Keep the claim inside that condition.

## Where this file stops

Build, test, and agent instructions belong to the project. Cloning a project does not include this file.
