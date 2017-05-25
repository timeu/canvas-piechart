[![Build Status](https://travis-ci.org/timeu/canvas-piechart.svg?branch=1.x)](https://travis-ci.org/timeu/canvas-piechart) [![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/timeu/canvas-piechart)


# &lt;canvas-piechart&gt;

> A web-component to draw a piechart using Polymer and HTML5 Canvas.

**This branch (1.x) works only with Polymer 1.x. For a Polymer 2.x version check out the [master branch](https://github.com/timeu/canvas-piechart/tree/master)**


## Demo
> [Check it live](https://www.webcomponents.org/element/timeu/canvas-piechart).

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install --save canvas-piechart
```

Or [download as ZIP](https://github.com/timeu/canvas-piechart/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

  ```html
<script src="../webcomponentsjs/webcomponents-lite.js"></script>
  ```

2. Import Custom Element:

  ```html
<link rel="import" href="../canvas-piechart/canvas-piechart.html">
  ```

3. Start using it!

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="canvas-piechart.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
  <canvas-piechart size="250" data="[10,20,50,20]"></canvas-piechart>
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

Check [Release](https://github.com/timeu/canvas-piechart/releases) list.

## License

[MIT License](http://timeu.mit-license.org/) © Ümit Seren
