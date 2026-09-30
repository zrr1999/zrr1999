# spore-lang/.github

Spore 的 GitHub 组织门面和默认社区文件。首页区分语言实现、设计过程和工具链。语言手册仍在项目仓库和文档站。

## 这个仓库里什么会对外生效

| 路径 | 作用 |
| --- | --- |
| `profile/README.md` | 组织首页 |
| `CONTRIBUTING.md`、`SUPPORT.md`、`SECURITY.md` | 同组织的仓库没有自己的同名文件时，GitHub 使用这里的版本 |
| `.github/pull_request_template.md` | 没有本地 PR 模板的仓库使用它 |
| `.github/ISSUE_TEMPLATE/` | 没有本地 Issue 模板的仓库整组使用它 |

项目里已经有对应文件时，用项目自己的。这些默认文件不会进入项目的 clone。Issue 模板是整组覆盖。

`spore`、`basic-cli`、`spore-evolution`、`spore-lang.dev` 已经有自己的 PR 模板，组织默认 PR 模板不会替换它们。

`spore-evolution` 目前没有自己的 Issue 模板。组织模板一旦发布，它会整组继承这里的缺陷报告和功能请求，而这两份表格是把“修改语言语义”推回 `spore-evolution` 的。发布前先在 `spore-evolution` 放上一组完整的本地 Issue 模板，让提案仓库继续使用自己的入口。只放一份 `config.yml` 不够，那样组织模板也不会再被补上。

## 编辑时守住的边界

- 首页只放现在可以公开阅读的入口：`spore`、`spore-evolution`、`basic-cli`、`spore-lang.dev`、`docs.spore-lang.dev`、`blog.spore-lang.dev`。
- 不把占位仓库和历史仓库放进精选列表。
- “实现没有遵守已有语义”进入实现仓库的缺陷报告。“提议修改语言语义”进入 `spore-evolution`。组织 Issue 模板用必选勾选框把这两类分开。
- 不把编译器命令或某一套测试框架写进组织默认文件。语言设计变更要能关联提案和符合性案例，这条写在 `CONTRIBUTING.md`。
- Issue 模板不预填标签。
- 安全邮箱使用组织资料上的 `contact@spore-lang.dev`。写了 `SECURITY.md` 不等于已经打开私有漏洞报告。

三个组织各自维护，不另做同步仓库。`LICENSE`、`AGENTS.md`、`CODEOWNERS`、workflows、Dependabot、rulesets 都不由这个仓库下发。
