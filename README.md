[![tests](https://github.com/ddev/ddev-addon-template/actions/workflows/tests.yml/badge.svg)](https://github.com/ddev/ddev-addon-template/actions/workflows/tests.yml) ![project is maintained](https://img.shields.io/maintenance/yes/2024.svg)

## What is this?

This repository allows you to quickly install [PHPQA](https://github.com/EdgedesignCZ/phpqa) into a [DDEV](https://ddev.readthedocs.io/en/stable/) project by simply `ddev get ddev/ddev-phpqa`.

It will install the docker image from [PHPQA](https://github.com/jakzal/phpqa) which comes with a set of pre-installed static analysis tools. 

## Installation

1. `ddev get nicobot/ddev-phpqa`
2. `ddev restart`

## Explanation

This plugin installs a docker-compose.phpqa.yaml using the [Docker image](https://hub.docker.com/r/jakzal/phpqa/) based on [PHPQA](https://github.com/jakzal/phpqa).

## Interacting with PHPQA

TODO:
How to configure?
How to run reports?

**Contributed and maintained by [@nicobot](https://github.com/nicobot)**
