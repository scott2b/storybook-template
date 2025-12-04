# Hybrid GitHub+Copier Template

This repository is a *hybrid* template:

- The `template/` directory contains the Copier template for **final projects**.
- After running sync (see below) the repository root will contain a rendered example
  project for GitHub’s “Use this template” feature.


## Workflow

1. Edit files in `template/` to define your project scaffolding.
2. Run `./sync_root.sh` to regenerate the example project in the repository root.
3. Consumers can either:
   - Click “Use this template” on GitHub to copy the rendered root, or
   - To generate a project with prompts.
     - Run `copier copy gh:username/this-repo new-project`
     - Or for ssh: `copier copy git@github.com:username/this-repo new-project`

