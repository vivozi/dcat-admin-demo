# Dcat Admin

This project is the DEMO source code of [Dcat Admin](https://github.com/jqhph/dcat-admin), for online preview [click here](https://jqhph.github.io/dcat-admin/demo.html).

## Install

Run
```shell
composer install
```

After installation, make a copy of the `.env.example` file and name it `.env`, then run
```shell
php artisan key:generate
```

Then configure the database connection information and run the following command

> Here you will be prompted that the folder already exists, just ignore it.

```php
php artisan admin:install
```

Finally run `php artisan serve`. Then open `http://localhost:8000/admin` to access it with account `admin` and password `admin`.



