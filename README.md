# Repository del mio sito personale


## Font utilizzati
- [Departure Mono](https://github.com/rektdeckard/departure-mono) (per link e titolo in Homepage)

---


# Mattia Audisio | Curriculum Vitae

My personal CV


## Tech Stack

- [Astro](https://astro.build)
- [tailwindcss](https://tailwindcss.com/)
- [DaisyUI](https://daisyui.com/)

## Project Structure

```php
├── src/
│   ├── components/
│   │   ├── BaseHead.astro
│   │   ├── Footer.astro
│   │   ├── Header.astro
│   │   └── SideBar.astro
│   │   └── SideBarMenu.astro
│   │   └── SideBarFooter.astro
│   │   └── TimeLine.astro
│   ├── layouts/
│   │   └── BaseLayout.astro
│   └── pages/
│   │   └── 404.astro
│   │   └── index.astro
│   ├── styles/
│   │   └── global.css
│   └── config.ts
├── public/
│   ├── favicon.svg
│   └── profile.webp
├── astro.config.mjs
├── tailwind.config.cjs
├── package.json
└── tsconfig.json
```