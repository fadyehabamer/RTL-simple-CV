# RTL CV
### Simple Arabic CV using
* HTML
* CSS
* BOOTSTRAP 4

A one-page, right-to-left (Arabic) CV/resume template. Replace the placeholder text in `index.html` with your own details.

**Live demo:** https://fadyehabamer.github.io/RTL-simple-CV/

## Run locally

No build step. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Structure

```
index.html            the CV (lang="ar" dir="rtl")
css/style.css         custom styles (Google Fonts: Changa, Quicksand, Merriweather, Jomhuria)
css/bootstrap*.css    Bootstrap 4 plus the RTL / flipped variants (vendored)
js/lib/               jQuery, Bootstrap bundle and Font Awesome (vendored)
```

## License

[MIT](LICENSE)
