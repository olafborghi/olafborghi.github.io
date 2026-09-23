# Academic Website

Source of [olafborghi.com](https://www.olafborghi.com), built with [Quarto](https://quarto.org) (1.10+).

## Build and publish

```bash
quarto preview   # live preview at http://localhost:22222
quarto render    # render the whole site into docs/
```

GitHub Pages serves the `docs/` folder from the `main` branch, so commit the rendered `docs/` together with the source changes.

## Structure

- `index.qmd`, `about/`, `cv/`: main pages
- `news.yml`: the "Recent news" cards on the home page (images in `img/news/`, 16:9, about 800×450)
- `research/articles/`, `research/preprints/`, `research/reports/`, `research/posters/`: one folder per item with an `index.qmd` (metadata in `pub-info`)
- `misc/`: talks, slides and other posts
- `html/`: custom SCSS theme and listing templates

## Credits

Built following the tutorial and template by Marvin Schmitt <https://www.marvinschmitt.com/blog/website-tutorial-quarto/>, with code largely based on the website of Andrew Heiss <https://github.com/andrewheiss/ath-quarto>. Thank you!
