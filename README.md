# Lavish Gangwani - Portfolio 2024

A modern, interactive portfolio website showcasing projects, articles, and professional experience. Built with performance and aesthetics in mind.

## 🌟 Features

- **Immersive 3D Experience**: Integrated Three.js models and animations.
- **Dynamic Content**: Sections for Projects, Articles (MDX), Experience, and Uses.
- **Modern Styling**: Responsive design with Framer Motion animations and custom CSS.
- **Optimized Performance**: Built on Remix and Vite for fast load times and efficient routing.
- **Dark/Light Mode**: Seamless theme switching support.

## 🛠️ Tech Stack

- **Framework**: [Remix](https://remix.run/) with React and [Vite](https://vitejs.dev/)
- **Deployment**: [Cloudflare Pages](https://pages.cloudflare.com/) (`@remix-run/cloudflare-pages`)
- **Animation**: [Framer Motion](https://www.framer.com/motion/)
- **3D Graphics**: [Three.js](https://threejs.org/) (`three`, `three-stdlib`)
- **Content Writing**: MDX for rich text articles with React components
- **Styling**: Vanilla CSS/PostCSS Modules

## 🚀 Getting Started

### Prerequisites

- Node.js (>= 18.0.0)
- npm or yarn

### Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Lavishgangwani/portfolio.git
   cd portfolio
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```
   The site will be available at `http://localhost:5173` (or the port specified by Vite).

### Storybook (Component Library)

To view and develop individual UI components in isolation:

1. **Start Storybook:**
   ```bash
   npm run dev:storybook
   ```

## 🏗️ Build and Deployment

### Build for Production

To create a production-ready build:
```bash
npm run build
```

### Deploy to Cloudflare Pages

This project is configured to be deployed on Cloudflare Pages.
Make sure your Wrangler CLI is configured or deploy via the Cloudflare dashboard linked to your GitHub repository.

Alternatively, to deploy via GitHub Pages:
```bash
npm run deploy
```

## 📝 License

This project is proprietary. Please check the `LICENSE` file for more terms and conditions.

## 👨‍💻 Author

**Lavish Gangwani**
- Role: Software Engineer, AI Engineer, System Designer
- GitHub: [@Lavishgangwani](https://github.com/Lavishgangwani)
- LinkedIn: [lavish-gangwani](https://linkedin.com/in/lavish-gangwani)