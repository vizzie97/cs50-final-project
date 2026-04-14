# F1 Fan Hub: CS50 Final Project

Welcome to the **F1 Fan Hub**, my first-ever project hosted on GitHub\! This web application was built over the course of the last few weeks, combining foundational knowledge from **Harvard's CS50x** with independent research into modern web design and API integration.

## Project Overview

The F1 Fan Hub is a dynamic dashboard for Formula 1 enthusiasts. Users can register, log in, and support their favorite constructors. The interface dynamically updates its theme—including colors and driver lineups—based on the team the user chooses to support.

## Tech Stack & Tools

* **Backend:** Python (Flask) 
* **Database:** SQLite3 
* **Frontend:** HTML5, CSS3 (Custom Grid & Flexbox layouts)  
* **Authentication:** Werkzeug Security (Password Hashing)  
* **Data Source:** [Jolpi API](https://www.google.com/search?q=https://api.jolpi.ca/)for live standings  

## Learning Journey & Resources
* **CS50 Basics:** Used SQL for user data management and Flask for routing and session handling .
* **AI Collaboration:** Leveraged Gemini to assist with complex CSS challenges, specifically for selecting team-accurate color palettes and implementing custom font files .

### **Documentation Referenced**

  **Flask & Jinja2:** Deep dives into template inheritance and session management .
  **MDN Web Docs:** Referenced for CSS Custom Properties (Variables) and the `backdrop-filter` property for glassmorphism .
  **CSS-Tricks:** Used for mastering Fluid Grid columns and flexbox alignment .
  **W3Schools:** Referenced for CSS transitions and pseudo-elements (navigation hover effects) .

## Key Features

 * **Custom Typography:** Features the premium **Costella** handwritten font for driver signatures and the **Formula1 Display** font for a brand-accurate feel .
 * **Dynamic Theming:** The dashboard UI (borders, buttons, shadows) changes color based on the selected team's identity .
 * **Responsive Standings:** Live-fetched data for both Constructor and Driver world championships .

## How to Run
To run the F1 Fan Hub on your local machine, follow these steps:

1. Prerequisites
Ensure you have Python 3.x installed on your system. You will also need pip (Python's package installer).

2. Clone the Repository
Open your terminal or command prompt and run:

Bash
git clone https://github.com/vizzie97/cs50-final-project
cd cs50-final-project

4. Set Up a Virtual Environment (Recommended)
This keeps the project dependencies isolated from your global Python installation:

Bash
# Create the environment
python -m venv venv

# Activate it (Windows)
venv\Scripts\activate

# Activate it (Mac/Linux)
source venv/bin/activate

4. Install Dependencies
Install all required libraries (Flask, CS50, Requests, etc.) using the provided requirements file:

Bash
pip install -r requirements.txt

5. Database Configuration
The project uses SQLite.

Ensure the f1.db file is in the root directory.

Note for Localhost: Ensure the database connection in app.py is set to the relative path:
db = SQL("sqlite:///f1.db")

6. Start the Engines
Run the Flask application:
---
Bash
python app.py
---
7. Access the Dashboard
Once the server is running, open your web browser and navigate to:
http://127.0.0.1:5000

Project Structure

* ├── app.py              # Main Flask application logic
* ├── f1.db               # SQLite database for users & preferences
* ├── requirements.txt    # List of Python dependencies
* ├── static/             # Assets (CSS, Fonts, Team Images)
* │   ├── css/
* │   ├── fonts/          # Includes Costella.ttf & F1-Bold.otf
* │   └── images/         # Constructor & Driver assets
* └── templates/          # HTML files (index, login, standings, etc.)
