
# Namespace eth <a id="namespace-eth"></a>

The namespace `eth` provides functions related to accounts, blocks, transactions,
configurations of networks or nodes, filters, and so on.

Klaytn now supports eth namespace of [Ethereum's JSON-RPC API](https://eth.wiki/json-rpc/API). But Please note that
there are some fields returning values adjusted to match Ethereum API response. 

And due to the fundamental design differences existing between Klaytn and Ethereum, 
Klaytn's data structure (Transaction, Block, and TransactionReceipt) cannot be fully supported via eth namespace APIs.

Please check the [Differences Overview from Ethereum](#differences_overview_from_ethereum) section of this document.

**NOTE**: `eth` namespace APIs are supported from Klaytn v1.8.0.

The list below enumerates the API functions. All `eth` namespace APIs are supported in Klaytn.

### [Account](./eth/account.md) <a id="account"></a>
- [eth_accounts](./eth/account.md#eth_accounts)
- [eth_getBalance](./eth/account.md#eth_getbalance)
- [eth_getCode](./eth/account.md#eth_getcode)
- [eth_getTransactionCount](./eth/account.md#eth_gettransactioncount)
- [eth_sign](./eth/account.md#eth_sign)

### [Block](./eth/block.md) <a id="block"></a>
- [eth_blockNumber](./eth/block.md#eth_blocknumber)
- [eth_getHeaderByNumber](./eth/block.md#eth_getheaderbynumber)
- [eth_getHeaderByHash](./eth/block.md#eth_getheaderbyhash)
- [eth_getBlockByNumber](./eth/block.md#eth_getblockbynumber)
- [eth_getBlockByHash](./eth/block.md#eth_getblockbyhash)
- [eth_getBlockByHash](./eth/block.md#eth_getblockbyhash)
- [eth_getUncleBlockByHashAndIndex](./eth/block.md#eth_getunclebyblockhashandindex)
- [eth_getUncleByBlockNumberAndIndex](./eth/block.md#eth_getunclebyblocknumberandindex)
- [eth_getBlockTransactionCountByNumber](./eth/block.md#eth_getblocktransactioncountbynumber)
- [eth_getBlockTransactionCountByHash](./eth/block.md#eth_getblocktransactioncountbyhash)
- [eth_getUncleCountByBlockNumber](./eth/block.md#eth_getunclecountbyblocknumber)
- [eth_getUncleCountByBlockHash](./eth/block.md#eth_getunclecountbyblockhash)
- [eth_getStorageAt](./eth/block.md#eth_getstorageat)
- [eth_mining](./eth/block.md#eth_mining)
- [eth_syncing](./eth/block.md#eth_syncing)


### [Transaction](./eth/transaction.md) <a id="transaction"></a>
- [eth_call](./eth/transaction.md#eth_call)
- [eth_estimateGas](./eth/transaction.md#eth_estimategas)
- [eth_getTransactionByBlockHashAndIndex](./eth/transaction.md#eth_gettransactionbyblockhashandindex)
- [eth_getTransactionByBlockNumberAndIndex](./eth/transaction.md#eth_gettransactionbyblocknumberandindex)
- [eth_getTransactionByHash](./eth/transaction.md#eth_gettransactionbyhash)
- [eth_getTransactionReceipt](./eth/transaction.md#eth_gettransactionreceipt)
- [eth_sendRawTransaction](./eth/transaction.md#eth_sendrawtransaction)
- [eth_sendTransaction](./eth/transaction.md#eth_sendtransaction)
- [eth_signTransaction](./eth/transaction.md#eth_signtransaction)


### [Configuration](./eth/config.md) <a id="configuration"></a>
- [eth_coinbase](./eth/config.md#eth_coinbase)
- [eth_etherbase](./eth/config.md#eth_etherbase)
- [eth_chainId](./eth/config.md#eth_chainid)
- [eth_gasPrice](./eth/config.md#eth_gasprice)


### [Filter](./eth/filter.md) <a id="filter"></a>
- [eth_getFilterChanges](./eth/filter.md#eth_getfilterchanges)
- [eth_getFilterLogs](./eth/filter.md#eth_getfilterlogs)
- [eth_getLogs](./eth/filter.md#eth_getlogs)
- [eth_newBlockFilter](./eth/filter.md#eth_newblockfilter)
- [eth_newFilter](./eth/filter.md#eth_newfilter)
- [eth_newPendingTransactionFilter](./eth/filter.md#eth_newpendingtransactionfilter)
- [eth_subscribe](./eth/filter.md#eth_subscribe)
- [eth_uninstallFilter](./eth/filter.md#eth_uninstallfilter)
- [eth_unsubscribe](./eth/filter.md#eth_unsubscribe)


### [Gas](./eth/gas.md) <a id="gas"></a>
- [eth_feeHistory](./eth/gas.md#eth_feehistory)
- [eth_maxPriorityFeePerGas](./eth/gas.md#eth_maxpriorityfeepergas)

### [Miscellaneous](./eth/misc.md) <a id="miscellaneous"></a>
- [eth_hashrate](./eth/misc.md#eth_hashrate)
- [eth_getWork](./eth/misc.md#eth_getwork)
- [eth_submitWork](./eth/misc.md#eth_submitwork)
- [eth_submitHashrate](./eth/misc.md#eth_submithashrate)