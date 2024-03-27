## What is this?

This repository allows you to quickly install MKdocs into a [DDEV](https://ddev.readthedocs.io) project using just `ddev get nireneko/ddev-mkdocs`.

## Installation

1. `ddev get nireneko/ddev-mkdocs`
2. `ddev restart`

MKdocs will now be accessible from `http://<project>.ddev.site:8001`

## Explanation

This MKdocs recipe for [DDEV](https://ddev.readthedocs.io) installs a [`.ddev/docker-compose.mkdocs.yaml`](docker-compose.mkdocs.yaml) using the [`squidfunk/mkdocs-material`](https://hub.docker.com/r/squidfunk/mkdocs-material/) Docker image.

## Documentation

This package creates one folder named `docs` in the root of your project and an mkdocs.yml file also in the root where you can add the configuration that you need for your project.

Check the official documentation of [MKdocs](https://www.mkdocs.org/) and the documentation of [MKdocs Material](https://squidfunk.github.io/mkdocs-material/) for more information about the configuration and page creation.

## Publishing

Contributed projects on Drupal.org can [automatically publish their projects via Gitlab CI](https://project.pages.drupalcode.org/gitlab_templates/jobs/pages/).

**Contributed and maintained by [@nireneko](https://github.com/nireneko) based on the original [ddev-contrib template](https://github.com/ddev/ddev-addon-template).**
