Bitcoin ABC version 0.19.8 is now available from:

  <https://download.bitcoinabc.org/0.19.8/>

This release includes the following features and fixes:
 - Remove `getinfo` RPC in favor of `getblockchaininfo`, `getnetworkinfo` and `getwalletinfo`.
 - `./bitcoin-cli -getinfo` will now throw a runtime error if there are any extra arguments after it.
