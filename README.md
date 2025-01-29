# Databricks Asset Bundles for UV

A Databricks Asset Bundle template for UV.

## Overview

This repository contains a Databricks Asset Bundle template for UV. The template is a starting point for creating a Databricks Asset Bundle for UV.

## Getting Started

To get started, follow the instructions below.

### Prerequisites

- [Databricks CLI](https://docs.databricks.com/dev-tools/cli/index.html)


### Installation

First you must configure [authentication](https://docs.databricks.com/en/dev-tools/bundles/index.html#authentication) with the Databricks CLI. Then you can initialize a new project using the template as follows:

```
# Initialize a new project using the template
databricks bundle init https://github.com/JenspederM/dab-uv

# Go to the project directory
cd <project-name>

# Deploy the bundle
databricks bundle deploy

# Run the jobs (defined in <project-name>/resources)
databricks bundle run my-job

# Destroy the bundle
databricks bundle destroy
```
