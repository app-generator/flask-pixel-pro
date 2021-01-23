# [Flask Pixel PRO](https://appseed.us/apps/flask-apps/flask-pixel-uikit-pro)

**Flask App** coded with basic modules, database, ORM and deployment scripts on top of **Pixel PRO** (premium version), a modern Bootstrap dashboard design. Pixel Pro is a premium Bootstrap 5 UI Kit without jQuery featuring over 1000 components, 50+ sections and 35 example pages including a fully fledged user dashboard.

<br />

> Product Features

- UI-Ready, Jinja2 templating
- SQLite database, Flask-SQLAlchemy ORM
- Session-Based authentication (via **flask_login**), Forms validation
- Deployment scripts: Docker, Gunicorn / Nginx, Heroku
- Support via **Github** (issues tracker) and [Discord](https://discord.gg/fZC6hup).

<br />

> Links

- [Flask Pixel PRO](https://appseed.us/apps/flask-apps/flask-pixel-uikit-pro) - product page
- [Flask Pixel PRO - Demo](https://flask-pixel-pro.appseed-srv1.com/) - LIVE deployment

<br />

![Flask Pixel PRO - Open-Source template project provided by AppSeed.](https://raw.githubusercontent.com/app-generator/flask-pixel-uikit-pro/master/media/flask-pixel-uikit-pro-screen.png)

<br />

## Build from sources

```bash
$ # Clone the sources
$ git clone https://github.com/app-generator/priv-flask-pixel-pro.git
$ cd priv-flask-pixel-pro
$
$ # Virtualenv modules installation (Unix based systems)
$ virtualenv env
$ source env/bin/activate
$
$ # Virtualenv modules installation (Windows based systems)
$ # virtualenv env
$ # .\env\Scripts\activate
$
$ # Install requirements
$ pip3 install -r requirements.txt
$
$ # Set the FLASK_APP environment variable
$ (Unix/Mac) export FLASK_APP=run.py
$ (Windows) set FLASK_APP=run.py
$ (Powershell) $env:FLASK_APP = ".\run.py"
$
$ # Set up the DEBUG environment
$ # (Unix/Mac) export FLASK_ENV=development
$ # (Windows) set FLASK_ENV=development
$ # (Powershell) $env:FLASK_ENV = "development"
$
$ # Run the application
$ # --host=0.0.0.0 - expose the app on all network interfaces (default 127.0.0.1)
$ # --port=5000    - specify the app port (default 5000)  
$ flask run --host=0.0.0.0 --port=5000
$
$ # Access the app in browser: http://127.0.0.1:5000/
```

> Note: To use the app, please access the registration page and create a new user. After authentication, the app will unlock the private pages.

<br />

## Code-base structure

The project has a super simple structure, represented as bellow:

```bash
< PROJECT ROOT >
    |
    |--- app/__init__.py
    |--- app/
    |     | --- <static/assets>
    |     |         |
    |     |         |--- <css>
    |     |         |--- <Js>
    |     |         |--- <img>
    |     |
    |     | --- <templates>
    |     |         |
    |     |         |---<includes>                     # Page chunks, components
    |     |         |       |
    |     |         |       | --- navigation.html      # Top bar
    |     |         |       | --- sidebar.html         # Left sidebar
    |     |         |       | --- scripts.html         # JS scripts common to all pages
    |     |         |       | --- footer.html          # The common footer
    |     |         |
    |     |         |---<layouts>                      # App Layouts (the master pages)
    |     |         |       |
    |     |         |       | --- base.html            # Used by common pages like index, UI
    |     |         |       | --- base-fullscreen.html # Used by auth pages (login, register)
    |     |         |
    |     |         |---<accounts>                     # Auth Pages (login, register)
    |     |         |       |
    |     |         |       | --- login.html           # Use layout `base-fullscreen.html`
    |     |         |       | --- register.html        # Use layout `base-fullscreen.html`  
    |     |         |
    |     |     index.html                             # The default page
    |     |     page-404.html                          # Error 404 page (page not found)
    |     |     page-500.html                          # Error 500 page (server error)
    |     |       *.html                               # All other pages provided by the UI Kit
    |
    |--- requirements.txt
    |
    |--- run.py
    |
    |-----------------------------
```

<br />

## Credits & Links

- [Flask Framework](https://www.palletsprojects.com/p/flask/) - The offcial website
- [Boilerplate Code](https://appseed.us/boilerplate-code) - Index provided by **AppSeed**
- [Boilerplate Code](https://github.com/app-generator/boilerplate-code) - Index published on Github

<br />

---
[Flask Pixel PRO](https://appseed.us/apps/flask-apps/flask-pixel-uikit-pro) - Provided by **AppSeed** [Web App Generator](https://appseed.us/app-generator).
