# md2pdfpic

English | [简体中文](./README.md) | [繁體中文](./README_tc.md)

![Deploy gh-pages](https://github.com/abc1319/md2pdfpic/actions/workflows/deploy.yaml/badge.svg)

Enhanced Markdown to PDF converter with long image export feature.

**Live Demo:** https://abc1319.github.io/md2pdfpic/

## Features

- ✅ **Markdown to PDF**: Convert your Markdown documents to PDF format
- ✅ **Long Image Export**: NEW! Export your Markdown as a long image (PNG format)
- ✅ **Live Preview**: Real-time preview of your Markdown content
- ✅ **Syntax Highlighting**: Code blocks with syntax highlighting
- ✅ **File Import**: Import existing Markdown files
- ✅ **Responsive Design**: Works on desktop and mobile devices

## New in This Version

This is an enhanced version of the original md2pdf project with the following improvements:

1. **Long Image Export**: Added the ability to export Markdown content as a long image using html2canvas
2. **Improved UI**: Redesigned header with three distinct action buttons:
   - 📁 **Import**: Import Markdown files
   - 📄 **Export as PDF**: Convert to PDF format
   - 🖼️ **Export as Long Image**: Convert to image format
3. **Better User Experience**: Streamlined interface without dropdown menus

## Usage

1. **Write or Import**: Type your Markdown content in the left panel or import an existing file
2. **Preview**: See the live preview in the right panel
3. **Export**: Choose your preferred export format:
   - Click "导出为PDF" to save as PDF
   - Click "导出为长图" to save as a long image

## Technology Stack

- React 16.14.0
- styled-components
- react-remarkable (Markdown parsing)
- highlight.js (Syntax highlighting)
- html2canvas (Image export)
- CodeMirror (Editor)
- github-markdown-css (Styling)

## Development

```bash
# Install dependencies
npm install

# Start development server
npm start

# Build for production
npm run build
```

## License

MIT License

## Credits

Based on the original [md2pdf](https://github.com/realdennis/md2pdf) project by realdennis.
Enhanced with long image export functionality by iBigQiang.
