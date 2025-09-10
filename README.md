# Thrive 🚀
*AI-Powered Web App Builder*

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-Visit_Now-blue?style=for-the-badge)](https://thrive-gem.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)](https://github.com/amaansyed27/thrive)
[![Discord](https://img.shields.io/badge/Discord-Join_Community-7289da?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/pScgXrRu)

> Transform your ideas into fully functional web applications with the power of AI. Simply describe what you want to build, and Thrive handles the rest.

---

## ✨ What is Thrive?

Thrive is an intelligent web application builder that bridges the gap between imagination and implementation. Powered by Google's Gemini API, it generates complete, production-ready web applications from natural language descriptions — no coding experience required.

### 🎯 Perfect For
- **Rapid Prototyping** → Validate ideas in minutes, not hours
- **Learning & Education** → See how modern web apps are structured
- **Non-Technical Users** → Build without writing a single line of code
- **Developers** → Accelerate initial development and focus on customization

---

## 🌟 Key Features

### 🤖 **Intelligent Code Generation**
Turn natural language into complete web applications with HTML, CSS, and JavaScript — all optimized for modern browsers.

### 🔄 **Conversational Development**
Iterate on your app through chat:
- *"Add a navigation bar with dark theme"*
- *"Include a contact form with validation"*
- *"Make it mobile responsive"*

### ⚡ **Instant Live Preview**
Watch your application come to life in real-time as the AI generates and updates your code.

### 📝 **Integrated Code Editor**
- Syntax highlighting for HTML, CSS, and JavaScript
- Browse and modify generated files
- Full project structure visibility

### 📂 **Asset Management**
Upload images, fonts, and other assets directly into your project for complete customization.

### 📦 **One-Click Export**
Download your complete project as a ready-to-deploy ZIP file — no build process needed.

---

## 🛠 Technology Stack

| Component | Technology | Purpose |
|-----------|------------|---------|
| **Frontend** | React 18 + TypeScript | Modern, type-safe UI development |
| **Styling** | Tailwind CSS | Utility-first responsive design |
| **AI Engine** | Google Gemini API | Advanced code generation |
| **Build Tool** | Vite | Lightning-fast development |
| **Deployment** | Vercel | Seamless hosting and CI/CD |

---

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ 
- npm or yarn
- Google Gemini API key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/amaansyed27/thrive.git
   cd thrive
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env.local
   # Add your Google Gemini API key to .env.local
   ```

4. **Start development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:5173`

---

## 📖 Usage Guide

### Getting Started
1. **Describe Your App**: Type what you want to build in plain English
   - *"Create a portfolio website with a hero section and project gallery"*
   - *"Build a todo app with drag-and-drop functionality"*

2. **Watch It Generate**: The AI creates your complete application structure

3. **Iterate & Refine**: Chat with the AI to make changes:
   - Add new features
   - Modify styling
   - Improve functionality

4. **Export & Deploy**: Download your project and deploy anywhere

### Example Prompts
```
"Create a modern landing page for a tech startup with a hero section, 
features grid, testimonials, and contact form"

"Build a personal blog with dark mode, search functionality, 
and responsive design"

"Design a dashboard for an e-commerce admin panel with charts, 
data tables, and user management"
```

---

## 📁 Project Structure

```
thrive/
├── 📁 components/          # Reusable React components
│   ├── CodeEditor.tsx      # Integrated code editor
│   ├── ChatInterface.tsx   # AI conversation UI
│   └── PreviewPane.tsx     # Live app preview
├── 📁 services/           # Core application services
│   ├── gemini.ts          # Google Gemini API integration
│   ├── codeGenerator.ts   # Code generation logic
│   └── fileManager.ts     # File handling utilities
├── 📁 hooks/              # Custom React hooks
├── 📁 utils/              # Helper functions
├── 📁 types/              # TypeScript type definitions
├── 📄 App.tsx             # Main application component
├── 📄 main.tsx            # Application entry point
├── 📄 index.html          # HTML template
├── ⚙️ vite.config.ts       # Vite configuration
├── ⚙️ tailwind.config.js   # Tailwind CSS config
├── ⚙️ tsconfig.json       # TypeScript configuration
└── 📦 package.json        # Dependencies and scripts
```

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help make Thrive better:

### Development Setup
1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Make your changes and test thoroughly
4. Commit: `git commit -m 'Add amazing feature'`
5. Push: `git push origin feature/amazing-feature`
6. Open a Pull Request

### Contribution Areas
- 🐛 **Bug Fixes** - Help us squash bugs
- ✨ **New Features** - Add exciting functionality
- 📚 **Documentation** - Improve guides and examples
- 🎨 **UI/UX** - Enhance user experience
- 🧪 **Testing** - Add test coverage

### Code Standards
- Follow TypeScript best practices
- Use Tailwind CSS for styling
- Write clear, self-documenting code
- Add JSDoc comments for functions
- Ensure mobile responsiveness

---


## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

## 🙏 Acknowledgments

- **Google Gemini** for powering our AI capabilities
- **Vercel** for seamless deployment and hosting
- **React Team** for the amazing framework
- **Tailwind CSS** for the utility-first approach
- **Our Community** for feedback, bug reports, and contributions

---

## 💬 Community & Support

- 💬 **Discord**: [Join our community](https://discord.gg/pScgXrRu)
- 🐛 **Issues**: [Report bugs on GitHub](https://github.com/amaansyed27/thrive/issues)
- 💡 **Feature Requests**: [Suggest new features](https://github.com/amaansyed27/thrive/discussions)
- 📧 **Email**: [Contact the maintainer](mailto:amaansyed27@gmail.com)

---

<div align="center">

**Made with ❤️ by the Thrive Community**

[⭐ Star this project](https://github.com/amaansyed27/thrive) if you find it helpful!

</div>
