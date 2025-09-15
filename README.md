# Chirun LaTeX Starter Template

A comprehensive LaTeX template designed specifically for creating lecture notes and educational content using [Chirun](https://chirun.org.uk/), the open-source tool that converts LaTeX documents to accessible HTML.

## 🎯 What is this template for?

This template serves as a starting point for anyone new to using Chirun. It contains LaTeX packages that have been tested and are known to be supported by Chirun, along with examples of commonly used features including:

- ✅ Sections and subsections
- ✅ Images with accessibility features (`\alttext`)
- ✅ Mathematical equations (rendered with MathJax)
- ✅ Tables with proper formatting
- ✅ Colored boxes for theorems and examples
- ✅ Code syntax highlighting
- ✅ Video embeds (YouTube/Vimeo)
- ✅ Scientific charts and diagrams (TikZ/PGFPlots)
- ✅ Custom HTML elements
- ✅ Citations and bibliography

## 🚀 Quick Start

1. **Download** – Download or clone this repository
2. **Edit** – Open `chirun-starter-template.tex` in your preferred LaTeX editor (VS Code, Overleaf, etc.)
3. **Customize** – Replace the placeholder content with your own material
4. **Upload** – Upload your file to the [Chirun LTI Tool](https://lti.chirun.org.uk/) to convert to HTML

## 📋 Prerequisites

- Basic knowledge of LaTeX
- Access to the Chirun conversion tool
- A LaTeX editor (recommended: VS Code with LaTeX Workshop extension, or Overleaf)

## 🎨 Features Demonstrated

### Accessibility
- **Alternative text for images** using `\alttext{}`
- **MathJax integration** for screen reader compatibility
- **Semantic HTML structure** in the output

### Mathematics
- Display equations with proper sizing
- Matrix representations
- Mathematical symbols and notation
- Golden ratio and Fibonacci sequence examples

### Visual Elements
- **Colored boxes** using `tcolorbox` package
- **Syntax-highlighted code** using `listings` package
- **Scientific plots** using TikZ and PGFPlots
- **Professional tables** using `booktabs` package

### Multimedia
- **YouTube video embeds** that work in HTML output
- **Custom HTML elements** for interactive content
- **Image handling** with proper captions and alt text

## 📦 Included Packages

The template includes these thoroughly tested packages:

| Package | Purpose | Status |
|---------|---------|--------|
| `chirun` | Accessibility features, video embeds | ✅ Core package |
| `amsmath`, `amssymb` | Mathematical notation | ✅ Full support |
| `tcolorbox` | Colored boxes and callouts | ✅ Re-implemented |
| `listings` | Code syntax highlighting | ✅ Basic support |
| `tikz`, `pgfplots` | Scientific diagrams and plots | ✅ Re-implemented |
| `booktabs` | Professional tables | ✅ Full support |
| `hyperref` | Links and cross-references | ✅ Full support |
| `graphicx` | Image handling | ✅ Full support |

## 🔧 Customization Tips

### Adding Your Own Content
- Replace the Fibonacci sequence examples with your subject matter
- Update the bibliography in `references.bib` with your sources
- Modify colors and styling to match your institution's branding
- Add or remove sections as needed

### Code Highlighting
The template includes a working code highlighting setup that's compatible with Chirun:

```latex
\begin{lstlisting}[language=Python, caption=Your code example]
# Your code here
def example_function():
    return "Hello, Chirun!"
\end{lstlisting}
```

### Math Equations
Use standard LaTeX math environments. The template demonstrates proper equation formatting:

```latex
\begin{equation}
E = mc^2
\end{equation}
```

## 🎓 Educational Use Cases

This template is perfect for:
- **Lecture notes** for mathematics, science, and engineering courses
- **Tutorial materials** with step-by-step explanations
- **Online course content** that needs to be accessible
- **Workshop handouts** combining text, equations, and code
- **Research documentation** with mathematical notation

## 🐛 Known Limitations

- **Syntax highlighting colors** may not display in some Chirun configurations
- **Complex TikZ diagrams** may need simplification for web compatibility  
- **Custom LaTeX packages** not in the supported list may cause issues

## 🤝 Contributing

Found a bug or have a suggestion? Please:
1. Open an issue describing the problem or enhancement
2. Submit a pull request with your improvements
3. Share your successful Chirun projects for inspiration!

## 📚 Resources

- [Chirun Documentation](https://chirun.org.uk/docs/en/latest/)
- [Chirun Sample Course](https://www.chirun.org.uk/demo/)
- [Chirun LTI Tool](https://lti.chirun.org.uk/)
- [LaTeX Package Documentation](https://chirun.org.uk/docs/en/latest/reference/latex/supported_packages.html)

## 📄 License

This template is provided under the MIT License. Feel free to use, modify, and distribute as needed for educational purposes.

## 🙏 Acknowledgments

- Built for the [Chirun project](https://chirun.org.uk/) by Newcastle University
- Inspired by the need for accessible educational content
- Thanks to the LaTeX and open-source communities

---

**Ready to create accessible, beautiful educational content?** Start with this template and let Chirun transform your LaTeX into engaging web-based materials! 🚀
