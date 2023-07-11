
# Student Management System

This is a student management system built using Django.

<img width="1000" alt="Screen Shot 2023-07-11 at 03 42 12" src="https://github.com/SahilMehdiyev/student-management-system/assets/86464376/e8be89c4-1632-4c3c-a44e-533cba8fe036">






## Installation

### 1. Create a virtual environment
From the root directory run:

```bash
  python -m venv venv
```

## 2. Activate the virtual environment
From the root directory run:

On macOS:
```bash
  source venv/bin/activate
```

On Windows:

```bash
  venv\scripts\activate
```
## 3. Install required dependencies
From the root directory run:

On macOS:
```bash
  pip install -r requirements.txt
```

## 4. Run migrations
From the root directory run:


```bash
  python manage.py makemigrations
```
```bash
  python manage.py migrate
```


## 5. Create an admin user to access the Django Admin interface
From the root directory run:


```bash
  python manage.py createsuperuser
```

## Run the application

From the root directory run: 

```bash
  python manage.py runserver
```
