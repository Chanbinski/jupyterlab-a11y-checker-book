---
draft: true
---

# a11y-checker-book

Quick guide to build and view this jupyter book for [jupyterlab-a11y-checker](https://github.com/berkeley-dsep-infra/jupyterlab-a11y-checker).

## MyST (mystmd)
You can preview and build this book using the MyST CLI (`mystmd`). See the Quickstart: https://mystmd.org/guide/quickstart

### Install mystmd (choose one)
```bash
# conda-forge
conda install -c conda-forge mystmd

# or pip
pip install mystmd

# or npm (requires Node >= 18)
npm install -g mystmd
```

### Develop and build with mystmd
```bash
# initialize (writes myst.yml if missing)
myst

# start local dev server (port 3000)
myst start

# build static site to _build/site
myst build
```
