# shares

画伞（huasanai）的公开分享物料仓库——演讲 deck、单页展示、临时分享页等，统一通过 GitHub Pages 对外开放。

线上访问入口：`https://huasanai.github.io/shares/<子目录名>/`

## 当前内容

| 子目录 | 内容 | 在线访问 |
|---|---|---|
| [huasan-ai-talk/](./huasan-ai-talk/) | 姜胡说分享：prompt → skills → harness → OPC | https://huasanai.github.io/shares/huasan-ai-talk/ |

## 部署原则

- 所有外部依赖（字体 / mermaid / 其他 CDN）一律 self-host，避免大陆访问被任何第三方 CDN 拖累
- 每个子目录是一个独立的静态页面，互不耦合
- 直接 push 到 `main` 即上线，无构建步骤
