simplez
=======

The pelican theme used on [betatim.github.io](http://betatim.github.io).
Aim is to keep things simple. Uses Bootstrap 3. The bootstrap
source is included as lots of things have been modified.

Currently it is extremely specific to my needs, but feel free to fork it!


Installation
============

Bootstrap uses `grunt` to compile all the `css` and `js`. If you
do not already have `grunt` follow the instructions below to get it.
Otherwise you are good to go:

1. `git clone https://github.com/betatim/simplez.git`
2. `cd simplez/bootstrap`
3. Install dependencies with `npm install`
4. Compile everything with `grunt dist`
5. Point the `THEME` variable in your `pelicanconf.py` to `/path/to/simplez`


Install Grunt
-------------

From the command line:

1. Install `grunt-cli` globally with `npm install -g grunt-cli`.
2. Continue with step 1. above.

When completed, you'll be able to run the various Grunt commands provided from the command line.

**Unfamiliar with npm? Don't have node installed?** That's a-okay. npm stands for [node packaged modules](http://npmjs.org/) and is a way to manage development dependencies through node.js. [Download and install node.js](http://nodejs.org/download/) before proceeding.
