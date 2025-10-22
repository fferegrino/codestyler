# Python Code Styler

A simple web application to syntax highlight Python code and copy it with colors preserved for pasting into Word, PowerPoint, and other rich text editors.

## Features

- 🎨 Beautiful syntax highlighting for Python code with multiple themes
- 🎭 8 different color themes to choose from (dark and light options)
- 📋 One-click copy with colors preserved
- 💾 Remembers your preferred theme
- 🎯 Simple and intuitive interface
- ✨ Modern, responsive design

## How to Use

1. **Open the application**: Simply open `index.html` in your web browser (Chrome, Firefox, Safari, or Edge)

2. **Choose a theme** (optional): Select your preferred color theme from the dropdown menu at the top

3. **Paste your Python code**: Enter or paste your Python code into the text area

4. **Highlight the code**: Click the "✨ Highlight Code" button (or press Ctrl+Enter / Cmd+Enter)

5. **Copy the highlighted code**: 
   - Click the "📋 Copy Highlighted Code" button, OR
   - Select all the highlighted code and copy it manually (Ctrl+C / Cmd+C)

6. **Paste into Word/PowerPoint**: The syntax colors will be preserved!

## Available Themes

The app includes 8 different color themes:

**Dark Themes:**
- Tomorrow Night (default) - Modern dark theme with vibrant colors
- Okaidia - Sublime Text inspired dark theme
- Twilight - Calm purple-based dark theme
- Dark - Classic dark theme

**Light Themes:**
- Coy - Clean light theme with subtle colors
- Solarized Light - Popular light theme with warm tones
- Default - Classic Prism light theme

**Special:**
- Funky - Colorful and bold theme

Your theme preference is automatically saved and will be remembered the next time you visit!

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

