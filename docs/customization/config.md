# Configuration
https://squidfunk.github.io/mkdocs-material/setup/

## 1 Theme
`material` theme adds the built-in search functionality to your site.
```yaml
theme:
  name: material
```
### Tabbed site
```yaml
theme:
  name: material
  features:
    - navigation.tabs
    - navigation.tabs.sticky
```

### Integrated TOC
```yaml
theme:
  name: material
  features:
    - navigation.tabs
    - navigation.tabs.sticky
    - toc.integrate
    - toc.follow
```

### Logo
```yaml
theme:
  logo: assets/logo.jpg
```
## 2 Navigation

Add a `nav` section to the configuration file `mkdocs.yml`:

```yaml
nav:
  - Home: index.md
  - Getting started:
      - installation/setup.md
  - Customization:
      - customization/config.md
      - customization/features.md
  - Publishing:
      - publishing/github_pages.md
```


