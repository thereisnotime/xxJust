# docker

Biased Justfile for easier Docker project management, optimization, troubleshooting etc.

## Usage

Place it in your Docker project folder next to your Dockerfile or add an import that references it from the root of your repository in case you have multiple projects.

## Installation

Just place the file in your project:

```bash
curl -s https://raw.githubusercontent.com/thereisnotime/xxJust/master/docker/justfile -o justfile
```

And do

```bash
just
```

## Update

To update the justfile from the current directory you do:

```bash
just update-self
```

NOTE: GitHub has a 5 minute cache of raw files.

## Import

If you want to use it in a single repo and not have it copied few times you can import it:

```just
import "../../justfile"
```

## Todos

The following tasks are in the roadmap:

- [ ] Add option to work with a local .env that contains a specific docker container registry configuration.
- [ ] Finish the open TODO's in the justfile.
- [ ] Add option to autogenerate yaml files for Docker tests with ChatGPT if there is a key provided.
