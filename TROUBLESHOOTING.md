# Troubleshooting / 故障排查

Use these checks to describe and narrow a problem. They do not identify a confirmed defect or promise a fix.

## The portable app does not open / 便携版无法打开

Confirm Windows 10/11 x64. Extract the complete official ZIP to a folder and run `WatermarkLite.exe` there with all supporting files. If Windows displays a message, record its exact text and the download source; do not disable security protections to troubleshoot.

确认系统为 Windows 10/11 x64，完整解压官方 ZIP，并在保留全部支持文件的目录运行。记录系统提示原文与下载来源，不要为排查问题关闭安全防护。

## Language is unexpected / 界面语言不符

The itch.io EN ZIP defaults to English. Select English or Simplified Chinese in Settings. Include the purchase channel and selected setting in a report; distributions can differ.

itch.io 英文 ZIP 默认英文。在 Settings 选择 English 或 Simplified Chinese；反馈时说明购买渠道和当前设置。

## Images are missing after import / 导入后缺少图片

Compare the imported count with the source folder. Folder and drag-and-drop imports have a 1,000-image limit per import. Try a smaller group of supported still images, and record the file extensions, dimensions and import method. Keep originals intact.

核对源目录与导入数量。文件夹和拖放每次导入上限为 1,000 张。用较小一组支持的静态图片复查，记录格式、尺寸及导入方式，保留原图。

## Export differs from your expectation / 导出结果不符预期

Check the selected images, per-image adjustments, output folder, dimensions, format and duplicate-name handling. Open the exported files directly and compare a small batch first. JPG and WebP quality settings affect output. GIF export is a single static frame. If processing is slow, record batch size, image dimensions, format and computer memory; no universal processing speed is promised.

检查所选图片、单张调整、输出目录、尺寸、格式和重名处理。先导出少量图片，直接打开结果核对；JPG/WebP 的质量设置会影响输出。GIF 仅导出静态单帧。若处理较慢，记录数量、尺寸、格式和电脑内存。

## Report what happened / 提交反馈

Use this repository's Issues tab and the bug-report template, or public comments on the [official itch.io page](https://heykim.itch.io/watermark-lite). Include repeatable steps, expected and actual results, app version, Windows version and exact messages. A small non-sensitive sample can help; do not post receipts, credentials, private paths or client material. Feature requests have a separate template. No response deadline or release commitment is stated.

通过仓库 Issues 的问题模板，或 itch.io 官方产品页公开评论反馈。写清复现步骤、预期与实际结果、应用和 Windows 版本、提示原文。示例应不含敏感信息；不要公开订单、凭据、私人路径或客户素材。功能建议请用对应模板，此处不承诺响应期限或发布计划。
