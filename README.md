# Eureka

Eureka builds and publishes [ciaranfinn.dev](https://ciaranfinn.dev), my little corner of the internet. It’s where I introduce myself and share the work I enjoy across machine learning, agentic systems, and product building.

Built with [Astro](https://astro.build/), TypeScript, and CSS, and deployed with GitHub Pages.

## Run locally

Use Node.js 20 (to match CI) and npm.

```sh
npm install
npm run dev
```

Then open [localhost:4321](http://localhost:4321).

## Commands

| Command                | Description                          |
| ---------------------- | ------------------------------------ |
| `npm run dev`          | Start the local development server   |
| `npm run build`        | Build the site to `dist/`            |
| `npm run preview`      | Preview the production build locally |
| `npm run format:check` | Check formatting with Prettier       |
| `npm run format:write` | Format files with Prettier           |

Pushes to `main` are built and deployed to GitHub Pages automatically.
