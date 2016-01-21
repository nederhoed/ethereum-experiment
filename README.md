# ethereum-experiment
Fiddling with Ethereum

Follow these instructions to create your own private chain:
  * http://adeduke.com/2015/08/how-to-create-a-private-ethereum-chain/

After that, try to run:
```
 $ ./geth-private.sh account new
 ...
 $ ./geth-private.sh account list

```

After that, try to run:
```
 $ curl -X POST --data '{"jsonrpc":"2.0","method":"eth_accounts","params":[],"id":1} http://127.0.0.1:30303'
 curl: (52) Empty reply from server
```
Which did not work for me...