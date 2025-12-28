# ✍️ MarkNote

<div align="center">

![MarkNote Banner](https://img.shields.io/badge/MarkNote-Markdown%20Note%20Taking%20App-blue?style=for-the-badge&logo=markdown)

**A beautiful, feature-rich Markdown note-taking application with live preview, folder organization, and seamless export options.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](https://opensource.org/licenses/MIT)

[Features](#-features) • [Demo](#-demo) • [Installation](#-installation) • [Usage](#-usage) • [Keyboard Shortcuts](#-keyboard-shortcuts) • [Export Options](#-export-options) • [Contributing](#-contributing)

</div>

---

## 📸 Demo

<div align="center">

| Light Mode | Dark Mode |
|:----------:|:---------:|
| ![Light Mode](https://raw.githubusercontent.com/MajnuRangeela/MarkNote/refs/heads/main/resources/light.png) | ![Dark Mode](https://raw.githubusercontent.com/MajnuRangeela/MarkNote/refs/heads/main/resources/dark.png) |

</div>

> 🔗 **Live Demo**: [View MarkNote Live](https://majnurangeela.github.io/MarkNote) *(Add your deployed link here)*

---

## ✨ Features

### 📁 Folder Organization
- Create custom folders to organize your notes
- Click to filter notes by folder
- Visual note count per folder
- Easy folder management with delete option

### 🔍 Powerful Search
- Real-time search across all notes
- Searches through titles, content, and tags
- Instant filtering as you type

### 🏷️ Tag System
- Add multiple tags to any note
- Filter notes by clicking on tags
- Easy tag management
- Tags displayed on note cards

### 📝 Live Markdown Preview
- Side-by-side editor and preview
- Real-time rendering as you type
- Full GitHub Flavored Markdown support:
  - Headings, bold, italic, strikethrough
  - Ordered and unordered lists
  - Task lists with checkboxes
  - Code blocks with syntax highlighting
  - Tables with beautiful styling
  - Blockquotes with elegant design
  - Links and images
  - Horizontal rules

### 🎨 Beautiful Preview Styling
- Magazine-quality typography
- Gradient-styled headings
- Custom bullet points and numbered lists
- macOS-style code blocks with window dots
- Elegant blockquotes with decorative quotes
- Hover effects on tables and links

### 📋 One-Click Code Copy
- Copy button on every code block
- Works in both preview and exported HTML
- Visual feedback with "Copied!" confirmation

### 🌓 Dark/Light Theme
- Toggle between dark and light modes
- Theme preference saved locally
- Smooth transitions between themes
- Syntax highlighting adapts to theme

### 📤 Multiple Export Options
- **Markdown (.md)** - Original markdown format
- **HTML (.html)** - Fully styled standalone webpage with:
  - Dark mode toggle button
  - Theme persistence
  - Syntax highlighted code
  - Copy buttons on code blocks
- **PDF** - Print-optimized styling

### 💾 Auto-Save
- All notes saved automatically to localStorage
- No data loss on browser refresh
- Instant save on every keystroke

---

## 🚀 Installation

### Option 1: Direct Download
1. Download the `index.html` file
2. Open it in any modern web browser
3. Start taking notes!

### Option 2: Clone Repository
```bash
# Clone the repository
git clone https://github.com/yourusername/marknote.git

# Navigate to the project
cd marknote

# Open in browser
open index.html
# or on Linux
xdg-open index.html
# or on Windows
start index.html
```

### Option 3: Use a Local Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

---

## 📖 Usage

### Creating Notes
1. Click the **"New Note"** button or press `Ctrl/Cmd + N`
2. Enter a title for your note
3. Start writing in Markdown in the editor
4. See your formatted note in real-time in the preview panel

### Organizing with Folders
1. Click the **folder icon** next to "Folders" to create a new folder
2. Select a folder from the dropdown when editing a note
3. Click on a folder in the sidebar to filter notes

### Adding Tags
1. In the tag input field, enter tags separated by commas
2. Example: `work, important, project-x`
3. Click on tags in the sidebar to filter notes

### Formatting Toolbar
Use the formatting buttons above the editor:
| Button | Action | Markdown |
|--------|--------|----------|
| **B** | Bold | `**text**` |
| *I* | Italic | `*text*` |
| H | Heading | `## text` |
| 🔗 | Link | `[text](url)` |
| `</>` | Code | `` `code` `` |
| ☰ | List | `- item` |

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl/Cmd + N` | Create new note |
| `Ctrl/Cmd + S` | Save notes (auto-saves anyway) |
| `Ctrl/Cmd + B` | Bold selected text |
| `Ctrl/Cmd + I` | Italicize selected text |

---

## 📤 Export Options

### Markdown Export (.md)
- Exports the raw markdown content
- Perfect for use in other markdown editors
- Maintains all formatting syntax

### HTML Export (.html)
Creates a beautiful standalone webpage with:
- ✅ All your content beautifully styled
- ✅ Dark/Light mode toggle button
- ✅ Theme preference saved to localStorage
- ✅ Syntax-highlighted code blocks
- ✅ Copy buttons on code blocks
- ✅ Responsive design
- ✅ No external dependencies (all styles inline)

### PDF Export
- Opens print dialog for saving as PDF
- Optimized print styles
- Tables won't break across pages
- Clean, professional output

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | Structure |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | Styling |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | Functionality |
| ![TailwindCSS](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) | Utility Styling |
| [Marked.js](https://marked.js.org/) | Markdown Parsing |
| [Highlight.js](https://highlightjs.org/) | Syntax Highlighting |
| [Font Awesome](https://fontawesome.com/) | Icons |

---

## 📂 Project Structure

```
marknote/
├── index.html      # Single-file application (all HTML, CSS, JS)
└── README.md       # Documentation
```

---

## 🌟 Markdown Examples

Try these in your notes:

### Headings
```markdown
# Heading 1
## Heading 2
### Heading 3
```

### Text Formatting
```markdown
**Bold text**
*Italic text*
~~Strikethrough~~
`inline code`
```

### Lists
```markdown
- Unordered item 1
- Unordered item 2

1. Ordered item 1
2. Ordered item 2

- [x] Completed task
- [ ] Pending task
```

### Code Block
````markdown
```javascript
function greet(name) {
    console.log(`Hello, ${name}!`);
}
```
````

### Table
```markdown
| Name | Role | Status |
|------|------|--------|
| Alice | Developer | Active |
| Bob | Designer | Active |
```

### Blockquote
```markdown
> This is a beautiful blockquote
> that spans multiple lines.
```

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### Ideas for Contributions
- [ ] Cloud sync support
- [ ] Note sharing via URL
- [ ] Markdown templates
- [ ] Full-text search with fuzzy matching
- [ ] Keyboard navigation
- [ ] Import from other note apps
- [ ] Mobile-responsive improvements
- [ ] PWA support for offline use

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 MarkNote

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 💖 Acknowledgements

- [Marked.js](https://marked.js.org/) - Fast markdown parser
- [Highlight.js](https://highlightjs.org/) - Syntax highlighting
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS
- [Font Awesome](https://fontawesome.com/) - Beautiful icons

---

<div align="center">

**Made with ❤️ by developers, for developers**

⭐ Star this repo if you find it useful!

</div>
