# Laravel-React SPA

Starter Boilerplate SPA made with Laravel and React.

## Features

- Laravel 5.6, React, Redux, React Router
- Authentication with JWT
- Login, register, reset password
- Socialite integration (Google Account Sign in)
- Flexible Page Layout
- Flexible, Protected Routing
- Tailwind CSS
- ESlint

## Installation

- Clone the repo
- Copy .env.example to .env
- Generate app key

```bash
php artisan key:generate
```

- Create an Application in the Google API Console, Add google client id to the env file.

```env
GOOGLE_CLIENT_ID=
```

- Installing all Composer & NPM dependencies.

```bash
composer install && npm install
 ```

- Compiling Assets

```bash
npm run dev
```

- Boot up a server

```bash
php artisan serve
```
