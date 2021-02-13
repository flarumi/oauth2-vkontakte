# Vkontakte OAuth2 client provider

This package provides [Vkontakte](https://vk.com) integration for [OAuth2 Client](https://github.com/thephpleague/oauth2-client) by the League.

## Installation

```sh
composer require flarumi/oauth2-vkontakte
```

## Usage

```php
$provider = new J4k\OAuth2\Client\Provider\Vkontakte([
    'clientId' => '1234567',
    'clientSecret' => 's0meRe4lLySEcRetC0De',
    'redirectUri' => 'https://example.org/oauth-endpoint',
]);
```
