### Transactions and UTXOs

In the Bitcoin network, transactions are used to transfer Bitcoin from one user to another. When a user wants to send Bitcoin, they create a transaction that specifies the amount they want to send, the recipient's Bitcoin address, and a fee to incentivize miners to include the transaction in a block.

When a transaction is broadcast to the network, it is added to each node's mempool, where it waits to be included in a block. Once a miner includes the transaction in a block, it is considered confirmed and the Bitcoin is transferred from the sender to the recipient.

The Bitcoin network keeps track of the ownership of each Bitcoin through a data structure called an unspent transaction output (UTXO). When a user receives Bitcoin, they receive a UTXO that specifies the amount of Bitcoin they received and the conditions under which they can spend it. To spend a UTXO, a user must create a new transaction that specifies the UTXO they want to spend as an input, along with a destination address and a fee for the miners.

When a transaction spends a UTXO, the UTXO is marked as spent and can no longer be used in future transactions. The amount of Bitcoin that was spent is transferred to the destination address specified in the transaction, and any change is returned to the sender as a new UTXO.

It's worth noting that a UTXO can only be spent once. Once it has been spent, it is removed from the list of unspent outputs and can no longer be used in future transactions. This is what allows the Bitcoin network to prevent double-spending of the same Bitcoin, as each UTXO can only be spent once.

In summary, transactions are used to transfer Bitcoin from one user to another, and each transaction spends one or more unspent transaction outputs (UTXOs). When a UTXO is spent, it is marked as spent and can no longer be used in future transactions, which helps prevent double-spending. The ownership of each Bitcoin is tracked through UTXOs, which are updated as Bitcoin is transferred between users.
