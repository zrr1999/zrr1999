# volvox-ai/.github

Volvox 的 GitHub 组织门面和默认社区文件。公开首页只写已经可以对外说的定位。不把内部仓库列表抄到组织主页上。

## 这个仓库里什么会对外生效

| 路径 | 作用 |
| --- | --- |
| `profile/README.md` | 组织首页 |
| `CONTRIBUTING.md`、`SUPPORT.md`、`SECURITY.md` | 同组织的仓库没有自己的同名文件时，GitHub 使用这里的版本 |
| `.github/pull_request_template.md` | 没有本地 PR 模板的仓库使用它 |
| `.github/ISSUE_TEMPLATE/` | 没有本地 Issue 模板的仓库整组使用它 |

项目里已经有对应文件时，用项目自己的。这些默认文件不会进入项目的 clone。Issue 模板是整组覆盖：本地一旦有有效模板或 `config.yml`，组织这整套都不再使用。

## 公开页现在故意不放的东西

- 私有仓库的链接。访客打不开的入口不要出现在组织首页。
- `tech-bench`。它是公开仓库，但还没有可以阅读的项目介绍，所以不放进精选列表。它也没有本地 Issue 模板，组织模板发布后会用在这个仓库上。
- 成员专属首页 `volvox-ai/.github-private`。现在不建。
- 一套跨组织同步脚本。这份文案独立维护。

## 编辑时守住的边界

- 首页保持短：为什么做这个方向、现在处于探索阶段、已经公开的入口。
- 组织默认文件强调实验可复现、数值正确性，以及性能结论所依赖的条件。
- 不把某个仓库的训练命令或基准脚本写进组织默认文件。
- Issue 模板不预填标签。
- 安全邮箱使用组织资料上的 `volvox@sixbones.dev`。发布前确认有人读这个地址。如果已经没人读，改成真实渠道再公开，不要留一个看起来可用的死邮箱。
- 写了 `SECURITY.md` 不等于已经打开 GitHub 私有漏洞报告。

`LICENSE`、`AGENTS.md`、`CODEOWNERS`、workflows、Dependabot、rulesets 都不由这个仓库下发。
