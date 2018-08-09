This is the professional webpage for Kathe Todd-Brown, PhD.

To render this website on a local host 

> bundle update

> bundle exec jekyll server

Then point a browser window to localhost:4000

Most of the formating is in the _includes

# Notes for changing things

In header.html it will look through the root directory with a layout:page in the yaml

Style information is in the _sass directory, mostly in the _custom.scss which is the last style file that gets read in.

Space seperater between parent child, class are '.' example a <p> inside of <div class="post-content"> would be ".post-content p"