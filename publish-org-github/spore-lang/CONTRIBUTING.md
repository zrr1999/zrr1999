# Contributing

This file is the organization default. If a project has its own `CONTRIBUTING.md`, follow that file. The commands and environments for a repository stay in that repository.

## Before you change anything

- Look for an existing issue or discussion that already covers the change.
- For a substantial change, start that discussion before a large diff. A substantial change alters public behavior, compatibility, or the meaning of the language.
- Keep the pull request focused on one change.

## In the pull request

- Say what changed and what a user or caller can observe.
- Provide the evidence you actually ran. If nothing was run, say so, and say why.
- State compatibility, migration, and risk directly.
- Name follow-up work when it is concrete and outside this pull request.

## Language design and implementation

- A change to language semantics, the type system, or a cross-cutting protocol goes through [spore-evolution](https://github.com/spore-lang/spore-evolution), together with the proposal and the conformance cases that proposal requires.
- An implementation change that follows an accepted proposal links that proposal.
- An implementation that disagrees with behavior already specified is a defect in the implementation repository.

## Where this file stops

Build, test, and agent instructions belong to the project. Cloning a project does not include this file.
