# HTML Builder Plugin

## Installation

Run the following command in your project to get the latest version of the plugin:

`composer require yajra/laravel-datatables-html:^1.0`

Open the file ```config/app.php``` and then add following service provider.

```php
'providers' => [
    // ...
    Yajra\Datatables\DatatablesServiceProvider::class,
    Yajra\Datatables\HtmlServiceProvider::class,
],
```

After completing the step above, use the following command to publish configuration & assets:

```
php artisan vendor:publish --tag=datatables-html
```
