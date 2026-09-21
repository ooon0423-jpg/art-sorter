<p align="center"><img src="docs/icon.png" width="96" alt="Art Sorter icon"></p>

<h1 align="center">Art Sorter</h1>

<p align="center"><b>Sort thousands of illustrations, fan art and AI-generated images by character and scene. Fully offline, on Windows.</b></p>

<p align="center">
<a href="https://orilabs.studio/artsorter/?utm_source=github">Website</a> ·
<a href="https://orilabs.studio/artsorter/get/?utm_source=github">Download for Windows</a> ·
<a href="https://orilabs.studio/artsorter/guides/?utm_source=github">Guides</a> ·
<a href="README.ko.md">한국어</a> · <a href="README.ja.md">日本語</a> · <a href="README.zh.md">简体中文</a>
</p>

<p align="center"><img src="docs/before-after.jpg" alt="The same images before and after Art Sorter: mixed up on the left, lined up by character and scene on the right" width="820"></p>

Drop in a folder. Art Sorter looks at the pictures, not the file names, and lines them up in one order: same character together, then same scene, then in sequence. Copies, including resized ones, are set aside. Everything runs on your own PC.

> This repository holds documentation and the public issue tracker. Art Sorter itself is a closed-source desktop app with a free trial.

## What it does

- **Groups by character.** A model trained on illustrations keeps the same character together across different sessions and artists.
- **Then by scene and sequence.** Inside each character, images are ordered by scene and then in sequence.
- **Sets duplicates aside.** Identical copies and resized, converted or re-saved versions go to their own folder so you can compare and decide. Nothing is deleted.
- **Adds without re-sorting.** New images slot in next to the ones they resemble. The order you already fixed stays.
- **Uses where files came from.** If most images from one folder, or with one file-name pattern, land in one group, the few that drifted away are brought back.
- **Name a group once.** Select images, type a name, and they are renamed together. Pin sets you never want touched.
- **Undo everything.** Every step can be undone, and moved files return to their original folders in one click.
- **Exports tags.** Hydrus sidecars, XMP for digiKam and XnView MP, Eagle, or CSV. Originals are never modified.
- **Handles big collections.** Tens of thousands of images in one run, with pause and resume.
- **18 interface languages.**

[![Watch the 2.5-minute demo](docs/sort-animation-poster.jpg)](https://youtu.be/OSMyfuTyGz8)

A real run: 113 demo images (3 characters, 4 scenes each) sorted in about two and a half minutes on a laptop, with 2 images out of place at the end.

## Who it is for

- People who generate a lot with **Stable Diffusion, NovelAI, Midjourney or ComfyUI** and want outputs separated by character and scene.
- People with thousands of images saved from **X, Pixiv or Discord** under random names.
- Collectors of **manga panels, CG sets and screenshots** who want them in a chosen order.
- Anyone whose folders turned into nested archives inside archives.

## Privacy

Art Sorter is a desktop program, not a web service. There is no account and no upload. Images, file names and folder names never leave your PC. After a one-time download of the analysis models on first run, it works with the internet off.

What goes online without asking: update checks, that one-time model download, and license checks with an anonymous PC code.

## Requirements

| | |
|---|---|
| OS | Windows 10 / 11 (64-bit) |
| Memory | 8 GB (16 GB recommended for 30,000+ images) |
| Disk | About 1.5 GB. Installer 200 MB, analysis models 840 MB downloaded once |
| Graphics | Optional. Any DirectX 12 GPU is used automatically |

## Pricing

- The first **300 images are free**. No account, no card.
- After that, a **one-time purchase** (not a subscription). One PC per key, all updates included.
- See the [pricing section](https://orilabs.studio/artsorter/?utm_source=github#pricing) for the current price.

## How it works (short version)

Three models run locally with ONNX Runtime (DirectML on Windows when a GPU is available):

1. A tagger reads each image (characters' features, clothing, setting).
2. A character-similarity model (CCIP) decides which images show the same character.
3. A scene model orders images within a character by background and outfit, then by sequence.

Duplicates are found with a perceptual hash, so size and format changes do not hide them.

## Guides

- [How to organize thousands of AI-generated images](https://orilabs.studio/artsorter/guides/organize-ai-images/?utm_source=github)
- [Find duplicate images, including resized copies](https://orilabs.studio/artsorter/guides/find-duplicate-images/?utm_source=github)
- [Sort anime and fan art images by character](https://orilabs.studio/artsorter/guides/sort-by-character/?utm_source=github)
- [Eagle alternative for large illustration folders](https://orilabs.studio/artsorter/guides/eagle-alternative/?utm_source=github)
- [Hydrus alternative without the learning curve](https://orilabs.studio/artsorter/guides/hydrus-alternative/?utm_source=github)

## Feedback and bug reports

Found a folder where it gets things wrong? That is the most useful thing you can tell us. Please [open an issue](../../issues/new/choose) with how many images, roughly what kind, and what went wrong. Screenshots are welcome, but please do not attach images you would not want public.

Email: contact@orilabs.studio

## FAQ

**Is it open source?** No. This repository is for documentation and issues. The models it uses are public models.

**Is there a Mac or Linux version?** Windows only for now.

**Does it change my original files?** In copy mode your originals are untouched. In move mode everything can be restored to its original place in one click.

**Does it know character names?** It groups images of the same character, and you name them. Name one group and it suggests the name for similar ones.

---

Made by OriLabs Studio (오리랩스), a one-person studio in Korea.
