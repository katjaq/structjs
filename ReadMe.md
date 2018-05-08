# struct.js
Roberto Toro, April 2017

`struct` (<https://www.npmjs.com/package/struct>) is an npm package that wraps binary data structures in javascript. `struct` works server-side – `struct.js` uses Browserify to make it available for use in the web browser.

To compile `struct.js` you need to have `browserify` installed, and do:

```
cd structjs
browserify main.js -o struct.js
```
