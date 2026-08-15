# databricks_test

The `databricks_test` project was generated using the default Python template.

This repository is a personal environment for testing, experimentation, and learning with Databricks.

## Project structure

* `src/`: Python source code for this project.
  * `src/databricks_test/`: Shared Python code that can be used by jobs and pipelines.
* `resources/`: Resource configurations such as jobs and pipelines.
* `tests/`: Unit tests for the shared Python code.
* `fixtures/`: Fixtures for data sets, primarily used for testing.

## Topics

This repository will be used to experiment with different Databricks features and practices, including:

* Databricks Bundles
* Databricks CLI
* Jobs and Workflows
* Notebooks
* Git and GitHub
* Unity Catalog
* Delta Lake
* Databricks SQL
* Python and PySpark
* ETL / ELT
* CI/CD
* Automation
* Performance optimization
* Development and deployment practices

## Getting started

Choose how you want to work on this project:

(a) Directly in your Databricks workspace.

(b) Locally with an IDE such as VS Code or Cursor.

(c) Using the Databricks CLI.

For local development, install the project dependencies using `uv`:

    uv sync --dev

## Using the project with the Databricks CLI

Authenticate to your Databricks workspace if you have not done so already:

    databricks configure

To validate the bundle configuration:

    databricks bundle validate

To deploy the development version:

    databricks bundle deploy --target dev

To deploy the production version:

    databricks bundle deploy --target prod

To run a job or pipeline defined in the bundle:

    databricks bundle run

To run the tests locally:

    uv run pytest

## Purpose

The main purpose of this repository is to provide a controlled environment to experiment with Databricks, validate implementations, and learn different development and deployment approaches.

All experiments are version-controlled using Git.

> Databricks experimentation project created and maintained by Edwin Torres.
>
> GitHub: https://github.com/edwinr2000