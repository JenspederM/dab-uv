# Databricks Asset Bundles for UV

A Databricks Asset Bundle template for UV.

## Overview

This repository contains a Databricks Asset Bundle template for UV. The template is a starting point for creating a Databricks Asset Bundle for UV.

## Getting Started

To get started, follow the instructions below.

### Prerequisites

Before installing the template, you must have the following installed:

- [Databricks CLI](https://docs.databricks.com/en/dev-tools/cli/install.html)
- [uv](https://docs.astral.sh/uv/getting-started/installation/) 

### Installation

Before you can use the template, you must configure [authentication](https://docs.databricks.com/en/dev-tools/bundles/index.html#authentication) with the Databricks CLI. Then you can initialize a new project using the template as follows:

```bash
# Initialize a new project using the template
databricks bundle init https://github.com/JenspederM/dab-uv

# Go to the project directory
cd <project-name>

# Deploy the bundle
databricks bundle deploy

# Run the template job (defined in <project-name>/resources)
databricks bundle run my-job

# Destroy the bundle
databricks bundle destroy
```
