Sprockets-sample
================

An example of how to embed sprockets in an arbitrary language/framework

## Requirements

Ruby 1.9.3 or later (probably; I doubt it works on much earlier)

## Installing / testing

After cloning this repo, you should be able to run:

```
gem install bundler
bundle install
bundle exec rackup path/to/config.ru -p 11111
```

In your browser, you should be able to navigate to `http://localhost:11111/assets/manifest.json` and see a JSON response describing the available assets.
