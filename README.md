# Quarterly Earnings Report - RevealJS Presentation

A professional interactive presentation created with RevealJS showcasing quarterly earnings report with data visualizations, financial analysis, and technical demonstrations.

## Features

- **Interactive Slides**: Navigate with arrow keys or mouse
- **Markdown Support**: Structured content with Markdown syntax
- **Animated Fragments**: Gradual reveal of content for emphasis
- **Code Highlighting**: Syntax-highlighted Python code examples
- **Mathematical Equations**: Professional financial formulas using KaTeX
- **Speaker Notes**: Detailed presenter guidance accessible with 'S' key
- **Responsive Design**: Works on desktop, tablet, and presentation displays

## Presentation Contents

1. **Title Slide** - Introduction with presenter contact (21f3001699@ds.study.iitm.ac.in)
2. **Key Financial Metrics** - Revenue growth, profit margin, market share (Markdown)
3. **Challenges Faced** - Market volatility, regulatory changes
4. **Earnings Breakdown** - Quarterly earnings with animated fragments
5. **Data Analysis Code** - Python example with line number highlighting
6. **Financial Formulas** - ROI and Compound Interest calculations
7. **Future Projections** - Growth expectations with speaker notes

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| F | Fullscreen |
| S | Speaker notes |
| O | Overview mode |
| ESC | Escape overview |
| ? | Help |
| Space | Next slide |
| Arrow keys | Navigate |

## Local Viewing

Open `index.html` directly in a modern web browser.

## Deployment to GitHub Pages

### Prerequisites
- GitHub account
- Git installed locally

### Steps

1. **Initialize Git Repository**
   ```bash
   cd q1
   git init
   git add .
   git commit -m "Initial commit: Quarterly Earnings Presentation"
   ```

2. **Create GitHub Repository**
   - Go to https://github.com/new
   - Create a repository named `q1`
   - Do NOT initialize with README (you already have it)

3. **Push to GitHub**
   ```bash
   git remote add origin https://github.com/[YOUR_USERNAME]/q1.git
   git branch -M main
   git push -u origin main
   ```

4. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll to "Pages" section
   - Set source to "main" branch
   - Wait 1-2 minutes for deployment

5. **Access Your Presentation**
   ```
   https://[YOUR_USERNAME].github.io/q1/
   ```

## Technologies

- **RevealJS 4.5.0** - Presentation framework
- **KaTeX** - Mathematical typesetting
- **Highlight.js** - Code syntax highlighting
- **HTML5 & CSS3** - Modern web standards

## File Structure

```
q1/
├── index.html          # Main presentation
├── README.md           # Documentation
└── .gitignore          # Git ignore rules
```

## Requirements Met

✅ Email included (21f3001699@ds.study.iitm.ac.in)
✅ Markdown slides with structured content
✅ Animated fragments for visual emphasis
✅ Code samples with syntax highlighting
✅ Mathematical equations (ROI, Compound Interest)
✅ Speaker notes for presentation guidance
✅ GitHub Pages ready for publication

## Browser Support

Works best in:
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+

## Notes

- The presentation loads all assets from CDN for portability
- No build step required - works as-is
- MathJax renders equations in real-time
- Code highlighting supports multiple languages

For questions or modifications, edit the `index.html` file directly.
