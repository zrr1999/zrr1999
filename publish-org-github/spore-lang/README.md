# spore-lang/.github

Organization profile and default community files for Spore. The profile separates the implementation, the design process, and the toolchain. The language manual stays in the repositories and on the docs site.

## What this repository publishes

| Path | Role |
| --- | --- |
| `profile/README.md` | Organization profile |
| `CONTRIBUTING.md`, `SUPPORT.md`, `SECURITY.md` | Used when a repository in this organization has no file of the same name |
| `.github/pull_request_template.md` | Used by repositories with no local pull request template |
| `.github/ISSUE_TEMPLATE/` | Used as a whole set by repositories with no local issue templates |

A file in the project wins. These defaults are not copied into a project clone. Issue templates apply as a set.

`spore`, `basic-cli`, `spore-evolution`, and `spore-lang.dev` already have pull request templates. The organization template leaves those in place.

`spore-evolution` has no issue templates yet. Once these organization forms are published, that repository would inherit the bug and feature forms, which send language-design changes back to `spore-evolution`. Before publication, add a complete local issue template set there. A lone `config.yml` also blocks the organization set, so the local set has to be complete.

## Editing

- The profile links entries that can be read now: `spore`, `spore-evolution`, `basic-cli`, `spore-lang.dev`, `docs.spore-lang.dev`, and `blog.spore-lang.dev`.
- Placeholder and historical repositories stay off the featured list.
- An implementation that misses specified behavior is a bug on the implementation repository. A proposal to change the language goes to `spore-evolution`. The issue forms use a required checkbox to keep those apart.
- Compiler commands and test harnesses stay in the project. `CONTRIBUTING.md` asks language changes to carry a proposal and conformance cases.
- Issue forms do not set labels.
- Security mail is the published organization address, `contact@spore-lang.dev`. This file does not turn on GitHub private vulnerability reporting.

The three organizations keep their own files. `LICENSE`, `AGENTS.md`, `CODEOWNERS`, workflows, Dependabot, and rulesets stay in the projects that need them.
