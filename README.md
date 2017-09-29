# Stock plugin for CakePHP

## Installation

You can install this plugin into your CakePHP application using [composer](http://getcomposer.org).

The recommended way to install composer packages is:

```
composer require caltj/stock-cake-call:dev-master
```
```
Update your config/bootstrap.php.
```
```
Plugin::load('Stock', ['bootstrap' => false, 'routes' => true]);
```
```
Run migrations
```
```
bin/cake migrations migrate --plugin Stock
```