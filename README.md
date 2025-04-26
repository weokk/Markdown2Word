# Markdown2Word

A client-side HTML tool to convert Markdown text into Word-compatible HTML, with direct input and clipboard-to-clipboard functionality. Uses marked.js (v4.3.0).


## Simple Markdown to Word-Compatible HTML Converter

This is a single-file, client-side HTML tool designed to quickly convert Markdown text into HTML format that pastes well into Microsoft Word and similar rich-text editors, preserving basic formatting.

It provides a straightforward way to bridge the gap between writing in Markdown and needing to share or archive content in a Word document format, without requiring server-side processing or complex software installation.

**Features:**

*   **Direct Input:** Paste or type Markdown directly into a text area.
*   **HTML Preview:** Instantly see the HTML rendering of your Markdown.
*   **Copy HTML Output:** Copy the generated HTML (rich text) to the clipboard with a button click.
*   **⭐ One-Click Clipboard Workflow:**
    1.  Copy your Markdown text to the clipboard.
    2.  Click the "Golden Button".
    3.  The tool reads the Markdown, converts it, and copies the resulting Word-compatible HTML back to the clipboard automatically.
*   **Client-Side:** Runs entirely in your browser. No data is sent anywhere.
*   **Offline Use:** Save the HTML file and use it offline.
*   **Compatibility Focused:** Uses `marked.js v4.3.0` for better compatibility with various browser environments.

**How to Use:**

1.  Download or save the `markdown2word.html` file.
2.  Open the file in your web browser.
3.  **Option A (Text Area):**
    *   Paste/type your Markdown into the text area.
    *   Click "Convert Below Text Box Content".
    *   Click "Copy Preview Result to Clipboard".
4.  **Option B (Clipboard Workflow):**
    *   Copy your Markdown text from another source.
    *   Click the "⭐ One-Click Convert Clipboard Content" button (Allow clipboard access if prompted.Note: Safari browser may have clipboard permission issues. Please use Option A and it is recommended to use browsers like Chrome.).
5.  Switch to Microsoft Word (or Google Docs, etc.) and paste (Ctrl+V / Cmd+V).

**Technology:**

*   HTML
*   CSS
*   JavaScript
*   [marked.js (v4.3.0)](https://github.com/markedjs/marked)
*   Browser Clipboard API

---

**中文版:**


一个客户端 HTML 工具，用于将 Markdown 文本转换为 Word 兼容的 HTML，支持直接输入和剪贴板到剪贴板的一键操作。使用 marked.js (v4.3.0)。


## 简洁的 Markdown 转 Word 兼容 HTML 转换器

这是一个单文件的、纯客户端运行的 HTML 工具，旨在快速将 Markdown 文本转换为能够良好粘贴到 Microsoft Word 及类似富文本编辑器中并保留基本格式的 HTML。

它提供了一种简单直接的方式，来弥合使用 Markdown 写作与需要以 Word 文档格式分享或归档内容之间的鸿沟，无需服务器端处理或安装复杂软件。

**功能特性:**

*   **直接输入:** 在文本框中直接粘贴或输入 Markdown。
*   **HTML 预览:** 即时查看 Markdown 渲染后的 HTML 效果。
*   **复制 HTML 输出:** 通过按钮点击，将生成的 HTML (富文本) 复制到剪贴板。
*   **⭐ 一键剪贴板工作流:**
    1.  复制你的 Markdown 文本到系统剪贴板。
    2.  点击“黄金按钮”。
    3.  工具会自动读取剪贴板中的 Markdown，进行转换，并将结果（Word 兼容的 HTML）复制回剪贴板。
*   **纯客户端:** 完全在您的浏览器中运行，数据不会发送到任何地方。
*   **离线使用:** 保存此 HTML 文件即可离线使用。
*   **注重兼容性:** 使用 `marked.js v4.3.0` 版本，以提高对不同浏览器环境的兼容性。

**如何使用:**

1.  下载或保存此 `markdown2word.html` 文件 。
2.  在你的网页浏览器中打开该文件。
3.  **方式 A (使用文本框):**
    *   将 Markdown 粘贴/输入到文本区域。
    *   点击 “转换下方文本框内容” 按钮。
    *   点击 “复制下方预览结果到剪贴板” 按钮。
4.  **方式 B (剪贴板一键操作):**
    *   从其他地方复制你的 Markdown 文本。
    *   点击 “⭐ 一键转换剪贴板内容” 按钮 (如果浏览器提示，请允许访问剪贴板. 注：Safari浏览器可能有剪贴板权限控制问题，请使用方式A，建议使用Chrome等浏览器。)。
5.  切换到 Microsoft Word (或 Google Docs 等) 并粘贴 (Ctrl+V / Cmd+V)。

**技术栈:**

*   HTML
*   CSS
*   JavaScript
*   [marked.js (v4.3.0)](https://github.com/markedjs/marked)
*   浏览器剪贴板 API (Clipboard API)
