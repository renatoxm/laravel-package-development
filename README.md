# Laravel Pagkage Development Project

Simple Laravel 10 project you can use to develop your own packages

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
- [x] ⛵ Laravel Sail - A light-weight CLI for interacting with Docker
- [x] ☁️ Ngrock - used to create publicly accessible URL for development purposes

## Installation

```sh
composer install
npm i
npm run prepare
```

## Ngrock

Create a ngrok account or already have one, navigate to the Dashboard [here](https://dashboard.ngrok.com/get-started/your-authtoken), and copy the auth-token and add it your projects `.env` file as shown below:

```env
NGROK_AUTHTOKEN=abcabcabcabc12312312312313123123123123
```

**Once this is done you can open the NGROK url using below 3 ways:**

- Open the below URL in the browser: <http://localhost:4040/status> and use search for the URL.
- Curl this link `curl localhost:4040/api/tunnels` , use the link under "public_url"

```php
$ curl localhost:4040/api/tunnels
{"tunnels":[{"name":"command_line","ID":"17392213123123b81cce385753","uri":"/api/tunnels/command_line","public_url":"https://123-51-37-97-194.eu.ngrok.io","proto":"https","config":{"addr":"http://laravel.test:80","inspect":true},"metrics":{"conns":{"count":43,"gauge":0,"rate1":0.024543318563119754,"rate5":0.0713663027223514,"rate15":0.03781519558791336,"p50":168847294,"p90":817055932.8000002,"p95":2911789251.399993,"p99":10355445542},"http":{"count":43,"rate1":0.024543318563119754,"rate5":0.0713663027223514,"rate15":0.03781519558791336,"p50":163345378,"p90":720535289.4000003,"p95":2894676624.1999927,"p99":10327856752}}}],"uri":"/api/tunnels"}

```

- Or navigate to the Ngrok Dashboard [here](https://dashboard.ngrok.com/cloud-edge/endpoints) to view the site URL.

You can use Ngrok url as a URL to redirect your webhook calls. Ngrok is available in this app via Laravel Sail.

## Used commands to create this project

### Project creation

```sh
composer create-project laravel/laravel my-app --prefer-dist
php artisan sail:install
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for more information.
