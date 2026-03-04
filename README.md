# Algorithms Practice

This repository contains several small algorithmic exercises implemented in Python, focusing on fundamental concepts in data structures and algorithm design.

## Contents

### 1. Stable vs Non-Stable Sorting
This exercise demonstrates the difference between **stable sort** and **non-stable sort** when sorting data using two keys: first by **time**, then by **location**. It illustrates how stable sorting preserves the relative order of elements with equal keys, while non-stable sorting may change their original order.

### 2. Hash Table with Separate Chaining
This implementation builds a simple **hash table** where each index stores a bucket (a list of key–value pairs).  
A hash function maps character keys to table indices using their ASCII values.

When inserting elements, the program checks whether the key already exists in the bucket and updates its value; otherwise, it appends a new entry. Because the table size is small, multiple keys may map to the same index, creating **collisions**. These collisions are handled using **separate chaining**, allowing multiple entries to be stored in the same bucket while maintaining efficient lookup operations.

### 3. Word Index (Symbol Table)
This program creates a simple **word index** from a text file. It reads the file line by line, extracts words, removes punctuation, and stores them in a dictionary acting as a **symbol table**. Each word maps to a list of line numbers where it appears.

After processing the file, the program outputs all words in sorted order along with the lines where they occur, demonstrating how symbol tables can be used for text indexing and basic information retrieval.
