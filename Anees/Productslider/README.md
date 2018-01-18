Magento 2 Product Slider


This is a Magento2 extension using various functions like:

* Show Latest Product

Installation
====

This package is registered on [Packagist](https://packagist.org/packages/genmato/sample) for easy installation. In your Magento installation root run:

`composer require anees/productslider`

This will install the latest version in your Magento installation, when completed run:

```
php bin/magento module:enable Anees_Productslider

php bin/magento setup:upgrade

php bin/magento cache:clean
```

This will enable the extension and run the Schema and Data scripts to create the database and insert a sample record.

(C)2018 Anees Ahmad, aneesahmadweb.com.