# Oportun interview questions

## Problem 1 - Reverse number

```txt
Input 1 - x = 123
Output - x = 321

Input 1 - x = -123
Output - x = -321

Input 1 - x = 120
Output - x = 21
```

## Problem 2 - Right rotation

```txt
Input - [2, 3, 4, 5, 6, 7], 
Index - 3
Output - [4, 5, 6, 7, 2, 3]
```

## Problem 3 - String concat 

```txt
Input - 45 + 35 + ‘111’
Output - ????  

Input - ‘111’ + 45 + 69
Output - ???? 
```

## Problem 4 - Hoisting

```js
var x = 24

(function() {
	var x = 43
  (function () {
    x++
    console.log(x) // Output - ???
    var x = 21
  })()
})()
```

## Problem - Object binding

```js
let x = {
  opertorName: 'hello'
  getOperatorName: function () {
    return this.operatorName
  }
}
console.log(x.getOperatoName()) // Output - ???
x.getOperatorName().apply(this, {
  operatorName: 'world'
})
console.log(x.getOperatoName())
```