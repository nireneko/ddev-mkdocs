## What is this?

This repository allows you to quickly install MKdocs into a [DDEV](https://ddev.readthedocs.io) project using just `ddev get nireneko/ddev-mkdocs`.

## Installation

1. `ddev get nireneko/ddev-mkdocs`
2. `ddev restart`

MKdocs will now be accessible from `http://<project>.ddev.site:8001`

## Explanation

This MKdocs recipe for [DDEV](https://ddev.readthedocs.io) installs a [`.ddev/docker-compose.mkdocs.yaml`](docker-compose.mkdocs.yaml) using the [`squidfunk/mkdocs-material`](https://hub.docker.com/r/squidfunk/mkdocs-material/) Docker image.

## Documentation

This package creates one folder named `mkdocs` in the root of your project and inside mkdocs.yml file, you can add the configuration that you need for your project.

Inside the folder `mkdocs` another one named `docs` also will be created, there you can put your documentation, one example file `index.md` is available.

Check the official documentation of [MKdocs](https://www.mkdocs.org/) and the documentation of [MKdocs Material](https://squidfunk.github.io/mkdocs-material/) for more information about the configuration and page creation.

**Contributed and maintained by [@nireneko](https://github.com/nireneko) based on the original [ddev-contrib template](https://github.com/ddev/ddev-addon-template).**