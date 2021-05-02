# simplez

The pelican theme used on [betatim.github.io](http://betatim.github.io).
Aim is to keep things simple.

Currently it is extremely specific to my needs, but feel free to fork it!


## Install

Run `yarn` to get bootstrap, install `sass` (via their webpage),
then run `sass --watch scss/custom.scss:static/simplez.css` to generate
the custom CSS.


## Templates

All the Pelican specific stuff is in `templates/`. The `static/` folder should
contain the built CSS as well as the Pygments style sheet for code highlighting.
