# databricks-demo

## Overview

This repository is a Databricks demo project showcasing data engineering, analytics, and/or machine learning workflows on the Databricks platform.

## Prerequisites

- A Databricks workspace (Azure, AWS, or GCP)
- A Databricks compute cluster or serverless compute
- Unity Catalog enabled (recommended)
- Permissions to create and run notebooks

## Getting Started

1. **Import the notebooks** — Clone or import the notebook(s) from this repository into your Databricks workspace.
2. **Attach a cluster** — Open a notebook and attach a running compute cluster or enable serverless compute.
3. **Run the cells** — Execute the notebook cells in order from top to bottom.

## Project Structure

| Path | Description |
|---|---|
| `notebooks/` | Main demo notebooks |
| `data/` | Sample or reference datasets (if applicable) |
| `sql/` | SQL scripts and queries (if applicable) |

## Key Features

- End-to-end data pipeline demonstration
- Delta Lake table operations
- Visualizations and dashboards
- Unity Catalog governance and security

## Cleanup

To avoid ongoing compute charges, stop any clusters started for this demo when finished:

```python
# Stop the cluster attached to this notebook (if managed)
dbutils.notebook.exit("Demo complete. Remember to stop your cluster.")
```

## License

This project is licensed under the MIT License.

