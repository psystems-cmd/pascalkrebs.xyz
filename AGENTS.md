## Project

Personal website for Pascal Krebs at pascalkrebs.xyz. Minimalistic portfolio/CV site with five pages: Home (centred hero), My Story, Projects, Work, Contact. Inner pages use a fixed left sidebar with the fraktur 𝔓 logo and navigation.

## Architecture

- **Stack:** Astro + Tailwind CSS v4
- **Font:** Averia Serif Libre (Google Fonts) — do not change
- **Logo:** Unicode fraktur 𝔓 rendered as text, not an image
- **Colour palette:** Black (#1a1a1a), grey (#999), light grey (#f5f5f5), white — no other colours
- **Layouts:** `BaseLayout.astro` (shared head/font), `SidebarLayout.astro` (inner pages with fixed sidebar)
- **Components:** `Logo.astro` (sm/lg sizes), `Sidebar.astro` (nav with active state)
- **Pages:** `/` (home), `/my-story`, `/projects`, `/work`, `/contact`
- **Design reference:** Figma exports at `~/Desktop/pascalkrebs.xyz/`

## Conventions

- Keep everything minimalistic — resist adding visual complexity
- Active nav item: bold black text. Inactive: grey (#999)
- Headings are bold, large serif. Body text is regular weight
- European English in all copy

## Development

When starting the dev server, use background mode:

```
astro dev --background
```

Manage the background server with `astro dev stop`, `astro dev status`, and `astro dev logs`.

## Documentation

Full documentation: https://docs.astro.build

Consult these guides before working on related tasks:

- [Adding pages, dynamic routes, or middleware](https://docs.astro.build/en/guides/routing/)
- [Working with Astro components](https://docs.astro.build/en/basics/astro-components/)
- [Using React, Vue, Svelte, or other framework components](https://docs.astro.build/en/guides/framework-components/)
- [Adding or managing content](https://docs.astro.build/en/guides/content-collections/)
- [Adding styles or using Tailwind](https://docs.astro.build/en/guides/styling/)
- [Supporting multiple languages](https://docs.astro.build/en/guides/internationalization/)
