# Material for MkDocs - SWO TechCommunity 20.10.2023

Material for MkDocs is a powerful documentation framework on top of MkDocs, a static site generator for project documentation. Recommended to use docker if not familiar with Python.
Source: https://squidfunk.github.io/mkdocs-material/getting-started/

## Setup

### Pull docker image
```docker pull squidfunk/mkdocs-material```

### Init Material for MkDocs

Bootstrap your project documentation using the mkdocs executable.
```
mkdocs new .
```
Running Material for MkDocs from within Docker:
```
docker run --rm -it -v "%cd%":/docs squidfunk/mkdocs-material new .
```

### Previewing as you write (live preview server)
```
mkdocs serve 
```

```
docker run --rm -it -p 8000:8000 -v "%cd%":/docs squidfunk/mkdocs-material
```

Point your browser to localhost:8000 