### Bitcoin Core Tech & Docs 
---
### Bitcoin Cash Indexer API
 v1 
[ Base URL: explorer.api.bitcoin.com/bch/v1 ]
The Bitcoin.com Indexer API serves blockchain data for Bitcoin Cash and Bitcoin.
Version 1 endpoints emulate BitPay's Insight API v5.
---
# Contact the developer
# Schemes
---
# HTTPS
addr
---
GET
/addr/{addr}
# Find address information
GET
/addr/{addr}/balance
# Find address balance
GET
/addr/{addr}/totalReceived
# Find address total received amount
GET
/addr/{addr}/totalSent
# Find address total sent amount
GET
/addr/{addr}/unconfirmedBalance
# Find address unconfirmed balance
GET
/addr/{addr}/utxo
# Get utxo set from an addresses
addrs
---
# POST 
-
/addrs/utxo
Get utxo set from multiple addresses
# POST
/addrs/txs
# Find transactions by multiple addresses
GET
/addrs/{addrs}/utxo
# Get utxo set from multiple addresses
GET
/addrs/{addrs}/txs
# Find transactions by multiple addresses
block
---
GET
/block/{blockHash}
# Find block information by block hash
GET
/block-index/{height}
# Find block hash by block height
blocks
---
GET
/blocks
# Find block summary by date
tx
---
GET
/tx/{txid}
# Find a transaction by txid
GET
/rawtx/{txid}
# Find a raw transaction by txid
txs
---
GET
/txs
# Find transactions by block hash or address
-Models
-TxsAddrErr
-Rawtx
-RawtxErr 
-Pagination
-Blocks
-BlocksObj
-BlockIndexErr
-BlockHash
-Block
-PoolInfo
-Addr
-ScriptPubKey
-Vout
-ScriptSig
-Vin
-Tx
-AddrsTxsObj
-StillSync
-Addrs
-Utxo
