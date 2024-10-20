## Hello Developers, This is a Stock-market-prediction tool according to daywise.

### Run into a locally Server - 

**STEP 1:** Create a virtual environment
(For Windows)
```bash
  python -m venv virtualenv
```
(For MacOS and Linux)
```bash
  python3 -m venv virtualenv
```

**STEP 2:** Activate the virtual environment.
(For Windows)
```bash
  virtualenv\Scripts\activate
```
(For MacOS and Linux)
```bash
  source virtualenv/bin/activate
```

**STEP 3:** Install the dependencies.
```bash
  pip install -r requirements.txt
```

**STEP 4:** Migrate the Django project.
(For Windows)
```bash
  python manage.py migrate
```
(For MacOS and Linux)
```bash
  python3 manage.py migrate
```

**STEP 5:** Run the application.
(For Windows)
```bash
  python manage.py runserver
```
(For MacOS and Linux)
```bash
  python3 manage.py runserver
```

### Deploy your Project On Render.com platform - 
**Step 1:** Build Command -  ./build.sh

**Step 2:** Start Command - gunicorn core.wsgi:application

**Step 3:** Enviorment Variable - PYTHON_VERSION : 3.11.5  (your latest version)
