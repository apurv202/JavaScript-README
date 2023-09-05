#### 📌 JSON

- JSON stands for **J**ava**S**cript **O**bject **N**otation

- JSON is a lightweight data interchange format

- JSON is language independent *

- JSON is "self-describing" and easy to understand

\* The JSON syntax is derived from JavaScript object notation syntax, but the JSON format is text only. Code for reading and generating JSON data can be written in any programming language.

## 🔺 JSON Example

This JSON syntax defines an employees object: an array of 3 employee records (objects):

```json
{
  "employees": [
    { "firstName": "John", "lastName": "Doe" },
    { "firstName": "Anna", "lastName": "Smith" },
    { "firstName": "Peter", "lastName": "Jones" },
    { "firstName": "Mary", "lastName": "Williams" }
  ]
}
```

```
JSON Syntax Rules
1. The top level must be either an object or an array.
2. An object begins with curly braces {}.
3. A property name in double quotes "".
4. Values are separated by commas , .
5. Arrays begin with square brackets [].
6. All values must be strings, numbers, booleans, nulls, objects, arrays, or undefined.
7. Strings use single quotations ' '.
8. Numbers do not need any separators.
9. Boolean true/false values should always be lowercased.
10. Null values should also be all lowercased.
11. Objects may contain other objects inside them.
12. Arrays can only have elements that are themselves objects or arrays.
13. Comments start with // and extend until the end of line.
```