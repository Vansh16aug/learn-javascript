# JSON

**J**ava**S**cript **O**bject **N**otation (JSON) is a text-based format for storing and transporting data.  The Javascript Objects can be easily converted into JSON and vice versa.  For example.

```javascript
//  a JavaScript object
let myObj = { name:"Ryan", age:30, city:"Austin" };

// converted into JSON:
let myJSON = JSON.stringify(myObj);
console.log(myJSON);
// Result: '{"name":"Ryan","age":30,"city":"Austin"}'

//converted back to JavaScript object
let originalJSON = JSON.parse(myJSON);
console.log(originalJSON);

// Result: {name: 'Ryan', age: 30, city: 'Austin'}
```



`stringify` and  `parse` are the two methods supported by JSON.

| Method        | Description                                            |
| ------------- | ------------------------------------------------------ |
| `parse()`     | Returns  JavaScript object from the parsed JSON string |
| `stringify()` | Returns JSON string from JavaScript Object             |



&#x20;The following data types are supported by JSON.

* string
* number
* array
* boolean
* object with valid JSON values
* `null`

It can not be `function`,  `date` or `undefined`.
