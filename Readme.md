# rework-beccapurple
  
  Converts beccapurple to hex value for more browser support.

## Installation

    $ npm install rework-beccapurple

## Example

```js
var hex = require('rework-beccapurple');

rework(css)
  .use(beccapurple)
  .toString();
```

## API

  In your CSS, use beccapurple as if they were already supported in all browsers:

```css
h2 {
  color: beccapurple;
}

div {
  background: url(test/image.png) beccapurple;
}
```

## Explanation

http://www.zeldman.com/2014/06/10/the-color-purple/ and http://meyerweb.com/eric/thoughts/2014/06/09/in-memoriam-2/

## License

  MIT

