[![devDependency Status](https://david-dm.org/trykickoff/kickoff/dev-status.png)](https://david-dm.org/trykickoff/kickoff#info=devDependencies) [![Build Status](https://travis-ci.org/TryKickoff/kickoff.svg?branch=master)](https://travis-ci.org/trykickoff/kickoff) [![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)](http://gruntjs.com/)

![FabzOff](http://i61.tinypic.com/1zyitqe.png)
# FabzOff
## A lightweight front-end framework for creating scalable and performant, responsive sites

Based on te work of [Ashley Nolan](https://github.com/ashleynolan) & [Zander Martineau](https://github.com/mrmartineau)
Developed and maintained by [Fabian Andrade](https://github.com/fabzl) 


### Features
* Mobile-first, responsive philosophy
* Rock-solid **CSS** framework using **Sass** (`.scss`) preprocessor
 * Starter content styles: [typography](http://trykickoff.github.io/demos/typography.html), [grids](http://trykickoff.github.io/demos/grids.html) & [components](http://trykickoff.github.io/demos/components.html)
 * Starter form element styles ([see demo](http://trykickoff.github.io/demos/forms.html)): stacked on small-screen to 2-column (if you choose) at the breakpoint of your choice, validation states
 * Lots of helper classes & Sass mixins for many CSS3 features like [media-queries](https://github.com/TryKickoff/kickoff/blob/master/assets/src/scss/mixins/_responsive.scss)
* Simple **Javascript** boilerplate that makes very little assumptions about your chosen style or workflow.
 * The default method uses a [list of files](https://github.com/TryKickoff/kickoff/blob/master/_grunt-configs/config.js#L41-L55) that are concatinated & compressed with Uglify
 * Sass compilation using [libsass](https://github.com/sass/libsass) (using [grunt-sass](https://github.com/sindresorhus/grunt-sass)) and uses [autoprefixer](https://github.com/ai/autoprefixer) to dynamically add vendor prefixes so you don't even have to think about them :)
 * Concatenation and minification of JS files
 * Simple server using [BrowserSync](http://browsersync.io)
 * SVG Icon generation using [grunticon](https://github.com/filamentgroup/grunticon)

## Bugs and feature requests
Have a bug or a feature request? Please search for existing and closed issues. If your problem or idea is not addressed yet, [please open a new issue](https://github.com/trykickoff/kickoff/issues/new).

### Browser compatibility
Kickoff has been tested in the following browsers:
- Chrome
- Safari
- Firefox 3+

### Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

