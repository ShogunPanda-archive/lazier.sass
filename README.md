# lazier.sass

A small set of tiny SASS files to avoid repetitive definitions.

https://sw.cowtech.it/lazier.sass

## Usage

The only requirement is the usage of [SASS](http://sass-lang.com/) and NPM.

~~~
npm install lazier.sass
~~~
 
You can then import file inside your stylesheets file and unleash your creativity.

Lazier.sass also includes [Normalize.css](https://necolas.github.io/normalize.css/), [Font Awesome](http://fontawesome.io/) and [Ribbon.css](https://sw.cowtech.it/ribbon.css).

Note the lazier.sass uses rem as the only unit, so it's advised to set the value explicitily:

~~~
html
  font-size: 10px // This is to set 1rem = 10px
~~~

## Examples

~~~sass
// ... other imports before ...
@import node_modules/lazier.sass/lazier/main
// ... other imports after ...

// ... other rules ...
~~~

~~~sass
// ... other imports before ...
@import node_modules/normalize.css/normalize
@import node_modules/lazier.sass/lazier/modules/_palette
@import node_modules/ribbon.css/_ribbon
// ... other imports after ...

// ... other rules ...
~~~

**That's it!** Pretty easy, isn't it?

## Browser compatibility

Tested to be working on the most recent (that is: latest two major versions) of all modern browsers.

## Contributing to lazier.sass

* Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet.
* Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it.
* Fork the project.
* Start a feature/bugfix branch.
* Commit and push until you are happy with your contribution.
* Make sure to add tests for it. This is important so I don't break it in a future version unintentionally.
* Please try not to mess with the Rakefile, version, or history. If you want to have your own version, or is otherwise necessary, that is fine, but please isolate to its own commit so I can cherry-pick around it.

## Copyright

Copyright (C) 2016 and above Shogun (shogun@cowtech.it).

Licensed under the MIT license, which can be found at http://www.opensource.org/licenses/mit-license.php.
