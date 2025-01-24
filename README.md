# jupyter-python-template
Template project to configure codespaces for use with jupyter - redacting
results on commit.

## Configuration
This template project has the following set up to make easier to clone and get
going messing around with Python and Jupyter.

- Devcontainer set up with
  - Python 3.11
  - Poetry
- Extensions
  - Jupyter renderers
  - Jupyter
  - Copilot
  - Markdown lint
  - github pull requests
- Auto installs poetry dependencies on devcontainer start
- Configures Jupyter notebook to be ready to go.
- Configures git to remove the output of Jupyter runs before committing
to ensure no sensitive output is saved in commits (e.g. results of data
used in an execution step).

## Initalisation

Once cloned from template - make sure to create poetry pyproject.toml with
`poetry init` before starting devcontainer.
