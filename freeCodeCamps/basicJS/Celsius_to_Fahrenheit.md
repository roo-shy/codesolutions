# Celsius to Fahrenheit

## Before:

```
function convertToF(celsius) {
  var fahrenheit;
  // Only change code below this line
  
  
  // Only change code above this line
  return fahrenheit;
}

// Change the inputs below to test your code
convertToF(30);
```

## After:

```
function convertToF(celsius) {
  var fahrenheit = (celsius * (9/5) + 32);
  
  // Only change code below this line
  if(typeof fahrenheit !== 'undefined') {
    return fahrenheit;
  } else {
    return 'fahrenheit is not defined';
  }
}

// Change the inputs below to test your code
convertToF(30);
```