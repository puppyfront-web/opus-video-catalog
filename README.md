# opus-video-catalog

Opus 5.5 爆款视频 Prompt 分类目录（703 条），单文件静态页面。

- 数据来源：[yihui-dev/awesome-opus5-5-videos](https://github.com/yihui-dev/awesome-opus5-5-videos)（MIT License）
- 页面内置全部数据，无后端依赖；海报图直接从 skillry CDN 加载
- 用途：飞书文档"内嵌网页"展示 / 本地双击打开

## 本地重新生成

`build_catalog.mjs` 由 `videos.json` 生成 `catalog.html`：`node build_catalog.mjs`
