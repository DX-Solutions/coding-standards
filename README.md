# DX-Solutions PHP Coding Standard

## Install in your project

### Add the repository in your composer.json

```json
    "repositories": [
        {
            "type": "vcs",
            "url": "git@gitlab.com:dx-solutions/internal/coding-standard.git"
        }
    ],
```

### Install with Composer

```
$ composer require dx/coding-standard
```

### Update your configs

grumphp.yml:

```yaml
phpcs:
    standard: "DX"
```
