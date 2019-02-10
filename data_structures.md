# Trees

## Binary trees

## Binary search trees

A binary search tree is a rooted binary tree that satisfies the binary search property: the value in each node must be greater than or equal to any value stored in the left subtree, and less than or equal to any value stored in the right subtree.

## Self-balancing binary search trees

A self-balancing binary search tree is a binary search tree that automatically keeps its height small during insertions and deletions.

* https://en.wikipedia.org/wiki/Self-balancing_binary_search_tree

## AVL (Adelson-Velskii&ndash;Landis) trees

An AVL tree is a self-balancing binary search tree in which is no node has subtrees differing in height by more than one.

### Description

* https://en.wikipedia.org/wiki/AVL_tree
* https://www.geeksforgeeks.org/avl-tree-set-1-insertion/

### Papers

G.M.Adelson-Velskii, E.M.Landis. *An algorithm for organization of information*. Doklady Akademii Nauk SSSR **146**, 263 (1962)\
[Full text](http://professor.ufabc.edu.br/~jesus.mena/courses/mc3305-2q-2015/AED2-10-avl-paper.pdf) | [Full text (russian)](http://www.mathnet.ru/links/29d35467640f7ae44d5d347a765fc559/dan26964.pdf)

### Videos

* [MIT OCW 6.006 *Introduction to algorithms* (2011), lecture 6: AVL Trees, AVL Sort](https://www.youtube.com/watch?v=FNeL18KsWPc)

## Binary indexed tree AKA Fenwick tree

A binary indexed tree is a data structure that can efficiently update elements and calculate prefix sums.

### Description

* https://en.wikipedia.org/wiki/Fenwick_tree

### Papers

P.M.Fenwick. *A new data structure for cumulative frequency tables*. Software: Practice and Experience **24**, [327](https://dx.doi.org/10.1002/spe.4380240306) (1994)\
[Full text](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.14.8917&rep=rep1&type=pdf)
<details>
<summary>Abstract</summary>
A new method (the "binary indexed tree") is presented for maintaining the cumulative frequencies which are needed to support dynamic arithmetic data compression. It is based on a decomposition of the cumulative frequencies into portions which parallel the binary representation of the index of the table element (or symbol). The operations to traverse the data structure are based on the binary coding of the index. In comparison with previous methods, the binary indexed tree is faster, using more compact data and simpler code. The access time for all operations is either constant or proportional to the logarithm of the table size. In conjunction with the compact data structure, this makes the new method particularly suitable for large symbol alphabets.
</details>
