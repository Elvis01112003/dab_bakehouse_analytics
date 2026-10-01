# Databricks Bakehouse Analytics

This project demonstrates how to develop, configure, and deploy a Databricks project using **Declarative Automation Bundles (DABs)**.

The project focuses on managing Databricks resources through configuration files and using separate environments for development and production.

## Project Overview

The main objective of this project is to understand how Databricks projects can be:

- Structured and managed using DABs
- Configured for different environments
- Deployed in a controlled and repeatable way
- Managed using CI/CD practices

## Technologies Used

- **Azure Databricks**
- **Declarative Automation Bundles (DABs)**
- **Databricks Workflows / Jobs**
- **GitHub**
- **CI/CD**
- **YAML**

## Project Structure

```text
dab_bakehouse_analytics/
│
├── .github/
│   └── workflows/
│
└── bakehouse_analytics/
    ├── databricks.yml
    └── resources/
