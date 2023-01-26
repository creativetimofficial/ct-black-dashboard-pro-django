# [Black Dashboard PRO Django](https://www.creative-tim.com/product/black-dashboard-pro-django) [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social&logo=twitter)](https://twitter.com/home?status=Material%20Dashboard,%20a%20free%20Material%20Bootstrap%204%20Admin%20Template%20%E2%9D%A4%EF%B8%8F%20https%3A//bit.ly/2Lyat1Y%20%23bootstrap%20%23material%20%23design%20%23developers%20%23freebie%20%20via%20%40CreativeTim)

 ![version](https://img.shields.io/badge/version-1.0.0-blue.svg) [![GitHub issues open](https://img.shields.io/github/issues/creativetimofficial/ct-black-dashboard-pro-django.svg?maxAge=2592000)](https://github.com/creativetimofficial/ct-black-dashboard-pro-django/issues?q=is%3Aopen+is%3Aissue) [![GitHub issues closed](https://img.shields.io/github/issues-closed-raw/creativetimofficial/ct-black-dashboard-pro-django.svg?maxAge=2592000)](https://github.com/creativetimofficial/ct-black-dashboard-pro-django/issues?q=is%3Aissue+is%3Aclosed) [![Join the chat at https://gitter.im/NIT-dgp/General](https://badges.gitter.im/NIT-dgp/General.svg)](https://gitter.im/creative-tim-general/Lobby) [![Chat](https://img.shields.io/badge/chat-on%20discord-7289da.svg)](https://discord.gg/E4aHAQy)

**Django Template** crafted on top of **[Black Dashboard PRO](https://www.creative-tim.com/product/black-dashboard-pro-django)**, a premium Bootstrap 4 design. Start your development with a modern, dark-themed Bootstrap 4 Admin template for **Django**. It features a huge number of components built to fit together and look fantastic. If you want to code faster, with a smooth workflow, then you should try this template carefully developed with **Django**, a well-known `Python Framework`. 

> **NOTE**: This product `requires a License` in order to access the theme. During the purchase, a `GitHub Access TOKEN` is provided. 

<br />

## Features: 

- ✅ `Up-to-date Dependencies`
- ✅ `Design`: [Django Theme Black](https://github.com/app-generator/django-admin-black-pro) - `PRO Version`
- ✅ `Sections` covered by the design:
  - ✅ **Admin section** (reserved for superusers)
  - ✅ **Authentication**: `Django.contrib.AUTH`, Registration
  - ✅ **All Pages** available in for ordinary users 
- ✅ `Docker`
- 🚀 `Deployment` 
  - `CI/CD` flow via `Render`

<br />

![Django Black Dashboard PRO - Premium Starter crafted by AppSeed and Creative-Tim.](https://user-images.githubusercontent.com/51070104/214872728-230a9955-d391-4900-b352-d68960dbd2c4.png)

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

> To authenticate use the default credentials ***test / PaSS_123*** or create a new user on the **registration page**.

- **Black Dashboard PRO Django** [Login Page](https://www.creative-tim.com/live/black-dashboard-pro-django)

<br />

## Quick start

> UNZIP the sources or clone this repository. After getting the code, open a terminal and navigate to the working directory, with product source code.

<br />

> Export `GITHUB_TOKEN` in the environment. The value is provided during purchase. 

This is required because the project has a private REPO dependency: `github.com/app-generator/priv-django-admin-black-pro`

```bash
$ export GITHUB_TOKEN='TOKEN_HERE'  # for Linux, Mac
$ set GITHUB_TOKEN='TOKEN_HERE'     # Windows CMD
$ $env:GITHUB_TOKEN = 'TOKEN_HERE'  # Windows powerShell 
```

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

The documentation for the **Black Dashboard PRO Django** is hosted at our [website](https://demos.creative-tim.com/black-dashboard-pro-django/docs/1.0/getting-started/getting-started-django.html).

<br />

## File Structure

Within the download you'll find the following directories and files:

```bash
< PROJECT ROOT >
   |
   |-- core/                   # Implements app configuration
   |    |-- settings.py        # Defines Global Settings
   |    |-- wsgi.py            # Start the app in production
   |    |-- urls.py            # Define URLs served by all apps/nodes
   |
   |-- home/
   |    |
   |    |-- views.py           # Serve HTML pages for authenticated users
   |    |-- urls.py            # Define some super simple routes  
   |
   |
   |-- manage.py               # Start the app - Django default start script
   |-- requirements.txt        # Development modules - SQLite storage
   |
   |-- ************************************************************************
```

<br />

> The bootstrap flow

- Django bootstrapper `manage.py` uses `core/settings.py` as the main configuration file
- `core/settings.py` loads the app magic from `.env` file
- Redirect the guest users to Login page
- Unlock the pages served by *app* node for authenticated users

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

We use GitHub Issues as the official bug tracker for the **Black Dashboard PRO Django**. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of the **Black Dashboard PRO Django**. Check the CHANGELOG from your dashboard on our [website](https://www.creative-tim.com/).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser-specific, so specifying in what browser you encountered the issue might help.

<br />

## Technical Support or Questions

If you have questions or need help integrating the product please [contact us](https://www.creative-tim.com/contact-us) instead of opening an issue.

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
[Black Dashboard PRO Django](https://www.creative-tim.com/product/black-dashboard-pro-django) - Provided by [Creative Tim](https://www.creative-tim.com/) and [AppSeed](https://appseed.us).
