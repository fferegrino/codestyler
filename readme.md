# highlighted.codes - Syntax Highlighter

A simple web application to syntax highlight code in 20+ programming languages and copy it with colors preserved for pasting into Word, PowerPoint, and other rich text editors.

## Features

- 💻 **20+ Programming Languages** - Python, JavaScript, TypeScript, Java, C#, C++, C, PHP, Ruby, Go, Rust, Swift, Kotlin, SQL, Bash, PowerShell, R, MATLAB, CSS, HTML, JSON, YAML, Markdown
- 🎨 **Beautiful syntax highlighting** with 8 different color themes
- 🎭 **Dark and light themes** - Tomorrow Night, Okaidia, Twilight, Dark, Funky, Coy, Solarized Light, Default
- 📋 **One-click copy** with colors preserved for Word/PowerPoint
- 💾 **Remembers your preferences** - Saves your chosen language and theme
- 🎯 **Simple and intuitive** interface
- ✨ **Modern, responsive design**
- 🔄 **Real-time switching** - Change languages or themes instantly

## How to Use

1. **Open the application**: Simply open `index.html` in your web browser (Chrome, Firefox, Safari, or Edge)

2. **Select your programming language**: Choose from 20+ languages in the dropdown menu

3. **Choose a color theme** (optional): Select your preferred theme from the theme dropdown

4. **Paste your code**: Enter or paste your code into the text area

5. **Highlight the code**: Click the "✨ Highlight Code" button (or press Ctrl+Enter / Cmd+Enter)

6. **Copy the highlighted code**: 
   - Click the "📋 Copy Highlighted Code" button, OR
   - Select all the highlighted code and copy it manually (Ctrl+C / Cmd+C)

7. **Paste into Word/PowerPoint**: The syntax colors will be preserved!

**Tip:** You can switch languages or themes at any time, even after highlighting, and it will automatically re-highlight your code!

## Supported Languages

The app supports syntax highlighting for 20+ programming languages:

**General Purpose:**
- Python
- JavaScript
- TypeScript
- Java
- C#
- C++
- C
- PHP
- Ruby
- Go
- Rust
- Swift
- Kotlin

**Scripting & Shells:**
- Bash
- PowerShell

**Data & Analytics:**
- SQL
- R
- MATLAB

**Markup & Data:**
- HTML
- CSS
- JSON
- YAML
- Markdown

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

Your theme and language preferences are automatically saved and will be remembered the next time you visit!

## Technical Details

- Uses [Prism.js](https://prismjs.com/) for syntax highlighting
- Automatic language component loading - only loads what you need
- No backend required - runs entirely in the browser
- Uses the modern Clipboard API for copying HTML with formatting
- Fallback to older methods for broader browser compatibility
- Saves user preferences to localStorage

## Browser Compatibility

Works best in modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari

## Local Usage

No installation needed! Just double-click `index.html` to open it in your default browser.

## License

Free to use and modify as needed.

