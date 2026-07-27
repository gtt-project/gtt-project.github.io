# gtt-project.org

The GTT Project website, served by GitHub Pages from the `gh-pages` branch at
[https://gtt-project.org](https://gtt-project.org).

## Structure

- `index.html` - the landing page (plain static HTML, no build step)
- `assets/css/style.css` - styles (light and dark scheme via CSS variables)
- `assets/img/` - logo and screenshots
- `CNAME` - custom domain configuration
- `.nojekyll` - disables Jekyll processing; files are served as-is

## Development

There is no toolchain. Open `index.html` in a browser, or serve the directory:

```sh
python3 -m http.server 8000
```

## Updating screenshots

Screenshots show a vanilla Redmine with the current
[`redmine_gtt`](https://github.com/gtt-project/redmine_gtt) release and a small
demo project. When retaking them, keep them as scaled JPEGs (quality 85)
so the page stays light.
