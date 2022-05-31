# Javascript

## Coding Tasks

### Palindrome

Check if the text is a palindrome.
For empty string, it is not considered a palindrome.
Whitespaces should not be counted

```javascript
const isPalindrome = (text) => {
  // your code here
}

console.log(isPalindrome('')); // false
console.log(isPalindrome('     ')); // false
console.log(isPalindrome('anna')); // true
console.log(isPalindrome('anna    ')); // true
console.log(isPalindrome('indul a gorog aludni')); // true
console.log(isPalindrome('alma')); // false
```

### Content weight

Takes a bottleWeight and scale of the bottle to its contents and returns the weight of its contents
Acceptable values for scale: `('2 times larger', '4 times larger', '50 times smaller')`

```javascript
/**
 * @param {number} bottleWeight: The weight of the entire bottle and contents
 * @param {string} scale: A string comparing the weight of the bottle contents to the weight of the bottle by itself
 */
const contentWeight = (bottleWeight, scale) => {
  // your code here
}

console.log(contentWeight(120, '2 times larger')); // 80
console.log(contentWeight(120, '2 times smaller')); // 40
```

### File extension

```javascript
const getFileExtension = filename => {
  // your code here
}

console.log(getFileExtension('data.txt')); // 'txt'
console.log(getFileExtension('component.test.js')); // 'js'
console.log(getFileExtension('README')); // false
console.log(getFileExtension('.git')); // false
```

### Longest string

```javascript
const getLongestString = array => {
  // your code here
}

console.log(getLongestString([[1, 2, 3, 4, 5], 'alma'])); // 'alma'
console.log(getLongestString(['abc', 'a', 'ab'])); // 'abc'
console.log(getLongestString([1, 2, 3])); // ''

```

### UUID Blocks

```javascript
const getUUIDBlocks = uuid => {
  // your code here
}

console.log(getUUIDBlocks('f782f011-636a-4d8b-9f63-dc34a4503c01')); // ['f7', '82', 'f0', '11', '63', '6a', '4d', '8b', '9f', '63', 'dc', '34',' a4', '50', '3c', '01']
```

### UUID Conversion

```javascript
const getConvertedUUIDBlocks = uuid => {
  // your code here
}

console.log(getConvertedUUIDBlocks('f782f011-636a-4d8b-9f63-dc34a4503c01')); // [247, 130, 240, 17, 99, 106, 77, 139, 159, 99, 220, 52, 164, 80, 60, 1]
```

### First duplicate

```javascript
const getFirstDuplicate = text => {
  // your code here
}

console.log(getFirstDuplicate('abccb')); // 'b'
console.log(getFirstDuplicate('abc')); // ''
```

### Sum all numbers in an array

```javascript
const arraySum = (array) => {
  // your code here
}

console.log(arraySum([1, 2, 3, 4, 5])); // 15
console.log(arraySum([1, 2, 3, 4, '5', null, undefined, NaN, Infinity, true, false, { id: '1' }, 5])); // 15
```

### Sum all numbers in a nested array

```javascript
const nestedSum = (array) => {
  // your code here
}

console.log(nestedSum([1, [2, [[[3]]]], [4, 5]])); // 15
console.log(nestedSum([1, [2, [3], [4, '5', null, undefined, [NaN, Infinity], [true, false], { id: '1' }, 5]]])); // 15
```

### Sum all the even numbers in an array

```javascript
const evenSum = (array) => {
  // your code here
}

console.log(evenSum([1, [2, 3], [[4], 5]])); // 6
console.log(evenSum([1, [1, 1], [[1], 1]])); // 0
```

### Order the elements in the array

The order should be odd followed by even numbers
- odd numbers should be ascendig
- even numbers should be descending

```javascript
const splitOrder = (array) => {
  // your code here
}

console.log(splitOrder([1, 2, 3, 4, 5, 6, 7, 8, 9, 0])); // [1, 3, 5, 7, 9, 8, 6, 4, 2, 0]

```

### Square the negatives and sum the digits

```javascript
const squareAndSum = (array) => {
  // your code here
}

console.log(squareAndSum([-1, 1, 12, -4, -5, 999])); // [1, 1, 3, 7, 7, 9]
```

### Friday 13

The function should return all of the friday 13s within the given year range. If no endYear is given it should check the startYear only.

```javascript
const getFriday13s = (startYear, endYear) => {
  // your code here
}

console.log(getFriday13s(1999, 2000)); // ['1999.08.13.', '2000.10.13']
console.log(getFriday13s(2000)); // ['2000.10.13']
```

