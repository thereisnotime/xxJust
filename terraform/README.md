# terraform

Biased Justfile for easier Terraform project management, optimization, troubleshooting etc.

## Usage

Place it in your Terraform project folder next to your main.tf or add an import that references it from the root of your repository in case you have multiple projects.

### Infracost

If you want to use infracost, make sure to have the $HOME/.config/infracost/credentials.yml file with the API key inside.

## Installation

Just place the file in your project:

```bash
curl -s https://raw.githubusercontent.com/thereisnotime/xxJust/master/terraform/justfile -o justfile
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

- [ ] Add examples for every recipe with description.
- [ ] Move tfk8s to Docker.
- [ ] Wrap more TF commands like refresh, workspace and others that are missing.
- [ ] Improve docs and graph recipes.
- [ ] Add soft fail on missing .env file.
