Symfony Application
========================

Agent promo

Requirements
------------

  * PHP 5.5 or higher;
  * PDO-SQLite PHP extension enabled;
  * and the [usual Symfony application requirements](http://symfony.com/doc/current/reference/requirements.html).
  * composer
  * npm

Installation
------------
```
$ git clone
$ composer install
$ npm install
$ bower install
$ gulp
```


Test
-----
```
sudo chown www-data:www-data -R app/cache
sudo chown www-data:www-data -R app/logs
```
```bash
$ php app/console server:run
```
localhost:8000
