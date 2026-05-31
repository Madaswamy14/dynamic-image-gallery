# 📸 LensFlow - Dynamic Image Gallery

**LensFlow** is a curated digital art and photography archive built with **React** and **Vanilla CSS**. It provides a premium, responsive, and highly interactive user experience for exploring breathtaking high-resolution photography from around the world.

---

## ✨ Features

- 🖥️ **Responsive Grid Layout**: Fully fluid 4-column photo grid that automatically adjusts to a 2-column layout on smaller screens and mobile devices.
- 🎨 **Dynamic Micro-Interactions**: Hover over cards to trigger smooth state changes (inverting to clean dark themes with high-contrast text).
- 🔍 **Interactive Search**: An integrated search bar component prepared for filtering visual content.
- ⚓ **Elegant Navigation & Structure**: A modern dark navbar featuring responsive link items, an informational About section, and a professional Footer with full contact integration.
- ⚡ **Optimized Asset Delivery**: Powered by dynamic placeholder imaging from *Picsum Photos* to showcase beautiful, lightweight mockup visual media.

---

## 🛠️ Technology Stack

- **Core Framework**: [React 19](https://react.dev/)
- **Styling Engine**: Vanilla CSS 3 (using custom Flexbox, CSS Grid, and dynamic `@media` query breakpoints)
- **Data Source**: Dynamic image generation using Picsum Photos API

---

## 📂 Project Structure

The project has a modular component-driven structure:

```text
dynamic-image-gallery/
├── public/                 # Static assets & index.html
├── src/
│   ├── components/
│   │   ├── About.js        # "About Us" and gallery vision statement
│   │   ├── Footer.js       # Contact links and copyright notices
│   │   ├── Gallery.js      # Responsive image grid loaded with sample media
│   │   ├── Navbar.js       # Main responsive site header and brand banner
│   │   └── Search.js       # User-centric search interface
│   ├── App.js              # Application root and component coordinator
│   ├── index.js            # Entry point for React DOM rendering
│   └── style.css           # Global stylesheet with responsive rules
├── package.json            # npm metadata and dependencies configuration
└── README.md               # Project documentation
```

---

## 🚀 Getting Started

Follow these steps to run the LensFlow project locally:

### 1. Prerequisites

Ensure you have **Node.js** (v16.0.0 or higher) and **npm** installed.

### 2. Installation

Clone the repository and install all required node modules:

```bash
# Clone the repository
git clone https://github.com/Madaswamy14/dynamic-image-gallery.git

# Navigate into the project folder
cd dynamic-image-gallery

# Install packages
npm install
```

### 3. Run the Development Server

Start the project locally to preview changes in real-time:

```bash
npm start
```

This will run the local development server at [http://localhost:3000](http://localhost:3000) inside your web browser.

### 4. Build for Production

To create an optimized production build of the gallery:

```bash
npm run build
```

The production assets will be placed into the `build/` folder ready for deployment.

---

## 📜 License & Credits

- All photographs are sourced from open-source photography platforms with credits to their respective creators.
- Built as an open-source responsive web portfolio project.