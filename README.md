# JavaScript For Noobs

```javascript
/**
 * Print Triangle with specific string
 * @param {number} maxLimit - Number of iterations
 */

/**
 * Solution 1
 */
function triangleLoop(maxLimit) {
  var stringChar = "#";
  for(var count = 1; count < maxLimit; count ++ ) {
    console.log(stringChar.repeat(count)+"\n");
  }
}


/**
 * Solution 2
 */
function triangleLoop(maxLimit) {
 for(var line = '#'; line.length < maxLimit; line += "#" ) {
    console.log(line);
  }
}
```
