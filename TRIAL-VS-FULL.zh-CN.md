# 轻水印试用版与付费版对照

[English](TRIAL-VS-FULL.md) · [中文使用指南](README.zh-CN.md) · [故障排查](TROUBLESHOOTING.md)

轻水印在 Windows 10/11 x64 上给静态图片添加可见的文字和 Logo 水印。可先用 itch.io 的独立试用包检查自己的图片，也可选择由微软单独授权的 Microsoft Store 版本。

## 当前发行包

以下版本信息核对日期为 2026 年 10 月 26 日。当前价格和优惠以各购买渠道页面为准。

| 发行渠道与版本 | 已发布包版本 | 试用期限 | 图片数量限制 |
| --- | --- | --- | --- |
| itch.io 免费 Windows 试用包 | 2.0.3 | 首次启动起 24 小时 | 工作区同时最多 3 张 |
| itch.io 付费完整便携 ZIP | 2.0.0 | 完整包没有试用到期限制 | 文件夹或拖放每次导入最多 1,000 张 |
| Microsoft Store | 2.0.2.0 | 微软商店 1 天试用，资格和授权由微软管理 | 不适用 itch.io 试用包的 3 张限制 |

- [在 itch.io 下载免费 Windows 试用包](https://heykim.itch.io/watermark-lite#demo)。
- [查看付费完整 ZIP 和 itch.io 当前价格](https://heykim.itch.io/watermark-lite)。
- [查看 Microsoft Store 的试用、购买与地区价格](https://apps.microsoft.com/detail/9P7ZDVBKJF4K?cid=wl_seo_github_trial_20261026_01)。

itch.io 与 Microsoft Store 分别购买，一个渠道的购买不包含另一个渠道的购买权益。

## itch.io 试用包可以检查什么

试用从首次启动开始计时，关闭软件后继续计时。24 小时内可同时处理最多 3 张图片，选择 16 个内置模板，预览设置并导出结果。

试用期导出不会额外添加 Demo 标记。用户自己设置的文字或 Logo 水印仍会出现在导出图片中。

到期后仍可编辑和预览，但新导出需要另行购买并使用完整 ZIP。试用包不会自动变成完整包。

付费完整包没有试用到期限制。文件夹或拖放每次最多导入 1,000 张，这只是导入上限，不保证每台电脑都能稳定处理 1,000 张。实际批量大小和耗时取决于图片尺寸、格式和可用资源。

## Microsoft Store 采用独立试用与授权

已发布的 Store 包通过微软授权提供 1 天试用。试用资格、购买权益和到期状态均独立于 itch.io 本地试用包。不能把 itch.io 的 3 张限制或本地计时机制套用于 Store。

请以所在地区的产品页面和电脑上的 Microsoft Store 应用所显示的账户可用方案为准。itch.io 试用说明不用于判断 Store 授权状态。

## 为什么版本号不同

itch.io 付费完整包为 2.0.0，独立试用包为 2.0.3，Store 包为 2.0.2.0。这些数字分别记录不同发行包及其发行、授权机制的迭代，不能只按数字判断功能是否完全相同、完整包是否缺少功能或未来升级权益。

一次性购买不等于承诺终身升级、无限设备或新增商用授权。具体权益以相应购买页面为准；有特殊用途请在购买前确认。

## 本地处理与联网

图片在电脑本地处理，不会上传到云端。下载和购买需要联网。本地图片处理不等于 Microsoft Store 授权一定能离线使用，Store 离线授权尚未完成验证。

## 先用少量图片检查

单独保留干净原图。选择最多 3 张横竖或明暗背景不同的图片，检查水印是否清晰，再导出并打开结果，核对尺寸和位置。

- [Logo 与文字商品预览图教程（英文）](https://heykim.itch.io/watermark-lite/devlog/1724491/how-to-add-a-logo-and-text-to-product-photo-previews-on-windows)。
- [重复 PREVIEW ONLY 水印教程（中文）](PREVIEW-ONLY.zh-CN.md)。

这些内容为开发者自述，并非独立评测。文档由 Codex（OpenAI）辅助整理并按已发布版本核对。
