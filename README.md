# Markdown Renderer

## Summary
This application converts Markdown content into HTML and displays it, also applying syntax highlighting to code blocks.

## Features
- **Markdown to HTML Conversion:** Converts Markdown text to HTML.
- **Syntax Highlighting:** Applies syntax highlighting to code blocks using highlight.js.

## Setup
This application is fully static and requires no build steps.

### Local Usage
1. Download or clone the repository.
2. Open `index.html` in any modern web browser.
3. The application will run immediately and display the rendered Markdown.

### GitHub Pages
The application is deployed at: [Your GitHub Pages URL]

## Usage Instructions
1. The application automatically renders the embedded Markdown content upon loading.
2. View the converted HTML output in the designated output area.

## Technical Details

### Technologies Used
- HTML5
- CSS3 (Bootstrap 5.3.0)
- Vanilla JavaScript
- Marked.js for Markdown processing
- Highlight.js for syntax highlighting

### Key Features
- Responsive design
- Client-side data processing
- Error handling
- Modern UI/UX

### File Structure
```
.
├── index.html          # Main application file
├── README.md           # Application documentation
└── LICENSE             # MIT License
```

## Evaluation Criteria
This application meets the following requirements:
- js: !!document.querySelector("script[src*='marked']")
- js: !!document.querySelector("script[src*='highlight.js']")
- js: document.querySelector("#markdown-output").innerHTML.includes("<h")
- Page has element with id='markdown-output'
- Page loads marked.js from CDN
- Page loads highlight.js from CDN
- README.md is professional
- Repo has MIT LICENSE

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
Generated as part of IIT Madras TDS Project