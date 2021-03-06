โ๏ธ ToDo
======================

![todo](https://aleksandertabor.pl/wp-content/uploads/2020/05/livewire-todo.gif)

# ๐ฉ Table of Contents

1. [Requirements](#-requirements)
2. [Installation](#-installation)
3. [Built with](#-built-with)
4. [To-do](#-to-do)

## ๐ Requirements

- PHP version: >= 7.2.5
- Composer
- Node.js

## ๐งพ Installation

1. `git clone https://github.com/souravtah/livewire-todo.git YOURPROJECTNAME`
2. `cd YOURPROJECTNAME`
3. Install dependencies:

    `composer install`

    `npm install`

4. `cp .env.example .env`
5. `php artisan key:generate`
6. Set your `.env` with credentials to your database server (`DB_*` settings) and your domain config (`APP_URL`).
8. `php artisan migrate`
11. Build frontend with `npm run production` for production.
11. Run your server `php artisan serve`.

> โ ๏ธ Caution: Remember about giving proper permissions to the project directory e.g.:
```bash
sudo chgrp -R www-data /var/www/YOURPROJECTNAME
sudo chmod -R 775 /var/www/YOURPROJECTNAME/storage
```

## ๐งฐ Built with

- Laravel 7
- Livewire
- Tailwind CSS
- Heroicons UI

## ๐ To-do

- More tests [Livewire tests](https://laravel-livewire.com/docs/testing)
