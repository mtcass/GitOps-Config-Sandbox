# GitOps Config Manager Sandbox

This is a companion repository containing sample configuration files and fixtures used to test and demonstrate the **[GitOps Config Manager](https://github.com/mtcass/gitops-config-manager)** project.

## 📂 Structure

- `configs/`: Sample JSON configuration files representing different environments (e.g., staging, production).
- `schemas/`: Sample JSON schemas used for structure validation.

## 🚀 Usage

Reference these paths in your local `.env` file when running the Config Manager:

```env
CONFIG_FILE_PATH=configs/
SCHEMA_FILE_PATH=schemas/