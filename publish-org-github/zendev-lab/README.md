# zendev-lab/.github

Organization profile and default community files for Zendev Lab. Product documentation stays in each project and on the documentation sites that are already live.

## What this repository publishes

| Path | Role |
| --- | --- |
| `profile/README.md` | Organization profile |
| `CONTRIBUTING.md`, `SUPPORT.md`, `SECURITY.md` | Used when a repository in this organization has no file of the same name |
| `.github/pull_request_template.md` | Used by repositories with no local pull request template |
| `.github/ISSUE_TEMPLATE/` | Used as a whole set by repositories with no local issue templates |

A file in the project wins. These defaults are not copied into a project clone.

Issue templates apply as a set. One local issue template or `config.yml` replaces the entire organization set. A small repository can use the organization defaults. A repository that needs its own templates keeps a complete local set.

## What this repository does not distribute

`LICENSE`, `AGENTS.md`, `CODEOWNERS`, `.github/workflows/`, `dependabot.yml`, and rulesets. Build and test instructions stay in the project.

## Editing

- The profile lists Zendev, Spark, Cue, and documentation that already resolves. Leave `lab.zrr.dev` unlinked until it resolves.
- Keep `uv`, `cargo`, `npm`, and other environment commands in the project contributing guide.
- The organization pull request template is for repositories that do not already have one. Zendev, Spark, and Cue keep their own templates, including the `pr-body:optional` marker. Those three repositories have no issue templates, so new issues will use the forms here. Their pull request templates stay where they are.
- Issue forms do not set labels.
- This copy stays specific to the boundary between Zendev Lab tools. The three organizations keep their own files.
- Security mail is the published organization address, `lab@zrr.dev`. This file does not turn on GitHub private vulnerability reporting.
