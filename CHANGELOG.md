# Change Log

## [1.0.6] 2023-06-16
### Changes

- Update Settings
  - Fix `$ python manage.py collectstatic`
  - Added `STATICFILES_DIRS` 

## [1.0.5] 2023-01-29
### Changes

- DOCS Update (readme). New sections:
  - `How to customize the theme`
  - Render deployment
- Configure the project to use `home/templates`
- Added `custom_footer` sample

## [1.0.4] 2023-01-26
### Changes

- Updated Codebase
- Latest **[Django](https://appseed.us/admin-dashboards/django/)** Version
- Theme-able UI (no more hardcoded inside the project)
- Integrate [Django Theme Black](https://github.com/app-generator/django-admin-black-pro) - `PRO Version`
  - Usable via `PIP`
- CI/CD included via `Render`

## [1.0.3] 2021-09-17
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

## [1.0.2] 2021-06-17
### Improvements

- Added style to highlight errors (registration page)
    - `core/templates/accounts/register.html`

## [1.0.1] 2021-04-13
### Improvements

- UI: [Jinja Black PRO](https://github.com/app-generator/jinja-black-dashboard-pro) v1.0.2
- Codebase: [Django Dashboard](https://github.com/app-generator/boilerplate-code-django-dashboard) v1.0.4

## [1.0.0] 2020-07-22
### Initial Release

- UI Kit version - v1.1.1
- [Codebase](https://github.com/app-generator/boilerplate-code-django-dashboard) version - v1.0.2
