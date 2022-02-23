
# Namespace eth <a id="namespace-eth"></a>

The namespace `eth` provides functions related to accounts, blocks, transactions,
configurations of networks or nodes, filters, and so on.

Klaytn now supports eth namespace of [Ethereum's JSON-RPC API](https://eth.wiki/json-rpc/API). But Please note that
there are some fields returning values adjusted to match Ethereum API response. 

And due to the fundamental design differences existing between Klaytn and Ethereum, 
Klaytn's data structure (Transaction, Block, and TransactionReceipt) cannot be fully supported via eth namespace APIs.

Please check the [Differences Overview from Ethereum](#differences_overview_from_ethereum) section of this document.