### Mangosta

**Bullet-proof front-end architecture for fast development**

## Install
You also need to have [Ruby](http://www.ruby-lang.org/en/downloads/) and [Sass](http://sass-lang.com/download.html) installed. If you're on OS X or Linux you probably already have Ruby; test with ruby -v in your terminal. When you've confirmed you have Ruby, run gem install sass to install Sass.

## Features

#Html

**Jade**
[Jade](http://jade-lang.com/) is a terse language for writing HTML templates.
- Produces HTML
- Supports dynamic code
- Supports reusability (DRY)

**HTML Hint**
[HTMLHint](https://github.com/yaniswang/HTMLHint) is a Static Code Analysis Tool for HTML, you can use it with IDE or in build system.
Hinting rules are set in .htmlhintrc file and all options explained [here](https://github.com/yaniswang/HTMLHint/wiki/Rules)

#CSS
**Sass**
[Sass](http://sass-lang.com/) is the most mature, stable, and powerful professional grade CSS extension language in the world.

**SCSS Linter**
[Scss-lint](https://github.com/juanfran/gulp-scss-lint) is a tool to help keep your SCSS files clean and readable. You can run it manually from the command-line, or integrate it into your SCM hooks. It uses rules established by the team at Causes.com.
Hinting rules are set in scsslint.yml and all options explained [in the scss-lint documentation](https://github.com/causes/scss-lint/blob/master/lib/scss_lint/linter/README.md)

**CSS linter**
[CSSLint](https://github.com/lazd/gulp-csslint) is a tool to help point out problems with your CSS code. It does basic syntax checking as well as applying a set of rules to the code that look for problematic patterns or signs of inefficiency.
You can find information about both using CSS Lint and contributing to the project in the [wiki](https://github.com/CSSLint/csslint/wiki)

#Javascript
**CoffeeScript**
[CoffeeScript](http://coffeescript.org/) is a little language that compiles into JavaScript. Underneath that awkward Java-esque patina, JavaScript has always had a gorgeous heart. CoffeeScript is an attempt to expose the good parts of JavaScript in a simple way.

**CoffeeScript Linter**
[CoffeeLint](https://github.com/janraasch/gulp-coffeelint) is a style checker that helps keep CoffeeScript code clean and consistent. CoffeeScript does a great job at insulating programmers from many of JavaScript's bad parts, but it won't help enforce a consistent style across a code base. CoffeeLint can help with that.
By default, CoffeeLint will help ensure you are writing idiomatic CoffeeScript, but every rule is optional and configurable so it can be tuned to fit your preferred coding style. You can find information about both using CoffeeLint [here](http://www.coffeelint.org/#usage)

#Optimization
**Image Minification**
[Imagemin](https://github.com/sindresorhus/gulp-imagemin) Minify images seamlessly with Node.js. Yo ucan find documentation on how to use imagemin [here](https://github.com/kevva/imagemin)

**Size**
[File Size](https://github.com/sindresorhus/gulp-size) keeps track of the size of your files. *Will you detect a [CSS critical path](http://addyosmani.com/blog/tag/critical-path-css/)?*

*Note that HTML and CSS minification and concatenation are included in their respectives gulp plugins*

#Development performance
**Server connect**
Streaming gulp plugin to run a [local webserver](https://www.npmjs.org/package/gulp-webserver)

**Watch**
[Watch files](https://github.com/gulpjs/gulp/blob/master/docs/API.md#gulpwatchglob--opts-cb) and do something when a file changes. This always returns an EventEmitter that emits change events.

**Server Reload**
[Web Server Reload](https://www.npmjs.org/package/gulp-webserver) your browser when something happens in your files.
