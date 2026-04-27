# riccardomerenda.dev

Personal website of [Riccardo Merenda](https://github.com/riccardomerenda) — AI & Backend Engineer.

Live at **[riccardomerenda.dev](https://riccardomerenda.dev)**.

## Stack

- [Astro 6](https://astro.build) — content-first, zero-JS by default
- [Tailwind CSS 4](https://tailwindcss.com) — via the Vite plugin
- [Cloudflare Workers](https://developers.cloudflare.com/workers/) — SSR at the edge, deployed with Wrangler
- Variable fonts: [Inter](https://rsms.me/inter/) + [JetBrains Mono](https://www.jetbrains.com/mono/)

## Project structure

```
src/
├── layouts/Layout.astro    # <head>, fonts, scroll & spotlight scripts
├── pages/
│   ├── index.astro         # composes the homepage sections
│   └── 404.astro
├── components/             # one .astro file per homepage section
└── styles/global.css       # design tokens & utilities
public/
├── og-image.png            # social card
├── favicon.svg
└── robots.txt
```

## Commands

| Command            | What it does                                |
| :----------------- | :------------------------------------------ |
| `npm run dev`      | Start Astro dev server on `localhost:4321`  |
| `npm run build`    | Build to `./dist/`                          |
| `npm run preview`  | Build, then serve via local Wrangler        |
| `npm run deploy`   | Build and deploy to Cloudflare              |

## License

Code is MIT. Content (copy, images, design) is © Riccardo Merenda.
