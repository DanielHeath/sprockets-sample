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
bundle exec rake server
```

In your browser, you should be able to navigate to `http://localhost:11111/assets/manifest.json` and see a JSON response describing the available assets.

## What does all this stuff do?

The `Gemfile` and `Gemfile.lock` specify which ruby libraries are needed.

The `Rakefile` provides command-line scripts to build assets or run the asset server.

The `assets` directory contains stylesheets/javascripts to be compiled.

The `public` directory (if present) contains compiled assets.

The `sprockets` directory contains the integration code for the sprockets library
