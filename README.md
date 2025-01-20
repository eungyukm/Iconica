# Icon Generation Project

## Overview
This project utilizes **Django Rest Framework (DRF)** and **DELL-3** to generate icons. It is designed to efficiently handle requests for customized icon creation and integrates with DRF-Spectacular for API documentation. The final deployment is planned for Azure.

---

## Features
- **Icon Generation**: Powered by DELL-3 for high-quality icon generation.
- **API Integration**: RESTful API built with Django Rest Framework.
- **API Documentation**: Automatically generated documentation using DRF-Spectacular.
- **Deployment**: Configured for Azure cloud deployment.

---

## Requirements
- Python 3.9+
- Django 4.0+
- Django Rest Framework
- DRF-Spectacular
- Azure CLI

---

## Installation

### 1. Clone the repository:
```bash
git clone https://github.com/yourusername/icon-generation-project.git
cd icon-generation-project
```

### 2. Set up a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate   # For Windows
```

### 3. Install dependencies:
```bash
pip install -r requirements.txt
```

### 4. Run the server:
```bash
python manage.py runserver
```

---

## API Endpoints
For full API documentation, visit `/swagger/` or `/redoc/` after starting the server.

---

## Deployment
1. Ensure Azure CLI is installed and logged in.
2. Configure Azure services for Django deployment.
3. Push the application to Azure.

---
