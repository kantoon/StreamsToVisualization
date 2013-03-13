#Data Structures

##Hash Tables

Hash tables are useful lookup structures widely used in many kinds of computer software, usually for associative arrays, database indexing, caches, and sets. They are made up of two parts: a table/array that stores the data/values to be searched and a hash function that maps keys to values. The hash function stores data in the array by assigning index values to the keys that suggest where the value can be found. In other words, an element with key k is stored in index f(k) where f is a hash function.

For a hash function, if each key maps into a different index in the array, we have ideal hashing. If the same index is used to store data for more than one key, we have collision. Collision is practically unavoidable when hashing a random subset of a large set of possible keys. Some collision resolution techniques include separate chaining, open addressing including linear probing, and coalesced hashing and other hashing techniques.

The main advantage of hash tables, more obvious over other data structures when the number of entries is large, is speed. Hash tables insert, search, and delete in O(1) expected time and Theta(n) worst case. However, the performance of a hash table will decrease with more collisions.

##Bloom Filters

##Count-Min Sketches
