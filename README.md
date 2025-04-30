# Skateboard Blog

Blog starter template for Skateboard apps. Scaffold a new blog with Astro, MDX, and Tailwind.

## Getting Started

```bash
npx degit stevederico/skateboard-blog my-blog-name
cd my-blog-name
deno install
deno run start
```

## Configuration

1. Set site title and description in `src/consts.ts`
2. Set site URL in `astro.config.mjs`
3. Set name in `package.json`
4. Add prod script: `"prod": "astro build; cp -r ./dist/* ../public/blog"`
5. Write about page (`src/pages/about.astro`)
6. Write blog posts in `src/content/blog/` (Markdown or MDX)
7. Set favicon in `public/`

## Stack

- Astro 5.7
- MDX content collections
- React 19 components
- Tailwind CSS v4
- RSS feed + sitemap
- Atkinson font

## Structure

```
src/
  content/blog/   — Blog posts (Markdown/MDX)
  components/     — Astro components (Header, Footer, BlogPost)
  pages/          — Routes (index, about, RSS, [slug])
  layouts/        — Page layout
  styles/         — Global CSS
public/           — Static assets (fonts, images, favicon)
```
