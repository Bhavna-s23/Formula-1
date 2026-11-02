FORMULA 1 RACE INTELLIGENCE
Web Integration – Project Documentation

1. Project Introduction

The Formula 1 Race Intelligence project is a data-driven web application developed to present Formula 1 racing insights from 2010 to 2026.

The application integrates an interactive Tableau Dashboard and a Tableau Story into a single website using Python Flask, HTML and CSS.

2. Project Objectives

- Develop a web interface for the Formula 1 project.
- Integrate the published Tableau Dashboard.
- Embed the Tableau Story containing nine scenes.
- Provide easy navigation between project sections.
- Present important Formula 1 performance indicators.

3. Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Flask | Web application framework |
| HTML5 | Webpage structure |
| CSS3 | Styling and responsive layout |
| Tableau Public | Interactive dashboard and story |
| Visual Studio Code | Development environment |

4. Project Implementation

Step 1: Project Setup**

Created a project folder and configured the Python development environment using Visual Studio Code.

Step 2: Flask Installation**

Installed Flask using:

`python -m pip install flask`

Step 3: Flask Application Development**

Created `app.py` to initialise the Flask application and render the homepage.

Step 4: Website Development**

Created an HTML homepage with:
- F1-themed navigation.
- Project overview.
- KPI summary cards.
- Dashboard section.
- Story section.

Step 5: Tableau Integration**

Embedded the published Formula 1 Race Intelligence Dashboard and Story using HTML iframe elements.

Step 6: Local Testing**

Ran the Flask application using:

`python Craftivo/app.py`

Accessed the application through:

`http://127.0.0.1:5000`

Verified that the homepage, website assets, Tableau Dashboard and Story loaded successfully.

5. Project Features

- Dark-themed Formula 1 homepage.
- Project overview and KPI summary.
- Interactive Tableau Dashboard.
- Embedded nine-scene Tableau Story.
- Navigation between website sections.
- Responsive page layout.

6. Testing and Validation

The following components were tested:

| Test | Result |
|---|---|
| Flask application startup | Successful |
| Homepage loading | Successful |
| CSS and image assets | Successful |
| Navigation links | Tested |
| Tableau Dashboard embedding | Successful |
| Tableau Story embedding | Successful |

7. Project Outcome

Successfully developed and locally tested a Flask-based web application integrating the Formula 1 Race Intelligence Dashboard and Story published on Tableau Public.

The application provides a single web interface through which users can explore Formula 1 performance insights and interactive visualisations.

8. Conclusion

This web integration demonstrates how Python Flask can be used to connect Tableau Public visualisations with a customised web interface. It provides an accessible presentation of the Formula 1 Race Intelligence project.

9. Future Scope

- Deploy the application on a public hosting platform.
- Add more interactive project features.
- Improve mobile responsiveness.
- Include additional Formula 1 analytical insights.