# Blog ergonomie

notre blog avec une accessibilité optimisée à l'aide de l'outil [Astro](https://astro.build) et [Markdoc](https://markdoc.dev).


## Newspaper Template

Le design du site est fait avec [Tailwind](https://tailwindcss.com).

- **Fast**. Fast by default. Astro websites are engineered to be fast and load before you could blink, even when not cached.
- **Dark mode**. All themes have light/dark mode built-in.
- **Mobile first**. Responsive and loads fast in all devices.
- **Accessible**. A well thought out semantic and accessible content.
- **Perfect lighthouse score.** 100 across the board.
- **Easy content authoring**. Author content using markdown (`.md`) from your code editor or directly in GitHub.
- **Extended markdown with [Markdoc](https://markdoc.dev).** Type-safe custom components like YouTube embed, Twitter embed (or anything you want really) in your markdown (`.md`) files.
- **RSS feed**. Your blog has an RSS feed setup that can be accessed at `/rss.xml`.
- **SEO**. All pages are setup with all the SEO you might need.

## Ajout de contenu

- All content is static and everything is straight forward. Change whatever you need to change.
- Delete or update the content in `content/{content-group}`. `content-group` could be `blog`, `projects` or `anything`.
- (Optional) If you need more content types like _Notes_, just create a new dir in `content` and add a new frontmatter validator like [src/lib/markdoc/blog/frontmatter](src/lib/markdoc/blog/frontmatter).


