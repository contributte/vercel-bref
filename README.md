![](https://heatbadger.now.sh/github/readme/contributte/vercel-bref/?deprecated=1)

<p align=center>
    <a href="https://bit.ly/ctteg"><img src="https://badgen.net/badge/support/gitter/cyan"></a>
    <a href="https://bit.ly/cttfo"><img src="https://badgen.net/badge/support/forum/yellow"></a>
    <a href="https://contributte.org/partners.html"><img src="https://badgen.net/badge/sponsor/donations/F96854"></a>
</p>

<p align=center>
    Website 🚀 <a href="https://contributte.org">contributte.org</a> | Contact 👨🏻‍💻 <a href="https://f3l1x.io">f3l1x.io</a> | Twitter 🐦 <a href="https://twitter.com/contributte">@contributte</a>
</p>

## Disclaimer

| :warning: | This project is no longer being maintained. Please use [vercel-php](https://www.npmjs.com/package/vercel-php).|
|---|---|

| NPM | [`vercel-bref`](https://www.npmjs.com/package/vercel-bref) |
|---| --- |
| Version | ![](https://badgen.net/npm/v/vercel-bref) |
| Downloads | ![](https://badgen.net/npm/dt/vercel-bref) |
| License | ![](https://badgen.net/github/license/contributte/vercel-bref) |

## Usage

1. Setup index.php

```php
phpinfo();
```

2. Setup composer.json

```json
{
    "require": {
        "bref/bref": "^1.0.0"
    }
}
```

3. Setup vercel.json

```json
{
  "version": 2,
  "builds": [
    { "src": "index.php", "use": "vercel-bref" }
  ]
}
```

4. Deploy with `vercel`

## Development

This package was maintained by these authors.

<a href="https://github.com/f3l1x">
  <img width="80" height="80" src="https://avatars2.githubusercontent.com/u/538058?v=3&s=80">
</a>

-----

Consider to [support](https://contributte.org/partners.html) **contributte** development team.
Also thank you for using this package.
