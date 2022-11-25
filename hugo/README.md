# Hugo CSS

## art.css
This will change color and size of your pre/code ascii text. This works by using existing data-lang tags. You can find all the font sizes an colors in css file. Install is simple add `art.css` to your styles directory in `project/static/styles/` and link it in your main html file with `<link rel="stylesheet" href="{{ .Site.BaseURL }}styles/art.css">` in your `project/layouts/_default/baseof.html` file.

Examples: https://readtexts.org/artwork/

Usage:
````
```art-20px-dog
ASCII Art Here
```
-OR-
```art-dog-20px
ASCII Art Here
```
````
