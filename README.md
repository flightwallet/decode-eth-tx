# decode-eth-tx

JS tool to decode ethereum transactions. Deployed at http://flightwallet.org/decode-eth-tx/

Try this tx:

```
0xf86e8201ae843b9aca0082520894f8558382014485843b9aca008382520880a0a0a088016345785d8a0000818027a065b3c5d88e000047adbaddd85de60860d82b9d5308121c74bd428175cea2e121a0250ad51582c58c9aaec612ef006dbab58e47bf1f68509dee7be0fb69548dc2ba
```

It should decode to:

```json
{
  "nonce": 430,
  "gasPrice": 1000000000,
  "gasLimit": 21000,
  "to": "0xf8558382014485843b9aca008382520880a0a0a0",
  "value": 100000000000000000,
  "data": "80"
}
```
