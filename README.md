Author: [Jason San Jose](http://github.com/jasonsanjose), Adobe

Example project using [Compass](http://compass-style.org) 3.2.3 to be compatible with [libsass](https://github.com/sass/libsass) 3 and the [brackets-sass](https://github.com/jasonsanjose/brackets-sass) extension.

Notes
----

* Requires Ruby and Compass to be [installed](http://compass-style.org/install/)

Initial Repository Setup
----

1. Use `compass create compass-example` to create a boilerplate project
2. Install Bower `npm install -g bower`. Bower requires Bower requires [Node and npm](http://nodejs.org) and [Git](http://git-scm.org/).
3. Install open-iconic in `compass-example` for spritesheet example used in sass/screen.scss
4. Create a `.brackets.json` file (see [example](./.brackets.json) in this project)
    * Add `sass.compiler: ruby` and `sass.compass: true`
    * Note that the standard brackets-sass options are not supported, but `config.rb` is used instead
5. Change `config.rb` to pull images from open-iconic `images_dir = "bower_components/open-iconic"`