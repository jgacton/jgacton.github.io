# jgacton.github.io

Source for my personal site, at [jgacton.github.io](https://jgacton.github.io).

Static HTML and CSS with a little vanilla JavaScript. No build step, no
dependencies, no framework — the files in this repo are the files that get
served. Hosted on GitHub Pages.

## Structure

```
index.html                     home: about, writing, projects, now
writing/superintelligence.html essays, one file each
writing/figures/               figures, WebP
images/                        avatar and favicon
```

## Notes

- Light and dark themes, following the OS setting by default and
  overridable with the toggle in the sidebar. The preference is kept in
  `localStorage` and applied before first paint to avoid a flash.
- Figures are WebP: lossless for charts and line art, lossy for anything
  photographic. Figures 2 and 3 have dark-mode treatments so they don't sit
  on a white card on a dark page.
- Type is Inter with IBM Plex Mono for metadata and figures.
