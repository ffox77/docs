# Gettxout method

Returns the corresponding transaction output (change) information based on the specified hash and index.

## Parameter Description

Txid: transaction ID.

N: the index of the transaction to be obtained in the transaction (starting from 0).

## Call the example

Request text:

```json
{
   "jsonrpc": "2.0",
   "method": "gettxout",
   "params": ["f4250dab094c38d8265acc15c366dc508d2e14bf5699e12d9df26577ed74d657", 0],
   "id": 1
}
```

Response text:

```json
{
   "jsonrpc": "2.0",
   "id": 1,
   "result": {
     "N": 0,
     "Asset": "c56f33fc6ecfcd0c225c4ab356fee59390af8560be0e930faebe74a6daff7c9b",
     "Value": "2950",
     "Address": "AHCNSDkh2Xs66SzmyKGdoDKY752uyeXDrt"
   }
}
```