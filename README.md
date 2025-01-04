# Jupyter Shared Dependencies

This package contains common Jupyter dependencies used across Jupyter projects. It helps maintain consistency and reduces duplication in dependency management.

## Installation

Add to your project's dependencies:

```toml
[project]
dependencies = [
    "jupyter-shared-deps @ git+https://github.com/anton-live/jupyter-shared-deps.git"
]
```

## Included Dependencies

- jupyter: Core Jupyter functionality
- pandas: Data manipulation and analysis
- plotly: Interactive plotting library
- google-cloud-bigquery: BigQuery client library
- google-cloud-storage: Cloud Storage client library
- gcsfs: Cloud Storage filesystem interface
- openpyxl: Excel file support
- fsspec: Filesystem interfaces

## Version Policy

Dependencies use semantic versioning with upper bounds to prevent breaking changes while allowing patch and minor updates.

## Development

1. Update dependencies in pyproject.toml
2. Update version number
3. Commit and push changes
4. Create a new release tag to trigger package publishing
