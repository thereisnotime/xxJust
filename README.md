# xxJust

A biased Justfile collection for various use cases.

[![Lint Justfiles](https://github.com/thereisnotime/xxJust/actions/workflows/ci.yml/badge.svg)](https://github.com/thereisnotime/xxJust/actions/workflows/ci.yml)

## Features

- Autoupdate from the repository.
- Recipes to help troubleshooting, management and operation.

## Goals and Philosophy

1. Justfiles should be self-contained.
2. Justfiles should have a help menu.
3. Justfiles should work with Docker containers where they use third party tools (other than busybox etc.).
4. Justfiles should can be biased if the bias implements a good practice.

## Requirements

Most of the requirements are:

- git
- curl
- [just](https://github.com/casey/just)
- Docker (for some of the fancier recipes)
- grep
- awk
- sed
