# images

个人图床。仓库内按项目分目录，路径即外链路径。

## 目录与命名
- 目录名 / 文件名：小写、kebab-case，不用空格、中文、特殊字符（避免 URL 编码）
- 同名文件不要覆盖后复用，改内容就换新文件名（见下方缓存说明）

## 外链模板
- raw:      https://raw.githubusercontent.com/<USER>/images/main/windhawk/demo.png
- jsDelivr: https://cdn.jsdelivr.net/gh/<USER>/images@main/windhawk/demo.png
- 生产环境建议把 @main 换成 tag 或 commit SHA，避免内容漂移

## 上传前
- 压到 1MB 以内，优先 WebP / AVIF
- 清掉 EXIF（手机原图可能带 GPS）
- 本仓库公开，图片会被公开 CDN 分发，勿传敏感内容

## 版权
图片版权归各项目 / 原作者，本仓库仅作托管。
