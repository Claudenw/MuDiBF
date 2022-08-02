# MuDiBF
Multidimensional Bloom Filter index (pronounced Moody-bee-eff)

# Project Step
Design an cloud first index to store arbitrary IDs associated with Bloom filters.  When searching a `target` Bloom filter will be submitted and the system shall return all of the matching Bloom filters (`candidate` filters) from the index.  Matching is defined as `target & candidate = target`.

System should allow new implementations of multidimensional Bloom filters to be plugged in.

 - [ ] Settle on distributed update strategy.  Possibly simple sharding with multiple copies.
 - [ ] Settle on implementation plugin strategy.  See https://github.com/Claudenw/BloomTest 
 - [ ] Develop interfaces.
 - [ ] Implement FlatBloofi as the first engine.
 - [ ] Implement BFTrie as the second engine.



