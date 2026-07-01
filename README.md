# English Reader

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-176b5b?style=for-the-badge)](https://jiahehu2000-lgtm.github.io/English-reader/)
[![Research Paper Reader](https://img.shields.io/badge/Research-Paper%20Reader-a65d12?style=for-the-badge)](https://jiahehu2000-lgtm.github.io/English-reader/)

A browser-based research paper reader for importing academic PDFs, extracting paper structure, clicking words for Chinese translation, saving vocabulary, and exporting notes or word lists.

If this project helps you, please consider giving it a Star:

[Star this project on GitHub](https://github.com/jiahehu2000-lgtm/English-reader)

## Live Demo

https://jiahehu2000-lgtm.github.io/English-reader/

## Features

- Import research papers by pasting text, uploading TXT, or uploading PDF.
- OCR scanned PDF pages in the browser with Tesseract.js.
- Extract paper body text and optionally stop before References.
- Detect Title, Abstract, Introduction, Methods, Results, Discussion, Conclusion, and other common sections.
- Navigate the paper by detected section headings.
- Generate high-frequency technical term candidates.
- Click words in the reading area to show Chinese translations.
- Save unfamiliar words to a local vocabulary notebook with frequency counts and examples.
- Export vocabulary as CSV, JSON, or TXT.
- Save and export paper notes with title, abstract, section outline, and term candidates.
- Keep imported text, notes, and vocabulary in each user's browser local storage.

## 中文说明

这是一个面向科研论文阅读的浏览器工具：

- 可以导入论文 PDF/TXT，也可以直接粘贴英文正文。
- 扫描版 PDF 可以指定页码范围后在浏览器本地 OCR。
- 自动识别论文标题、摘要、章节，并默认跳过 References。
- 右侧提供论文助手：摘要、章节导航、术语候选和论文笔记。
- 点击正文英文单词显示中文释义。
- 生词本会统计单词记录次数，支持 CSV、JSON、TXT 导出。
- 数据保存在用户自己的浏览器里，不需要登录。

如果你觉得这个工具有用，欢迎点 Star：

https://github.com/jiahehu2000-lgtm/English-reader

## Privacy

The app is static and runs in the browser. Vocabulary data, notes, and imported article text are stored in local storage on each user's device. OCR also runs in the browser.

## Copyright Note

This repository provides a reader tool only. Do not publish copyrighted papers, textbooks, IELTS materials, or extracted full text unless you have the rights to do so.

## Local Use

Open `index.html` directly in a browser.
