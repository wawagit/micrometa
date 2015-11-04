Micrometa Parser
=========

(Symfony'ish fork of https://github.com/jkphl/micrometa)

Installation
------------

Install it with Composer:

```bash
{
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/wawagit/micrometa"
        }
    ],
    "require": {
        "jkphl/micrometa": "0.3.*@dev"
    }
}
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
