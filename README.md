# Turborepo starter

This is an official pnpm starter turborepo.

## What's inside?

This turborepo uses [pnpm](https://pnpm.io) as a package manager. It includes the following packages/apps:

### Apps and Packages

- `server`: a Laravel app, which comes with:
  - `Laravel 9`, `PHP 8.1`, and `MySQL`.
  - User system with authentication.
  - Code generation using [laravel-generator](https://github.com/infyomlabs/laravel-generator).
  - Admin panel using [laravel-ui-adminlte](https://github.com/infyomlabs/laravel-ui-adminlte).
  - The following packages:
    - [bepsvpt/secure-headers](https://github.com/bepsvpt/secure-headers).
    - [spatie/laravel-permission](https://github.com/spatie/laravel-permission).
    - [guzzlehttp/guzzle](https://github.com/guzzlehttp/guzzle).
    - [rinvex/laravel-subscriptions](https://github.com/rinvex/laravel-subscriptions).
    - [propaganistas/laravel-phone](https://github.com/propaganistas/laravel-phone).
    - [cybercog/laravel-ban](https://github.com/cybercog/laravel-ban).
    - [codebyray/laravel-review-rateable](https://github.com/codebyray/laravel-review-rateable).
- `app`: a `Vue 3` and `Quasar` app, which comes with:
  - Communication layer with [@tanstack/vue-query](https://github.com/Tanstack/query).
  - I18n with [vue-i18n](https://github.com/kazupon/vue-i18n).
  - Login, register, and logout functionality and views.
  - Data-driven layouts.
  - The following packages:
    - [@vueuse/core](https://github.com/vueuse/vueuse).
- `eslint-config-custom`: `eslint` configurations (includes `eslint-config-next` and `eslint-config-prettier`)

### Utilities

This turborepo has some additional tools already setup:

- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Prettier](https://prettier.io) for code formatting


### To start
