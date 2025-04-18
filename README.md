# [Black Dashboard PRO Django](https://www.creative-tim.com/product/black-dashboard-pro-django) 

Premium **[Django Template](https://www.creative-tim.com/templates/django)** crafted on top of **Black Dashboard PRO**, a modern Bootstrap 5 design. Start your development with a modern Bootstrap 5 Admin template for Django. Soft UI Dashboard is built with over 70 individual components, giving you the freedom of choosing and combining. If you want to code faster, with a smooth workflow, then you should try this template carefully developed with Django, a well-known Python Framework.

> NOTE: Starter provided in partnership with [App-Generator](https://app-generator.dev/), an open-source platform for developers

<br />

## Features: 

- Simple, Easy-to-Extend Codebase
- **Black Dashboard PRO** Design Integration 
- Dynamic Tables - read [docs](https://app-generator.dev/docs/developer-tools/dynamic-datatables.html)
- Dynamic API - read [docs](https://app-generator.dev/docs/developer-tools/dynamic-api.html)
- Charts
- Session-based Authentication, Password recovery
- OAuth (GitHub & Google)
- DB Persistence: SQLite (default), can be used with MySql, PgSql
- [Django CLI Package](https://app-generator.dev/docs/developer-tools/django-cli/index.html)
    - [Commit/rollback Git Changes](https://app-generator.dev/docs/developer-tools/django-cli/git-interface.html)
    - `Backup & restore DB`
    - [Interact with Django Core](https://app-generator.dev/docs/developer-tools/django-cli/query-django.html)
    - `Manage Environment`
    - `Manage Dependencies`
- Session-based Authentication, Password recovery
- DB Persistence: SQLite (default), can be used with MySql, PgSql
- Docker, CI/CD for Render
- [Vite](https://app-generator.dev/docs/technologies/vite/index.html) for assets management 

<br />

[![Django Black Dashboard PRO - Premium Starter crafted by AppSeed and Creative-Tim.](https://user-images.githubusercontent.com/51070104/214872728-230a9955-d391-4900-b352-d68960dbd2c4.png)](https://www.creative-tim.com/product/black-dashboard-pro-django)

<br />

## Table of Contents

* [Demo](#demo)
* [Quick Start](#quick-start)
* [Documentation](#documentation)
* [File Structure](#file-structure)
* [Browser Support](#browser-support)
* [Resources](#resources)
* [Reporting Issues](#reporting-issues)
* [Technical Support or Questions](#technical-support-or-questions)
* [Licensing](#licensing)
* [Useful Links](#useful-links)

<br />

## Demo

> To authenticate use the default credentials ***test / Pass12__*** or create a new user on the **registration page**.

- **Black Dashboard PRO Django** [Login Page](https://www.creative-tim.com/live/black-dashboard-pro-django)

<br />

## Quick start

> UNZIP the sources (requires a purchase from the official product page)

<br />

> 👉 Install modules via `VENV`.


```bash
$ virtualenv env
$ source env/bin/activate
$ pip install -r requirements.txt
```

<br />

> 👉 Edit the `.env` using the template `.env.sample`. 

```env

# True for development, False for production
DEBUG=True

```

<br />

> 👉 Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> 👉 Create the Superuser

```bash
$ python manage.py createsuperuser
```

<br />

> 👉 Start the app

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

## Documentation

The documentation for the **Black Dashboard PRO Django** is hosted at our [website](https://app-generator.dev/docs/products/django/black-dashboard-pro/index.html).

<br />

## Codebase structure

The project is coded using a simple and intuitive structure presented below:

```bash
< PROJECT ROOT >
   |
   |-- config/                            
   |    |-- settings.py                  # Project Configuration  
   |    |-- urls.py                      # Project Routing
   |
   |-- apps/
   |    |-- charts                        
   |    |-- dyn_api                       
   |    |-- dyn_dt                         
   |    |-- pages                        
   |    |-- file_manager                        
   | 
   |     
   |-- requirements.txt                  # Project Dependencies
   |
   |-- env.sample                        # ENV Configuration (default values)
   |-- manage.py                         # Start the app - Django default start script
   |
   |-- ************************************************************************
```

<br />

## Deploy on [Render](https://render.com/)

- Create a Blueprint instance
  - Go to https://dashboard.render.com/blueprints this link.
- Click `New Blueprint Instance` button.
- Connect your `repo` which you want to deploy.
- Fill the `Service Group Name` and click on `Update Existing Resources` button.
- After that your deployment will start automatically.

At this point, the product should be LIVE.

<br />

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/chrome.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/firefox.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/edge.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/safari.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/opera.png" width="64" height="64">

<br />

## Resources

- Demo: <https://www.creative-tim.com/live/black-dashboard-pro-django>
- Download Page: <https://www.creative-tim.com/product/black-dashboard-pro-django>
- Documentation: <https://demos.creative-tim.com/black-dashboard-pro-django/docs/1.0/getting-started/getting-started-django.html>
- License Agreement: <https://www.creative-tim.com/license>
- Support: <https://www.creative-tim.com/contact-us>
- Issues: [Github Issues Page](https://github.com/creativetimofficial/ct-black-dashboard-pro-django/issues)

<br />

## Reporting Issues

We use GitHub Issues as the official bug tracker for the **Soft UI Dashboard Django**. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of the **Soft UI Dashboard Django**. Check the CHANGELOG from your dashboard on our [website](https://www.creative-tim.com/).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser-specific, so specifying in what browser you encountered the issue might help.

<br />

## Support

Being a product that is actively supported and improved, feel free to contact us using these funnels: 

- **Creative-Tim** [Discord](https://discord.gg/haJ7ErsNY3) Server - for general product assistance and UI/UX
- **App Generator** [Discord](https://discord.gg/fZC6hup) Server - for **Django specific questions** and assistance. 

<br />

## Licensing

- Copyright 2019 - present [Creative Tim](https://www.creative-tim.com/)
- Licensed under [Creative Tim EULA](https://www.creative-tim.com/license)

<br />

## Useful Links

- [More products](https://www.creative-tim.com/bootstrap-themes) from Creative Tim
- [Tutorials](https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w)
- [Freebies](https://www.creative-tim.com/bootstrap-themes/free) from Creative Tim
- [Affiliate Program](https://www.creative-tim.com/affiliates/new) (earn money)

<br />

## Social Media

- Twitter: <https://twitter.com/CreativeTim>
- Facebook: <https://www.facebook.com/CreativeTim>
- Dribbble: <https://dribbble.com/creativetim>
- Instagram: <https://www.instagram.com/CreativeTimOfficial>

<br />

---
[Black Dashboard PRO Django](https://www.creative-tim.com/product/black-dashboard-pro-django) - Provided by [Creative Tim](https://www.creative-tim.com/) and [App-Generator](https://app-generator.dev/).
