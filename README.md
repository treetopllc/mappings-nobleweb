# mappings-nobleweb

> List of ID/string mappings for nobleweb

This reference lib is used to help translate ID numbers into human-friendly strings.
(and vice versa) It does so by exposing several properties on the exported object,
where each one has a `by_id` and `by_name` plain JS object.

## Usage

```js
var mapping = require("mappings-nobleweb");

console.log(mapping.roles.by_name.CITIZEN);
// => 5

console.log(mapping.roles.by_id[1]);
// => "Noblehour Admin"
```
