# AVL Tree

This is a Python implementation of an AVL (Adelson-Velsky and Landis) tree. AVL trees are self-balancing binary search trees that maintain their balance during insertion and deletion operations. This implementation includes methods for inserting elements into the tree while ensuring it remains balanced.

## Table of Contents

- [Introduction](#avl-tree)
- [Usage](#usage)
- [Methods](#methods)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)

## Usage

To use this AVL tree implementation, create an instance of the `AvlTree` class and use the `insert` method to insert elements. The tree will automatically balance itself after each insertion.

```python
# Create an AVL tree
avl_tree = AvlTree()

# Insert elements into the tree
avl_tree.insert(5)
avl_tree.insert(10)
avl_tree.insert(3)
```

## Methods

### `insert(key)`

Inserts a new key into the AVL tree while maintaining its balance.

### `re_balance()`

Rebalances the AVL tree after insertion or deletion operations.

### `update_heights(recursive=True)`

Updates the height of each node in the tree.

### `update_balances(recursive=True)`

Calculates the balance factor of each node in the tree.

### `rotate_right()`

Performs a right rotation to balance the tree.

### `rotate_left()`

Performs a left rotation to balance the tree.

### `in_order_traverse()`

Performs an in-order traversal of the tree and returns a list of keys.

## Example

```python
# Create an AVL tree
avl_tree = AvlTree()

# Insert elements into the tree
avl_tree.insert(5)
avl_tree.insert(10)
avl_tree.insert(3)

# Perform in-order traversal
result = avl_tree.in_order_traverse()
print("In-order traversal:", result)
```

## Contributing

If you'd like to contribute to this AVL tree implementation, feel free to submit a pull request. Issues and feature requests are also welcome.

## License

This AVL tree implementation is released under the [MIT License](LICENSE).
