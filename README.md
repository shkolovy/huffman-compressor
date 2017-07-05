# Implementation of archivator using Huffman coding

### How to use

```python
compress("compress-me.txt", "compressed.bin")

decompress("compressed.bin", "decompressed.txt")
```

**Result**
```
encoded huffman tree code: 0010010000001011001010001011100001001011000101100011...
encoded text code: 000000001111011011010010001111010011101101111110111001110100...
before: 7528bytes, after: 4109bytes, compression 45.4%
```

compression can be negative if the text is too short, as the binary file with encoded text also contains a Huffman tree data, which needed to decode the text.

average result is 45%, depends on frequency can be up to 90%

> !not working with cyrillic symbols, it's a simple archivator made with learning purposes
