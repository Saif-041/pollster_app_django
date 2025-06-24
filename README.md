# Pollster App

A Django-based polling application that allows users to create and vote on polls.

## Features

- Create and manage polls with questions and multiple choice options
- Allow users to vote on existing polls
- Track and display poll results
- Modern web interface with Django templates

## Project Structure

```
pollster/
├── polls/          # Poll application
│   ├── models.py   # Database models for Questions and Choices
│   └── ...         # Views, URLs, templates
├── pages/          # Static pages application
├── templates/      # Shared template files
├── db.sqlite3      # SQLite database
└── manage.py       # Django management script
```

## Setup Instructions

1. Install dependencies:
```bash
pip install pipenv
pipenv install
```

2. Run migrations:
```bash
pipenv run python manage.py migrate
```

3. Start the development server:
```bash
pipenv run python manage.py runserver
```

4. Access the application at `http://localhost:8000`

## Technology Stack

- Backend: Django
- Database: SQLite
- Package Management: pipenv

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

