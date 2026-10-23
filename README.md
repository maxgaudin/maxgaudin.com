# maxgaudin.com

Max Gaudin’s personal website, built with static HTML and CSS. No dependencies or build step are required.

## Local preview

From the repository root, run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open http://localhost:8000. Refresh after editing files; press Ctrl+C to stop the server.

## Editing

- `index.html`: biography, experience, civic projects, leadership, links, and metadata.
- `css/style.css`: colors, typography, layout, and mobile styles.
- `css/reset.css`: browser style reset.
- `img/`: existing image assets, including the social preview image.

Before publishing, review role dates and metrics, check project links, and inspect the page at desktop and mobile widths. External links that open a new tab use `rel="noopener noreferrer"`.

## License

[MIT](LICENSE).
