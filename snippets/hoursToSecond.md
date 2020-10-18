---
title: howManySeconds
tags: JavaScript, math,numbers,beginner

---
Function that converts hours into seconds.

- Use Multiplication (*) JavaScript Arithmetic Operators that perform arithmetic on numbers.
- Use Number.isInteger(value) to return Boolean value indicating whether or not the given value is an integer.
- If the number is integer, Return the real value. If not, Return an "error" message.


```js
const howManySeconds = hours => Number.isInteger(hours) ? hours*60*60 : "error";
```

```js
howManySeconds(2) //7200
howManySeconds(10) //36000
```
