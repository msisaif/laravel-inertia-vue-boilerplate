# laravel-inertia-vue-boilerplate

This is boilerplate with

-   [Laravel 10.x](https://laravel.com/docs/10.x)
-   [Inertia](https://inertiajs.com/)
-   [Vue 3](https://vuejs.org/)
-   [Laravel Sanctum](https://laravel.com/docs/10.x/sanctum)
-   [Laravel Breeze](https://laravel.com/docs/10.x/starter-kits#laravel-breeze)
-   [Tailwind CSS](https://tailwindcss.com/)

## Installation

Clone the repository

```sh
git clone https://github.com/msisaif/laravel-inertia-vue-boilerplate.git
```

Change the directory

```sh
cd laravel-inertia-vue-boilerplate
```

Install all the dependencies using composer

```sh
composer update
```

Copy `.env.example` to `.env`

```sh
cp .env.example .env
```

Update the database name and credentials in `.env` file

    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=laravel
    DB_USERNAME=root
    DB_PASSWORD=

Run the database migrations

```sh
php artisan migrate
```

Run the database seeders

```sh
php artisan db:seed
```

Generate application key

```sh
php artisan key:generate
```

Link your public storage folder

```sh
php artisan storage:link
```

Install the javascript dependencies using npm

```sh
npm install
```

Compile and Hot-Reload for Development

```sh
npm run dev
```

Compile and Minify for Production

```sh
npm run build
```

Start the local development server

```sh
php artisan serve
```

You can now access the server at [http://localhost:8000](http://localhost:8000)

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
