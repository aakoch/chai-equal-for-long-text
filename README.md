# chai-equal-for-long-text

I needed something a little better for long strings and couldn't find anything. If you find something better, let me know. 🙂

## Disclaimer?

Assertion is only done on strings greater than 20 characters. Otherwise this calls the original method.

## Installation

```shell
npm i chai-equal-for-long-text
```

## Usage

```js
import equal from 'chai-equal-for-long-text'

chai.use(equal);
```

## License
MIT