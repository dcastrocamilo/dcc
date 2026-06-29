# Daniela Castro-Camilo personal website

This is a Quarto website scaffold for `https://dcastrocamilo.github.io/dcc/`.

## Files

- `_quarto.yml`: site configuration and navigation
- `index.qmd`: home page and short bio
- `research.qmd`: visual research areas with circular buttons and related publications
- `publications.qmd`: full publication list grouped by year
- `talks.qmd`: talks and event links page
- `supervision.qmd`: PhD supervision and student project information
- `admin.qmd`: admin, service, grants and teaching
- `styles.css`: custom styling

## Preview locally

```bash
quarto preview
```

## Render

```bash
quarto render
```

The rendered website will be placed in the `docs/` folder, which works well for GitHub Pages when the repository is configured to serve from `/docs`.

## Notes

- Replace or expand placeholder talk entries as needed.
- The site uses external links for Google Scholar, ORCID, GitHub and email.
- If you want a photo on the home page, add it to the folder, for example `profile.jpg`, and add an image block in `index.qmd`.
