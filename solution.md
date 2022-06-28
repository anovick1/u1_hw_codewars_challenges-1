## Return Negative

```js
function makeNegative(num) {
  if (num > 0) {
    return num * -1
  }
  return num
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let sum = 0
  for (let i = 0; i < arr.length; i++) {
    if (arr[i] > 0) {
      sum += arr[i]
    }
  }
  return sum
}
```

## Function 2

```js
function square(num) {
  return Math.pow(num, 2)
}
```

## Sum Arrays

```js
function sum(numbers) {
  'use strict'
  let sum = 0
  for (let i = 0; i < numbers.length; i++) {
    if (!isNaN(numbers[i])) {
      sum += numbers[i]
    }
  }
  return sum
}
```

## Reversed Strings

```js
function solution(str) {
  let ans = ''
  for (let i = str.length - 1; i >= 0; i--) {
    ans = ans + str[i]
  }
  return ans
}
```
