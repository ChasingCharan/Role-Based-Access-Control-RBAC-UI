# Role-Based Access Control (RBAC) Project

## Overview

This project implements a Role-Based Access Control (RBAC) system using Django. It enables administrators to assign roles and permissions to users for managing access to various parts of an application.

## Features

- User authentication and registration.
- Role and permission management.
- Secure access control with Django models.
- Use of Bootstrap for responsive design.
- Custom forms for user interaction.

## Technologies Used

- **Backend:** Python, Django
- **Frontend:** HTML, CSS, Bootstrap 5
- **Database:** SQLite (default for Django; replaceable with other databases)
- **Other Libraries:** 
  - `crispy-bootstrap5` for enhanced form styling.
  - `django-crispy-forms` for form management.

## Prerequisites

- Python 3.10 or above
- pip (Python package manager)
- Git (for version control)

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/ChasingCharan/Role-Based-Access-Control-RBAC-UI.git
cd RBAC_Project

# Install Dependencies
pip install -r requirements.txt

# Apply Migrations
python manage.py makemigrations
python manage.py migrate

# Run the Development Server
python manage.py runserver