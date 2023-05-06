# A custom version of [ACSONE Odoo project template](https://github.com/acsone/acsone-odoo-project-template)

> support acsone/odoo-bedrock:`14.0-py39`-latest **only**

## How to use this template

### Prerequisites

`pipx install copier`

### Initializing a new project

`copier copy git+https://github.com/DoJ33/odoo-project-template {project-root-dir}`

This will ask questions and create the `{project-root-dir}` directory and initialize the
project inside it.

### Updating an existing project

Inside the project root, run `copier -f update`, or `copier update` if you want to
change the answers to some questions.

## How to use the generated project

See the generated [README](src/README.md.jinja).
