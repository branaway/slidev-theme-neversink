# Customizing

Generally you can customize this theme following the recommendations of [Slidev](https://sli.dev/custom/directory-structure). But there are a few hints:

## Customizing CSS

To add custom CSS styles to your project simply create a folder in the same files as your slide markdown file (usually `slides.md`) called `styles`.

```sh
your-presentation-folder/
  ├── slides.md
  └── styles/
      ├── index.ts
      └── custom.css
```

in `index.ts` add the following:

```ts
// styles/index.ts

import './custom.css'
```

Then add whatever classes you want to `custom.css`.

## Customizing fonts

To customize the fonts used in the theme, you can set the following CSS variables in your `custom.css` file:

```css
:root {
  --neversink-title-font: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  --neversink-main-font: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  --neversink-mono-font: 'SF Mono', Monaco, 'Cascadia Code', 'Roboto Mono', Consolas, 'Courier New', monospace;
  --neversink-quote-font: 'SF Mono', Monaco, 'Cascadia Code', 'Roboto Mono', Consolas, 'Courier New', monospace;
}
```
