# Change Log

## [1.0.21] 2025-04-01
### Changes

- Update RM (minor)

## [1.0.20] 2024-12-16
### Changes

- Preselect the design in the Generator:
  - [Django App Generator - Argon Design](https://app-generator.dev/tools/django-generator/argon/)

## [1.0.19] 2024-12-15
### Changes

> Mention [Django App Generator](https://app-generator.dev/tools/django-generator/) Service:

- Access the [App Generator](https://app-generator.dev/tools/django-generator/) page
- Select the preferred design
- (Optional) Design Database: edit models and fields
- (Optional) Edit the fields for the extended user model
- (Optional) Enable OAuth for GitHub
- (Optional) Add Celery (async tasks)
- (Optional) Enable Dynamic API Module
- Docker Scripts
- Render CI/Cd Scripts

**The generated Django project is available as a ZIP Archive and also uploaded to GitHub.**

## [1.0.18] 2024-12-05
### Changes

- Bump UI Version
- Update Media (minor)

## [1.0.17] 2024-12-04
### Changes

- Bump UI Version

## [1.0.16] 2024-11-24
### Changes

- Update RM Links
- 👉 [Django Argon Dashboard](https://app-generator.dev/docs/products/django/argon-dashboard/index.html) - **Complete Documentation**
- 👉 [Django Argon Dashboard PRO](https://app-generator.dev/product/argon-dashboard-pro/django/) - The premium version

## [1.0.15] 2024-05-18
### Changes

- Updated DOCS (readme)
  - [Custom Development](https://appseed.us/custom-development/) Section
  - [CI/CD Assistance for AWS, DO](https://appseed.us/terms/#section-ci-cd)

## [1.0.14] 2024-03-31
### Changes

- Added Local Statics 
- Added Gulp for SCSS Compilation 

## [1.0.13] 2024-03-05
### Changes

- Update [Custom Development](https://appseed.us/custom-development/) Section
  - New Pricing: `$3,999`

## [1.0.12] 2024-03-04
### Changes

- Deprecate `distutils`
  - use `str2bool`
- Update Deps 
  - `requirements.txt`  
- Update README: [PRO Version](https://appseed.us/product/argon-dashboard2-pro/django/), List features
  - `API`, **Charts** 
  - **DataTables** (Filters, Export)
  - **Celery**
  - **Media Files Manager**
  - **Extended User Profiles**

## [1.0.11] 2024-01-07
### Changes

- Update LOCAL Template:
  - added Dashboard Page

## [1.0.10] 2024-01-04
### Changes

- Update Settings:
  - local static
  - local templates

## [1.0.9] 2023-10-24
### Changes

- Update Dependencies 
- Update README 

## [1.0.8] 2023-01-31
### Changes

- Bump UI: [Django Admin Argon](https://github.com/app-generator/django-admin-argon-dashboard) `v1.0.15`
- DOCS Update (readme). New sections:
  - `How to customize the theme`
  - Render deployment
- Configure the project to use `home/templates`
- Added `custom_footer` sample

## [1.0.7] 2023-01-10
### Changes

- Bump Theme Version
  - [Django Admin Argon](https://github.com/app-generator/django-admin-argon-dashboard) `v1.0.13`

## [1.0.6] 2023-01-07
### Changes

- Move to theme-based pattern
  - [Django Admin Argon](https://github.com/app-generator/django-admin-argon-dashboard)
- 🚀 `Deployment` 
  - `CI/CD` flow via `Render`

## [1.0.5] 2022-08-09
### Improvements

- Bump UI Version
  - [Argon Dashboard](https://www.creative-tim.com/product/argon-dashboard?AFFILIATE=128200) v2.0.4

## [1.0.4] 2022-06-09
### Improvements

- Built with [Argon Dashboard Generator](https://appseed.us/generator/argon-dashboard/)
  - Timestamp: `2022-06-09 17:45`

## [1.0.3] 2022-01-16
### Improvements

- Bump Django Codebase to [v2stable.0.1](https://github.com/app-generator/boilerplate-code-django-dashboard/releases)
- Dependencies update (all packages) 
  - Django==4.0.1
- Settings update for Django 4.x
  - `New Parameter`: CSRF_TRUSTED_ORIGINS
    - [Origin header checking isn`t performed in older versions](https://docs.djangoproject.com/en/4.0/ref/settings/#csrf-trusted-origins)  

## [1.0.2] 2021-09-20
### Improvements

- Bump Django Codebase to [v2.0.4](https://github.com/app-generator/boilerplate-code-django-dashboard/releases)
- Dependencies update (all packages)
  - Use Django==3.2.6 (latest stable version)
- Better Code formatting
- Improved Files organization
- Optimize imports
- Docker Scripts Update 
- Tooling:
  - Gulp SASS compilation script   
  - `Update README` - Recompile SCSS (new section)
- Fixes: 
  - Patch 500 Error when authenticated users access `admin` path (no slash at the end)
  - Patch [#16](https://github.com/app-generator/boilerplate-code-django-dashboard/issues/16): Minor issue in Docker 

## [1.0.1] 2021-01-15
### Improvements 

- Bump UI: [Jinja Template Argon](https://github.com/app-generator/jinja-argon-dashboard) v1.0.1
- Bump Codebase: [Django Dashboard](https://github.com/app-generator/boilerplate-code-django-dashboard) v1.0.4

## [1.0.0] 2020-02-07
### Initial Release
