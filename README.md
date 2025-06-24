# Elevate^ Website

A modern, responsive website built with Framer and optimized for Vercel deployment.

## 🚀 Quick Start

### Local Development

1. Clone this repository
2. Install dependencies (optional for local serving):
   ```bash
   npm install
   ```
3. Start local development server:
   ```bash
   npm run dev
   ```
   Or simply open `index.html` in your browser.

### Deploy to Vercel

#### Option 1: Deploy via Vercel CLI
1. Install Vercel CLI:
   ```bash
   npm i -g vercel
   ```
2. Login to Vercel:
   ```bash
   vercel login
   ```
3. Deploy:
   ```bash
   vercel
   ```

#### Option 2: Deploy via Vercel Dashboard
1. Push your code to a Git repository (GitHub, GitLab, or Bitbucket)
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your repository
5. Vercel will automatically detect it as a static site and deploy it

#### Option 3: Deploy via Git Integration
1. Connect your repository to Vercel
2. Every push to main branch will automatically trigger a deployment

## 📁 Project Structure

```
.
├── index.html          # Main HTML file (Framer export)
├── package.json        # Project configuration
├── vercel.json         # Vercel deployment configuration
├── README.md          # Project documentation
└── .gitignore         # Git ignore rules
```

## ⚙️ Configuration

The project includes a `vercel.json` configuration file that:
- Serves the static HTML file
- Routes all requests to `index.html` for SPA-like behavior
- Optimizes for static content delivery

## 🎨 Features

- Fully responsive design
- Modern UI/UX built with Framer
- Optimized for performance
- SEO-friendly meta tags
- Cross-browser compatibility

## 📝 Customization

To customize the website:
1. Edit the `index.html` file directly, or
2. Modify the original Framer project and re-export

## 🌐 Live Demo

After deployment, your site will be available at your Vercel domain (e.g., `https://your-project.vercel.app`)

## 📞 Support

For deployment issues, refer to:
- [Vercel Documentation](https://vercel.com/docs)
- [Vercel Static Site Guide](https://vercel.com/docs/concepts/projects/overview)
