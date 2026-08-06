# phpnitro/jwt

Décodage de JWT (header/payload), sans vérification de signature.

Fait partie de [PhpNitro](https://github.com/phpnitro/phpnitro) — un framework PHP qui compile vers de vraies apps Android natives (moteur de rendu Canvas, pas de WebView).

## Installation

```bash
composer require phpnitro/jwt
```

## Usage

```php
use Engine\Jwt\JwtDecoder;

JwtDecoder::payload($token);
```

## Licence

MIT
