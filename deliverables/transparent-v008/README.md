# 透明动态 WebP v008

本版本把 ai-biaoqingbao 的 100 个含义各提供为 240×240 与 512×512 动态 WebP，共 200 个成品。正式使用位置是：

- 图鉴预览：`docs/preview/001.webp` 至 `docs/preview/100.webp`
- 高清素材：`stickers/webp/512/001.webp` 至 `stickers/webp/512/100.webp`
- 下载包：`downloads/dafeiyu-webp-240.zip` 与 `downloads/dafeiyu-webp-512.zip`
- 资源索引：`docs/webp-manifest.json`

WebP 保留源 GIF 的每帧时长、帧序与无限循环；透明区域只作用于背景蒙版。原始 GIF 成品及两个旧 GIF 下载包没有替换或删除。项目图鉴失败时回退到原有 GIF 预览。

`rollback/docs-preview-before-v008.zip` 是更换前的 100 个图鉴预览 WebP 备份。`rollback/docs-index-before-v008.html`、`docs-MOTION-before-v008.md` 与 `README-before-v008.md` 是本次改动前的文本备份；恢复时只恢复对应文件即可。512 WebP 是新增目录，没有覆盖已有文件。

此目录不包含改绘后的角色图。022、024、025 使用生成工具输出的灰度 alpha 蒙版；最终 WebP 的颜色通道仍来自原 GIF 帧。`alpha-masks/` 仅留供复核和复用。
