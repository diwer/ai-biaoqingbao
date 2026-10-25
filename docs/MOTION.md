# 动效说明

当前表情库包含 100 个中文循环 GIF，每个含义对应一项动图，并提供两种尺寸：

- 240×240 轻量版：`docs/media/001.gif` 至 `docs/media/100.gif`
- 512×512 清晰版：`stickers/512/001.gif` 至 `stickers/512/100.gif`
- 打包下载：`downloads/dafeiyu-240.zip` 与 `downloads/dafeiyu-512.zip`

## 透明动态 WebP（v008）

- `docs/preview/001.webp` 至 `docs/preview/100.webp`：240×240 透明动态 WebP，作为图鉴主预览。
- `stickers/webp/512/001.webp` 至 `stickers/webp/512/100.webp`：512×512 透明动态 WebP 清晰版。
- 下载包：`downloads/dafeiyu-webp-240.zip` 与 `downloads/dafeiyu-webp-512.zip`，各含 100 项。
- 浏览器优先加载 WebP；不支持或解码失败时，图鉴会回退到对应的 `docs/media/{id}.gif`。
- WebP 保留原 GIF 帧数、帧时序和无限循环设置。透明的是背景区域；表情中的人物、文字和必要道具保持在画面内。原 GIF 文件和 GIF 下载包继续保留。
- 全量路径、帧时序与 SHA-256 索引见 `docs/webp-manifest.json`；v008 视觉与文件验收记录在 `deliverables/transparent-v008/`。

每项采用舒缓循环动效。来源与使用边界见仓库根目录的 `NOTICE.txt`。
