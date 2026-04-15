# Mo Boroumand — Personal Website (Quarto)

## Setup

1. Install [Quarto](https://quarto.org/docs/get-started/) and the [Quarto VS Code extension](https://marketplace.visualstudio.com/items?itemName=quarto.quarto).
2. Open this folder in VS Code.
3. Run `quarto preview` in the terminal to see live edits.
4. Run `quarto render` to build the `_site/` folder for deployment.

## Structure

```
mo-website/
├── _quarto.yml        ← Site config, navbar, theme
├── index.qmd          ← Home / hero page
├── about.qmd          ← About Me
├── resume.qmd         ← Resume
├── experience.qmd     ← Experience timeline
├── products.qmd       ← Products / projects
├── startup.qmd        ← Startup ideas
├── styles/
│   ├── custom.scss    ← Quarto SCSS variables
│   └── custom.css     ← All custom styles (navy + purple theme)
└── assets/            ← Put profile.jpg, resume.pdf, product images here
```

## Filling in your content

Each `.qmd` file has `[Placeholder]` comments — replace them with your real data.

## Deploying

- **GitHub Pages**: `quarto publish gh-pages`
- **Netlify / Vercel**: point to the `_site/` folder after `quarto render`
- **Quarto Pub**: `quarto publish quarto-pub`
