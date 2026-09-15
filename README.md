# URL Shortener

A simple and lightweight URL Shortener web application built using **Python, Flask, and SQLite**.

The application allows users to enter a long URL and generate a shortened URL that redirects to the original website.

## Features

* Shorten long URLs
* Generate unique short URLs
* Redirect short URLs to the original URL
* Store URL data using SQLite
* Simple web interface
* Flask-based backend
* Deployed on Render

## Technologies Used

* Python
* Flask
* SQLite
* HTML
* Git & GitHub
* Render

## Project Structure

```text
URL-Shortener/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── instance/
│   └── urls.db
│
├── templates/
│   └── index.html
│
└── venv/
    ├── Include/
    ├── Scripts/
    ├── Lib/
    └── pyvenv.cfg
```

## How It Works

1. The user enters a long URL.
2. The Flask application receives the URL.
3. A unique short code is generated.
4. The URL mapping is stored in the SQLite database.
5. A shortened URL is generated.
6. When the shortened URL is opened, Flask finds the original URL.
7. The user is redirected to the original website.

## Database

This project uses **SQLite** for storing URL information.

Database location:

```text
instance/urls.db
```

## Run Locally

### 1. Clone the repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd <YOUR_PROJECT_FOLDER>
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

For Windows:

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the application

```bash
python app.py
```

Open:

```text
http://127.0.0.1:5000/
```

## Live Demo

https://codealpha-urlshortener-c39e.onrender.com

## CodeAlpha Internship

This project was developed as part of the **CodeAlpha Virtual Internship – Full Stack Development** program.

### Task: URL Shortener

The objective was to build a functional web application that converts long URLs into shorter, shareable URLs.

## Author

**THARUN M**

Backend & AI/ML Software Engineer

* GitHub: https://github.com/mekalatharun-dev
* LinkedIn: https://linkedin.com/in/tharun-m-416271290
