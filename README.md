# Little Lemon Restaurant

A Django-based restaurant management system for Little Lemon restaurant. This application provides a modern web interface for customers to view the menu, make reservations, and learn about the restaurant.

## Features

- Interactive menu display with detailed item information
- Online reservation system
- Restaurant information and location
- Responsive design for all devices
- Interactive Google Maps integration

## Technology Stack

- Python 3.x
- Django 5.2.1
- SQLite Database
- HTML5/CSS3
- JavaScript

## Installation

1. Clone the repository:
```bash
git clone [your-repository-url]
cd littlelemon
```

2. Create and activate a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate  # On Linux/Mac
# or
.venv\Scripts\activate  # On Windows
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run migrations:
```bash
python manage.py migrate
```

5. Start the development server:
```bash
python manage.py runserver
```

The application will be available at `http://127.0.0.1:8000/`

## Project Structure

- `restaurant/` - Main application directory
  - `templates/` - HTML templates
  - `static/` - Static files (CSS, JS, images)
  - `models.py` - Database models
  - `views.py` - View functions
  - `urls.py` - URL configurations

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



## Contact

Your Name - [your-email@example.com]

Project Link: [https://github.com/yourusername/littlelemon](https://github.com/yourusername/littlelemon) 
