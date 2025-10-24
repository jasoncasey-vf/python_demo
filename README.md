# python_demo

A single-page personal website built with Python Flask.

## Description

This is a simple, elegant single-page website that showcases personal information including skills, interests, and background. The website is built using Flask, a lightweight Python web framework, and features a modern, responsive design.

## Features

- **Single Page Design**: All information on one page for easy navigation
- **Responsive Layout**: Works great on desktop and mobile devices
- **Modern UI**: Beautiful gradient design with smooth animations
- **Skills Showcase**: Highlights key technical skills
- **Personal Interests**: Displays hobbies and areas of interest

## Requirements

- Python 3.7 or higher
- Flask 3.0.0

## Installation

1. Clone this repository
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Running the Application

To run the Flask application:

```bash
python app.py
```

The website will be available at `http://localhost:5000`

## Project Structure

```
python_demo/
├── app.py                 # Main Flask application
├── requirements.txt       # Python dependencies
├── templates/
│   └── index.html        # Main HTML template
├── static/
│   └── style.css         # CSS styles
└── README.md             # This file
```

## Development

The application runs in debug mode by default, which means:
- Automatic reloading when files change
- Detailed error messages
- Development server runs on all network interfaces (0.0.0.0)

**Note**: For production deployment, use a production WSGI server like Gunicorn or uWSGI instead of the built-in development server.