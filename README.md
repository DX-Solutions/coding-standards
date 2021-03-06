# DX-Solutions PHP Coding Standard

## Install in your project

### Add the repository in your composer.json

```json
    "repositories": [
        {
            "type": "vcs",
            "url": "git@github.com:DX-Solutions/coding-standards.git"
        }
    ],
```

### Install with Composer

```
$ composer require --dev "dx/coding-standard:dev-master"
```

### Update your configs

grumphp.yml:

```yaml
phpcs:
    standard: "DX"
```

## Usage

### All errors & warnings

```
$ php vendor/bin/phpcs --standard=DX <path to source files>
```

### Only errors

```
$ php vendor/bin/phpcs --standard=DX <path to source files> -n
```

### Show offending sniffs

```
$ php vendor/bin/phpcs --standard=DX <path to source files> -s
```

### Fix errors/warnings via CBF

```
$ php vendor/bin/phpcbf --standard=DX <path to source files>
```
