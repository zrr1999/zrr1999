# volvox-ai/.github

Organization profile and default community files for Volvox. The public profile states the direction that can be read publicly.

## What this repository publishes

| Path | Role |
| --- | --- |
| `profile/README.md` | Organization profile |
| `CONTRIBUTING.md`, `SUPPORT.md`, `SECURITY.md` | Used when a repository in this organization has no file of the same name |
| `.github/pull_request_template.md` | Used by repositories with no local pull request template |
| `.github/ISSUE_TEMPLATE/` | Used as a whole set by repositories with no local issue templates |

A file in the project wins. These defaults are not copied into a project clone. One local issue template or `config.yml` replaces the entire organization set.

## What the public profile leaves out

- Links to private repositories.
- `tech-bench`. The repository is public and has no introduction worth featuring. It also has no local issue templates, so these forms will apply there.
- A member-only profile at `volvox-ai/.github-private`.
- A sync system shared with the other organizations.

## Editing

- Keep the profile short: the direction, the exploratory stage, and public entries that can already be read.
- Organization defaults ask for reproducible experiments, numerical checks, and the conditions on a performance claim.
- Training commands and benchmark scripts stay in the project.
- Issue forms do not set labels.
- Security mail is the published organization address, `volvox@sixbones.dev`. Confirm that someone reads it before publication.
- This `SECURITY.md` does not turn on GitHub private vulnerability reporting.

`LICENSE`, `AGENTS.md`, `CODEOWNERS`, workflows, Dependabot, and rulesets stay in the projects that need them.
