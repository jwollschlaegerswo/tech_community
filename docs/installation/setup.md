# Installation, Initialization and Startup

## Installation

Pull docker image

```docker pull squidfunk/mkdocs-material```

## Initialization

Bootstrap your project documentation using the mkdocs executable:
```
mkdocs new .
```
or running Material for MkDocs with Docker:
```
docker run --rm -it -v "%cd%":/docs squidfunk/mkdocs-material new .
```

## Startup (live preview server)
```
mkdocs serve
```

[//]: # (Unix, Powershell)

[//]: # (```)

[//]: # (docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material)

[//]: # (```)

[//]: # (Windows)

[//]: # (```)

[//]: # (docker run --rm -it -p 8000:8000 -v "%cd%":/docs squidfunk/mkdocs-material)

[//]: # (```)

=== "Unix, Powershell"
    ```
    docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material
    ```
=== "Windows"
    ```
    docker run --rm -it -p 8000:8000 -v "%cd%":/docs squidfunk/mkdocs-material
    ```
Point your browser to localhost:8000 