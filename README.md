# FastLorem

A fast, simple lorem ipsum generator that creates random placeholder text instantly. Perfect for designers, developers, and content creators who need dummy text quickly.

## Features

- **Instant Generation**: Random lorem ipsum text on every page load/refresh
- **One-Click Copy**: Copy all generated text to clipboard with a single click
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **No Dependencies**: Single HTML file with everything embedded
- **GitHub Pages Ready**: Deploy instantly with zero configuration

## Live Demo

[View Live Demo](https://yourusername.github.io/fastlorem) *(Replace with your actual GitHub Pages URL)*

## Quick Start

1. **Clone or Download**: Get the repository files
2. **Open**: Simply open `index.html` in any modern browser
3. **Use**: Click "Generate New Text" or refresh to get new content
4. **Copy**: Click "Copy to Clipboard" to copy the text

## GitHub Pages Deployment

### Option 1: Upload Files
1. Create a new GitHub repository
2. Upload `index.html` to the repository
3. Go to repository Settings → Pages
4. Select "Deploy from a branch" → "main" → "/ (root)"
5. Your site will be available at `https://yourusername.github.io/repositoryname`

### Option 2: Fork and Deploy
1. Fork this repository
2. Go to Settings → Pages in your forked repo
3. Enable GitHub Pages from the main branch
4. Access your site at `https://yourusername.github.io/fastlorem`

## Local Development

No build process required! Simply:

```bash
# Open the file in your browser
open index.html

# Or serve with a simple HTTP server
python -m http.server 8000
# Then visit http://localhost:8000
```

## Browser Support

- ✅ Chrome 70+
- ✅ Firefox 65+  
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers

## Technical Details

### Architecture
- **Single File**: Everything contained in `index.html`
- **Vanilla JavaScript**: No frameworks or libraries
- **CSS Grid/Flexbox**: Modern responsive layout
- **Clipboard API**: Modern copy functionality with fallback

### Performance
- **Zero HTTP Requests**: All assets embedded
- **Fast Loading**: Typically loads in under 500ms
- **Lightweight**: Total file size under 15KB

### Customization
The application generates:
- **3-7 paragraphs** per generation
- **3-8 sentences** per paragraph
- **8-20 words** per sentence
- **150+ unique words** in the lorem ipsum vocabulary

## File Structure

```
fastlorem/
├── index.html          # Complete application
├── README.md          # This file
└── PRD.md             # Product Requirements Document
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## FAQ

**Q: Does this work offline?**
A: Yes! Once loaded, the application works completely offline.

**Q: Can I customize the number of paragraphs?**
A: Currently, the count is randomized automatically. Custom controls may be added in future versions.

**Q: Why doesn't the copy button work?**
A: Make sure you're using a modern browser and the site is served over HTTPS (required for Clipboard API).

**Q: Can I use this for commercial projects?**
A: Yes! Lorem ipsum text is placeholder content meant for design and development purposes.

## Support

If you encounter any issues or have suggestions:
1. Check the [PRD.md](PRD.md) for detailed specifications
2. Open an issue on GitHub
3. Submit a pull request with improvements

---

Made with ❤️ for the developer community. Happy coding!