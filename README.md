# Forms plugin for TheatreCMS

Form builder, submissions and notifications for TheatreCMS.

## Installing

TheatreCMS plugins are folders in the core install's `plugins/` directory:

```sh
git clone git@github.com:TheatreCMS/forms-plugin.git plugins/forms-plugin
bin/composer-local            # inside DDEV: ddev exec bin/composer-local
```

See `documentation/plugins.md` in [TheatreCMS](https://github.com/TheatreCMS/theatrecms) for how plugins are discovered, installed and loaded.

## Developing

```sh
composer install       # installs TheatreCMS core from GitHub as a dependency
vendor/bin/phpunit
vendor/bin/phpstan analyse -c phpstan.neon.dist
vendor/bin/phpcs
```
