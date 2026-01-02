# 📑 Gemini Paper CopyEditor | Gemini 论文润色工坊

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://streamlit.io)
![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Gemini](https://img.shields.io/badge/AI-Google%20Gemini-orange)

**Gemini Paper CopyEditor** is an intelligent academic writing assistant built with Streamlit and Google Gemini models. It allows researchers to upload Word documents, polish text section by section, view "Track Changes" style diffs, and export the result back to a clean Word document.

**Gemini 论文润色工坊** 是一个基于 Streamlit 和 Google Gemini 模型构建的智能学术写作辅助工具。它允许研究人员上传 Word 文档，按章节逐段润色，查看类似 Word 的“修订模式”差异对比，并一键导出润色后的完美文档。

---

## ✨ Features | 功能特点

* **📄 Smart Parsing (智能解析)**: Automatically splits `.docx` files into sections based on Heading styles (Heading 1, 2...).
    * 自动根据 Word 的标题样式（标题 1、2...）将文档拆分为独立的章节。
* **🔍 Track Changes (修订追踪)**: Visualizes changes with a red/green highlight system, similar to Word's track changes.
    * 提供类似 Word 修订模式的差异对比视图，直观显示删除（红色）和新增（绿色）的内容。
* **🤖 Multi-Model Support (多模型支持)**: Switch between `Gemini 3.0 Flash` (Best Quality) and `Gemini 2.5 Flash` (Fastest).
    * 支持在 Gemini 3.0 Flash（质量最佳）和 Gemini 2.5 Flash（速度最快）之间自由切换。
* **✍️ Dual Modes (双模式)**: Upload a file or paste text directly for quick fixes.
    * 支持“上传文件”和“直接粘贴文本”两种模式，满足不同场景需求。
* **📥 One-Click Export (一键导出)**: Compiles all sections (original or polished) into a new `.docx` file.
    * 将所有章节（包括未修改的和已润色的）重新打包，一键导出为新的 Word 文档。

---
