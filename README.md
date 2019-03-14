# decode-eth-tx

JS tool to decode ethereum transactions. Deployed at https://flightwallet.org/decode-eth-tx/

Try this tx:

```
0xf86d820144843b9aca0082520894b78777860637d56543da23312c7865024833f7d188016345785d8a0000802ba0e2539a5d9f056d7095bd19d6b77b850910eeafb71534ebd45159915fab202e91a007484420f3968697974413fc55d1142dc76285d30b1b9231ccb71ed1e720faae
```

It should be decoded to:

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


# credit

(c) Credit goes to https://reddit.com/user/dontmindme42

https://www.reddit.com/r/ethereum/comments/48rf3d/weve_heard_you_loud_and_clear_so_tonightweve/d0m07bg/?context=3

[<img src="https://raw.githubusercontent.com/morejust/foundation/master/madebymorejust.png" width="100">](https://morejust.foundation/?from=decode-eth-tx)
