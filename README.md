# Laravel Pagkage Development Project

Simple Laravel 10 project used to develop my packages

## Stack

![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

## Features

- [x] 📏 ESLint — To find and fix problems in your code
- [x] 💖 Prettier — Code Formatter for consistent style
- [x] 🐶 Husky — For running scripts before committing
- [x] 🚓 Commitlint — To make sure your commit messages follow the convention
- [x] 🚫 lint-staged — Run ESLint and Prettier against staged Git files
- [x] ⌨️ .vscode settings - Auto formating options
- [x] 🗲 Pretty-quick - Runs prettier on git changed files
- [x] 🍺 Laravel Pint - An opinionated PHP code style fixer for minimalists
- [x] 😸 Github CI/CD workflow - Enforcing code formatting on pull requests
- [x] 🤓 Laravel IDE Helper - Generates helper files that enable your IDE to provide accurate autocompletion
- [x] 📦 Laravel Packager - A cli tool for creating Laravel packages

## Installation

```sh
composer install
npm i
npm run prepare
```

## Usefull commands

### Project creation

```sh
composer create-project laravel/laravel my-app --prefer-dist
```

### Install Sail

```sh
php artisan sail:install
```

### Install Laravel Packager

```sh
composer require jeroen-g/laravel-packager --dev
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for more information.
