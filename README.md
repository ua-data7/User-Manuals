# User-Manuals

Welcome to the User Manual Documentation for Soteria.

## MkDocs deploy GitHub Action

The `mkdocs-material` branch uses [deploy-mkdocs](https://github.com/marketplace/actions/deploy-mkdocs) GitHub Action.

Do not commit changes directly to the `main` branch unless necessary. 

Please commit your updates to the `mkdocs-material` branch, test on CodeSpaces or locally, and then commit those merges back to `mkdocs-material`.

The Action will re-build the MkDocs website and make changes to the `gh-pages` branch, where the .html files are used by Github.io Pages.

Commits to `mkdocs-material` will trigget the Action which re-builds and deploys the website to https://ua-data7.github.io/user-manuals -- which is publicly available. 

## Rendered with the Material Theme

To make changes the [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) theme, change [Action](./github/workflows/main.yml) to `@master` and set `theme: material` in the [mkdocs.yml](./mkdocs.yml):

```{yaml}
theme:
  name: material
```

To make changes to the Font and Style (background colors, header, etc.), edit `/stylesheets/custom.css`:

```{css}
body {
    font-family: "Helvetica Neue", "Open Sans", Helvetica, Arial, sans-serif;
}

[data-md-color-primary="white"] .md-header {
    color: #000000;
}
[data-md-color-primary="white"] .md-tabs  {
    color: #000000;
}


.md-nav__item .md-nav__link--active {
    color: #e4154b;
}

...
```

## Build the pages locally or on CodeSpaces

```
git clone https://github.com/ua-data7/user-manuals
cd user-manuals
git switch mkdocs-material 
pip install -r requirements.txt
python -m mkdocs serve
```

After compiling the new pages the service will open on `http://localhost:8000/user-manuals/` 

Open in a separate Browser Tab to view while editing changes in real-time.

*Recommended: two monitors for side by side viewing* 