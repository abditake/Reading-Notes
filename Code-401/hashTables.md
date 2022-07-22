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