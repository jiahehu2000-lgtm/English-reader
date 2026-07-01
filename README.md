# English Reader

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-176b5b?style=for-the-badge)](https://jiahehu2000-lgtm.github.io/English-reader/)
[![Research Paper Reader](https://img.shields.io/badge/Research-Paper%20Reader-a65d12?style=for-the-badge)](https://jiahehu2000-lgtm.github.io/English-reader/)

English Reader is a browser-based research paper reading assistant. It helps you import academic PDFs, extract paper structure, read English text with click-to-translate support, save unfamiliar words, and export vocabulary or paper notes.

Live site:

https://jiahehu2000-lgtm.github.io/English-reader/

If this project helps you, please consider giving it a Star:

https://github.com/jiahehu2000-lgtm/English-reader

## What It Does

- Imports research paper PDFs, TXT files, or pasted English text.
- Runs OCR on scanned PDF pages in the browser with Tesseract.js.
- Extracts paper body text and can stop before `References`.
- Detects common paper structure: Title, Abstract, Introduction, Methods, Results, Discussion, Conclusion, and related sections.
- Shows a paper assistant panel with abstract, section navigation, technical term candidates, and notes.
- Lets you click English words to view Chinese translations.
- Saves unfamiliar words to a local vocabulary notebook.
- Tracks how many times each word is recorded.
- Exports vocabulary as CSV, JSON, or TXT.
- Exports paper notes with title, abstract, outline, terms, and your notes.
- Stores data locally in your browser. No account or backend is required.

## How To Use

1. Open the live site:

   https://jiahehu2000-lgtm.github.io/English-reader/

2. Import a paper:

   - Upload a PDF.
   - Upload a TXT file.
   - Or paste English text directly into the input box.

3. Choose the document mode:

   - `科研论文`: best for academic papers.
   - `雅思阅读`: keeps the older IELTS reading extraction mode.
   - `完整文本`: keeps the full extracted text without trimming.

4. Read and translate:

   - Click any English word in the reading area.
   - View the Chinese translation on the right.
   - Click `加入生词本` to save it.
   - Use the vocabulary notebook to search, sort, count, and export words.

5. Use the paper assistant:

   - Read the detected Abstract.
   - Jump by section heading.
   - Review high-frequency technical terms.
   - Write paper notes.
   - Export notes as TXT.

## Scanned PDF / OCR

If the PDF is a scanned image and cannot be extracted directly:

1. Enter the page range you want to OCR, for example `3-12`.
2. Click `OCR 当前 PDF`.
3. Wait for OCR to finish.
4. The reader will try to extract the paper body from the OCR text.

OCR runs in the browser, so large page ranges can be slow. Use a smaller page range when possible.

## Current Limitations

- The current version mainly reads extracted text.
- Figures, tables, formulas, and original paper layout are not yet shown in the main reading area.
- OCR quality depends on PDF image clarity.
- Translation uses a small built-in dictionary first, then an online translation fallback.
- Vocabulary and notes are stored in the current browser only.

## Planned Next Step

The next major version should become a PDF preview reader, closer to tools like Zhiyun:

- Left side: original PDF page preview with figures, tables, formulas, and layout.
- Right side: word translation, sentence translation, vocabulary notebook, paper notes, abstract, section outline, and figure/table captions.
- PDF.js text layer: click or select text directly on the original PDF page.
- Keep the current vocabulary and note system.

## 中文说明

English Reader 是一个面向科研论文阅读的浏览器工具。

它目前可以：

- 导入论文 PDF、TXT 或粘贴的英文文本。
- 扫描版 PDF 可以指定页码范围后在浏览器本地 OCR。
- 自动识别论文标题、摘要、章节，并默认跳过 References。
- 右侧提供论文助手：摘要、章节导航、术语候选、论文笔记。
- 点击正文英文单词显示中文释义。
- 把生词加入生词本，并统计记录次数。
- 导出生词本 CSV、JSON、TXT。
- 导出论文笔记。

使用入口：

https://jiahehu2000-lgtm.github.io/English-reader/

目前它还不是完整的 PDF 原版预览器。下一步会把主阅读区升级成 PDF.js 原版预览，让你边看论文图片、表格、公式和排版，边用右侧工具查词、翻译和做笔记。

## Privacy

The app is static and runs in the browser. Imported text, vocabulary, translations, and notes are stored in local storage on each user's device. OCR also runs in the browser.

## Copyright Note

This repository provides a reader tool only. Do not publish copyrighted papers, textbooks, IELTS materials, or extracted full text unless you have the rights to do so.

## Local Use

Open `index.html` directly in a browser.
