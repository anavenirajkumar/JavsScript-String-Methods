# String Methods Cheat Sheet

```javascript
const str = 'HeLlo';
const stringObj = new String('grace');
```

| Methods       | Code Example                | Result                    | Return Type |
| ------------- | --------------------------- | ------------------------- | ----------- |
| length        | let length = str.length     | 5                         | number      |
| toLowerCase() | str.toLowerCase()           | hello                     | string      |
| toUpperCase() | str.toUpperCase()           | HELLO                     | string      |
| indexOf()     | str.indexOf('L')            | 2                         | number      |
| indexOf()     | 'hello'.indexOf('l')        | 2                         | number      |
| indexOf()     | str.indexOf('L')            | 2                         | number      |
| lastIndexOf() | 'hello'.lastIndexOf('l')    | 3                         | number      |
| search()      | str.search("o")             | 4                         | number      |
| search()      | str.search(/[a-z]/g)        | 1                         | number      |
| endsWith()    | str.endsWith('z')           | FALSE                     | boolean     |
| endsWith()    | str.endsWith('o', 6)        | TRUE                      | boolean     |
| includes()    | str.includes('a')           | FALSE                     | boolean     |
| startsWith()  | str.startsWith('H', 1)      | FALSE                     | boolean     |
| startsWith()  | str.startsWith('H')         | TRUE                      | boolean     |
| charAt()      | str.charAt(1)               | e                         | string      |
| at()          | str.at(0)                   | H                         | string      |
| concat()      | str.concat(' grace')        | HeLlo grace               | string      |
| padEnd()      | str.padEnd(10, '!')         | HeLlo!!!!!                | string      |
| padStart()    | str.padStart(10, '!')       | !!!!!HeLlo                | string      |
| repeat()      | str.repeat(3)               | HeLloHeLloHeLlo           | string      |
| replace()     | str.replace('L', 'l')       | Hello                     | string      |
| replaceAll()  | hello'.replaceAll('l', 'z') | hezzo                     | string      |
| slice()       | str.slice(1, 3)             | eL                        | string      |
| slice()       | str.slice(2)                | Llo                       | string      |
| substring()   | str.substring(2)            | Llo                       | string      |
| substring()   | str.substring(1, 3)         | eL                        | string      |
| substr()      | str.substr(2)               | Llo                       | string      |           
| toLowerCase() | str.toLowerCase()           | hello                     | string      |
| toUpperCase() | str.toUpperCase()           | HELLO                     | string      |
| trim()        | ' hello '.trim()            | 'hello'                   | string      |
| trimEnd()     | ' hello '.trimEnd()         | ' hello'                  | string      |
| trimStart()   | ' hello '.trimStart()       | 'hello '                  | string      |
| valueOf()     | stringObj.valueOf()         | grace                     | string      |
| match()       | str.match(/[A-Z]/g)         | ["H", "L"]                | array       |
| split()       | str.split()                 | ["HeLlo"]                 | array       |
| split()       | str.split('')               | ["H", "e", "L", "l", "o"] | array       |
| charCodeAt()  | str.charCodeAt(0)           | 72                        | Get the Unicode of the  <br> first character in a string |
| codePointAt() | str.codePointAt(0)          | 72                        | Get char code value |
| constructor | let con = str.constructor | function String() { <br> [native code] <br> } | returns the function |
| fromCharCode()| str.fromCharCode(65)        | A                         | Unicode character value |
| fromCharCode()| str.fromCharCode(72, 69, 76, 76, 79) | HELLO | Unicode characters values |

