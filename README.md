FPDF for use with Symfony2
==============================

Uses FPDF_TPL 1.2

Setup
-----

those to `vendor/composer/autoload_namespaces.php`:

```php

// autoload_namespaces.php generated by Composer

$vendorDir = dirname(__DIR__);
$baseDir = dirname($vendorDir);

return array(
    ...
    'Fpdftpl_' => $vendorDir . '/fpdf_tpl/lib',
    ...
    )
```

Now run `php bin/vendors update` or `php bin/vendors install`.

Usage
-----

```php
$pdf = new \Fpdftpl_Fpdftpl;
```


Sources
-------

1. [FPDF_TPL](http://www.setasign.de/products/pdf-php-solutions/fpdi/)