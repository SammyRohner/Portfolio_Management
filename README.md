# Portfolio Management – lecture site

Served by GitHub Pages from the `main` branch root.

## Adding a presentation

1. Copy the HTML file into `lectures/` with a short, space-free name, e.g. `lectures/lab-5.html`.
2. If the file doesn't start with `<!doctype html>`, add these three lines at the very top:
   ```html
   <!doctype html>
   <meta charset="utf-8">
   <meta name="viewport" content="width=device-width, initial-scale=1">
   ```
3. Add a back link to the overview just above the page's eyebrow line (copy the `.home` style and `<a class="home" href="../">← All sessions</a>` from an existing lecture).
4. Add a link to it in `index.html`.
5. Commit and push. The site updates within a minute or two.
