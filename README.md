# Marvisaer

Small browser tools, hosted with GitHub Pages at **https://marho4.github.io**.

| Tool | Link |
| --- | --- |
| Battlefront Loadout Roulette | https://marho4.github.io/battlefront/ |

## Adding a tool

1. Create a folder with an `index.html`, e.g. `my-tool/index.html`. Keep it self-contained (HTML, CSS and JS in one file).
2. In the start page `index.html`, copy one `<a class="tool">` block and point its `href` to `my-tool/`.
3. Commit and push. GitHub Pages publishes it within a minute or two at `https://marho4.github.io/my-tool/`.

To test locally first:

```
python -m http.server 8000
```

Then open http://localhost:8000.
