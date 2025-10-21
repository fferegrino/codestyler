# Python Code Styler

A simple web application to syntax highlight Python code and copy it with colors preserved for pasting into Word, PowerPoint, and other rich text editors.

## Features

- 🎨 Beautiful syntax highlighting for Python code
- 📋 One-click copy with colors preserved
- 💾 Works offline (uses CDN but can be saved locally)
- 🎯 Simple and intuitive interface
- ✨ Modern, responsive design

## How to Use

1. **Open the application**: Simply open `index.html` in your web browser (Chrome, Firefox, Safari, or Edge)

2. **Paste your Python code**: Enter or paste your Python code into the text area

3. **Highlight the code**: Click the "✨ Highlight Code" button (or press Ctrl+Enter / Cmd+Enter)

4. **Copy the highlighted code**: 
   - Click the "📋 Copy Highlighted Code" button, OR
   - Select all the highlighted code and copy it manually (Ctrl+C / Cmd+C)

5. **Paste into Word/PowerPoint**: The syntax colors will be preserved!

## Technical Details

- Uses [Prism.js](https://prismjs.com/) for syntax highlighting
- No backend required - runs entirely in the browser
- Uses the modern Clipboard API for copying HTML with formatting
- Fallback to older methods for broader browser compatibility

## Browser Compatibility

Works best in modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari

## Local Usage

No installation needed! Just double-click `index.html` to open it in your default browser.

## License

Free to use and modify as needed.

