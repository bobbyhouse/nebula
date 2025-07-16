# Nebula

Nebula is a lightweight app

> **Tagline:** *Build workflows that scale like the stars.*

---
## ✨ Features

- 🔧 YAML or Python-based workflow definitions  
- 🧩 Plugin architecture for custom task runners  
- 🔄 Retry policies, timeout enforcement, and circuit breaking  
- 📊 CLI and Web Dashboard for real-time monitoring  
- 📁 Supports local, Docker, and Kubernetes task execution  
- 🔐 Secrets management using environment or Vault  

---
## 🚀 Getting Started

## Prerequisites

Make sure that you have `uv` installed

```
pipx install uv
```

or via homebrew (on macOS):
```
brew install astral-sh/uv/uv
```

Make sure that you have Python 3.8+ installed
## Setup Instructions

### 1. Create and Activate Virtual Environment

For macOS and Linux
```
uv venv
source .venv/bin/activate
```

For Windows
```
uv venv
.venv\Scripts\activate
```
### 2. Install project dependencies

```
uv sync
```
### 3. Run the project

`uv run main.py`
## Project Structure

```
nebula/
├── README.md
├── pyproject.toml
├── main.py
├── tests/
│   └── test_main.py
├── .gitignore
```
