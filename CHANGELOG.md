# Change Log

## [1.0.7] 2023-06-14
### Changes

- Codebase Improvements
- Deployment-ready for Render (CI/CD)
  - `render.yaml`
  - `build.sh`
- `DB Management` Improvement
  - `Silent fallback` to **SQLite**

## [1.0.6] 2022-04-01
### Changes

- **Patch ImportError**: [cannot import name 'safe_str_cmp' from 'werkzeug.security'](https://docs.appseed.us/content/how-to-fix/importerror-cannot-import-name-safe_str_cmp-from-werkzeug.security)
  - `Werkzeug` deprecation of `safe_str_cmp` starting with version `2.1.0`
    - https://github.com/pallets/werkzeug/issues/2359

- 2021-11-10 - `v1.0.6-rc1`
  - ImportError: cannot import name 'TextField' from 'wtforms'
    - Problem caused by `WTForms-3.0.0`
    - Fix: use **WTForms==2.3.3**

## [1.0.5] 2021-11-01
### Improvements

- Bump UI: Material Dashboard - v2.2.2
- Bump Codebase: [Flask Dashboard](https://github.com/app-generator/boilerplate-code-flask-dashboard) v2.0.0
  - Dependencies update (all packages) 
    - Flask==2.0.1 (latest stable version)
  - Better Code formatting
  - Improved Files organization
  - Optimize imports
  - Docker Scripts Update
  - Gulp Tooling  (SASS Compilation)

## [1.0.4] 2021-10-18
### Tooling

- Added SCSS compilation scripts (via Gulp)

## [1.0.3] 2021-05-16
### Dependencies Update

- Bump Codebase: [Flask Dashboard](https://github.com/app-generator/boilerplate-code-flask-dashboard) v1.0.6
- Freeze used versions in `requirements.txt`
    - jinja2 = 2.11.3

## [1.0.2] 2021-03-18
### Improvements

- Bump Codebase: [Flask Dashboard](https://github.com/app-generator/boilerplate-code-flask-dashboard) v1.0.5
- Freeze used versions in `requirements.txt`
    - flask_sqlalchemy = 2.4.4
    - sqlalchemy = 1.3.23

## [1.0.1] 2021-02-17
### Improvements

- UI: [Jinja Material PRO](https://github.com/app-generator/jinja-material-dashboard-pro) v1.0.2
- Codebase: [Flask Dashboard](https://github.com/app-generator/boilerplate-code-flask-dashboard) v1.0.4

## [1.0.0] 2020-02-07
### Initial Release
