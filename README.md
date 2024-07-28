# Cloudsmith Package Deployment

This repository demonstrates how to create a simple Python package and deploy it to Cloudsmith using GitHub Actions. The workflow automates packaging and uploading to Cloudsmith, utilizing OIDC for authentication.

## Repository Structure
Cloudsmith_Package/
├── .github/
│ └── workflows/
│ └── package-and-push.yml
├── sample_package/
│ └── init.py
└── setup.py

==========================================


## Getting Started

### Prerequisites

- Python 3.x
- GitHub Account
- Cloudsmith Account

### Clone the Repository

```sh
git clone https://github.com/IndranarayanChaudhuri/Cloudsmith_Package.git
cd Cloudsmith_Package