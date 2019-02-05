# StoryStrong blog project

This repo contains both the CSS and blog content for the HCPSS StoryStrong project.

## Updating Gems

Project uses [Bundler](https://bundler.io/) to manage Ruby dependencies. Run `bundle update` every once and a while to ensure that any gem security patches are applied.

## Making changes

### With Livereload

Run `bundle exec guard` after installing the Livereload browser extension. This will automatically update the dev site each time a change is made. 

### Without Livereload

Run `bundle exec jekyll serve --watch`
