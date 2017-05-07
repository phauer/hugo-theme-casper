# CASPER theme for hugo

Fork of [vjeantet's great hugo-theme-casper](https://github.com/vjeantet/hugo-theme-casper). Adjustments:

## Code

- Utilize SASS
- Use webpack to process SASS, concat and minify css.
- Use Google Fonts and cloudflare instead of delivering it by ourselves. Keeps build simple. Utilizes browser caching due to CDN. 
- Reduce required fonts.

## Design

- Integrated [liqenyip's nice hugo-easy-gallery](https://github.com/liwenyip/hugo-easy-gallery/) and made them work within the theme.
- support non-root base urls (e.g. "http://domain.de/bla") in conjunction with image references in the theme and gallery.
- minor format and style changes (margins, paddings, text align, sans-serif font family)
- remove "authorlocation" and "authorwebsite"
- `google-maps` shortcode and styling.
- clean up document outline (`hn` tags only for content)
- featured image for each post on index page
- remove blog logo
- author bio also on index page
- to be continued...

# Build

```bash
npm install
npm run build
```

development:

```bash
# in theme folder
npm run watch
# in project root
hugo server
```
