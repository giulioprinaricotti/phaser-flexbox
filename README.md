# phaser-flexbox

Forked from [liangdas/phaser-flexbox](https://github.com/liangdas/phaser-flexbox)

Phaser-flexbox uses facebook's open source yoga as a flexbox library


### Getting started with flexbox

[flexbox tutorial](http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html)

### Yoga links

[getting-started](https://facebook.github.io/yoga/docs/getting-started/)

[flexbox setup function](https://github.com/facebook/yoga/blob/master/javascript/sources/Node.hh)

[flexbox-style enumeration](https://github.com/facebook/yoga/blob/master/javascript/sources/YGEnums.js)

### File Description

> Since yoga only supports es6 by default, incompatibility will occur on some browsers. Visual UC Browser does not support this.

> So I compiled an es5 version

### es5 version

Use [yoga.bundle.js](https://github.com/giulioprinaricotti/phaser-flexbox/blob/master/lib/yoga.bundle.js)

    <script src="/static/js/lib/yoga.bundle.js"></script>

Yoga is loaded into the environment

    var yoga = window.yoga;

### phaser-yoga tools

Since yoga needs to set every element and it is relatively complicated to operate, I wrote a class to automate this step.

    Lib/yoga-layout.js

### Example

see [DialogState.js](https://github.com/giulioprinaricotti/phaser-flexbox/blob/master/DialogState.js)

### Library size

    The yoga library is compiled from the asm.js using the C++ version. The body size is about 700k. When used can be compressed by gzip
    120k after gzip compression

![phaser-flexbox](https://github.com/liangdas/phaser-flexbox/blob/master/demo.png)

### Optimization

    At present, this library is not very complete. There are some features that can be optimized. For example, if you use the js feature to set flexbox more conveniently.
    Complete the settings with the approach to the native configuration of the CSS. Hope that interested students can continue to optimize.
