underscores-sass
================

[underscores.me](http://underscores.me) is a great base for wordpress themes, unfortunately it only provides the styles in `.scss` flavor. It also lacks of a config.rb to start using compass right away. This repo aims to fix those issues.

## Install

* Go to [underscores.me](http://underscores.me/)
* Generate and download your theme (without sass)
* `unzip yourtheme.zip && cd yourtheme/`
* `git clone https://github.com/tonekk/underscores-sass sass`


### Install as submodule

If your theme is already a git repo itself, you can also [use this as a submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules):

`git submodule add https://github.com/tonekk/underscores-sass sass`


## Usage

To have your themes `style.css` updated, do as follows:

* Open terminal
* `cd yourtheme/sass`
* `compass watch`

## Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/tonekk/underscores-sass/issues/new).
