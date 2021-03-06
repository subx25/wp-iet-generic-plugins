[![Build status: Travis-CI][travis-icon]][travis-ci]
[![js-semistandard-style][semi-icon]][semi]

# IET-OU / wp-iet-generic-plugins

A collection of generic WordPress plugins, including:

* ` [tagcloud] ` shortcode
* ` [wp_query] ` shortcode
* Simple Embed
* Simple Menu
* IET attribution
* IET custom style
* _... And others!_

## Install .. test

```sh
composer install && composer npm-install
composer test
```

Work-in-progress:

```sh
composer cs && composer semi
composer fix
```

## [Usage and how-to guide](docs/USAGE.md)

---

Compatible with WordPress 4.1 (onwards)

This project is [Composer][]-enabled. See [Using Composer with WordPress][].

Developed for the [JuxtaLearn][] and [LACE][] projects. Used in:

* [@IET-OU/oer-evidence-hub-org][]
* LACE Evidence Hub, http://evidence.laceproject.eu
* Tricky Topics Guide, http://tricky-topics-guide.ac.uk


---
License: [GNU GPL 2 onwards][gpl]

© 2014-2017 The Open University. ([Institute of Educational Technology][])


[gpl]: https://gnu.org/licenses/gpl-2.0.html "GPL-2.0+"
[Using Composer with WordPress]: https://roots.io/using-composer-with-wordpress/
[Composer]: https://getcomposer.org/
[@IET-OU/oer-evidence-hub-org]: https://github.com/IET-OU/oer-evidence-hub-org
[JuxtaLearn]: http://juxtalearn.eu/
[LACE]: http://www.laceproject.eu/ "Learning Analytics Community Exchange"
[Institute of Educational Technology]: http://iet.open.ac.uk/
[github]: https://github.com/IET-OU/wp-iet-generic-plugins
[bitbucket]: https://bitbucket.org/nfreear/wp-iet-generic-plugins
[travis-ci]: https://travis-ci.org/IET-OU/wp-iet-generic-plugins "Build status – Travis-CI"
[travis-icon]: https://travis-ci.org/IET-OU/wp-iet-generic-plugins.svg
[semi]: https://github.com/Flet/semistandard
[semi-icon]: https://img.shields.io/badge/code_style-semistandard-brightgreen.svg?style_x=flat-square
  "Javascript coding style — 'semistandard'"

[End]: //
