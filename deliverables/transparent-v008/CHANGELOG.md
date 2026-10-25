# 变更

- 用透明动态 WebP 更新项目 240px 图鉴预览，浏览器无法解码时回退到原 GIF。
- 新增 512px WebP 正式资源目录和 240/512 两个 WebP ZIP 下载包。
- 新增包含每个含义、路径、帧数、时序、字节数和 SHA-256 的 `docs/webp-manifest.json`。
- 在 `docs/MOTION.md` 与 README 中记录新格式，在图鉴首页加入两种 WebP 下载链接。
- 仅改透明 alpha 与格式映射；动画帧 RGB 来自原项目 GIF，人物、文字和语义道具保持。
- 保留更换前预览 ZIP 和文本回滚副本；未触碰 `publishing/`、未提交、未推送、未发布。
