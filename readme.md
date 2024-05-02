Serialization is to store a tree in an array so that it can be later restored and deserialization is reading tree back from the array. Complete the functions

serialize() : stores the tree into an array a and returns the array.
deSerialize() : deserializes the array to the tree and returns the root of the tree.
Note: Multiple nodes can have the same data and the node values are always positive integers. Your code will be correct if the tree returned by deSerialize(serialize(input_tree)) is same as the input tree. Driver code will print the in-order traversal of the tree returned by deSerialize(serialize(input_tree)).

Example 1:
```
Input:
      1
    /   \
   2     3
Output: 
2 1 3
```
Example 2:
```
Input:
         10
       /    \
      20    30
    /   \
   40  60
Output: 
40 20 60 10 30
```
