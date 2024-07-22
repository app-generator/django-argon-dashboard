# [Django Argon Dashboard](https://appseed.us/product/argon-dashboard/django/)

Open-source **[Django Dashboard](https://appseed.us/admin-dashboards/django/)** project crafted on top of **Argon Dashboard**, an open-source `Bootstrap 5` design from Creative-Tim.
The product is designed to deliver the best possible user experience with highly customizable feature-rich pages. `Material Material` has easy and intuitive responsive design whether it is viewed on retina screens or laptops.

- 👉 [Django Argon Dashboard](https://appseed.us/product/argon-dashboard/django/) - `Product page`
- 👉 [Django Argon Dashboard](https://django-argon-dash2.onrender.com) - `LIVE Demo`

<br />

## Features

> `Have questions?` Contact **[Support](https://appseed.us/support/)** (Email & Discord) provided by **AppSeed**

| Free Version                          | [PRO Version](https://appseed.us/product/argon-dashboard2-pro/django/)    | [Custom Development](https://appseed.us/custom-development/) |  
| --------------------------------------| --------------------------------------| --------------------------------------|
| ✓ **Django 4.2.9**                    | **Everything in Free**, plus:                                                                  | **Everything in PRO**, plus:         |
| ✓ Best Practices                      | ✅ **Premium Bootstrap 5 Design**                                                              | ✅ **1 Week** `Custom Development`  | 
| ✓ Bootstrap 5, `Material` Design      | ✅ `OAuth` GitHub                                                                              | ✅ **Team**: PM, Developer, Tester  |
| ✓ `CI/CD` Flow via Render             | ✅ `API`, **[Charts](https://django-argon-dash2-pro.onrender.com/charts/)**                    | ✅ Weekly Sprints                   |
| ✓ `Docker`                            | ✅ **[DataTables](https://django-argon-dash2-pro.onrender.com/tables/)** (Filters, Export)     | ✅ Technical SPECS                  |
| ✓ `Free Support` (GitHub Issues)      |✅ **Celery**                                                                                   | ✅ Documentation                    |
| -                                     | ✅ **Media Files Manager**                                                                     | ✅ **30 days Delivery Warranty**    |
| -                                     | ✅ **Extended User Profiles**                                                                  | ✅ [CI/CD for AWS, DO](https://appseed.us/terms/#section-ci-cd) **(Extra)**    |
| -                                     | ✅ `Private REPO Access`                                                                       |  -                                   |
| -                                     | ✅ **[Premium Support](https://appseed.us/support/)**                                          |  -                                   |
| ------------------------------------  | ------------------------------------                                                           | ------------------------------------|
| ✓ [LIVE Demo](https://django-argon-dash2.onrender.com)  | 🚀 [LIVE Demo](https://django-argon-dash2-pro.onrender.com/)  | **[Get in Touch ➡️](https://appseed.us/custom-development/)** |   

![Argon Dashboard 2 - Free Starter.](https://user-images.githubusercontent.com/51070104/215804889-94eba681-8262-41a3-8e57-7d5b12dcc209.png)

<br />

## Manual Build 

> 👉 Download the code  

```bash
$ git clone https://github.com/app-generator/django-argon-dashboard.git
$ cd django-argon-dashboard
```

<br />

> 👉 Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip install -r requirements.txt
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

## Codebase structure

The project is coded using a simple and intuitive structure presented below:

```bash
< PROJECT ROOT >
   |
   |-- core/                            
   |    |-- settings.py                  # Project Configuration  
   |    |-- urls.py                      # Project Routing
   |
   |-- home/
   |    |-- views.py                     # APP Views 
   |    |-- urls.py                      # APP Routing
   |    |-- models.py                    # APP Models 
   |    |-- tests.py                     # Tests  
   |    |-- templates/                   # Theme Customisation 
   |         |-- includes                # 
   |              |-- custom-footer.py   # Custom Footer      
   |     
   |-- requirements.txt                  # Project Dependencies
   |
   |-- env.sample                        # ENV Configuration (default values)
   |-- manage.py                         # Start the app - Django default start script
   |
   |-- ************************************************************************
```

<br />

## How to Customize 

When a template file is loaded in the controller, `Django` scans all template directories starting from the ones defined by the user, and returns the first match or an error in case the template is not found. 
The theme used to style this starter provides the following files: 

```bash
# This exists in ENV: LIB/admin_argon
< UI_LIBRARY_ROOT >                      
   |
   |-- templates/                     # Root Templates Folder 
   |    |          
   |    |-- accounts/       
   |    |    |-- sign-in.html         # Sign IN Page
   |    |    |-- sign-up.html         # Sign UP Page
   |    |
   |    |-- includes/       
   |    |    |-- footer.html          # Footer component
   |    |    |-- sidebar.html         # Sidebar component
   |    |    |-- navigation.html      # Navigation Bar
   |    |    |-- scripts.html         # Scripts Component
   |    |
   |    |-- layouts/       
   |    |    |-- base.html            # Masterpage
   |    |    |-- base-fullscreen.html # Masterpage for Auth Pages
   |    |
   |    |-- pages/       
   |         |-- dashboard.html       # Dashboard page
   |         |-- profile.html         # Settings  Page
   |         |-- *.html               # All other pages
   |    
   |-- ************************************************************************
```

When the project requires customization, we need to copy the original file that needs an update (from the virtual environment) and place it in the template folder using the same path. 

> For instance, if we want to **customize the footer.html** these are the steps:

- ✅ `Step 1`: create the `templates` DIRECTORY inside the `home` app
- ✅ `Step 2`: configure the project to use this new template directory
  - `core/settings.py` TEMPLATES section
- ✅ `Step 3`: copy the `footer.html` from the original location (inside your ENV) and save it to the `home/templates` DIR
  - Source PATH: `<YOUR_ENV>/LIB/admin_argon/includes/footer.html`
  - Destination PATH: `<PROJECT_ROOT>home/templates/includes/footer.html`

> To speed up all these steps, the **codebase is already configured** (`Steps 1, and 2`) and a `custom footer` can be found at this location:

`home/templates/includes/custom_footer.html` 

By default, this file is unused because the `theme` expects `footer.html` (without the `custom-` prefix). 

In order to use it, simply rename it to `footer.html`. Like this, the default version shipped in the library is ignored by Django. 

In a similar way, all other files and components can be customized easily.

<br />

## Recompile SCSS  

The SCSS/CSS files used to style the Ui are saved in the `static/assets` directory. 
In order to update the Ui colors (primary, secondary) this procedure needs to be followed. 

```bash
$ yarn # install modules
$ # # edit variables 
$ vi static/assets/scss/argon-dashboard/custom/_variables.scss 
$ gulp # SCSS to CSS translation
```

The `_variables.scss` content defines the `primary` and `secondary` colors: 

```scss
$primary:       #5e72e4 !default; // EDIT for customization
$secondary:     #8392ab !default; // EDIT for customization
$info:          #11cdef !default; // EDIT for customization
$success:       #2dce89 !default; // EDIT for customization
$warning:       #fb6340 !default; // EDIT for customization
$danger:        #f5365c !default; // EDIT for customization
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

## [PRO Version](https://appseed.us/product/argon-dashboard2-pro/django/)   

This design is a pixel-perfect [Bootstrap 5](https://www.admin-dashboards.com/bootstrap-5-templates/) Dashboard with a fresh, new design inspired by Google's Material Design. `Argon Dashboard 2 PRO` is built with over 300 frontend individual elements, like buttons, inputs, navbars, nav tabs, cards, or alerts, giving you the freedom of choosing and combining.

> Features: 

- ✅ `Up-to-date Dependencies`
- ✅ `Design`: Django Theme Argon 2 - `PRO Version`
- ✅ `Sections` covered by the design:
  - ✅ **Admin section** (reserved for superusers)
  - ✅ **Authentication**: `Django.contrib.AUTH`, Registration
  - ✅ **All Pages** available in for ordinary users 
- ✅ `Docker`
- 🚀 `Deployment` 
  - `CI/CD` flow via `Render`

<br />

![Argon Dashboard 2 PRO - Automotive (Premium Bootstrap 5 Design).](https://user-images.githubusercontent.com/51070104/211158013-fea76b79-bb54-4066-a617-5ec3b4b6ec42.jpg)

<br />

---
[Django Argon Dashboard](https://appseed.us/product/argon-dashboard/django/) - Minimal **Django** core provided by **[AppSeed](https://appseed.us/)**
