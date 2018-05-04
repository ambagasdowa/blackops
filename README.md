# CakePHP Application Skeleton

[![Build Status](https://img.shields.io/travis/cakephp/app/master.svg?style=flat-square)](https://travis-ci.org/cakephp/app)
[![Total Downloads](https://img.shields.io/packagist/dt/cakephp/app.svg?style=flat-square)](https://packagist.org/packages/cakephp/app)

The framework source code can be found here: [cakephp/cakephp](https://github.com/cakephp/cakephp).
# Development


## Installation

```bash
git clone https://github.com/ambagasdowa/blackops.git
```
then
composer install

run
```bash
git submodule update --init
```

```php
composer update
```

and after [optional]

```php
composer suggests | xargs -i composer require {}
```


* Build a schema for users table

```bash
bin/cake migrations migrate -p CakeDC/Users
```


* Create a superuser

```bash
bin/cake users addSuperuser
```
