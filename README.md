# Binary-Search-Trees.
The class implements a binary search tree and provides the interface to a storage of items of type T by hiding the details of the pointer operations.
The declaration and partial implementation of the BinSTree class is in ”bstree.h”, which includes the Node class in the given ”treenode.h”.

The Insert method takes the data of the node as argument, dynamically create the node using GetTreeNode and insert the node in the binary search tree. Insertion is always as a leaf node.
The FindNode method returns the node address of the searched data item and a pointer to its parent, and NULL otherwise. If there are multiple, it returns the address of the one found first.
Note that BinSTree is a class template. The examples below are for a BinSTree <int> class. 
