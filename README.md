# VSCode Markdown Viewer

This repository extracts VS Code's built‑in Markdown extensions. `index.html` uses
these files to render Markdown in the same way as VS Code's preview.

Open `index.html` in a modern browser. The page loads VS Code's Markdown
renderer and CSS from the `markdown-language-features` and `markdown-math`
folders. It then renders the extension's `README.md` as a demo.

If you want to render another Markdown file, adjust the `fetch` path in
`index.html`.
