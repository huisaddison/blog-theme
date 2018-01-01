# blog-theme
Simple theme for my [blog](http://huisaddison.com/blog) (powered by Pelican).

## Changes January 2018
* Revised entire theme to be way cleaner, and also mobile friendly-ish.
  Though, a lot of features that I don't use may be broken.

## Original changes
The theme is heavily derived fro
[pelican-simplegrey](https://github.com/fle/pelican-simplegrey).  The only
changes I have made are:
* Change greys to blues
* Tune the fonts to my preferences
* Update the footer in `base.html` to reflect the current year and my heavy
  reliance on [MathJax](https://www.mathjax.org/).
* Fix `article_link.inc.html` so that tags are delimited by commas (strange
  that this was an oversight in the original theme as the tags are delimited
  properly in `metadata.inc.html`.
* Tune the 'huisaddison/blog' header to link to my base website and the blog,
  respectively.
* Insert the current year in the footer dynamically using datetime.
* Grab jinja vars (?) for home site url, blog source, etc. from pelicanconf.

