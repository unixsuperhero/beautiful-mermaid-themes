# Beautiful Mermaid themes

A visual comparison of the 13 themes available in the [Beautiful Mermaid skill](https://github.com/intellectronica/agent-skills/tree/main/skills/beautiful-mermaid). The gallery renders the same three runtime relationship diagrams in each theme, plus their original versions, for 42 SVGs in 14 groups.

[Browse the gallery file (`index.html`)](index.html) · [View the original skill](https://github.com/intellectronica/agent-skills/blob/main/skills/beautiful-mermaid/SKILL.md)

## View the gallery

Download or clone this repository, then open `index.html` in your browser. Keep the SVG files beside it so the diagrams load. No installation, build step, or local server is required.

Choose a theme in the gallery navigation, then select a diagram to open its full-size SVG. On GitHub, the `index.html` link opens the source code rather than a rendered page. Use GitHub Pages to publish the gallery as a website.

## Publish with GitHub Pages

GitHub Pages can serve the existing `index.html` directly. No custom workflow is needed.

1. Open this repository's [Pages settings](https://github.com/unixsuperhero/beautiful-mermaid-themes/settings/pages).
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Select **main** and **/ (root)**, then select **Save**.
4. Wait for the Pages deployment to finish.

Once deployed, the rendered gallery is available at:

**[https://unixsuperhero.github.io/beautiful-mermaid-themes/](https://unixsuperhero.github.io/beautiful-mermaid-themes/)**

This URL requires GitHub Pages to be enabled. It is not a live preview of the repository's HTML file before deployment.

## What's included

- [`index.html`](index.html) is the static gallery, grouped by theme.
- [`context.mmd`](context.mmd), [`frames.mmd`](frames.mmd), and [`objects.mmd`](objects.mmd) are the editable Mermaid sources.
- `context-<theme>.svg`, `frames-<theme>.svg`, and `objects-<theme>.svg` are the themed exports.
- The SVGs without a theme suffix and the three PNGs are the original exports.

The examples depict context lookups, active frames, and object references from Ochazuke. They provide consistent sample content for comparing themes. The gallery still uses the original Ochazuke heading and includes a walkthrough link whose target is not part of this repository.

## Themes

Catppuccin Latte, Default, Dracula, GitHub Dark, GitHub Light, Nord, Nord Light, One Dark, Solarized, Tokyo Night, Tokyo Night Light, Tokyo Night Storm, and Zinc Dark.

## Original skill and credits

The rendering workflow comes from the public [Beautiful Mermaid skill by intellectronica](https://github.com/intellectronica/agent-skills/tree/main/skills/beautiful-mermaid), part of [intellectronica/agent-skills](https://github.com/intellectronica/agent-skills). See its [SKILL.md](https://github.com/intellectronica/agent-skills/blob/main/skills/beautiful-mermaid/SKILL.md) for rendering commands, dependencies, and PNG export instructions.

This repository contains example diagrams and a theme comparison gallery, not the skill implementation.
