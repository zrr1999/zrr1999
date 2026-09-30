# zendev-lab/.github

Zendev Lab 的 GitHub 组织门面和默认社区文件。产品说明在各项目仓库和已经上线的文档站，不在这里展开。

## 这个仓库里什么会对外生效

| 路径 | 作用 |
| --- | --- |
| `profile/README.md` | 组织首页 |
| `CONTRIBUTING.md`、`SUPPORT.md`、`SECURITY.md` | 同组织的仓库没有自己的同名文件时，GitHub 使用这里的版本 |
| `.github/pull_request_template.md` | 没有本地 PR 模板的仓库使用它 |
| `.github/ISSUE_TEMPLATE/` | 没有本地 Issue 模板的仓库整组使用它 |

项目里已经有对应文件时，用项目自己的。这些默认文件不会进入项目的 clone。

Issue 模板是整组覆盖。项目本地只要出现有效的 Issue 模板或 `config.yml`，组织这整套模板都不会再生效。小仓库继续用组织默认；需要专用模板的仓库在本地保留完整的一组。

## 这里不下发

`LICENSE`、`AGENTS.md`、`CODEOWNERS`、`.github/workflows/`、`dependabot.yml`、rulesets。构建和测试所需要的说明留在项目仓库里。

## 编辑时守住的边界

- 首页只放 Zendev、Spark、Cue，以及现在打得开的文档。`lab.zrr.dev` 还没有解析，先不要链。
- 不把 `uv`、`cargo`、`npm` 或某一套开发环境写进组织默认文件。
- 组织默认 PR 模板用英文，给还没有本地模板的仓库。Zendev、Spark、Cue 已有中文模板，并带有 `pr-body:optional`。那些文件留在项目里，组织模板不复制这个标记。
- Issue 模板不预填标签。目标仓库未必有同名标签。
- 不把另外两个组织的文案抄过来。Zendev Lab 这里要强调的是工具之间的职责边界。
- 安全联系使用组织资料上的 `lab@zrr.dev`。写了 `SECURITY.md` 不等于已经打开私有漏洞报告。

三个组织各自维护这份短文案，不另做同步仓库。
