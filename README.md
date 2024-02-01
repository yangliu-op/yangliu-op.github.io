A Github Pages template for academic websites. One can fork the original template from [this repository](https://github.com/academicpages/academicpages.github.io), which was forked (then detached) by [Stuart Geiger](https://github.com/staeiou) from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), which is © 2016 Michael Rose and released under the MIT License. See LICENSE.md.

## To run locally

1. Clone the repository
1. Make sure ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `gem install bundler`
1. Run `bundle update`
1. Run `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `bundle exec jekyll serve -l` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.
