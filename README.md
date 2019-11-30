# validator-sa

Implements validation and normalization of strings, for South African ID
numbers. Maybe in future other validation that is specific to South Africa.

# How to Use

Install it via `npm`:

```
npm i validator-sa
```

In ES6, import what you need:

```
import { isValidSouthAfricanIDNumber } from 'validator-sa'
```

In ES5, `require` it, and use it form there:

```
var validator = require('validator-sa');

var isValid = validator.isValidSouthAfricanIDNumber('123')
// `isValid` should be false
```

# API

Documentation is [here](./api.md).