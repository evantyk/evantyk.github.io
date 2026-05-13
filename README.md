# Evan Tyk Quarto Portfolio Website

This is a cleaned-up Quarto portfolio site. It includes:

- `index.qmd` — homepage with short self-introduction and visual identity card.
- `project.qmd` — project page.
- `data-visualization.qmd` — data visualisation page with a responsive SVG chart.
- `hobbies.qmd` — extra personal interests page.
- `genai-reflection.qmd` — reflection on using GenAI.
- `styles.css` — custom responsive styling.
- `docs/` — ready-to-serve HTML output for GitHub Pages.

## How to preview locally

```bash
quarto preview
```

## How to rebuild the `docs/` folder

```bash
quarto render
```

If your GitHub Pages source is set to the `docs/` folder, the website can also be served directly from the included `docs/` output.
