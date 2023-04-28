### What is Timestamp

Timestamps are an important part of Bitcoin mining and are used to record the time at which a block is created. In the Bitcoin protocol, each block contains a timestamp field that records the time at which the block was created.

The timestamp is stored as a Unix timestamp, which is a 32-bit integer representing the number of seconds since January 1, 1970, at 00:00:00 UTC. This format is used because it is a standardized way of representing time that is recognized by many computer systems.

The timestamp is important for several reasons. First, it ensures that blocks are created in a specific order and that there is a clear record of when each block was created. This is important for maintaining the integrity of the Bitcoin blockchain and ensuring that it is an accurate representation of the Bitcoin transaction history.

Second, the timestamp is used to adjust the Bitcoin network's difficulty level. The Bitcoin protocol adjusts the difficulty level every 2016 blocks based on the amount of time it took to create the previous 2016 blocks. If blocks are being created too quickly, the difficulty level is increased, and if blocks are being created too slowly, the difficulty level is decreased. This ensures that blocks are created at a steady rate and that the Bitcoin network remains secure.

Finally, the timestamp can also be used to verify the authenticity of a block. Since the timestamp is recorded in each block, it can be used to verify that the block was created at a specific time and that it was not created at a later time and inserted into the blockchain.

In summary, timestamps are an important part of Bitcoin mining and are used to record the time at which a block is created. The timestamp is stored as a Unix timestamp and is used to ensure the order of blocks, adjust the difficulty level, and verify the authenticity of blocks.

#### What's the Miners do when all the Nonce get Exhausted and Miner not have hit the target?

When all possible nonce values have been tried and a miner has not yet found a block hash that meets the network's difficulty requirements, the miner must change another field in the block header in order to generate a new hash.

One field that miners can change is the timestamp field. By changing the timestamp, the miner can create a new block header that can be hashed to check if it meets the network's difficulty requirements. Since the timestamp is a 32-bit integer, it has a range of 4.3 billion possible values, which provides a large number of possibilities for miners to try.
In summary, if a miner exhausts all possible nonce values and still does not find a block hash that meets the network's difficulty requirements, they must change other fields in the block header, such as the timestamp or Merkle root, in order to generate a new hash. If all possible combinations of these fields have been tried and the miner still has not found a block hash that meets the requirements, they will not be able to mine a block and receive a reward.
