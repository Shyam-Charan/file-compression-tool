# Architecture

## Components

### Input Module
Reads input file and computes character frequencies.

### Huffman Tree Builder
Constructs the Huffman tree using a min-heap priority queue.

### Encoder
Generates binary codes and compresses the input file.

### Decoder
Reconstructs original file from compressed data using the Huffman tree.

## Data Flow

Input File → Frequency Analysis → Huffman Tree → Encoded Output
