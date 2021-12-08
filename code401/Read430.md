# What we will learn

- Hashtables

The source of this summary [The first link](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-30/resources/Hashtables.html)

The source of this summary [The second link](https://www.youtube.com/watch?v=MfhjkfocRR0)

______________________________________

## What is a Hashtables

**Hash tables are a type of data structure in which the address or the index value of the data element is generated from a hash function. That makes accessing the data faster as the index value behaves as a key for the data value.**

### Terminology:

1. Hash - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.

2. Buckets - A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.

3. Collisions - A collision is what happens when more than one key gets hashed to the same location of the hashtable.


## Why do we use Hashtable?

**The idea of a hash table is to provide a direct access to its items. So that is why the it calculates the "hash code" of the key and uses it to store the item, insted of the key itself. The idea is to have only one hash code per key.**

### Creating a Hash

- Add or multiply all the ASCII values together.

- Multiply it by a prime number such as 599.

- Use modulo to get the remainder of the result, when divided by the total size of the array.

- Insert into the array at that index.

### Hash function

**A hash function is any function that can be used to map data of arbitrary size to fixed-size values. The values returned by a hash function are called hash values, hash codes, digests, or simply hashes. The values are usually used to index a fixed-size table called a hash table.**

### Bucket Sizes

*Hash Maps can have any number of buckets. If a hash map has only a few buckets it will be densely full and have many collisions. If a hash map has more buckets it will be more sparsely populated, there will be less collisions, but there may be a lot of extra empty space.*

### Internal Methods

- Add() --> When adding a new key/value pair to a hashtable

- Find() --> takes in a key, gets the Hash, and goes to the index location specified. Once at the index location is found in the array, it is then then the responsibility of the algorithm the iterate through the bucket and see if the key exists and return the value.

- Contains() --> will accept a key, and return a bool on if that key exists inside the hashtable.

- GetHash() --> will accept a key as a string, conduct the hash, and then return the index of the array where the key/value should be placed.

