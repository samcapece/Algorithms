# CSCI 1913: Algorithms and Program Development - Project 3

## Project Overview

**Project 3: Huffman Coding Trees** explores efficient data storage and retrieval techniques using Huffman coding schemes. This project serves as a practical application of tree-based data structures and encoding algorithms, crucial for understanding the principles of data compression and optimization in computer science.

### Objectives

- Implement Huffman coding for text compression and decompression.
- Design and develop the `HuffmanCodeBook` and `HuffmanCodeTree` classes for encoding and decoding text.
- Apply tree-based structures to solve complex problems in data encoding.

### Description

Huffman coding is a method of lossless data compression that is frequently used to compress textual data. The technique builds a variable-length prefix code based on the frequency of each character in the dataset to be encoded. This project involves creating a system that can both encode textual data into compressed binary form and decode it back into text using Huffman coding trees.

### Components

- **HuffmanCodeBook**: Manages mappings between characters and their corresponding binary sequences.
- **HuffmanNode**: Represents each node in the Huffman tree, capable of storing a character or linking to other HuffmanNodes.
- **HuffmanCodeTree**: Utilizes HuffmanNodes to create and manage the tree structure necessary for decoding the encoded data.

### Features

- **Data Compression**: Implements Huffman coding to compress text files effectively.
- **Dynamic Encoding and Decoding**: Dynamically encodes text to binary data and decodes it back using the generated Huffman tree.
- **Efficiency Analysis**: Focuses on optimizing the compression and decompression processes to handle large texts efficiently.

## Getting Started

### Prerequisites

- Java Development Kit (JDK)
- Basic knowledge of Java programming and data structures

### Installation

Clone the repository to get started with the Huffman coding project:

```bash
git clone (link to project)
cd (path to project)

# Compile project
javac HuffmanCoding.java
java HuffmanCoding


