# GitHub Pages 工程作品集

此目录是 `https://nhh37740-glitch.github.io/` 的公开静态站点。首页直接展示八个项目、演示状态、源码仓库入口和公开简历摘要；不依赖框架、CDN 或 JavaScript。

## 发布

将 `index.html`、`.nojekyll` 和本说明放在公开仓库 `nhh37740-glitch/nhh37740-glitch.github.io` 根目录，再从默认分支根目录发布 GitHub Pages。发布前后都应检查所有项目链接。

## 链接与公开范围

- 项目服务器主页：`http://portfolio.72945645.xyz/`
- Media Workspace：`http://portfolio.72945645.xyz:8088/`
- 其余网页演示分别位于服务器的 `/projects/radar/`、`/projects/apps/go/`、`/projects/apps/java/agent.html`、`/projects/apps/cpp/`、`/projects/apps/rag/`。
- 文档问答展示 v0.8.0、18 个编译模块（含鉴权业务模块 `auth-facade`），回答默认使用简体中文；默认由服务端接入 OpenRouter 免费模型（`openrouter/free`），无需访问者填写模型密钥。游客只能看和查公开资料；真实登录用户可被授予指定笔记本的 viewer（查看）、editor（编辑）或 manager（笔记本管理）角色。查看者可阅读和提问，编辑者可导入文档，笔记本管理者可管理本笔记本成员与名称说明，但不能创建、归档笔记本或获得全局管理员身份。全局管理员可创建、归档和恢复私人笔记本，归档保留文档和成员关联；公开内置资料始终只读。公开、私人和管理员工作区共享全站每日共 20 次 Web 问答，按北京时间零点更新；有效且未命中成功缓存的问答开始时计数，失败或超时不退还，缓存命中不消耗。20 次问答不等于 20 次上游模型请求。模型与额度规则以 RAG 仓库的 `docs/OPENROUTER_RUNTIME.md` 为准，笔记本权限以 `docs/NOTEBOOK_PERMISSIONS.md` 为准；部署与验收以构建发布记录为准。
- RAG v0.8.0 的成员权限、关系表目录、默认中文分别归属 `auth-facade`、`data-facade`、`agent-facade`；正式归属与验收见 RAG 仓库 `docs/BUSINESS_CHANGE_MAP.md`、`docs/NOTEBOOK_ACCESS_VALIDATION.md`。Provider/model 目录、管理员 Web 模型配置、管理员重置额度仍为设计，尚未实现，不作为展示能力。
- 服务器简历页：`https://portfolio.72945645.xyz:8443/resume.html`。完整简历只通过另行提供的专属链接访问。不要在此仓库加入链接令牌、原始 PDF、个人联系方式或服务器私有文件。
- 仓库入口统一使用“查看仓库”；视频平台仓库为 `https://github.com/nhh37740-glitch/media-workspace`。仓库可见性由 GitHub 账户管理。
- Qt 雷达程序与浏览器雷达回放共用一个源码仓库，但属于不同运行方式。Qt 设备工作台没有网页演示。

HTTP 演示仅供浏览，不应输入密码或模型密钥。
