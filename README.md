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

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element and iscroll:

    ```html
    <link rel="import" href="bower_components/x-iscroll/dist/x-iscroll.html">
    ```

3. Start using it!

    ```html
    <x-iscroll></x-iscroll>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`zoom`        | *boolean*   | `false`      | Enables pinch to zoom.
`scrollY`     | *boolean*   | `true`       | Enables scroll on Y axis.
`scrollX`     | *boolean*   | `false`      | Enables scroll on X axis.
`freeScroll`  | *boolean*   | `false`      | Enables free panning when scroll on both axis is enabled.


## License
&lt;x-iscroll&gt; is released under the [MIT License](http://opensource.org/licenses/MIT).


## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style.

## Release history
- 1.0.0
  - Initial release

## Thanks

Special thanks to [Matteo Spinelli](http://cubiq.org/) ([@cubiq](https://twitter.com/cubiq)) for his awesome work. :D
