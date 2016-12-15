# yii2-phpdotenv
Package to automatically include .env via `vlucas/phpdotenv` in your yii2 application.

# installation
1. `composer require brixms/yii2-phpdotenv`
2. edit `index.php` or your `yii` entry points to include `Dotenv` (after autoload has been required):

`(new \Dotenv\Dotenv("your full .env file location"))->overload();`  
