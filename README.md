This is the professional webpage for Kathe Todd-Brown, PhD.

To render this website on a local host

> bundle update

If this runs very slow then you need to check that the `gem 'github-pages'` is up to date (https://rubygems.org/gems/github-pages), delete the Gemfile.lock, and then run `bundle install`

> bundle exec jekyll server

Then point a browser window to localhost:4000


# Notes for changing things

Moving over to Hugo is a bad idea without a web developer or a lot of time to learn it.
Spent about a day in Aug 2024 trying to move over and it was a mess.
Custom template did not port over with default inputs.

Most of the formatting is in the _includes

In header.html it will look through the root directory with a layout:page in the yaml

Style information is in the _sass directory, mostly in the _custom.scss which is the last style file that gets read in.

Space seperater between parent child, class are '.' example a <p> inside of <div class="post-content"> would be ".post-content p"
