# Inventory Management System (Flask)

Backend inventory management system built with Flask and SQLAlchemy featuring supplier relationships and full CRUD operations.

## Features
- Create, read, update, and delete Suppliers and Products
- Relational modeling (Supplier → Products)
- Server-rendered UI using Jinja2 templates

## Tech Stack
- Python
- Flask
- SQLAlchemy
- HTML/CSS (templates)

## Project Structure
- app.py– main application entry
- models.py – database models
- templates/ – Jinja2 templates
- static/css/ – styling

## How to Run (Local)
1. Clone the repo
2. Create and activate a virtual environment
3. Install dependencies
4. Run the app

Example (Windows PowerShell):
```bash
python -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt
python app.py
