# A Dockerized Microservice Application environment

## I. App Container
* PHP 8.1.17
* Symfony 6.1.1
* Symfony Components
    * Databases and the Doctrine ORM
        * symfony/orm-pack
        * symfony/maker-bundle (dev)
    * HTTP Client
        * symfony/http-client
    * The Serializer Component
        * symfony/serializer
    * The UID Component
        * symfony/uid
    * The Lock Component
        * symfony/lock
* PHPStan
    * [PHPStan document URL](https://phpstan.org/user-guide/getting-started)
    * Run composer script inside of app container: `bin/composer run phpstan`
* PHP_CodeSniffer
    * [Configuration Options](https://github.com/squizlabs/PHP_CodeSniffer/wiki/Configuration-Options)
    * Run composer script inside of app container: `bin/composer run php-cs`

## II. DB Container
* MySQL 8.0.29

# Initialized URL
If the app container publish port change, then change the url port accordingly.
* Symfony welcome page: http://localhost:8888
* PHP Info page: http://localhost:8888/phpinfo.php
