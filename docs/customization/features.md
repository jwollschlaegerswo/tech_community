# Features

## 1 Color palette toggle
```yaml
theme:
  palette: 

    # Palette toggle for light mode
    - scheme: default
      toggle:
        icon: material/brightness-7 
        name: Switch to dark mode

    # Palette toggle for dark mode
    - scheme: slate
      toggle:
        icon: material/brightness-4
        name: Switch to light mode
```

## 2 Content tabs
```yaml
markdown_extensions:
  - pymdownx.superfences
  - pymdownx.tabbed:
      alternate_style: true
```

## 3 Code features

### Copy button
```yaml
theme:
  features:
    - content.code.copy
```


## Other

- [Versioning](https://squidfunk.github.io/mkdocs-material/setup/setting-up-versioning/)
- [GitHub repository link](https://squidfunk.github.io/mkdocs-material/setup/adding-a-git-repository/) (display meta data)
- [Comment system](https://squidfunk.github.io/mkdocs-material/setup/adding-a-comment-system/)
- [Diagrams](https://squidfunk.github.io/mkdocs-material/reference/diagrams/)
- [SEO](https://squidfunk.github.io/mkdocs-material/setup/setting-up-site-analytics/)
- [Cookie consent](https://squidfunk.github.io/mkdocs-material/setup/ensuring-data-privacy/)