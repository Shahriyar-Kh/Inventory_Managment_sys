# Inventory Management System — Python Desktop Application

A desktop business application built with **Python, Tkinter, SQLite, and Pillow** to manage employees, suppliers, product categories, inventory, sales records, and dashboard totals.

## Engineering Scope

This repository demonstrates practical Python desktop development with a multi-module GUI and local relational persistence.

Implemented modules include:

- employee management
- supplier management
- category management
- product management
- sales management
- dashboard totals for key business entities
- SQLite-backed persistence
- image/icon handling with Pillow

## Technology Stack

- **Python 3**
- **Tkinter**
- **SQLite**
- **Pillow / PIL**

## Repository Structure

```text
Inventory_Managment_sys/
├── Dashborad.py
├── Employee.py
├── Supplier.py
├── Category.py
├── Product.py
├── Sales.py
├── billing.py
├── Create_db.py
├── images/
└── Screenshorts/
```

## Run Locally

```bash
python -m venv .venv
# Windows
.venv\Scripts\activate

pip install pillow
python Dashborad.py
```

SQLite database files in this repository represent local/demo application state; they should not be treated as a production database strategy.

## What This Project Shows

- Python GUI engineering
- modular desktop application structure
- CRUD-style business workflows
- local relational data handling
- event-driven Tkinter UI development

## Author

**Shahriyar Khan** — Software Engineer · Full-Stack Python Developer

- Portfolio: https://shahriyarkhan.com
- GitHub: https://github.com/Shahriyar-Kh
- LinkedIn: https://www.linkedin.com/in/shahriyar-khan-developer/
