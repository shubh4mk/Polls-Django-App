# 🗳️ Django Polls App

A simple web application built using Django, following the official [Django documentation tutorial](https://docs.djangoproject.com/en/stable/intro/). This app lets users view and vote on poll questions.

---

## 🚀 Features

- List all available polls
- View individual poll details
- Vote on poll choices
- See poll results

---

## 🛠️ Tech Stack

- Python 3.x
- Django 4.x or 5.x
- SQLite (default database)

---

## 📦 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/django-polls.git
cd django-polls
````

### 2. Create and Activate a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run Migrations

```bash
python manage.py migrate
```

### 5. Start the Development Server

```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000/polls/` to see the app in action.

---

## 🧪 Running Tests

```bash
python manage.py test
```

---

## 📁 Project Structure

```
django-polls/
├── manage.py
├── mysite/
│   └── settings.py, urls.py, ...
├── polls/
│   └── views.py, urls.py, models.py, ...
├── templates/
│   └── polls/
│       └── index.html, detail.html, ...
└── requirements.txt
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgments

Based on the official [Django Tutorial](https://docs.djangoproject.com/en/stable/intro/).
