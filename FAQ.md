# FolderPDF FAQ / 常见问题

[English overview](README.md) · [中文说明](README.zh-CN.md)

This is a documentation-only repository. It contains neither FolderPDF source code nor executable downloads and does not grant an open-source software license.

本仓库仅提供产品说明，不包含 FolderPDF 源码或可执行文件，不授予软件开源许可。

## Where can I download FolderPDF? / 从哪里下载？

- [Portable download on itch.io / itch.io 便携版](https://heykim.itch.io/folderpdf)
- [Microsoft Store / 微软商店版](https://apps.microsoft.com/detail/9P0JF2BBK21B)

This FAQ describes the Windows x64 portable release 0.1.2 unless a section explicitly refers to Microsoft Store. Download pricing and availability are shown on the respective pages.

除单独注明 Microsoft Store 的部分外，本文以 Windows x64 便携版 0.1.2 为准。各渠道价格和下载情况以对应页面为准。

## Is there an English interface? / 有英文界面吗？

No. The application interface is currently Simplified Chinese only. These English documents describe the Chinese-interface application.

目前只有简体中文界面。英文文档是使用说明，不代表软件已有英文界面。

## Can I make one PDF per folder? / 能每个文件夹生成一份吗？

Yes. Add multiple image folders and choose one PDF per folder. Subfolders become separate tasks. You can instead combine the queued images into one PDF.

可以。添加多个图片文件夹后，选择每个文件夹一份；子文件夹也会分别成为任务。也可以将队列中的图片全部合成一份 PDF。

## How are pages sorted? / 页面如何排序？

File names use natural sort, such as `1`, `2`, `10`. Check the thumbnails and drag pages to adjust their order before exporting. Selected pages can be rotated or removed.

文件名按自然顺序排列，例如 `1、2、10`。导出前可以检查缩略图，拖动调整顺序，并旋转或移除选中页面。

## Does export include only selected pages? / 只导出勾选的页面吗？

No. Selection controls page editing. Export includes all remaining pages in every queued task. Remove unwanted pages before exporting.

不是。勾选用于页面编辑，导出包含所有任务中尚未移除的全部页面。不需要的页面请先移除。

## Are images uploaded or changed? / 图片会上传或被修改吗？

Image processing happens on your computer without uploading the images. Source files are not modified or deleted. A numbered suffix protects existing PDFs when an output name is already in use.

图片在本机处理，不上传、不修改或删除源文件。输出文件重名时会添加数字后缀，保留已有 PDF。

## What happens when a task fails? / 失败后怎么重试？

Check the reported image or task, fix the source image and retry failed tasks. Successful PDFs are kept. A failed combined document is retried as a whole. If you want to add new images, import them again.

根据提示检查对应图片或任务，修复源图片后重试失败项。成功 PDF 会保留；合并文档失败需要整份重试。需要新增图片时请重新导入。

## Which image formats work? / 支持哪些格式？

JPEG, PNG, WebP, single-page TIFF and AVIF, subject to decoding support. Existing PDFs, HEIC, BMP, SVG, animation and multipage images are not supported. OCR and editing existing PDFs are not included.

支持 JPEG、PNG、WebP、单页 TIFF、AVIF，具体以程序解码结果为准。不支持已有 PDF、HEIC、BMP、SVG、动画或多页图片，不含 OCR 和已有 PDF 编辑。

## Can it guarantee a small PDF? / 能保证压到指定大小吗？

No. The smaller-file preset can reduce detail; it does not target a fixed file size and may not produce a smaller result for every image. Use clarity for important small text and inspect the output. FolderPDF is not a general-purpose tool for compressing existing PDFs.

不能。较小文件预设可能损失细节，不保证固定体积，也不保证每次都更小。重要小字建议使用清晰优先并检查结果。本软件不提供已有 PDF 的通用压缩功能。

## What are the batch limits? / 一次能处理多少？

Up to 5,000 pages and 1,000 input paths. Each source image must be no larger than 100 million pixels or 256 MiB. Split large, high-resolution collections into smaller batches.

一次最多 5,000 页、1,000 个输入路径；单图不超过 1 亿像素或 256 MiB。大量高分辨率图片建议分批。

## Will my queue be restored after closing? / 关闭后能恢复队列吗？

No. Export settings and the last valid output folder are remembered, but the image queue is not saved between launches. Finish exporting before closing.

不能。软件记住导出设置和仍有效的保存目录，但不保存图片整理队列，关闭前请完成导出。

## How do I run the portable version? / 便携版如何运行？

Extract the entire ZIP and run `FolderPDF.exe` from its extracted application folder. Keep all files and the `resources` folder together. Do not move only the EXE. No separate runtime, app account or activation code is required. The portable application is not digitally signed.

完整解压 ZIP，在解压后的应用文件夹中运行 `FolderPDF.exe`。保留全部文件和 `resources` 文件夹，不要只复制 EXE。无需单独安装运行时、注册应用账号或输入激活码。便携程序未进行数字签名。

## Does the portable ZIP have a one-day trial? / 便携版也只有一天试用吗？

The itch.io download is the full portable application, without subscriptions or in-app purchases. Microsoft Store is a separate channel with Store-managed purchase and trial licensing. Its listing offers a one-day trial; check the current Store listing and your account for the applicable terms and expiration. Those Store terms do not impose a trial period on the standalone portable ZIP.

itch.io 下载的是完整便携版，没有订阅或内购。Microsoft Store 是独立渠道，由商店处理购买和试用许可，商店页面提供一天试用；具体条款和到期时间以当前商店页面与账户为准。该商店试用期限不适用于独立便携 ZIP。

## How can I get support? / 如何反馈问题？

Email **774244989@qq.com** with your download channel, version, image format and error text. Share sample images only if you are comfortable doing so.

请联系 **774244989@qq.com**，说明下载渠道、版本、图片格式和错误提示。请自行决定是否分享示例图片。
