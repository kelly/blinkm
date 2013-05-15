# BlinkM

control your BlinkM LED with node.js

# Install

````bash
$ npm install blinkm
````

# Example

```javascript

var BlinkM = require('blinkm');
var address = 0x05;

var pixel = new BlinkM(address, '/dev/i2c-1');

pixel.setRGB(255,0,0); // red
pixel.off();
````
