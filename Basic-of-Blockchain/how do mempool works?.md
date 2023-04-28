### How do Mempool works?

When a user creates a Bitcoin transaction and broadcasts it to the network, it is initially sent to each node on the network. Each node verifies the transaction to ensure that it is valid according to the rules of the Bitcoin protocol. If the transaction is valid, the node adds it to its mempool.

The mempool is essentially a database of unconfirmed transactions that have been verified by each node on the network. Each node maintains its own mempool, which is a list of transactions that it has verified but have not yet been included in a block.

Miners use the transactions in the mempool to create new blocks. When a miner creates a new block, they choose which transactions to include in the block from the mempool. Miners typically choose transactions with the highest transaction fees, since they earn those fees as part of their reward for mining the block.

As the mempool grows in size, nodes may begin to prioritize transactions based on their transaction fees. Transactions with higher fees are typically processed more quickly, since miners are more likely to choose those transactions for inclusion in their blocks.

However, if the mempool becomes too large, nodes may begin to drop low-fee or low-priority transactions from their mempools in order to conserve resources. When a transaction is dropped from a mempool, it is not included in any future blocks and must be rebroadcast to the network if the user wants it to be processed.

It's worth noting that the mempool only includes transactions that have been verified by each node on the network. If a transaction is not valid according to the rules of the Bitcoin protocol, it will not be added to the mempool and will not be processed by the network.

In summary, the mempool is a database of unconfirmed transactions that have been verified by each node on the Bitcoin network. Miners use the transactions in the mempool to create new blocks, prioritizing transactions with higher fees. If the mempool becomes too large, nodes may drop low-priority transactions to conserve resources.
