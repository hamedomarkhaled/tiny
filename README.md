# @omar_eldamrawy/tiny


![npm (scoped)](https://img.shields.io/npm/v/@omar_eldamrawy/tiny)
![npm bundle size (minified)](https://img.shields.io/badge/-minified%20size-black)


Removes all spaces from string.


# Install

```
    npm install @omar_eldamrawy/tiny
```

# Usage
```
const tiny = require("@omar_eldamrawy/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1

```