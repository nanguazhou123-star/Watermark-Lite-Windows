# Watermark Lite for Windows

Watermark Lite is a Windows desktop app for adding text and logo watermarks to still images. Use it to prepare product-photo previews, label supplier samples or add photo credits, with a live preview and local batch export.

Developed by **HeyKim**. Microsoft Store publisher: **DaMiZhou Studio**. This repository provides public user documentation, FAQs and an issue tracker for the paid, proprietary application. Application source code and binaries are not distributed here.

[中文使用指南](README.zh-CN.md) · [Troubleshooting / 故障排查](TROUBLESHOOTING.md)

## Get the app

- [Microsoft Store](https://apps.microsoft.com/detail/9P7ZDVBKJF4K?cid=wl_geo_github_product_20261024_01) — purchase and install through the Store; regional pricing applies.
- [Official itch.io product page](https://heykim.itch.io/watermark-lite) — paid portable Windows ZIP.

The two purchase channels are separate. Buying through one does not grant the other channel's purchase. Refer to the selected product page for the current offer.

## Trial and paid editions

[Download the free 24-hour Windows trial](https://heykim.itch.io/watermark-lite#demo) to check your own images. The separate itch.io trial allows up to 3 workspace images at once, adds no extra Demo mark to exports during the trial, and keeps counting while the app is closed. After expiry, editing and preview remain available; new exports require the separately purchased full ZIP.

| Edition | Published package as of 26 October 2026 | Trial |
| --- | --- | --- |
| itch.io free trial | 2.0.3 | 24 hours from first launch; up to 3 images at once |
| itch.io paid full ZIP | 2.0.0 | No trial expiry in the full package |
| Microsoft Store | 2.0.2.0 | Separate 1-day Microsoft trial; the itch.io 3-image cap does not apply |

These version numbers track separate distributions and release/licensing revisions; they do not establish feature parity, missing functionality or future upgrade rights. [Compare trial and paid editions](TRIAL-VS-FULL.md) · [中文版本对照](TRIAL-VS-FULL.zh-CN.md).

## What it does

- Choose from **16 built-in templates**, including text, corner logos, combined logo-and-text layouts and repeating text.
- Adjust the controls available for the selected template, including text, logo, placement and opacity, and inspect the preview.
- Apply a setup across images and retain individual adjustments when compositions differ.
- Import images or a folder; export the current image or a selected batch.
- Work with still-image formats including JPG/JPEG, PNG, WebP and BMP. Export controls include dimensions, filenames, duplicate-name handling, and quality for JPG and WebP.

Image processing takes place on your computer, without cloud image uploads, an app account, ads or app telemetry. Purchase and download require internet access.

![Watermark Lite interface showing a logo and text layout](https://img.itch.zone/aW1nLzMxMjU0ODYzLnBuZw==/original/D7xAdI.png)

*Actual application interface with an AI-generated demonstration product photograph. Logo and brand text are placeholders. This illustrates placement, rather than a customer endorsement or a timed performance test.*

## Install the itch.io ZIP packages

The paid itch.io full ZIP **2.0.0** targets **Windows 10/11, x64**. Download it from the official product page, extract the **complete ZIP** into a folder, then run `WatermarkLite.exe` from that extracted folder. Keep the supporting files and subfolders together; do not move only the EXE or launch it inside the compressed archive.

English is the default for this paid full ZIP. Open **Settings** to select English or Simplified Chinese.

The separate itch.io trial **2.0.3** must also be fully extracted. Run `WatermarkLite-Demo.exe` from its extracted folder, keeping its supporting files together. On first use, this trial follows the system language; use **Settings** to choose English or Simplified Chinese.

## First workflow

1. Keep clean originals separately. Import the images or folder you want to process and check the imported count.
2. Choose a template. Enter text or load a logo you have permission to use; adjust placement, size and opacity using the available controls.
3. Check a landscape image, a portrait image and contrasting backgrounds. Apply the setup across the batch, then adjust individual images where needed.
4. Choose export format, dimensions, filename and duplicate-name handling. Select an output folder and export the current image or selected batch.
5. Open the output folder, count the files and inspect exported images at their intended viewing size before sending them.

## FAQ

**How large can a batch be?** In the paid full edition, folder and drag-and-drop imports are capped at **1,000 images per import**. This is an import limit, not a whole-queue limit or a promise that every computer can process 1,000 images reliably. Practical batch size and processing time depend on image dimensions, formats and available resources.

**Does it preserve GIF animation?** No. The app processes still images; GIF export contains a single static frame.

**Does a watermark prevent copying?** It can identify or label an image, but cannot guarantee protection against copying, cropping or removal. Check a marketplace's image rules before using watermarked listing photos.

**What are the device, team and update entitlements?** This guide does not define those purchase terms. Check the relevant product page and ask before buying if your intended use needs clarification. A one-time purchase is not a promise of lifetime upgrades or unlimited-device use.

**Where can I ask for help?** Read [troubleshooting](TROUBLESHOOTING.md), then use this repository's **Issues** tab or the public comments on the [itch.io product page](https://heykim.itch.io/watermark-lite). Do not post purchase receipts, credentials or private client images. No response-time guarantee is stated here.

## Related guides

- [English illustrated workflow: logo and text on product-photo previews](https://heykim.itch.io/watermark-lite/devlog/1724491/how-to-add-a-logo-and-text-to-product-photo-previews-on-windows)
- [English checklist for client photo previews](https://medium.com/@nanguazhou123/a-windows-checklist-for-adding-a-logo-and-text-to-client-photo-previews-d880ff0b9cbf)
- [中文图文教程：Windows 批量加水印](https://telegra.ph/Windows-批量加水印给客户样图添加-Logo-和文字-10-23)
- [English illustrated workflow: repeating PREVIEW ONLY watermarks on client photos](https://heykim.itch.io/watermark-lite/devlog/1726171/how-to-add-a-repeating-preview-only-watermark-to-client-photos-on-windows)
- [中文教程：重复 PREVIEW ONLY 水印](PREVIEW-ONLY.zh-CN.md)

These are developer-authored guides, not independent reviews. Documentation was prepared with Codex (OpenAI) assistance and checked against product information.

## 中文概述

轻水印用于在 Windows 本地给静态图片添加文字和 Logo，提供 16 个内置模板、预览和批量导出。这里是付费闭源应用的公开文档与反馈仓库。itch.io 付费完整 ZIP 2.0.0 须全部解压后运行 `WatermarkLite.exe`，默认英文；独立试用包 2.0.3 须全部解压后运行 `WatermarkLite-Demo.exe`，首次使用跟随系统语言。两者均可在 Settings 切换语言。完整步骤、限制和购买说明见[中文指南](README.zh-CN.md)。

