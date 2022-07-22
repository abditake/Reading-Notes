# Implementation: HashTables



## HashTables:

- ### `HashTables` are a data Structure that uses key value pairs. This means every Node or Bucket has both a key, and a value. A Hash is the ability to encode the key that will eventually map to a specific location in the data structure that we look at to retrieve the value. The benefits of a HashTable is being able to instead needing to iterating through an entire array looking for specific data we can just fast access the information. 


## How does a Hashtable work
- accept a key
- calculate the hash of the key
- use modulus to convert the hash into an array index
- use the array index to access the short LinkedList representing a bucket
- search through the bucket looking for a node with a key/value pair that matches the key you were given

- # The following example below is a `HashTable`

![java Example](https://howtodoinjava.com/wp-content/uploads/2018/10/hashtable.gif)

Methods in a HashTable

## `Add()`
- When adding a new key/value pair to a hashtable:

  - send the key to the GetHash method.
  - Once you determine the index of where it should be placed, go to that index
  - Check if something exists at that index already, if it doesn’t, add it with the key/value pair.
  - If something does exist, add the new key/value pair to the data structure within that bucket.
## `Find()`
  - The Find takes in a key, gets the Hash, and goes to the index location specified. Once at the index location is found in the array, it is then the responsibility of the algorithm the iterate through the bucket and see if the key exists and return the value.

## `Contains()`
  - The Contains method will accept a key, and return a bool on if that key exists inside the hashtable. The best way to do this is to have the contains call the GetHash and check the hashtable if the key exists in the table given the index returned.

## `GetHash()`
  - The GetHash will accept a key as a string, conduct the hash, and then return the index of the array where the key/value should be placed.