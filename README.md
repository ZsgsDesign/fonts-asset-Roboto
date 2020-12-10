# fonts-asset-Roboto
Roboto for composer.

## Install

```bash
composer require oomphinc/composer-installers-extender
composer require fonts-asset/roboto
```

And in `composer.json`:

```json
    "extra": {
        "installer-types": [
            "fonts-asset"
        ],
        "installer-paths": {
            "public/fonts/{$name}": [
                "type:fonts-asset"
            ]
        }
    },
```

## Usage

```html
<link rel="stylesheet" href="/fonts/roboto/roboto.css">
```

## Credit

[Google Fonts](https://fonts.google.com/)