### What is Nonce Range?

Nonce range refers to the range of values that a miner can use for the nonce field in a Bitcoin block header. The nonce is a 32-bit field in the block header that miners can vary in order to try to find a block hash that meets the Bitcoin network's difficulty requirements.

When a miner creates a new block, they set the nonce to a specific value, and then they hash the block header to create a hash value. If the hash value meets the network's difficulty requirements, the miner has successfully mined a block and is eligible to receive a reward in the form of newly created Bitcoin.

However, if the hash value does not meet the difficulty requirements, the miner must change the value of the nonce and try again. The miner can change the value of the nonce by incrementing it by one, which creates a new block header that can be hashed to check if it meets the difficulty requirements.

The nonce range is the total number of values that a miner can use for the nonce field in a block header. Since the nonce field is 32 bits long, the nonce range is 2^32 or 4.3 billion possible values. Miners must cycle through all of these values in order to exhaust the nonce range and try all possible combinations.

In summary, the nonce range is the total number of values that a miner can use for the nonce field in a Bitcoin block header. Miners must cycle through all possible values in order to exhaust the nonce range and try to find a block hash that meets the network's difficulty requirements.
