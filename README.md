# Octicons jekyll tag

[![Gem version](https://img.shields.io/gem/v/jekyll-octicons.svg)](https://rubygems.org/gems/jekyll-octicons)
[![Build Status](https://travis-ci.org/primer/jekyll-octicons.svg?branch=master)](https://travis-ci.org/primer/jekyll-octicons)

> A liquid jekyll tag that injects Octicon svg into the page

This jekyll liquid tag, is a plugin that will let you easily include svg [octicons][octicons] in your jekyll sites.

## Install

1. Add this to your `Gemfile`

    ```rb
    gem 'jekyll-octicons'
    ```

2. Add this to your jekyll `_config.yml`

    ```yml
    gems:
      - jekyll-octicons
    ```

3. Use this tag in your jekyll templates

    ```
    {% octicon alert size:large class:"right left" aria-label:hi %}
    ```

The minimum CSS you'll need in your jekyll site is in the [octicons][octicons] repository. You can also npm install that package and include `build/octicons.css` in your styles.

## Documentation

For a full list of options available, see the [octicons_gem documentation](https://github.com/primer/octicons_gem#documentation)

## License

_Code License:_ [MIT](./LICENSE) &copy; [GitHub](https://github.com/)

_Font License:_ [SIL OFL 1.1](./LICENSE) &copy; [GitHub](https://github.com/)

[octicons]: https://github.com/primer/octicons
[octicons-docs]: https://octicons.github.com/
