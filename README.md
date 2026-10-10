# GitHub Pages 工程作品集

此目录是 `https://nhh37740-glitch.github.io/` 的公开静态站点。首页直接展示八个项目、演示状态、源码仓库入口和公开简历摘要；不依赖框架、CDN 或 JavaScript。

## 发布

将 `index.html`、`.nojekyll` 和本说明放在公开仓库 `nhh37740-glitch/nhh37740-glitch.github.io` 根目录，再从默认分支根目录发布 GitHub Pages。发布前后都应检查所有项目链接。

## 链接与公开范围

- 项目服务器主页：`http://portfolio.72945645.xyz/`
- Media Workspace：`http://portfolio.72945645.xyz:8088/`
- 其余网页演示分别位于服务器的 `/projects/radar/`、`/projects/apps/go/`、`/projects/apps/java/agent.html`、`/projects/apps/cpp/`、`/projects/apps/rag/`。
- 文档问答展示 v0.6.0、18 个编译模块（含鉴权业务模块 `auth-facade`）；默认由服务端接入 OpenRouter 免费模型（`openrouter/free`），无需访问者填写模型密钥。游客只能看和查，管理员登录后可创建笔记本和导入文档。公开、私人和管理员工作区共享全站每日共 20 次 Web 问答，按北京时间零点更新；有效且未命中成功缓存的问答开始时计数，失败或超时不退还，缓存命中不消耗。20 次问答不等于 20 次上游模型请求。配置与额度规则以 RAG 仓库的 `docs/OPENROUTER_RUNTIME.md` 为正式依据，部署与验收以构建发布记录为准。
- 服务器简历页：`https://portfolio.72945645.xyz:8443/resume.html`。完整简历只通过另行提供的专属链接访问。不要在此仓库加入链接令牌、原始 PDF、个人联系方式或服务器私有文件。
- 仓库入口统一使用“查看仓库”；视频平台仓库为 `https://github.com/nhh37740-glitch/media-workspace`。仓库可见性由 GitHub 账户管理。
- Qt 雷达程序与浏览器雷达回放共用一个源码仓库，但属于不同运行方式。Qt 设备工作台没有网页演示。

HTTP 演示仅供浏览，不应输入密码或模型密钥。
