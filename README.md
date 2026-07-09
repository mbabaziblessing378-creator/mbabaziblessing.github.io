# EKSEL Medical Clinic

A modern, responsive healthcare website for EKSEL Medical Clinic built with React and Vite.

## Features

- Responsive design
- Online appointment booking
- Medical services
- Doctor profiles
- Patient information
- Health articles
- Contact form
- WhatsApp integration
- SEO optimized
- Fast and modern UI

## Tech Stack

- React
- Vite
- React Router
- Framer Motion
- React Icons
- CSS / Tailwind CSS (depending on the project)

## Getting Started

### Install dependencies

```bash
npm install
```

### Start the development server

```bash
npm run dev
```

Open the local URL shown in the terminal (for example, http://localhost:5173).

## Project Structure

```
src/
├── assets/
├── components/
├── context/
├── data/
├── hooks/
├── pages/
├── services/
├── styles/
├── utils/
├── App.jsx
└── main.jsx
```

## Development Workflow

1. Copy or reuse components as needed from the `components/` folder.
2. Paste them into the matching files in this project if reusing external examples.
3. Save the file.
4. Run `npm run dev`.
5. Test the application.
6. Commit changes to GitHub regularly.

## Scripts

Start development server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

Preview production build:

```bash
npm run preview
```

## License

Copyright © 2026 EKSEL Medical Clinic.

All rights reserved.

## Deployment (Quick instructions)

The project is a Vite + React app. Use one of the options below to deploy a production build.

- Vercel (recommended):
	1. Push the repo to GitHub.
	2. Sign in to https://vercel.com and import the repository.
	3. Vercel auto-detects Vite; use the default build command `npm run build` and output directory `dist`.
	4. Deploy — commits to the connected branch auto-deploy.

- Netlify:
	1. Push the repo to GitHub.
	2. Create a new site on https://app.netlify.com and link the repo.
	3. Set build command to `npm run build` and publish directory to `dist`.
	4. Deploy the site.

- GitHub Pages (simple static deploy):
	1. Ensure `gh-pages` is installed and `predeploy`/`deploy` scripts exist in `package.json`.
	2. Run:
		 ```bash
		 npm install
		 npm run build
		 npm run deploy
		 ```
	3. GitHub Pages will publish the `dist/` folder to the configured pages branch.

Notes:
- Use `npm run dev` to preview locally with Vite (do not use Live Server for development). 
- If you see a blank page after deploying, open browser DevTools → Console/Network to check for 404s or JS errors (usually caused by incorrect `base` or absolute asset paths).
