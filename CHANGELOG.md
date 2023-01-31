# Change Log

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
