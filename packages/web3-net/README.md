# web3-net

This is a sub package of [web3.js][repo]

This is the net package to be used in other web3.js packages.
Please read the [documentation][docs] for more.

## Installation

```bash
npm install web3-net
```

## Usage

```js
import {Network} from 'web3-net';

const net = new Network(
    'http://127.0.0.1:4546',
    options
);
```

## Types 

All the typescript typings are placed in the types folder. 

[docs]: http://web3js.readthedocs.io/en/1.0/
[repo]: https://github.com/ethereum/web3.js
