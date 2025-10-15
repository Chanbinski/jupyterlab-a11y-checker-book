# a11y-checker-book

Quick guide to build and view this jupyter book for [jupyterlab-a11y-checker](https://github.com/berkeley-dsep-infra/jupyterlab-a11y-checker).

## Build
```bash
jupyter-book build .
```
- Output is generated in `_build/html/`.

## Preview
- Open the built site directly:
```bash
open _build/html/index.html
```
- Or serve locally:
```bash
python3 -m http.server -d _build/html 8000
# Visit http://localhost:8000
```

## Clean
```bash
jupyter-book clean .
# remove all build artifacts
jupyter-book clean --all .
```


