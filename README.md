# Chat Simulation ![CI status](https://img.shields.io/badge/build-passing-brightgreen.svg)

This is just for practice please support us.

## Installation

### Requirements
* PHP >= 5.6.4
* OpenSSL PHP Extension
* PDO PHP Extension
* Mbstring PHP Extension
* Tokenizer PHP Extension
* XML PHP Extension

### Terminal

```
$ cp .env.example .env
```

```
$ php artisan key:generate
```

```
$ composer install
```

### Local Development Server

```
php artisan serve
```

## Configuration

### Public Directory
After installing Laravel, you should configure your web server's document / web root to be the  `public` directory. The `index.php` in this directory serves as the front controller for all HTTP requests entering your application.

### Configuration Files
All of the configuration files for the Laravel framework are stored in the `config` directory. Each option is documented, so feel free to look through the files and get familiar with the options available to you.

### Directory Permissions

After installing Laravel, you may need to configure some permissions. Directories within the  `storage` and the `bootstrap/cache` directories should be writable by your web server or Laravel will not run. If you are using the [Homestead](https://laravel.com/docs/5.4/homestead) virtual machine, these permissions should already be set.  