# sourangsu.github.io

A simple static personal website built with plain HTML and CSS.

## Files

- `index.html` — About / homepage
- `projects.html` — Projects, current work, and selected publications
- `writing.html` — Writing
- `assets/style.css` — site styles
- `assets/script.js` — footer year


## GitHub Pages

Upload these files to the root of your `sourangsu.github.io` repository and enable GitHub Pages from the repository's default branch.

## Links to update

### Homepage
The LinkedIn and email links are populated. The GitHub and Google Scholar icon links currently point to their generic homepages; replace those URLs with your exact profile URLs when ready.

### Project publications
Each paper title in `projects.html` is already an HTML link with `href="#"`. Replace the `#` with the paper URL you want to use. Search for the comments beginning with:

`<!-- Replace ... -->`

Example:

```html
<li>
  <a href="https://your-paper-link.example">
    <em>Paper title</em>
  </a>
  — <em>Journal</em>, 2020
</li>
```
