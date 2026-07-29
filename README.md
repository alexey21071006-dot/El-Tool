# 🛠️ El Tools

**El Tools** is a lightweight, high-performance CLI utility engineered to automate daily reporting routines for developers. It aggregates local Git activity, monitors workspace events, and generates clean, structured engineering reports directly inside your terminal—zero GUI, zero OOP bloat.

The project is strictly built on procedural architecture, pure functions, and zero heavy external dependencies.

---

## 🎯 Key Features

* **Git Automation:** Instant collection of commit hashes and messages from the past 24 hours.
* **Streamlined Logging:** Isolated logging engine with event-type classification and UTF-8 validation.
* **Zero Dependencies:** Relies entirely on native Python modules and direct system subprocess calls.
* **Modular Control:** Clear separation of concerns with a centralized command-line interface.

---

## 📂 Architecture Breakdown

The project is structured into autonomous functional modules:
* `el_core.py` — Central orchestrator. Glues data collection, logging, and application logic.
* `el_console.py` — Command-line interface. Parses user arguments, flags, and inputs.
* `el_logger.py` — Core logging system. Safely writes categorized data into `reserve.log.txt`.
* `el_reporter.py` — Analytical module. Executes Git lookups and compiles final reports.

---

## 🚀 Quick Start

### Prerequisites
* Python 3.10+
* Git installed and configured in your system environment

### Execution
To orchestrate the system and compile your daily activity report, run:
```bash
python el_core.py --report --today
```

---

## 🛡️ Engineering Philosophy (Fears-256)
1. **Pure Functions First:** No redundant classes or boilerplate where explicit functions excel.
2. **Data Privacy:** All logs, tracking data, and reports remain strictly local.
3. **Maximum Throughput:** Lightning-fast execution utilizing native system processes.

---
Engineered for the **Fears-256** developer ecosystem.
