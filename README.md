Lumen Helpers
==========
![php-badge](https://img.shields.io/packagist/php-v/albertcht/lumen-helpers.svg)
[![packagist-badge](https://img.shields.io/packagist/v/albertcht/lumen-helpers.svg)](https://packagist.org/packages/albertcht/lumen-helpers)
[![Total Downloads](https://poser.pugx.org/albertcht/lumen-helpers/downloads)](https://packagist.org/packages/albertcht/lumen-helpers)


## Description

It can be used for improving implementation compatibility, assuming that you are planning to migrate from Lumen to Laravel in the future.

> Session is not included in this package.

## Installation

If composer is used, it can be introduced by adding the following description.

```
composer require --dev albertcht/lumen-helpers
```

## How to use

This package currently provides the following helper functions.

- **abort_if**
- **abort_unless**
- **action**
- **app_path**
- **asset**
- **auth**
- **back**
- **bcrypt**
- **cache**
- **cookie**
    It will return `Symfony\Component\HttpFoundation\Cookie` directly.
- **logger**
- **method_field**
- **mix**
- **policy**
- **public_path**
- **report**
- **validator**
- **app_with**:
    An app () compatible helper corresponding to makeWith call.
    illuminate/container: From 5.4, you can not pass $parameters to make, instead makeWith prepared,
    By using app_with, make can be done by passing parameters that ask Lumen, illuminate / container version.
