# Windows 批量添加 PREVIEW ONLY 重复水印：轻水印实测教程

轻水印（Watermark Lite）可在 Windows 10/11 本地为一批静态图片添加重复的 **PREVIEW ONLY** 文字，再导出带水印的客户预览副本。本示例使用便携 ZIP 版 2.0.0，将界面设为 English，检查两张横图、两张竖图，以及明暗背景下的文字效果。核验日期为 2026-10-24。

**开发者说明：** 我是轻水印开发者，本文使用 AI 辅助编写。商品图片均为 AI 生成的演示素材，并非客户照片。

## 1. 导入四张图片

先把干净原图保存在独立文件夹。便携版需完整解压 ZIP，再从解压后的文件夹运行 `WatermarkLite.exe`。选择 **Add folder**，选中原图文件夹，然后点击 **Start watermarking**。

保留四张图片的选择勾选框。本示例中 A/B 是横图，C/D 是竖图；提前命名便于将导出结果与原图对应。

## 2. 设置重复文字

勾选 **Apply to all (4)**，选择 **Repeat text**，保留默认文字 **PREVIEW ONLY**。这次演示使用以下界面参数：

| 参数 | 设置 |
|---|---|
| Font size | 44 px |
| Direction | Diagonal |
| Opacity | 35% |
| Density | 36% |
| Spacing | 40% |
| Angle | 45° |
| 初始颜色 | #111827 |

![轻水印批量重复文字水印的实际参数界面](https://img.itch.zone/aW1nLzMxMjkyMjQ1LnBuZw==/original/4oeTTj.png)

这组参数只用于本次示例。按实际分享时的观看尺寸检查文字能否读清，以及是否遮住重要的产品细节。

## 3. 单独调整深色样图

取消勾选 **Apply to all**。点击 B 的缩略图，把文字颜色改为 **#ffffff**；再对 D 做同样调整。A/C 保持 **#111827**，字号、Opacity 与排列参数不变。

切换当前编辑图片时，保留四张图片的选择勾选框，使四张图都进入导出批次。

| 样图 | 背景与构图 | 实际导出尺寸 | 文字颜色 |
|---|---|---|---|
| A | 明亮背景，横图 | 1536 × 1024 | #111827 |
| B | 深色背景，横图 | 1536 × 1024 | #ffffff |
| C | 明亮背景，竖图 | 1024 × 1536 | #111827 |
| D | 深色背景，竖图 | 1024 × 1536 | #ffffff |

![实际导出：浅色横图上的深色 PREVIEW ONLY 重复水印](https://img.itch.zone/aW1nLzMxMjkyMjQ2LnBuZw==/original/gtpMGz.png)

![实际导出：深色竖图上的白色 PREVIEW ONLY 重复水印](https://img.itch.zone/aW1nLzMxMjkyMjQ3LnBuZw==/original/p39KDF.png)

D 的浅色文字在深背景上清楚，但经过银灰色瓶身时，对比会降低。因此要检查整张图片，不能只看背景区域。

## 4. 导出并打开文件检查

打开 **Export settings**，在 **Output folder** 旁点击 **Choose**，选择独立的 **exports** 文件夹。设置为：

- **File format：PNG**
- **Resize output：不勾选**
- **Preserve folder structure：不勾选**
- **Keep original filename**
- **Keep both files**

![轻水印 PNG 导出设置：保持原尺寸并使用独立目录](https://img.itch.zone/aW1nLzMxMjkyMjQ0LnBuZw==/original/TPRO46.png)

点击 **Save settings**，再点击 **Export all 4**。

本次输出目录中实际保存了四张 PNG。逐张打开后，四图均包含重复的 PREVIEW ONLY 文字，保留原像素尺寸，产品主体仍可辨认；四张输入原图未被修改。保留像素尺寸不等于承诺无损导出。

## 常见问题

**导出文件在哪里？**

在 **Export settings** 中选定的输出文件夹。本示例使用独立的 exports 文件夹，并保留原文件名。

**同一批图片为什么用了两种文字颜色？**

深色文字适合本次的明亮背景，白色文字在深背景上更容易看清。文字经过产品表面时，局部对比仍会变化。

**重复水印能保证无法移除吗？**

不能。它用于标记预览图，无法保证防止裁切、编辑、复制或移除。请保留干净原图。

## 下载与帮助

轻水印是付费软件。可选择 [itch.io 的 Windows 便携 ZIP](https://heykim.itch.io/watermark-lite)，或 [Microsoft Store 版本](https://apps.microsoft.com/detail/9P7ZDVBKJF4K?cid=wl_seo_github_preview_20261024_01)。两渠道需分别购买，Store 价格因地区而异。

另一个使用场景可参阅 [Logo 与文字水印教程](https://heykim.itch.io/watermark-lite/devlog/1724491/how-to-add-a-logo-and-text-to-product-photo-previews-on-windows)。安装帮助与问题反馈见 [GitHub 文档](https://github.com/nanguazhou123-star/Watermark-Lite-Windows)。

[英文实测图文教程](https://heykim.itch.io/watermark-lite/devlog/1726171/how-to-add-a-repeating-preview-only-watermark-to-client-photos-on-windows) · [中文使用指南](README.zh-CN.md) · [故障排查](TROUBLESHOOTING.md)
