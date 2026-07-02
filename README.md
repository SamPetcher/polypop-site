# polypop-site

A basic [Astro](https://astro.build) site.

## Commands

All commands are run from the root of the project, from a terminal:

| Command           | Action                                       |
| :---------------- | :------------------------------------------- |
| `npm install`     | Install dependencies                         |
| `npm run dev`     | Start local dev server at `localhost:4321`   |
| `npm run build`   | Build the production site to `./dist/`       |
| `npm run preview` | Preview the build locally before deploying   |

## Project structure

```text
/
├── public/            # static assets served as-is (e.g. favicon.svg)
├── src/
│   ├── layouts/       # shared page layouts
│   └── pages/         # file-based routes
└── astro.config.mjs   # Astro configuration
```
