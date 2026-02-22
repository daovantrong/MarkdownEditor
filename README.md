# Markdown Editor - Markdown ↔ HTML Converter Suite

A comprehensive collection of web-based tools for seamless conversion between Markdown and HTML formats. This project includes three specialized converters with live preview, syntax highlighting, and modern UI design.

## 🚀 Features

- **Live Conversion**: Real-time bidirectional conversion between Markdown and HTML
- **Syntax Highlighting**: Powered by PrismJS for both Markdown and HTML code
- **Dual Panel Interface**: Side-by-side editing with synchronized scrolling
- **Multiple View Modes**: Edit mode, rendered preview, and code view
- **Dark/Light Themes**: Toggle between dark and light themes
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Export Options**: Download files as `.md` or `.html` formats
- **Copy to Clipboard**: Quick copy functionality for converted content
- **No Server Required**: Pure client-side JavaScript applications

## 📁 Project Structure

```
markdown-editor/
├── html-to-markdown.html          # HTML → Markdown converter (live sync)
├── markdown-to-html.html         # Markdown → HTML converter (live sync)
├── md-html-converter.html         # Bidirectional converter suite
├── README.md                      # This file
└── LICENSE                        # MIT License
```

## 🛠️ Tools Overview

### 1. HTML → Markdown Converter (`html-to-markdown.html`)
- **Purpose**: Convert HTML code to Markdown format
- **Features**: Live conversion, rendered HTML view, Markdown preview
- **Technology**: Turndown.js, PrismJS, Marked.js
- **UI**: Split panel with HTML input (left) and Markdown output (right)

### 2. Markdown → HTML Converter (`markdown-to-html.html`)
- **Purpose**: Convert Markdown to HTML format
- **Features**: Live conversion, Markdown preview, HTML code view
- **Technology**: Marked.js, PrismJS
- **UI**: Split panel with Markdown input (left) and HTML output (right)

### 3. Markdown Editor Suite (`md-html-converter.html`)
- **Purpose**: Comprehensive bidirectional converter
- **Features**: Manual conversion buttons, multiple libraries support
- **Technology**: Marked.js, Turndown.js, Showdown.js, PrismJS
- **UI**: Advanced interface with conversion controls and tabbed views

## 🎨 Design Features

### Visual Design
- Modern dark/light theme system
- Gradient accents and subtle grid backgrounds
- Smooth animations and transitions
- Professional typography using Syne and JetBrains Mono fonts

### User Interface
- Intuitive split-panel layout
- Tab-based view switching (Edit/Preview/Code)
- Responsive toolbar with action buttons
- Toast notifications for user feedback
- Flash animations on successful conversions

### Accessibility
- Semantic HTML structure
- Keyboard navigation support
- High contrast color schemes
- Responsive breakpoints for all devices

## 🧩 Technical Stack

### Core Libraries
- **Marked.js** (v9.1.6): Markdown to HTML parsing
- **Turndown.js** (v7.1.2): HTML to Markdown conversion
- **Showdown.js** (v2.1.0): Alternative Markdown parser
- **PrismJS** (v1.29.0): Syntax highlighting for multiple languages

### Supported Languages
- Markdown
- HTML/Markup
- JavaScript
- Python
- CSS
- Bash
- JSON

### Frontend Technologies
- HTML5 semantic structure
- CSS3 with custom properties
- Vanilla JavaScript (ES6+)
- CSS Grid and Flexbox layouts
- Web APIs (Clipboard, Blob, URL)

## 📱 Responsive Design

### Desktop (>900px)
- Full split-panel layout
- Complete toolbar functionality
- Optimized for large screens

### Tablet (≤900px)
- Compact header
- Reduced button sizes
- Maintained split layout

### Mobile (≤640px)
- Stacked vertical layout
- Touch-optimized controls
- Simplified interface

### Small Mobile (≤380px)
- Further compacted layout
- Grid-based footer buttons
- Minimal spacing

## 🚀 Getting Started

### Quick Start
1. Clone or download this repository
2. Open any HTML file in your web browser
3. Start converting immediately - no installation required

### Local Development
```bash
# Clone the repository
git clone https://github.com/your-username/markdown-editor.git

# Navigate to the project directory
cd markdown-editor

# Open any converter in your browser
open html-to-markdown.html
# or
open markdown-to-html.html
# or
open md-html-converter.html
```

### Using the Tools

#### HTML → Markdown Converter
1. Paste HTML code in the left panel
2. Watch live conversion to Markdown in the right panel
3. Switch between Code and Rendered views for HTML
4. Switch between Edit and Preview views for Markdown
5. Copy or download the converted Markdown

#### Markdown → HTML Converter
1. Type or paste Markdown in the left panel
2. See live HTML conversion in the right panel
3. Use preview tabs to see rendered output
4. Copy or download the generated HTML

#### Markdown Editor Suite
1. Choose your conversion direction with the central buttons
2. Input content in the respective panel
3. Click conversion buttons to transform content
4. Use tabs to switch between edit and preview modes
5. Export results using the footer actions

## 🎯 Use Cases

- **Content Migration**: Convert between HTML and Markdown formats
- **Documentation Writing**: Write in Markdown, export to HTML
- **Blog Publishing**: Convert HTML blog posts to Markdown
- **Code Documentation**: Format code examples with syntax highlighting
- **Educational Tools**: Learn Markdown and HTML relationships
- **Content Management**: Batch convert documents between formats

## 🔧 Customization

### Theme Customization
The applications use CSS custom properties for easy theming:
```css
:root {
  --bg: #0d0f14;           /* Background */
  --surface: #131720;      /* Panel backgrounds */
  --accent: #4fffb0;       /* Primary accent */
  --accent2: #ff6b6b;      /* Secondary accent */
  --accent3: #7eb8ff;      /* Tertiary accent */
}
```

### Adding New Languages
Add PrismJS language support:
```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/components/prism-YOUR-LANGUAGE.min.js"></script>
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📞 Support

If you encounter any issues or have questions:
1. Check the browser console for errors
2. Ensure you're using a modern browser with JavaScript enabled
3. Verify that CDN resources are accessible

## 🙏 Acknowledgments

- **Marked.js** - Excellent Markdown parser
- **Turndown.js** - Robust HTML to Markdown converter
- **Showdown.js** - Alternative Markdown implementation
- **PrismJS** - Beautiful syntax highlighting
- **Google Fonts** - Syne and JetBrains Mono typography

---
## ☕ Support My Work
Enjoying this open-source HTML script?
- [Buy me a 🍻](https://buymeacoffee.com/trong)
- Tip via ❤️ [PayPal](https://paypal.me/DaoVanTrong)

---
**Created by Đào Văn Trong**  
© 2026 - MIT License

