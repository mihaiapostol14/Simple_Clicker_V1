# Simple Clicker V1

A simple clicker web application built using **Python** with the **Django** framework, styled using **Bootstrap** and enhanced with **JavaScript**.

## Purpose
This project demonstrates a minimal clicker app where users can increment or decrement a counter value. It serves as a learning and demonstration tool for Django web development with modern front-end integration.

## Main Features
- **Counter App**: Increment/decrement a visible counter using buttons or keyboard arrows.
- **Responsive UI**: Styled with Bootstrap and custom CSS for a modern look.
- **JavaScript Enhancements**: Real-time updates of the counter and keyboard support.
- **Django Project Structure**: Follows Django best practices for project and app organization.

## Tech Stack
- **Backend**: Python 3, Django 4.2
- **Frontend**: Bootstrap, JavaScript, CSS (with Google Fonts)
- **Database**: SQLite (default for Django development)
- **Other**: Django templating system, static files management

## Project Structure
- `Clicker/Clicker/`: Django project settings and configuration files.
- `Clicker/clicker_app/`: Django app containing main logic, utilities, and admin config.
- `Clicker/templates/`: HTML templates for the app.
- `Clicker/static/`: Static files (CSS, JS).

## How It Works
- The main interface displays a counter and two buttons (`+` and `-`).
- Users can click the buttons or use the `ArrowUp`/`ArrowDown` keys to change the counter.
- Input is validated to prevent negative or non-numeric values.

## How to Get Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/mihaiapostol14/Simple_Clicker_V1.git
   ```
2. **Navigate to the project folder:**
   ```bash
   cd Simple_Clicker_V1/Clicker
   ```
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Run migrations:**
   ```bash
   python manage.py migrate
   ```
5. **Start the development server:**
   ```bash
   python manage.py runserver
   ```
6. **Access the app:**  
   Open `http://127.0.0.1:8000/` in your browser.

## Code Highlights

- **settings.py**: Django configuration, app registration, middleware, static files setup.
- **clicker.js**: Handles counter logic and user interactions.
- **clicker.css**: Provides modern, responsive styling.

## License
_Not specified in repository_

## Author
**[mihaiapostol14](https://github.com/mihaiapostol14)**