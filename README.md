# Campus Bite - HTML Website

A modern HTML website built with Vite, providing fast development and optimized production builds.

## Project Structure

```
campus-bite/
├── .github/                 # GitHub metadata and documentation
├── public/                  # Static assets
├── src/                     # Source files
│   ├── main.js             # Entry point
│   ├── style.css           # Global styles
│   └── counter.js          # Sample component
├── index.html              # Main HTML file
├── package.json            # Dependencies and scripts
└── vite.config.js          # Vite configuration
```

## Quick Start

### Install Dependencies
```bash
npm install
```

### Development
Start the development server with hot module replacement:
```bash
npm run dev
```

The application will be available at `http://localhost:5173/`

### Build for Production
Create an optimized production build:
```bash
npm run build
```

### Preview Production Build
Preview the production build locally:
```bash
npm run preview
```

## Features

- ⚡ **Fast Build** - Powered by Vite for lightning-fast HMR
- 📦 **Optimized** - Automatic code splitting and minification
- 🔄 **Hot Module Replacement** - Real-time updates during development
- 📱 **Responsive** - Build responsive websites with vanilla HTML/CSS/JS

## File Organization

- **index.html** - Main entry point, update the `<title>` and add your content
- **src/main.js** - JavaScript entry point
- **src/style.css** - Global styles
- **public/** - Place static assets here (images, fonts, etc.)

## Customization

Edit the files in `src/` to customize your website. Any changes will automatically reload in the browser during development.

## Browser Support

Modern browsers with ES modules support.

---

Built with [Vite](https://vitejs.dev/)
