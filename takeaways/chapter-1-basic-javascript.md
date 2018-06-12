# Chapter 1 - Basic JavaScript

## Statements Versus Expressions

> The distinction between statements and expressions is best illustrated by the fact that JavaScript has two different ways to do `if-then-else—either` as a statement:

```javascript
var x;
if (y >= 0) {
  x = y;
} else {
  x = -y;
}
```

> or as an expression:

```javascript
var x = y >= 0 ? y : -y;
```

> You can use the latter as a function argument (but not the former):

```javascript
myFunction(y >= 0 ? y : -y);
```
