# Contributing

This file is the organization default. If a project has its own `CONTRIBUTING.md`, follow that file. The commands, package manager, and development environment for a repository stay in that repository.

## Before you change anything

- Look for an existing issue or discussion that already covers the change.
- For a substantial change, start that discussion before a large diff. A substantial change alters public behavior, compatibility, or which project owns a problem.
- Keep the pull request focused on one change.

## In the pull request

- Say what changed and what a user or caller can observe.
- Provide the evidence you actually ran. If nothing was run, say so, and say why.
- State compatibility, migration, and risk directly.
- Name follow-up work when it is concrete and outside this pull request.

## Project boundaries

Zendev, Spark, and Cue own different problems. Land the change in the repository that owns the behavior. Keep each tool inside its own job. When ownership is unclear, ask before writing the patch.

## Where this file stops

Build, test, and agent instructions belong to the project. Cloning a project does not include this file.
