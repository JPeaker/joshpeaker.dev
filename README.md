# joshpeaker.dev

Single-page freelance site for [Josh Peaker](mailto:josh@joshpeaker.dev) — Senior Product Engineer (React, TypeScript & Design Systems).

Built with [Astro](https://astro.build) and [Tailwind CSS](https://tailwindcss.com), forked from the [Astro Sphere](https://github.com/markhorn-dev/astro-sphere) template and trimmed down to a single page.

## Commands

All commands are run from the root of the project, from a terminal:

| Command               | Action                                        |
| :-------------------- | :-------------------------------------------- |
| `npm install`         | Installs dependencies                         |
| `npm run dev`         | Starts local dev server at `localhost:4321`   |
| `npm run build`       | Build your production site to `./dist/`       |
| `npm run preview`     | Preview your build locally, before deploying  |
| `npm run astro ...`   | Run CLI commands like `astro add`, `astro check` |

## Site configuration

- Site-wide settings (title, description, email) live in `src/consts.ts`.
- Page content (hero, pitch, experience, CTA) lives in `src/pages/index.astro`.
- Replace `public/open-graph.jpg` and `public/favicon.svg` with your own branding.

## License

MIT — see `LICENSE` (original template by [Mark Horn](https://github.com/markhorn-dev)).
