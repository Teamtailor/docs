# Changelog

## Version 1.3.4

_April 18, 2018_

**Features:**

* Add the 8 user notification settings attributes to the user object.
* Add TeamMembership object to enable index, view, create and destroy actions on hiring team members.

## Version 1.3.3

_June 11, 2016_

Documentation and example changes.

## Version 1.3.2

_February 3, 2016_

A small bugfix for slightly incorrect background colors on code samples in some cases.

## Version 1.3.1

_January 31, 2016_

A small bugfix for incorrect whitespace in code blocks.

## Version 1.3

_January 27, 2016_

We've upgraded Middleman and a number of other dependencies, which should fix quite a few bugs.

Instead of `rake build` and `rake deploy`, you should now run `bundle exec middleman build --clean` to build your server, and `./deploy.sh` to deploy it to Github Pages.

## Version 1.2

_June 20, 2015_

**Fixes:**

* Remove crash on invalid languages
* Update Tocify to scroll to the highlighted header in the Table of Contents
* Fix variable leak and update search algorithms
* Update Python examples to be valid Python
* Update gems
* More misc. bugfixes of Javascript errors
* Add Dockerfile
* Remove unused gems
* Optimize images, fonts, and generated asset files
* Add chinese font support
* Remove RedCarpet header ID patch
* Update language tabs to not disturb existing query strings

## Version 1.1

_July 27, 2014_

**Fixes:**

* Finally, a fix for the redcarpet upgrade bug

## Version 1.0

_July 2, 2014_

[View Issues](https://github.com/tripit/slate/issues?milestone=1&state=closed)

**Features:**

* Responsive designs for phones and tablets
* Started tagging versions

**Fixes:**

* Fixed 'unrecognized expression' error
* Fixed #undefined hash bug
* Fixed bug where the current language tab would be unselected
* Fixed bug where tocify wouldn't highlight the current section while searching
* Fixed bug where ids of header tags would have special characters that caused problems
* Updated layout so that pages with disabled search wouldn't load search.js
* Cleaned up Javascript
