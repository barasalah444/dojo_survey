# Dojo Survey (Django Application)

A web application built using **Python** and **Django** that processes form submissions via POST requests and displays the submitted data on a response page using session storage.

---

##  Features

- Interactive HTML Form for collecting user responses (Name, Location, Favorite Language, and Comments).
- Form handling via **POST** request methods with CSRF security tokens (`{% csrf_token %}`).
- Data retention across requests using Django's `session` object.
- Clean separation of routes, views, and templates.
- Styled user interface matching project wireframe specifications.

---

##  Tech Stack & Prerequisites

- **Language:** Python 3.x
- **Framework:** Django
- **Frontend:** HTML5, CSS3
- **Version Control:** Git & GitHub

---

##  Repository Structure

```text
dojo_survey/
│
├── dojo_survey/         # Core Project Configuration
│   ├── settings.py      # App registration & general configurations
│   ├── urls.py          # Root URL routing
│   └── ...
│
├── survey_app/          # Main Django Application
│   ├── static/          # Static files (CSS stylesheet)
│   │   └── style.css
│   ├── templates/       # HTML Templates
│   │   ├── index.html   # Main Survey Form
│   │   └── result.html  # Submission Results Page
│   ├── urls.py          # Application-specific routing
│   ├── views.py         # Controller / Request handling logic
│   └── ...
│
├── manage.py            # Django CLI Utility
└── README.md            # Project Documentation
