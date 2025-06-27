# AI Code Hub 🧠

A comprehensive web-based platform for exploring AI, Machine Learning, and Data Science study materials through an elegant, modern interface with GitHub integration.

## ✨ Key Features

- **🎨 Glassmorphism UI** - Modern glass-effect design with advanced gradients
- **🔍 Smart Search** - Real-time filtering of topics and concepts  
- **📚 GitHub Integration** - Direct access to repository notebooks and content
- **🚀 Performance Optimized** - Lazy loading, responsive design, full accessibility
- **📱 Mobile Ready** - Touch-friendly interface for all devices

## 🏗️ Core Architecture

**`docs/index.html`** - Main application entry point with modular CSS/JS architecture

**`docs/config.js`** - GitHub API configuration:
```javascript
const GITHUB_USER = 'efrat-dev';
const GITHUB_REPO = 'ai-code-notebooks';
const NOTEBOOKS_FOLDER = 'notebooks/';
```

**`docs/variables.css`** - Advanced design system with 17+ gradient themes and glassmorphism variables

## 🛠️ Quick Start

1. **Clone and setup:**
   ```bash
   git clone https://github.com/efrat-dev/ai-code-notebooks.git
   cd ai-code-notebooks
   ```

2. **Configure (optional):**
   Edit `docs/config.js` to point to your repository

3. **Open in the browser:**

Since this project is based on static files (HTML, CSS, and JavaScript),  
you can easily preview it by right-clicking on `index.html` and selecting: **"Open with Live Server"** 

## 🎨 Design Highlights

**Colors:** Ocean blues (#5a9fd4), pink accents (#ff7eb3), sky blue (#87ceeb)  
**Typography:** Orbitron headers, Inter body text, JetBrains Mono code  
**Effects:** Glassmorphism, animated gradients, floating particles

## 📚 Full Documentation

For comprehensive documentation including:
- Complete architecture breakdown
- Detailed feature descriptions  
- Advanced customization options
- Technical specifications
- Contributing guidelines
- Mobile optimization details

**👉 [View Complete Documentation](./DOCUMENTATION.md)**

## 🤝 Quick Contributing

1. **Content** - Add notebooks to `notebooks/` folder
2. **Features** - Extend JavaScript modules in `scripts/`
3. **Design** - Customize variables in `variables.css`

## 📄 License

MIT License - Open source and community-driven

---

*For detailed setup, architecture, and advanced features, see [DOCUMENTATION.md](DOCUMENTATION.md)*
