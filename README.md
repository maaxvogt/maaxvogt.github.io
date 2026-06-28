# maaxvogt.github.io

Personal portfolio of **Max Vogt** — AI Developer.

Built with [Astro](https://astro.build), this site showcases featured projects spanning applied AI, full-stack engineering, security, and product development, along with an about page and contact links.

🔗 **Live site:** https://maaxvogt.github.io

## 🚀 Project Structure

```text
/
├── public/              # Static assets (images, favicon)
├── src/
│   ├── layouts/         # Shared page layout
│   ├── pages/           # Routes (index, about, project detail pages)
│   └── styles/          # Global styles
└── package.json
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build the production site to `./dist/`           |
| `npm run preview`         | Preview the build locally, before deploying       |

## 📦 Deployment

The site builds and deploys automatically to GitHub Pages on every push to `main` via the workflow in `.github/workflows/deploy.yml`.
