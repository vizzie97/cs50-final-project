# F1 Fan Hub: CS50 Final Project

Welcome to the **F1 Fan Hub**, my first-ever project hosted on GitHub\! This web application was built over the course of the last few weeks, combining foundational knowledge from **Harvard's CS50x** with independent research into modern web design and API integration.

## Project Overview

The F1 Fan Hub is a dynamic dashboard for Formula 1 enthusiasts. Users can register, log in, and support their favorite constructors. The interface dynamically updates its theme—including colors and driver lineups—based on the team the user chooses to support.

## Tech Stack & Tools

  * [cite_start]**Backend:** Python (Flask) [cite: 1]
  * [cite_start]**Database:** SQLite3 [cite: 1]
  * [cite_start]**Frontend:** HTML5, CSS3 (Custom Grid & Flexbox layouts) [cite: 1]
  * [cite_start]**Authentication:** Werkzeug Security (Password Hashing) [cite: 1]
  * [cite_start]**Data Source:** [Jolpi API](https://www.google.com/search?q=https://api.jolpi.ca/)for live standings [cite: 1]

## Learning Journey & Resources

  * [cite_start]**CS50 Basics:** Used SQL for user data management and Flask for routing and session handling[cite: 1].
  * [cite_start]**AI Collaboration:** Leveraged Gemini to assist with complex CSS challenges, specifically for selecting team-accurate color palettes and implementing custom font files[cite: 1].

### **Documentation Referenced**

  * [cite_start]**Flask & Jinja2:** Deep dives into template inheritance and session management[cite: 1].
  * [cite_start]**MDN Web Docs:** Referenced for CSS Custom Properties (Variables) and the `backdrop-filter` property for glassmorphism[cite: 1].
  * [cite_start]**CSS-Tricks:** Used for mastering Fluid Grid columns and flexbox alignment[cite: 1].
  * [cite_start]**W3Schools:** Referenced for CSS transitions and pseudo-elements (navigation hover effects)[cite: 1].

## Key Features

  * [cite_start]**Custom Typography:** Features the premium **Costella** handwritten font for driver signatures and the **Formula1 Display** font for a brand-accurate feel[cite: 1].
  * [cite_start]**Dynamic Theming:** The dashboard UI (borders, buttons, shadows) changes color based on the selected team's identity[cite: 1].
  * [cite_start]**Responsive Standings:** Live-fetched data for both Constructor and Driver world championships[cite: 1].

## How to Run

1. Clone the repo:
   git clone https://github.com/yourusername/cs50-final-project.git

2. Install dependencies:
   pip install -r requirements.txt

3. Run the app:
   python app.py
   Ensure `f1.db` is in the root directory with a `users` table containing `id`, `username`, `hash`, `team`, and `driver`.

4. Open in browser:
   http://127.0.0.1:5000

## Final Notes

**Built for the CS50 Final Project.**
