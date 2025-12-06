# 🎨 Website Creator

<div align="center">

![Website Creator](https://img.shields.io/badge/Version-1.0.0-blue.svg)
![Angular](https://img.shields.io/badge/Angular-19.2.19-red.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

**A modern, intuitive drag-and-drop website builder built with Angular**

[Features](#-features) • [Demo](#-demo) • [Installation](#-installation) • [Usage](#-usage) • [Roadmap](#-roadmap)

</div>

---

## ✨ Features

### 🎯 Current Features (v1.0)

- **🎨 Beautiful UI/UX**
  - Clean, minimalist "Relax Mind" light theme
  - Soft color palette with calming blues and whites
  - Smooth animations and transitions
  - Responsive design

- **📊 Dashboard**
  - View all your projects at a glance
  - Quick access to recent projects
  - Filter projects (All, Published, Drafts)
  - Create new projects with one click

- **🏗️ Drag & Drop Builder**
  - Intuitive drag-and-drop interface
  - Real-time component preview
  - Visual canvas for building pages
  - Component library sidebar

- **🧩 Components**
  - **Text Block** - Add and customize text content
  - **Button** - Interactive call-to-action buttons
  - **Image** - Add images with placeholder support
  - **Container** - Organize content in containers

- **📱 Responsive Design**
  - Device preview toggles (Desktop, Tablet, Mobile)
  - Adaptive layout system

## 🚀 Demo

### Dashboard View
The dashboard provides a clean overview of all your projects with easy navigation.

### Builder Interface
Drag components from the sidebar and drop them onto the canvas to build your website visually.

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** (v18 or higher)
- **npm** (v9 or higher)
- **Angular CLI** (v19 or higher)

## 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/macamisp/website-creator-.git
   cd website-creator-
   ```

2. **Navigate to the frontend directory**
   ```bash
   cd frontend
   ```

3. **Install dependencies**
   ```bash
   npm install
   ```

4. **Start the development server**
   ```bash
   npm start
   ```

5. **Open your browser**
   ```
   Navigate to http://localhost:4200
   ```

## 💻 Usage

### Creating a New Project

1. Click the **"Create New Site"** card on the dashboard
2. You'll be redirected to the builder interface

### Building Your Website

1. **Drag Components**: Select a component from the left sidebar
2. **Drop on Canvas**: Drag it to the canvas area in the center
3. **Preview**: See your changes in real-time
4. **Device Toggle**: Switch between Desktop, Tablet, and Mobile views

### Available Components

| Component | Description | Icon |
|-----------|-------------|------|
| Text Block | Add paragraphs and text content | 📝 |
| Image | Insert images into your page | 🖼️ |
| Button | Add interactive buttons | 🔘 |
| Container | Group and organize content | 📦 |

## 🏗️ Project Structure

```
website-creator-/
├── frontend/                  # Angular application
│   ├── src/
│   │   ├── app/
│   │   │   ├── core/         # Core modules (Layout, Components)
│   │   │   │   ├── layout/
│   │   │   │   │   └── main-layout/
│   │   │   │   └── components/
│   │   │   │       ├── header/
│   │   │   │       └── sidebar/
│   │   │   ├── features/     # Feature modules
│   │   │   │   ├── dashboard/
│   │   │   │   │   └── dashboard-home/
│   │   │   │   └── builder/
│   │   │   │       ├── builder-canvas/
│   │   │   │       └── services/
│   │   │   │           └── drag-drop.service.ts
│   │   │   ├── shared/       # Shared modules
│   │   │   ├── app.component.*
│   │   │   └── app.routes.ts
│   │   ├── styles.css        # Global styles
│   │   └── index.html
│   ├── angular.json
│   └── package.json
├── README.md
└── VERSION_2_PLAN.md
```

## 🎨 Design System

### Color Palette

```css
--bg-primary: #f8fafc      /* Soft White/Slate 50 */
--bg-secondary: #ffffff    /* Pure White */
--bg-tertiary: #f1f5f9     /* Slate 100 */

--text-primary: #334155    /* Slate 700 */
--text-secondary: #64748b  /* Slate 500 */
--text-accent: #60a5fa     /* Blue 400 */

--primary-color: #60a5fa   /* Calming Blue */
--primary-hover: #3b82f6   /* Blue 500 */
```

### Typography

- **Font Family**: Inter (Google Fonts)
- **Font Weights**: 400 (Regular), 500 (Medium), 600 (Semibold), 700 (Bold)

## 🛣️ Roadmap

### Version 2.0 (Planned)

- [ ] **Component Editing**
  - Inline text editing
  - Properties panel for styling
  - Real-time preview

- [ ] **Component Management**
  - Delete components
  - Reorder components
  - Undo/Redo functionality

- [ ] **Project Persistence**
  - Save projects to localStorage
  - Load saved projects
  - Export HTML/CSS code

- [ ] **Enhanced Components**
  - Headings (H1, H2, H3)
  - Paragraphs
  - Links
  - Dividers
  - Cards

- [ ] **Template System**
  - Pre-built templates
  - Template preview
  - Quick start from templates

- [ ] **Advanced Features**
  - Layers panel
  - Zoom controls
  - Responsive breakpoint editor

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**macamisp**

- GitHub: [@macamisp](https://github.com/macamisp)
- Repository: [website-creator-](https://github.com/macamisp/website-creator-)

## 🙏 Acknowledgments

- Built with [Angular](https://angular.dev/)
- Styled with custom CSS
- Icons from Unicode Emoji
- Inspired by modern website builders

## 📞 Support

If you have any questions or need help, please open an issue in the GitHub repository.

---

<div align="center">

**Made with ❤️ by macamisp**

⭐ Star this repo if you find it helpful!

</div>
