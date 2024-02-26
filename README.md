## Overview

The `@keshav-0907/is-mobile.js` function is a utility designed to determine whether the current environment is considered mobile based on the window width. It returns a boolean value indicating whether the width of the window is less than a specified breakpoint or if it is less than 480 pixels.


## Installation 

To install the isMobile function, you can use npm:

```
npm install @keshav-0907/is-mobile.js
```

## Example 

```javascript
// Import the function
import isMobile from '@keshav-0907/is-mobile.js';

// Set your desired breakpoint (e.g., 768 pixels)
const breakpoint = 768;

// Check if the current environment is mobile
const result = isMobile(breakpoint);

console.log(result); // Output: true or false
```
