# Drink management system build with Laravel and React

An application to monitor drinks en stats while doing an evening of gamble using laravel and reactjs.

# Instructions

Clone the repository.
```bash
git clone https://github.com/<your-user-name>/drink-management-system-laravel-react.git
```

## backend

Create the .env:
```bash
cp .env.example .env
```

Create the database and fill in the credentials in the .env

Install the composer dependencies:
```bash
composer i
```

Generate an application key:
```bash
php artisan key:generate
```

```bash
php artisan migrate
```

## Frontend

Install NPM dependencies:
```bash
npm i
```

## Serving frontend and backend

For the backend run:
```bash
php artisan serve
```
or use Valet if you are on macOS

For the frontend run:
```bash
npm run watch
```
