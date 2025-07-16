# Nebula

Nebula is a lightweight, modular task orchestration engine for managing distributed workflows in Python. Whether you're automating your personal projects or building a microservice pipeline, Nebula makes it easy to define, run, and monitor tasks across your system.

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

### Prerequisites

- Python 3.8+
- Docker (optional)
- Redis (for task queue backend)

### Installation

```bash
pip install nebulaforge

# Example

```
from nebula import Task, Workflow

@Task(name="greet")
def greet(name: str):
    print(f"Hello, {name}!")

wf = Workflow("morning-routine")
wf.add_task("greet", args=["Alice"])
wf.run()
```

# CLI Usage

nebulaforge run workflow.yaml

