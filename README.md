# Randomized-Binary-Search-Trees-Implementation-Video-Explaination-
[YouTube Video](https://www.youtube.com/watch?v=LRK6LfJAovY&ab_channel=MohammedBayan)

# Treap Data Structure

The Treap (Tree + Heap) is a randomized binary search tree that combines the properties of a binary search tree and a heap. It maintains the binary search tree property with respect to the keys of the nodes and the heap property with respect to the priorities assigned to the nodes.

## Structure

A Treap is made up of nodes, each containing a key-value pair and a priority. The key follows the binary search tree property, where the keys in the left subtree are smaller than the key at the current node, and the keys in the right subtree are greater. The priorities are chosen randomly and follow the heap property, where the priority of a node is greater than or equal to the priorities of its children.

## Operations

### Insertion

To insert a new element into the Treap, we first perform a standard binary search tree insertion based on the key. After insertion, we maintain the heap property by performing rotations to ensure that the priorities are in the correct order.

### Deletion

Deleting an element from the Treap involves finding the node with the given key and removing it. After deletion, we ensure that the tree remains a valid Treap by performing rotations to maintain the heap property.

### Search

Searching for an element in the Treap is similar to searching in a binary search tree. We start at the root and recursively search the left or right subtree based on the comparison of the key with the current node's key.

## Advantages

- The Treap combines the advantages of both binary search trees and heaps, providing efficient search, insertion, and deletion operations.
- Its randomized nature helps in balancing the tree, resulting in better performance compared to deterministic binary search trees in certain scenarios.
- It is relatively simple to implement and does not require complex balancing algorithms.

## Applications

- Treaps are commonly used in scenarios where both search and priority-based operations are required, such as priority queues.
- They are also used in randomized algorithms and data structures, where the randomization properties of Treaps can be beneficial.
