# openutd-site

Website for <https://open.utdallas.edu>

## Building

This website is built using [Jekyll](https://jekyllrb.com/).

### Prerequisites

Run `gem install bundler` to install the [Bundler](https://bundler.io/) gem.
Run `bundle install` to install the dependencies listed in `Gemfile`.

To add a new set of slides, create the file in the `slides` directory and point the `theme-override` to a file in the `slides/css` file. Then run `bundle exec jekyll build`.
