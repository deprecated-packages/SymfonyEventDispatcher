# Symplify/SymfonyEventDispatcher

[![Build Status](https://img.shields.io/travis/Symplify/SymfonyEventDispatcher.svg?style=flat-square)](https://travis-ci.org/Symplify/SymfonyEventDispatcher)
[![Quality Score](https://img.shields.io/scrutinizer/g/Symplify/SymfonyEventDispatcher.svg?style=flat-square)](https://scrutinizer-ci.com/g/Symplify/SymfonyEventDispatcher)
[![Code Coverage](https://img.shields.io/scrutinizer/coverage/g/Symplify/SymfonyEventDispatcher.svg?style=flat-square)](https://scrutinizer-ci.com/g/Symplify/SymfonyEventDispatcher)
[![Downloads](https://img.shields.io/packagist/dt/symplify/symfony-event-dispatcher.svg?style=flat-square)](https://packagist.org/packages/symplify/symfony-event-dispatcher)
[![Latest stable](https://img.shields.io/packagist/v/symplify/symfony-event-dispatcher.svg?style=flat-square)](https://packagist.org/packages/symplify/symfony-event-dispatcher)


Integration of Symfony\EventDispatcher into Nette\DI.



## Install

```sh
$ composer require symplify/symfony-event-dispatcher
```

Register the extension in `config.neon`:

```yaml
extensions:
	- Symplify\SymfonyEventDispatcher\Adapter\Nette\DI\SymfonyEventDispatcherExtension
```


## Usage

See [fresh and short article about EventDispatcher](http://pehapkari.cz/blog/2016/12/05/symfony-event-dispatcher).



## Testing

```sh
vendor/bin/phpunit
composer check-cs
```
