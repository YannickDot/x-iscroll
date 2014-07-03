# &lt;x-iscroll&gt;

&lt;x-iscroll&gt; is a web component built using Polymer.js which provides smooth scrolling utilities at 60fps using the [iScrolljs](http://iscrolljs.com/) library.

## Demo

> [Check it live](http://yannickdot.github.io/labs/x-iscroll).


## Install

Install with [Bower](http://bower.io):

```sh
$ bower install --save x-iscroll
```
## Usage

Include platform.js, polymer.html and iscroll.html :

```html
<script src="lib/platform.js"></script>

<link rel="import" href="lib/polymer.html">
<link rel="import" href="lib/iscroll.html">
```

Import Custom Element:

```html
<link rel="import" href="x-iscroll.html">
```

Use it like a classic DOM:

```html
<x-iscroll zoom scrollX scrollY freeScroll>
    <img src="picture.jpg">
</x-iscroll> 
```

## Configuration options

For the moment the only availible options are :

- zoom (default : 'false')
- scrollY (default : 'true')
- scrollX (default : 'false')
- freeScroll (default : 'false')


## License
&lt;x-iscroll&gt; is released under the [MIT License](http://opensource.org/licenses/MIT).


## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style.

## Release history
- 1.0.0
  - Initial release

## Thanks

Special thanks to [Matteo Spinelli](http://cubiq.org/) ([@cubiq](https://twitter.com/cubiq)) for his awesome work. :D
