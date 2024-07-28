# Cloudsmith Package Deployment

This repository demonstrates how to create a simple Python package and deploy it to Cloudsmith using GitHub Actions. The workflow automates packaging and uploading to Cloudsmith, utilizing OIDC for authentication.

## Repository Structure

Cloudsmith_Package/
├── .github/
│   └── workflows/
│       └── package-and-push.yml
├── sample_package/
│   └── __init__.py
└── setup.py


- **.github/workflows/package-and-push.yml**: CI workflow for building and pushing the Python package to Cloudsmith.
- **sample_package/**: Contains the sample Python package module.
- **setup.py**: Script for packaging and distributing the Python package.

## Getting Started

### Prerequisites

- Python 3.x
- GitHub Account
- Cloudsmith Account

### Clone the Repository

```sh
git clone https://github.com/IndranarayanChaudhuri/Cloudsmith_Package.git
cd Cloudsmith_Package
