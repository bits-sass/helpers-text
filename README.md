# Bits.sass helpers: text

Collection of text-related functions and mixins. See [other helpers](https://github.com/bits-sass/helpers).

Read more about [Bits.sass toolkit](https://github.com/bits-sass/bits.sass).

## Installation

* __Bower:__ `bower install --save bits-sass-helpers-text`
* __Download:__ [zip](https://github.com/bits-sass/helpers-text/zipball/master), [tar.gz](https://github.com/bits-sass/helpers-text/tarball/master)
* __Git:__ `git clone https://github.com/bits-sass/helpers-text.git`

## Available SASS variables

* `bits-use-rem` - whether to use rem-based font-size, defaults to false
* `bits-base-font-size` - defaults to 14px
* `bits-base-line-height` - defaults to 20px

## Available functions

* `relative-line-height` - returns unitless multiple of 'line-height' based on 'font-size'
* `absolute-line-height` - returns multiple of 'line-height' based on 'font-size' in length value (px, em, ...)

## Available mixins

* `font-size` - sets font size while ensuring proper vertical rhythm using single value

## Requirements

* Sass 3.2+

## Browser support

* Google Chrome (latest)
* Opera (latest)
* Firefox 4+
* Safari 5+
* Internet Explorer 8+