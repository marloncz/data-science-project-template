# Data Science Project Template

Welcome to the Data Science Project Template! This template is build on top of [copier](https://github.com/copier-org/copier) and is designed to handle the initial setup of data science projects for myself. It provides a customizable structure and integrates various tools.

## Features

- **Customizable Project Structure**: Set up your project with a predefined folder structure for organizing data, code, and results.
- **Hydra Integration**: Optionally use Hydra for orchestration.
- **Python Version Configuration**: Specify the Python version for your project.
- **Direnv Support**: Optionally use Direnv for environment variable management.
- **JupyterLab Installation**: Optionally install JupyterLab for interactive development.
- **Docker Support**: Optionally initialize a Dockerfile for containerized development.

## Usage

To create a new project based on this template, use the Copier tool with the following command:

```bash
copier copy --trust "git@github.com:marloncz/data-science-project-template" /path/to/new/project
```

Ensure you have Copier installed. If not, you can install it using pip:

```bash
pip install copier
```
