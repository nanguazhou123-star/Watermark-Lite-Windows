# 轻水印 Watermark Lite：Windows 使用指南

[English](README.md) · [故障排查](TROUBLESHOOTING.md)

轻水印是一款给静态图片添加文字和 Logo 水印的 Windows 桌面应用，适合整理商品预览图、标记供应商样图或添加摄影署名。开发者为 **HeyKim**，Microsoft Store 发布者为 **DaMiZhou Studio**。本仓库提供公开使用文档、常见问题与反馈入口；应用为付费闭源软件，仓库不分发应用源码或二进制。

## 购买与运行

- [Microsoft Store](https://apps.microsoft.com/detail/9P7ZDVBKJF4K?cid=wl_geo_github_product_20261024_01)：通过商店购买安装，价格以所在地区页面为准。
- [itch.io 官方产品页](https://heykim.itch.io/watermark-lite)：购买便携 ZIP。

两个渠道分别购买，一个渠道的购买不包含另一个渠道的购买权益。设备数、团队使用与未来升级范围以购买渠道的明确说明为准；本指南不增加授权条款。

itch.io ZIP 面向 **Windows 10/11 x64**。下载后将**整个 ZIP 全部解压**到文件夹，在解压后的目录运行 `WatermarkLite.exe`，保留同目录支持文件和子目录。不要只复制 EXE，也不要直接在压缩包中启动。此 ZIP 默认英文，可在 **Settings** 选择 **Simplified Chinese**；也可选择 English。

## 试用与完整包

[下载免费 24 小时 Windows 试用包](https://heykim.itch.io/watermark-lite#demo)，先用自己的图片检查效果。itch.io 独立试用包工作区同时最多 3 张，试用期导出不额外添加 Demo 标记，关闭软件后继续计时。到期仍可编辑和预览，新导出需要另行购买并使用完整 ZIP。

| 发行渠道与版本 | 2026 年 10 月 26 日已发布包版本 | 试用说明 |
| --- | --- | --- |
| itch.io 免费试用包 | 2.0.3 | 首次启动起 24 小时，同时最多 3 张 |
| itch.io 付费完整 ZIP | 2.0.0 | 完整包没有试用到期限制 |
| Microsoft Store | 2.0.2.0 | 微软独立授权的 1 天试用，不适用 itch.io 的 3 张限制 |

这些版本号分别记录不同发行包及其发行、授权机制的迭代，不据此承诺功能完全相同、完整包缺少功能或未来升级权益。详见[试用版与付费版对照](TRIAL-VS-FULL.zh-CN.md) · [English comparison](TRIAL-VS-FULL.md)。

## 能做什么

16 个内置模板包含文字、角落 Logo、Logo＋文字和重复文字布局。可按所选模板提供的控件调整内容、位置、大小和透明度，查看预览，将设置应用到一批图片，并按需保留单张调整。可导入图片或文件夹，导出当前图片或所选批次。

静态图片格式包括 JPG/JPEG、PNG、WebP 和 BMP。导出设置包含尺寸、文件名、重名处理，JPG 与 WebP 可调质量。图片在电脑本地处理，无需应用账号，没有应用内广告、云端图片上传或应用遥测；购买和下载仍需联网。

## 从导入到交付

1. 单独保留干净原图，导入本次要处理的图片或文件夹，核对数量。
2. 选模板，输入文字或载入有权使用的 Logo，再调整位置、大小和透明度。
3. 检查横图、竖图及明暗背景，应用到批次后逐张查看；遇到遮挡主体或文字时单独调整。
4. 设置导出格式、尺寸、命名和重名处理，选择输出文件夹，再导出当前图片或所选批次。
5. 打开输出文件夹核对文件数，实际打开导出图片，检查文字、Logo 和最终尺寸。

![真实软件界面中的 Logo 与文字布局](https://img.itch.zone/aW1nLzMxMjU0ODYzLnBuZw==/original/D7xAdI.png)

*这是实际应用界面；商品照片为 AI 生成的演示素材，Logo 和品牌文字为占位内容，用于展示位置，不代表客户背书或性能测试。*

## 常见问题

**批量数量有限制吗？** 付费完整包的文件夹和拖放导入每次上限为 1,000 张。这不是整个队列的上限，也不是稳定处理 1,000 张的性能承诺。实际批量大小和耗时取决于图片与电脑资源。

**GIF 可以保留动画吗？** 不可以，GIF 导出只有一帧静态图片。

**水印能保证防盗吗？** 不能保证防止复制、裁剪或移除。上架商品前请检查目标平台及具体展示位置的图片规则。

**如何反馈？** 先看[故障排查](TROUBLESHOOTING.md)，再通过仓库 Issues 或 itch.io 产品页公开评论描述问题。不要公开订单、凭据或客户私密图片；这里不承诺响应时限。

## 图文教程

- [中文完整教程](https://telegra.ph/Windows-批量加水印给客户样图添加-Logo-和文字-10-23)
- [英文操作教程](https://heykim.itch.io/watermark-lite/devlog/1724491/how-to-add-a-logo-and-text-to-product-photo-previews-on-windows)
- [英文客户样图检查清单](https://medium.com/@nanguazhou123/a-windows-checklist-for-adding-a-logo-and-text-to-client-photo-previews-d880ff0b9cbf)
- [英文实测教程：重复 PREVIEW ONLY 水印](https://heykim.itch.io/watermark-lite/devlog/1726171/how-to-add-a-repeating-preview-only-watermark-to-client-photos-on-windows)
- [中文教程：重复 PREVIEW ONLY 水印](PREVIEW-ONLY.zh-CN.md)

这些内容为开发者自述，并非独立评测。文档由 Codex（OpenAI）辅助整理并按产品资料核对。

