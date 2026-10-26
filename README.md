# FolderPDF — one PDF per folder on Windows

[简体中文](README.zh-CN.md) · [FAQ](FAQ.md)

FolderPDF turns folders of images into PDF documents on Windows x64. Create **one PDF per folder** in a batch, or combine the queued images into one PDF. It is useful for product photos, design references, photographed receipts and scanned images.

**Documentation only.** This repository contains product documentation, not application source code or executable downloads. It does not grant an open-source software license for FolderPDF.

## Download

- [FolderPDF portable on itch.io](https://heykim.itch.io/folderpdf) — this guide covers the 0.1.2 Windows x64 portable download. See the download page for its current price and availability.
- [FolderPDF on Microsoft Store](https://apps.microsoft.com/detail/9P0JF2BBK21B) — a separate distribution with Store-managed purchase and trial licensing. The Store listing offers a one-day trial; check the listing and your Store account for current terms and the actual expiration time.

The portable download is the full portable application. It does not require an app account or activation code and has no subscription or in-app purchases. Microsoft Store trial terms do not apply to this portable ZIP.

**Interface language: Simplified Chinese only.** English documentation does not mean that an English application interface is available.

## Make a PDF for each image folder

1. Download `FolderPDF-0.1.2-Windows-x64.zip` from the itch.io page and extract the entire archive.
2. Open `FolderPDF-win32-x64-v0.1.2` and run `FolderPDF.exe`. Keep all files and the `resources` folder together. No separate runtime installation is required. The portable application is not digitally signed.
3. Add your image folders. Subfolders become separate tasks. File names use natural sort: for example, `1`, `2`, `10`.
4. Check the thumbnails, double-click for a larger view, and drag pages to change their order. Rotate or remove selected pages as needed; the most recent removal can be undone.
5. Choose one PDF per folder or one combined PDF, choose a page size and output folder, then generate the PDFs.
6. Check each output's actual page count and file size. If an image or task fails, fix the source image and retry failed tasks. Successful PDFs are kept; a failed combined document must be retried as a whole.

Page selection is for editing. Export includes **all remaining pages in every queued task**, not only checked thumbnails.

## Output and local image processing

- Image processing takes place on your computer without uploading your images. Source images are not modified or deleted.
- Existing output PDFs are protected by adding a numbered suffix to new files with the same name.
- Choose fit-to-image, A4 or Letter. A4 and Letter preserve image proportions, add margins and do not crop the image.
- Choose clarity or a smaller-file preset. The smaller-file preset may lose detail and does not guarantee a fixed KB/MB size or a smaller result for every image. Use clarity for important small text and inspect the PDF.
- Export settings and the last valid output folder are remembered. The image queue is not saved between launches; finish exporting before closing.

## Supported files and limits

Inputs: JPEG, PNG, WebP, single-page TIFF and AVIF, subject to decoding support.

Existing PDFs, HEIC, BMP, SVG, animated images and multipage images are not supported. FolderPDF does not include OCR, editing of existing PDFs or general-purpose PDF compression.

A batch supports up to 5,000 pages and 1,000 input paths. Each source image must be at most 100 million pixels and 256 MiB. Split large, high-resolution collections into smaller batches.

## Illustrated tutorial

[How to Convert Multiple Image Folders into Separate PDFs on Windows](https://heykim.itch.io/folderpdf/devlog/1730911/how-to-convert-multiple-image-folders-into-separate-pdfs-on-windows) includes a 24-second real-screenshot walkthrough and a Simplified Chinese summary.

## Help

See the [FAQ](FAQ.md). For support, email **774244989@qq.com**. When reporting a problem, include the download channel, version, image format and error text. Avoid sending private images unless you choose to share them.
