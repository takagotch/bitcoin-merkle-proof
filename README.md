### bitcoin-merkle-proof
---
https://github.com/mappum/bitcoin-merkle-proof

```js
var bmp = require('bitcoin-merkle-proof')

var merkleProof = bmp.build({
  hashes: [
    new Buffer('xxx', 'hex'),
    new Buffer('xxx', 'hex'),
    new Buffer('xxx', 'hex'),
    new Buffer('xxx', 'hex'),
    new Buffer('xxx', 'hex')
  ],
  include: [
    new Buffer('xxx', 'hex'),
    new Buffer('xxx', 'hex')
  ]
})

var hashes = bmp.verify(merkleProof)
console.log('Matched transactions: ', hashes)

```

```json
{
  flags: number[],
  hashes: Buffer[],
  numTransactions: number,
  merkleRoot: Buffer
}
```

```
```


