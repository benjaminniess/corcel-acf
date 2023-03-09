# Corcel ACF Plugin

**This is a fork of https://github.com/corcel/acf**

# Changelog

### V5.0.0

- Fix composer version compatibility
- Allow to parse SVG without metadata


# Version Compatibility

 Corcel    | Laravel | PHP
:----------|:--------|:----------
 `^6.0`    | 10.x    | `>=8.1`

# Installation

To install the ACF plugin for Corcel is easy:

In composer.json
```
"repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/benjaminniess/corcel.git"
        },
        {
            "type": "vcs",
            "url": "https://github.com/benjaminniess/corcel-acf.git"
        }
    ],
```
Then
```
composer require benjaminniess/corcel-acf
```
