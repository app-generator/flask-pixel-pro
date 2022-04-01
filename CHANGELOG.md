# Change Log

## [1.0.5] 2022-04-01
### Fixes

- **Patch ImportError**: [cannot import name 'safe_str_cmp' from 'werkzeug.security'](https://docs.appseed.us/content/how-to-fix/importerror-cannot-import-name-safe_str_cmp-from-werkzeug.security)
  - `Werkzeug` deprecation of `safe_str_cmp` starting with version `2.1.0`
    - https://github.com/pallets/werkzeug/issues/2359

## [1.0.4] 2021-09-16
### Improvements & Fixes

- Bump Flask Codebase to [v1.0.7](https://github.com/app-generator/boilerplate-code-flask/releases)
  - Dependencies update (all packages)
    - Use Flask==2.0.1 (latest stable version)
  - Better Code formatting
  - Improved Files organization
  - Optimize imports
  - Docker Scripts Update 
  - Rename model `User` to `Users` to avoid name conflict with ORACLE DBMS

## [1.0.3] 2021-07-01

- Bump UI: Pixel Pro Bootstrap 5 - v5.4.0
- Added scripts to recompile SCSS
    - `app/static/assets`: Gulp toolchain

## [1.0.2] 2021-06-04
### Improvements

- Codebase: [Flask Boilerplate](https://github.com/app-generator/boilerplate-code-flask/releases) - v1.0.5
- Freeze used versions in `requirements.txt`
    - jinja2 = 2.11.3
    - flask_sqlalchemy = 2.4.4
    - sqlalchemy = 1.3.23

## [1.0.1] 2021-01-23
### Improvements

- UI: [Jinja Pixel PRO](https://github.com/app-generator/jinja-pixel-pro/releases) v1.0.1 
- Pixel Pro Bootstrap 5 - v5.2.0
- Codebase: [Flask Boilerplate](https://github.com/app-generator/boilerplate-code-flask/releases) - v1.0.3

## [1.0.0] 2020-02-07
### Initial Release
