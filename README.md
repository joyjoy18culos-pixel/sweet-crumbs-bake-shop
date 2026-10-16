# Sweet Crumbs Bake Shop – Django Templates Final Project

A multi-page bakery website built with **Django templates**.  
This project was created as the final individual system demonstration for the College of Information Technology at **Don Mariano Marcos Memorial State University – North La Union Campus**.

## Project Overview

This website demonstrates:

- Django project and app setup
- Multiple pages with individual views and named URL patterns
- Template inheritance using `base.html` and `{% block %}` / `{% extends %}`
- Reusable components with `{% include %}` (navbar & footer)
- Navigation links built with `{% url %}` tags (no hard-coded paths)
- Static files (CSS) loaded with `{% load static %}` and `{% static %}`
- Clean, responsive design that works on smaller screens
- Proper Git & GitHub workflow

**Problem it solves:** Gives a small local bake shop an online presence so customers can view the menu, see photos of products, and contact the shop for orders.

**Target users:** Local customers looking for fresh bread, cakes, and pastries; people who want to place custom cake orders.

## Pages

| Page     | URL          | Description                                      |
|----------|--------------|--------------------------------------------------|
| Home     | `/`          | Welcome hero + quick links                       |
| About    | `/about/`    | Story of the bake shop and what makes it special |
| Menu     | `/services/` | Breads, cakes, cookies, drinks                   |
| Gallery  | `/gallery/`  | Photos of products                               |
| Contact  | `/contact/`  | Address, hours, and contact form                 |

## Features

- Responsive navbar and footer (included on every page)
- Consistent warm bakery-themed design
- Mobile-friendly layout
- Named URL routing
- Static CSS with modern styling

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/joyjoy18culos-pixel/sweet-crumbs-bake-shop.git
cd sweet-crumbs-bake-shop
```

### 2. Create and activate a virtual environment (recommended)

```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS / Linux
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run migrations (creates the database)

```bash
python manage.py migrate
```

### 5. Start the development server

```bash
python manage.py runserver
```

Open your browser and go to: **http://127.0.0.1:8000/**

## Project Structure

```
├── manage.py
├── requirements.txt
├── .gitignore
├── README.md
├── portfolio_project/          # Django project settings
├── main/                       # Main app (views, urls)
├── templates/
│   ├── base.html               # Base layout with blocks
│   ├── includes/
│   │   ├── navbar.html
│   │   └── footer.html
│   ├── home.html
│   ├── about.html
│   ├── services.html           # Menu page
│   ├── gallery.html
│   └── contact.html
└── static/
    └── css/
        └── style.css           # Responsive bakery theme
```

## Technologies Used

- Python 3
- Django 5 / 6
- HTML5 + CSS3 (responsive)

## Acknowledgments

- Django documentation and official tutorials
- Any AI assistance used was reviewed and understood by the student

## License

This project is for educational purposes (DMMMSU-NLUC Final Project).
