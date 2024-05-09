# Data Pipelines with Dagster

Please note that this repository is intended solely for educational purposes.

## Dagster Project

This repository is dedicated to a [Dagster](https://dagster.io/) project designed to complement Dagster University coursework.

## Getting Started

To begin, install your Dagster code location as a Python package by executing the following command in your terminal. Utilizing the `--editable` (`-e`) flag, pip will install your Python package in ["editable mode"](https://pip.pypa.io/en/latest/topics/local-project-installs/#editable-installs), ensuring that local code changes are automatically applied during development.

```bash
pip install -e ".[dev]"
```

Create a `.env` file as it is include to .gitignore as security and define the necessary environment variables

Then, start the Dagster UI web server:

```bash
dagster dev
```

Open http://localhost:3000 with your browser to see the project.

## Development

### Adding new Python dependencies

You can specify new Python dependencies in `setup.py`.

## Deploy on Dagster Cloud

The easiest way to deploy your Dagster project is to use Dagster Cloud.

Check out the [Dagster Cloud Documentation](https://docs.dagster.cloud) to learn more.
