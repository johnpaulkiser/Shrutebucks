# Shrutebucks
A [satirical](https://www.youtube.com/watch?v=3IYQXUfezxY) but functional cryptocurrency.


## Basic Features
* Uses POW (need to find hashing algorithm)
* Uses UTXO based accounting
* Full p2p client
* Uses Bitcoin's ecdsa signature scheme
* Only supports pay to public key hash (P2PKH)
* 2 minute block times
* 2kb blocks


## Monetary Policy
_Since this has no intention to be used as real money, the monetary policy is set up to prevent this coin from ever having real market value_

* The block reward will remain constant at 1 shrutebuck.
* Shrutebucks may not be reduced smaller than 1. 
  * _You cannot have 0.5 shrutebucks_
  

 ## SBCLI
 _command-line interface Shrutebucks client_

 All commands start with `sbcli`
 ```
 -d "daemon mode"

 -m <block reward address> "start mining, paying out to submitted address"

 -cp <ip address> "connect to peer"

 -get_block <block hash> "return block by block hash"

 -create_tx "create and submit transaction, is interactive"

 -get_tx <txid> "returns corresponding transaction"

 -create_keypair <seed> "returns public key and corresponding private key"

 -get_balance <pub key hash> "Gets the spendable balance of pub key" 
 ```


  
