# Laravel Pint Config

## About

This package provides a [Laravel Pint](https://laravel.com/docs/pint) configuration for PHP projects which follow the [PSR-12 coding style](https://www.php-fig.org/psr/psr-12/) and coding style commonly seen in the official PHP documentation.

## Installation

Install the package using Composer:

```sh
composer require --dev laravel/pint jskrd/pint-config
```

## Usage

Either run Pint directly with the configuration file:

```sh
./vendor/bin/pint --config vendor/jskrd/pint-config/pint.json
```

Or add a `format` script to your `composer.json` file to run Pint with the configuration file:

```sh
composer config scripts.format 'pint --config vendor/jskrd/pint-config/pint.json' --file composer.json
```

And run the script:

```sh
composer format
```
