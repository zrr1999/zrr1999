# 待发布的三个组织 `.github` 仓库

这里的三个目录是组织仓库的根目录，不是个人主页的内容。

| 目录 | 发布为 |
| --- | --- |
| `zendev-lab/` | 公开仓库 `zendev-lab/.github` |
| `volvox-ai/` | 公开仓库 `volvox-ai/.github` |
| `spore-lang/` | 公开仓库 `spore-lang/.github` |

个人主页仍然只看本仓库根目录的 `README.md`。

这三个组织仓库必须公开，默认社区文件才会生效。`profile/README.md` 是组织首页。根目录的 `CONTRIBUTING.md`、`SUPPORT.md`、`SECURITY.md` 是默认回退。Issue 模板和 PR 模板放在目录内部的 `.github/` 里。

当前 Cloud Agent 使用的 GitHub App 不能在这些组织里创建仓库（`POST /orgs/{org}/repos` 返回 403 `Resource not accessible by integration`）。文案先放在这里供审阅。三个仓库发布到组织之后，从个人主页仓库删除本目录。
