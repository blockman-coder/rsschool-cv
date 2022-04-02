# Dmitry Bodnarchuk

## Contacts
 * **Location:** Zaporizhia, Ukraine
 * **Phone:** +38 066 746 35 11
 * **Email:** blockman.coder@gmail.com
 * **GitHub:** [blockman-coder](https://github.com/blockman-coder)

## Skills
 * Core JS/Java/Python/C/C++
 * Basic HTML/CSS
 * Git

## Code Examples
**WeIrD StRiNg CaSe KATA from CODEWARS:** *Write a function toWeirdCase (weirdcase in Ruby) that accepts a string, and returns the same string with all even indexed characters in each word upper cased, and all odd indexed characters in each word lower cased. The indexing just explained is zero based, so the zero-ith index is even, therefore that character should be upper cased and you need to start over for each word.*
```js
function toWeirdCase(str) {
  return str.split(" ")
    .map(
      (word) => word.split("")
      .map(
        (char, idx) => idx % 2 == 0 ? char.toUpperCase() : char.toLowerCase()
      )
      .join("")
    )
    .join(" ");
}
```
**Count characters in your string KATA from CODEWARS:** *The main idea is to count all the occurring characters in a string. If you have a string like aba, then the result should be {'a': 2, 'b': 1}.*
```js
function count (str) {  
  const chars = {};
  for (let i = 0; i < str.length; ++i) {
    const c = str[i];
    chars[c] = chars[c] ? chars[c] + 1 : 1;
  }
  return chars;
}
```
