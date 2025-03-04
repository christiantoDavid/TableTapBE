# TableTap – Django REST API 🌟

Welcome to **TableTap**, a SaaS (Software as a Service) platform designed to streamline the ordering process for restaurants, cafes, and coffee shops. This project provides a Django REST API that powers the backend, enabling features like:

- **Digital Menu Creation**: Easily create and manage menus with categories, items, and pricing.  
- **QR Code Generation**: Automatically generate unique QR codes for each table, allowing quick access to the menu by scanning.  
- **Seamless Ordering**: Guests can scan the QR code at their table to view the menu and place orders directly.  
- **Order Management**: Staff can view and manage orders in real time.  

<br />

## 🚀 Table of Contents
1. [Features](#features)  
2. [Tech Stack](#tech-stack)  
3. [Getting Started](#getting-started)  
4. [Project Setup Commands](#project-setup-commands)  
5. [Configuration](#configuration)  
 

<br />

## 🌟 Features
- **Easy Setup**: Quickly configure your digital menu and table QR codes.  
- **Scalable**: Perfect for both small cafes and large restaurants.  
- **Responsive**: Built with Django REST Framework for robust API endpoints.  

<br />

## ⚙️ Tech Stack
- **Python** 
- **Django REST Framework** ![Django REST](https://img.shields.io/badge/-Django%20REST%20API-092E20?logo=django&logoColor=white&style=flat-square)
- **Git & GitHub** 

<br />

## 🏁 Getting Started
Follow these steps to get a local copy up and running:
1. **Fork or create** a new repository on GitHub.  
2. **Clone** the repository to your local machine.  
3. Create and activate a **virtual environment**.  
4. **Install** required dependencies.  
5. **Run** the development server to test the API.  

<br />

## 📋 Project Setup Commands
Below is a quick reference of essential commands when starting from scratch:

1. **Create GitHub repository** in your GitHub account.
   ```bash
   # On GitHub, create a new repository (e.g., TableTap-Backend).
2. **Clone your GitHub** repository into your local machine (open CMD/Terminal and navigate to the desired folder):.
   ```bash
   git clone https://github.com/yourusername/TableTap-Backend.git
3. **Create virtual environment**:
   ```bash
   python -m venv env
   env\Scripts\activate
4. **Install Django and Django REST Framework:**:
   ```bash
   pip install djangorestframework
5. **Start a new Django project in the current directory:**
   ```bash
   django-admin startproject YourProjectName .
6. **Start a new Django app**:
    
    ```
    django-admin startapp YourAppName
    ``` 
7. **Add your `.gitignore` and `requirements.txt`**:
    
    ```
    # Example .gitignore snippet:
    env/
    *.pyc
    __pycache__/
    .DS_Store
    .vscode/
    
    # Example requirements.txt:
    pip freeze > requirements.txt
    ```
    
8. **Update `settings.py`** to include:
    
    ```python
    INSTALLED_APPS = [
        # ...
        'rest_framework',
        'YourAppName',  # Add this line
    ]
    ```

<br />

## 🛠️ Configuration
1. **Run Migrations** to set up your database:
    
    ```
    python manage.py migrate
    ```
    
2. **Create a Superuser** for admin access:
    
    ```
    python manage.py createsuperuser
    ```
    
3. **Run the Development Server**:
    
    ```
    python manage.py runserver
    ```
    
4. **Access the Admin Panel** at [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin).

<br />


---

<p align="center">
  Made with :❤️ & Django by <strong>David Christianto</strong>
</p>

