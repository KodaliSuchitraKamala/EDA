# Salesforce Education Data Architecture (EDA)

**Version:** 244 (Latest release: Apr 27, 2023) :contentReference[oaicite:1]{index=1}

EDA provides a standardized, open-source data model and framework built on the Salesforce Platform—designed to support K‑20 institutions in managing the full student lifecycle.

---

## 📚 Overview

- Built by Salesforce.org in collaboration with the K‑20 community :contentReference[oaicite:2]{index=2}.
- Offers preconfigured objects, relationships, logic, and automation tailored for educational use cases.
- Provides flexibility and extensibility to meet diverse institutional needs.

---

## 🔧 Key Features

- **Pre-defined Data Model**: Includes objects like `Account`, `Contact`, `ProgramEnrollment`, `CourseOffering`, `Affiliation`, `AccountContactRelation`, and more.
- **Automation & Logic**: Pre-built rollups, validation rules, triggers, and flows to ensure data integrity and streamline workflows.
- **Extensible Architecture**: Customize with your own objects, fields, and automations without modifying core metadata.
- **Open Collaboration**: Developed with community contributions—welcomes extensions, bug fixes, and new enhancements.

---

## 🚀 Installation

Choose your setup path:

| Setup Option             | Steps                                                                 |
|--------------------------|------------------------------------------------------------------------|
| **Trial Org**            | 1. Sign up for a Salesforce trial<br>2. Install EDA via Salesforce AppExchange or CLI |
| **Existing Salesforce Org** | 1. Use EDA Installer<br>2. Follow prompts to install core package |

---

## 🛠️ Getting Started (Developer Setup)

```bash
# Clone the repo
git clone https://github.com/SalesforceFoundation/EDA.git
cd EDA

# Install dependencies
yarn install

# Run pre-commit hooks and format code
yarn lint
yarn prettier --check .

# To bypass hooks (use cautiously)
git commit --no-verify
