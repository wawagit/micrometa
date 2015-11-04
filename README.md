Micrometa Parser
=========

(Symfony'ish fork of https://github.com/jkphl/micrometa)

Installation
------------

Install it with Composer:

```bash
composer require jkphl/micrometa
```

Add this to your autoload.php:

```bash
$loader->add('Jkphl', __DIR__.'/../vendor/jkphl/micrometa/src');
```

Usage
-----

```php
$micrometaParser = new \Jkphl\Micrometa($uri);
$micrometaObjectData    = $micrometaParser->toObject();
```
